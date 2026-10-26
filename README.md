# RFRC Website

A simple, mobile-friendly static website for Rehabilitation Foundation and Research Centre (RFRC). It introduces RFRC's rehabilitation services and lists therapeutic equipment for families and professionals.

## Preview on your computer

Open `index.html` in a web browser. This project uses plain HTML, CSS and JavaScript, so it does not need npm, a build step or a server.

## Pages

- `index.html` — home page and featured equipment
- `services.html` — rehabilitation services and session price range
- `shop.html` — equipment catalogue with search and category filters
- `product.html?id=1` — product details, selected by its URL ID
- `cart.html` — cart, delivery form and WhatsApp order message
- `about.html` and `contact.html` — RFRC information and contact options

## Editing the site

- Edit product names, descriptions, categories and sample prices in `js/products.js`.
- Replace the contact, WhatsApp and UPI placeholders in the `CONFIG` object near the top of `js/main.js` before launch.
- Replace the placeholder UPI QR image and sample product illustrations with RFRC's verified payment QR and product photos.
- Update the site text, contact details, prices, and service information to match RFRC's confirmed information before publishing.
- The cart is saved in the visitor's browser using `localStorage`. Checkout prepares a WhatsApp message; it does not process payments or save orders to a server.

## Publishing

The files can be hosted as a static website, for example with GitHub Pages or another static hosting service. Keep the folder structure intact so the HTML pages can load `css/`, `js/` and `images/` files.

## Currency and sample content

Prices currently use the Indian rupee symbol (₹) as requested. Product catalogue details and prices are starter examples and should be checked by RFRC before the site goes live.
