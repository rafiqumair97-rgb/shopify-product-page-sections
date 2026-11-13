# Shopify Product Page Sections

Drop-in **Online Store 2.0** sections that make Shopify product pages clearer and easier to buy from. No apps, no page builders — native Liquid, small CSS, and only a few lines of JavaScript where needed.

## Sections

| File | What it does |
|---|---|
| `sections/pp-sticky-add-to-cart.liquid` | Sticky bar with image, title, price, variant picker and Add to cart. Appears when the main product form scrolls off screen. Price updates with the variant. |
| `sections/pp-benefits.liquid` | Row of benefit blocks (icon + title + text). 2–6 columns on desktop, 2 on mobile. |
| `sections/pp-faq-accordion.liquid` | FAQ accordion using native `<details>` (works without JavaScript). Optional FAQPage structured data for SEO. |

Every section is editable in the theme editor: colors, text, columns and blocks.

## Install

1. In Shopify admin go to **Online Store → Themes → … → Edit code**.
2. Under **Sections**, click **Add a new section**, name it the same as the file (for example `pp-benefits`) and paste the file's contents.
3. Open **Customize**, go to a product template and click **Add section** to add it.

Tested on Dawn. Other 2.0 themes work too; the sticky bar looks for the theme's main `form[action*="/cart/add"]`.

## Why these sections

Most product pages lose buyers at the same points: the Add to cart button scrolls away, the reasons to buy are buried in a long description, and common questions go unanswered. These three sections fix those points without slowing the store down.

---

Built by **Umair Rafiq** — Shopify developer & designer.
