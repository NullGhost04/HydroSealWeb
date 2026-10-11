# HydroSeal Gel — Student E-commerce Demo

A responsive, single-product e-commerce demonstration built with vanilla HTML, CSS, and JavaScript.

## Features
- Product introduction, benefits, and general application flow
- Five size variants with separate sample prices
- Cart, quantity controls, and delivery estimate
- Browser-only demo registration/login and profile
- Simulated card, GCash, Maya, and Cash on Delivery choices
- Simulated payment success/failure
- Confirmation page and receipt
- Per-demo-account order history and demo tracking timeline
- Wishlist and delivered-order reviews/ratings
- Responsive layout for desktop and mobile

## Run it
1. Extract the ZIP.
2. Open the `hydroseal-gel` folder.
3. Open `index.html` in a modern browser. For a smoother multi-page development experience, use VS Code with the Live Server extension.
4. Create a demo account using made-up details.
5. Add a product size to the bag, proceed to checkout, and select a simulated payment result.

## Before presenting
- Confirm the actual HydroSeal Gel sizes, packaging, and prices. The included variants/prices are placeholders.
- Replace the CSS-built product illustration with the real approved product photo if available.
- Use only verified product directions. The application section is generic guidance and must be checked against manufacturer instructions.
- Use fictional demo customer data only.

## Important limitations
This is a browser-only school demo, not a production e-commerce application:
- `localStorage` data is editable by the visitor and stored only in that browser.
- Demo passwords are stored in browser data and are not securely hashed. Never use real passwords.
- There is no shared database, secure server authentication, inventory coordination, real order fulfillment, or real payment processing.
- Payment choices are simulations only. No real card, GCash, or Maya credentials should be entered.
- Browser data can be cleared and orders will be lost.
- The demo order status can be advanced by the customer to demonstrate tracking; this is not real courier tracking.

## Project files
- `index.html` — landing page and product selector
- `auth.html` — demo registration/login
- `cart.html` — shopping cart
- `checkout.html` — delivery and simulated payment
- `confirmation.html` — receipt
- `account.html` — profile, orders, tracking, wishlist, reviews
- `products.js` — product variants and sample prices
- `storage.js` — browser persistence helpers
- `app.js` — interactive behavior
- `style.css` — complete responsive design
