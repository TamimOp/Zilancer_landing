# Zilancer Landing – Starter

This starter includes **plain HTML/CSS** and a **Shopify dynamic section** so you can quickly reproduce a static design and (optionally) drop it into a Shopify theme.

## What's inside
- `index.html` – static demo using semantic HTML and modern CSS.
- `styles.css` – tokens, responsive grid, and components.
- `sections/landing-hero.liquid` – a Shopify section with settings/blocks.
- `assets/` – placeholders for images & logos.

## How to use (static)
1. Open `index.html` directly in your browser or host the folder on Netlify/Vercel/GitHub Pages.
2. Replace placeholders in `/assets` and copy/edit the text.

## How to use (Shopify)
1. In Shopify Admin → **Online Store → Themes → Edit code**.
2. Create a new file in **/sections** named `landing-hero.liquid`.
3. Paste the contents of `/sections/landing-hero.liquid` from this starter.
4. In the Theme Editor, add the **Landing Hero** section to a page and configure settings (text, images, buttons, badges, and feature cards).
5. Tweak colors in the section settings or inside the `<style>` block if needed.

## Notes
- The markup is intentionally clean and minimal so it's easy to adapt to any provided mockup.
- Fonts use Google Fonts (Inter). Swap to match the design.
- All spacing/typography is responsive via `clamp()` and mobile-first CSS.

Good luck!
