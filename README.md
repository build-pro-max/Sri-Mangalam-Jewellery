# Sri Mangalam Jewellery — website

Static site. No build step, no dependencies to install.

## Publish with GitHub Pages

1. Upload **everything inside this folder** to the root of `build-pro-max/Sri-Mangalam-Jewellery` (keep the `images/` folder and the two `.dc.html` shell files alongside the pages).
2. Repository → **Settings → Pages** → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → **Save**.
3. The site goes live at `https://build-pro-max.github.io/Sri-Mangalam-Jewellery/` within a minute or two.

## Files

| File | Page |
| --- | --- |
| `index.html` | Home |
| `about.html` | Our Story |
| `shop.html` | Collections catalogue (WhatsApp enquiry per item) |
| `journal.html` | Journal index |
| `journal-care.html` … `journal-news.html` | The six Journal articles |
| `contact.html` | Address, timings, map |
| `SiteHeader.dc.html`, `SiteFooter.dc.html` | Shared header and footer used by every page |
| `support.js` | Runtime that renders the pages |
| `images/` | All 17 shop photographs |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Editing content

- Shop address, phone and timings: `SiteFooter.dc.html` and `contact.html`
- Catalogue items and codes: the `items()` list inside `shop.html`
- WhatsApp number: search for `919677703232` and replace everywhere
