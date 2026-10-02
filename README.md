# TrackShop - No Data Layer E-commerce Practice

This is a small static e-commerce website designed for GTM / JavaScript tracking practice.

## Important
There is NO `window.dataLayer` and NO `dataLayer.push()` in this project.

## Customer flow
Home -> Product -> Add to Cart -> Cart -> Checkout -> Thank You

## Storage
Cart data is stored in browser `localStorage` under:
`trackshop_cart`

## Tracking practice ideas
1. Track product clicks from DOM.
2. Read product ID/name/price from the page.
3. Track Add to Cart button clicks.
4. Read cart data from localStorage.
5. Create your own JavaScript variable / Custom JavaScript in GTM.
6. Later create a dataLayer yourself and push:
   view_item
   add_to_cart
   begin_checkout
   purchase

## Run locally
You can simply open index.html in a browser. For best results, use VS Code + Live Server.

## Free hosting
Upload this project to GitHub and enable GitHub Pages.
