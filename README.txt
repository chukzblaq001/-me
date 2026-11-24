EVERYTHING ABBY WEBSITE - START HERE

FILES
- index.html: website pages and layout
- style.css: design and responsive styling
- app.js: shopping cart, checkout, demo order storage, reviews and admin tools
- assets/: your uploaded product photos

HOW TO PREVIEW
1. Extract the ZIP.
2. Keep index.html, style.css, app.js and the assets folder together.
3. Double-click index.html to preview in Chrome.
4. For GitHub Pages, upload the contents of this folder (including assets) to your repository root.

DEMO ADMIN
- Open the website and scroll to the footer.
- Click Store admin.
- Demo PIN: 2468.
- Change this before sharing the website. This PIN is only a front-end demo lock and is NOT secure for a live store.

IMPORTANT BEFORE TAKING REAL ORDERS
This is a functional front-end prototype. Orders, reviews, products and settings are stored in the current browser's localStorage only. They are not sent to a central database, so customers on different devices will not share orders or reviews yet.
- Add your real bank details in Store admin > Settings. Do not publish the site with blank or example account details.
- The bank-transfer flow records an order as awaiting transfer; verify payments in your bank account before marking them verified.
- Cash on delivery is recorded as pending confirmation.
- No card processor or automatic bank-payment verification is connected.
- The custom gift form opens WhatsApp after you add your WhatsApp number in Store admin > Settings. Without that, it saves the request only in that browser.
For a real public launch with shared customer accounts, central order management, secure admin authentication, reliable image uploads and verified payments, connect a backend such as Supabase and implement server-side payment/order verification. Do not put secret API keys in app.js or any browser code.
