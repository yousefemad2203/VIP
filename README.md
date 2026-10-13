# NOIRÉ Perfume Store — GitHub Pages

Responsive Arabic-first perfume store demo with dark luxury styling, ambient gold glow, scroll-reveal animations, product type filters (men/women/unisex), price-tier filtering (Premium/Signature/Essentials), sorting, and a client-side shopping bag that drafts an order in WhatsApp.

## Before publishing
- Replace the example products, descriptions, and prices with accurate details for your actual inventory.
- Replace `201000000000` in `index.html` and `script.js` with your WhatsApp number in international format, digits only (Egypt example: `201XXXXXXXXX`, without `+` or leading `0`).
- This is a front-end demo: it does not process payments, verify stock, or arrange shipping.
- Use accurate product descriptions and do not present imitation products as genuine branded goods.

## Edit products
Open `index.html`, find `id="products"`, and edit each `<article class="product">`.
- `data-category` must be `men`, `women`, or `unisex`.
- `data-tier` must be `premium`, `signature`, or `essentials`.
- Update `data-price`, `data-name`, visible product name, description, and price.
- Duplicate a product article to add more products.

## Publish
Upload `index.html`, `style.css`, `script.js`, and `README.md` to the root of your GitHub Pages repository and commit changes.
