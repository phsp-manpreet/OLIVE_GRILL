OLIVE GRILL BAR & RESTAURANT - WEBSITE
=======================================
HOW TO OPEN
 1. Unzip the folder.
 2. Double-click index.html (needs internet for Tailwind CSS and Google Fonts).
 Pages use "#/" routes, e.g. index.html#/about, index.html#/menu/indian, so they work on any hosting without server setup.

FILES
 index.html          page shell (header, footer, lightbox, SEO meta, Restaurant structured data)
 css/style.css       custom styles and all animations
 js/config.js        EDIT HERE: phone, address, WhatsApp number, menu items, FAQs, gallery, image paths
 js/app.js           pages, router, animation logic, forms
 assets/images/      all photos (WebP) and logo.png

EASY EDITS (js/config.js)
 - PH / TEL / PHD / ADDR : phone and address
 - IT : menu items [category, name, description, image key or emoji, price, dietary]. Leave price as null until confirmed.
 - GL : gallery images [label, image key]
 - IMG : image key -> file path. Replace a file in assets/images/ with a better photo using the same name.
 - FAQ : questions and answers
 - Opening hours are not published; add them once verified.

FORMS
 Reservation and contact forms open a pre-filled WhatsApp message to the restaurant. A table is not confirmed until the restaurant replies.

HOSTING
 Upload the whole folder to any static host (Netlify, GitHub Pages, cPanel). For best speed in production, replace the Tailwind CDN script in index.html with a built Tailwind CSS file.

NOTES
 - Dish names are descriptive placeholders until the restaurant confirms its menu. No prices are shown.
 - Original high-resolution photos will look sharper than the enhanced ones included here.
 - Replace the privacy policy draft with a reviewed version before launch.

--- HINGLISH ---
index.html double-click karke kholo. Menu, phone, photos badalne ke liye js/config.js edit karo. Photos assets/images/ folder mein hain; wahi naam rakhkar nayi photo replace kar sakte ho.
