# SÚPERCHIDO — Menu

A modern, single-page web menu for [SÚPERCHIDO](https://www.superchido.com.au/) — a regional Mexican kitchen and agave bar in Seddon, Melbourne.

## What's inside

- **Sticky left-rail navigation** with the SÚPERCHIDO wordmark, all menu sections, opening hours, and Book / Pick Up / Uber Eats CTAs
- **Hero** with overhead food photography, a glassy location badge, and a rotating "Taco Tuesday" sticker
- **Live search + dietary filters** — instantly narrow to Vegetarian, Vegan, Gluten-free, Dairy-free, Customer Favourites, New Dishes, or Chef's Selection
- **Responsive cards** for every dish — name, description, price, dietary tags, and special markers
- **El Clásico** showcase block — chef's tasting selection with photo and per-person pricing
- **Mobile-first**: full hamburger drawer, swipeable filter chips, optimized layout under 1100px
- **Print-ready**: Cmd-P degrades gracefully to a clean printable menu
- **Same brand palette as the live site** — pink (`#E91E63`), cream, and black, with Archivo Black, Fraunces, Caveat, DM Mono, and Inter typography

## File structure

```
superchido-menu/
├── chido.html          # the entire site — single self-contained file
├── assets/             # menu photography and brand wordmark
│   ├── pomelli_bdna_image_0518-2.png   # Taco Tuesday sticker
│   ├── pomelli_bdna_image_0518-3.png   # SÚPERCHIDO wordmark logo
│   ├── pomelli_bdna_image_0518-4.png   # Birria + consomé hero shot
│   └── pomelli_bdna_image_0518-5.png   # Overhead spread (hero visual)
└── README.md
```

## Run locally

No build step — just open `chido.html` in any modern browser.

```bash
open chido.html        # macOS
xdg-open chido.html    # Linux
start chido.html       # Windows
```

Or serve it with any static server:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000/chido.html
```

## Hosting it permanently

Three easy options when you're ready to put this on a real URL:

1. **GitHub Pages** (free) — Settings → Pages → Source: `main` → root. Rename `chido.html` to `index.html` and visit `https://easyans.github.io/superchido-menu/`.
2. **Netlify / Vercel** (free) — drag the folder onto netlify.com/drop for an instant `.netlify.app` URL.
3. **WordPress** — drop into a child theme as a custom Page Template (`page-menu.php`) and serve at `superchido.com.au/menu`.

## Credits

- Design + build by Aakash
- Photography and brand wordmark courtesy of SÚPERCHIDO
- "We acknowledge the Traditional Owners of the land, the Wurundjeri Woi Wurrung and Bunurong peoples of the Kulin Nation and pay our respect to their Elders, past, present and emerging."
