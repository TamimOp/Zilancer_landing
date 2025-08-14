# Zilancer Landing

This includes **plain HTML/CSS** and a **Shopify dynamic section** so you can quickly reproduce a static design and (optionally) drop it into a Shopify theme.

## What's inside

- `index.html` – static demo using semantic HTML and modern CSS.
- `styles.css` – tokens, responsive grid, and components.
- `assets/` – placeholders for images & logos.

## How to use (static)

1. Open `index.html` directly in your browser or host the folder on Netlify/Vercel/GitHub Pages.
2. Replace placeholders in `/assets` and copy/edit the text.

## How to use (Shopify)

**What's inside**

- `sections/navbar.liquid` – a Shopify section for the header.

- `sections/hero.liquid` – a Shopify section with dynamic content for the main hero area.

- `sections/content-block.liquid` – a reusable Shopify section for your "Project Management" and "Work Together" sections, configured with presets.

- `templates/index.liquid` – the main template file that calls all your sections.

**How to use**

1. In Shopify Admin → Online Store → Themes → Edit code.

2. Create the sections:

- In the /sections folder, create a new file named navbar.liquid and paste the code.

- Repeat this for hero.liquid and content-block.liquid.

3. Create the template:

- In the /templates folder, open index.liquid and replace its content with the provided templates/index.liquid code.

4. Configure in the Theme Editor:

- In the Theme Editor, go to the homepage and you'll see your navbar, hero, and content-block sections.

- You can now add, remove, and reorder the content-block sections and customize all of their settings (text, images, links) directly in the editor.

## Notes

assets folder needed to be placed inside the shopify folder as Shopify has a very specific folder structure that must be followed for the theme to work correctly

content-block.liquid is designed to be reusable for both the "Project Management" and "Work Together" sections. You can add it multiple times and set the layout for each instance in the Theme Editor.

The index.liquid file acts as the blueprint for homepage, telling Shopify which sections to render and in what order.

Good luck!
