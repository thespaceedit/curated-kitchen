# The Curated Kitchen

**Live editorial Amazon.co.uk affiliate catalogue — 12 kitchen categories, every link verified.**

🌐 **Live site:** https://thespaceedit.github.io/curated-kitchen/

---

## What this is

A single-page affiliate catalogue built for Amazon.co.uk. 12 categories, 12 hero products, accessories for each. Every link is a direct Amazon.co.uk product page with affiliate tag `sinkedit-21`.

## Repo structure

```
/
├── index.html                              ← The full catalogue
├── assets/
│   ├── images/
│   │   └── the-curated-kitchen-logo.png   ← Brand logo
│   ├── curated-kitchen-image-manifest.csv ← Product image reference list
│   └── curated-kitchen-image-manifest.txt ← Same, plain text
└── README.md
```

## Product images

The `assets/curated-kitchen-image-manifest.csv` contains the filename convention for all product images. Drop product images into `assets/images/` using the filenames in the manifest and the site will display them automatically once image tags are added to the HTML.

## Hero products (verified April 2026)

| # | Category | Product | ASIN |
|---|---|---|---|
| 01 | Coffee Station | ASCOT Retro Glass Kettle — Sage | B0CDC3XNW2 |
| 02 | Cookware | Cuisinart GreenChef 13-Piece — Sage | B09WB482BT |
| 03 | Knives | ZWILLING Gourmet Knife Block | B07C1SBHTF |
| 04 | Bakeware | Mason Cash Mixing Bowl 26cm | B01MR8VD09 |
| 05 | Storage | Kilner Clip Top Jar Set x4 | B084RNVYJN |
| 06 | Serving | Argon Tableware Slate Tray + Rope | B09TRXRQP2 |
| 07 | Boards | JF James F Acacia Board 40cm | B0B5QYS717 |
| 08 | Mixer | KitchenAid Artisan 4.8L Almond Cream | B07L34Y2PD |
| 09 | Air Fryer | Ninja Foodi Dual Zone AF300UK | B08CN3G4N9 |
| 10 | Textiles | Small Snail Cross-Back Apron — Sage | B09B34N8KZ |
| 11 | Sink | Joseph Joseph Sink Caddy | B006BSCOTK |
| 12 | Under-Sink | Joseph Joseph Wheeled Storage Caddy | B08QH23M2P |

## Affiliate tag

`sinkedit-21` — applied to every link on the page.

## To enable GitHub Pages

1. Go to **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, folder: **/ (root)**
4. Save — site goes live in ~2 minutes
