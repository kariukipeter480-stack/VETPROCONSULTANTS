# Vetpro Consultancy E-commerce UI Prototype

A responsive front-end storefront concept for Vetpro Consultancy, using a clean Kenyan agri-equipment retail style with a green palette, product categories, search, product filters, cart drawer, WhatsApp enquiry flow and browser-based admin panel.

## Run it
1. Extract `vetpro-consultancy-website.zip`.
2. Open `index.html` in a modern browser. For best results, use a local static server (for example VS Code Live Server).
3. Click **Admin** and sign in with the demo credentials below.

## Demo admin login
- Username: `admin`
- Password: `Vetpro@2026`

## What works
- Responsive desktop/mobile storefront
- Search and category filters
- Add products to cart, update quantities and remove items
- Prepare a WhatsApp enquiry from cart contents
- Admin demo login
- Add, edit and delete products
- Edit hero messaging, announcement and brand tagline
- Edit contact details
- Saves demo data in the current browser with `localStorage`

## Important production notes
This is a front-end prototype, not a production e-commerce backend. The admin login is client-side demo authentication and must not be used to protect real data. Browser storage only affects the browser/device where changes were made. Before public launch, implement secure server-side authentication and authorization, a database/API, image upload and validation, stock management, server-side price validation, order management, privacy/security controls, backups and a trusted payment provider. Confirm all product prices, availability, images, addresses and contact details before launch.

Product prices and product imagery in the sample catalog are placeholders for design demonstration. Images are loaded from Unsplash and require an internet connection.
