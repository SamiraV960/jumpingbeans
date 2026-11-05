# Jumping Beans Coffee — Website

Marketing site for **Jumping Beans Coffee Ltd**, a mobile, plant-based coffee
truck serving markets, festivals and communities across London.

Single self-contained page (`index.html`) with inline CSS/JS. Open it in any
browser — no build step. Deployed as a static site on Vercel (serves this
repo's root `index.html`).

## Structure

```
index.html              The whole site (inline <style> + <script>)
assets/                 Images + the truck video (referenced by index.html)
jumping-beans-unified/  Brand source-of-truth + companion-app spec (see its README)
```

## Sections

Promo bar → Hero → Our Story (story, values, vision, founder bio) →
Find Our Truck (photos + video) → Menu (Brews & Treats) →
Get the App (Perk Me Up loyalty, coming soon) → FAQs & Allergens → Merch →
Gallery → Reviews → Events / booking CTA → Footer.

## Media

All photography and the truck video live in `assets/` and are referenced by
relative path. They were extracted from an earlier all-in-one build and
compressed, which took the page from ~13.9 MB down to ~50 KB (the video now
streams on demand instead of being embedded). The design and content are
unchanged.

## Fonts

Fraunces (headings), Great Vibes (script accents) and Manrope (body), loaded
from Google Fonts.

## Contact / social (in the footer)

- Email: `jumping_bean26@hotmail.com`
- Instagram: https://www.instagram.com/jumping_beans26/
- TikTok: https://www.tiktok.com/@jumpingbeanscoffee

The Events booking form composes a pre-filled email to the address above.
