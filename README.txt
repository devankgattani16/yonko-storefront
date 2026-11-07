# YONKO Storefront Starter

This is a responsive static storefront prototype built with HTML, CSS and JavaScript.

## Run locally
- Unzip the project.
- Open `index.html` in a browser, or serve the folder with any static web server.

## Included
- Responsive YONKO landing page and product catalogue
- Anime category filters and product search
- Product detail modal with size selection
- Working cart saved in browser localStorage
- Newsletter and account placeholder interactions
- DP WebTech footer credit

## Important before launch
This is a frontend prototype, not a live ecommerce backend.
- The listed products/prices and shirt graphics are demo placeholders.
- Replace demo product data and CSS shirt graphics with your exact original product images/artwork.
- Customer accounts, secure admin login, inventory, real order creation, shipping, and payment processing are not connected yet.
- The checkout button deliberately does not claim to place an order.
- ShopNx integration must be implemented only after verifying the actual API endpoints, authentication method, CORS rules, and required payloads from https://admin.shopnx.in/doc.
- Never put private API keys or admin secrets in browser JavaScript. Use a secure server-side function/backend for secrets and order/payment operations.

## Deploy
This folder can be deployed to a static hosting service such as Cloudflare Pages or GitHub Pages. Upload the folder contents as a static site. A custom domain can be connected in the hosting provider's dashboard.
