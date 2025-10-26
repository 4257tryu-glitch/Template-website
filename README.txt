
Bhai Template — Ready demo marketplace front-end
-----------------------------------------------
Files:
  - index.html
  - style.css
  - script.js
  - templates/ (contains placeholder .zip files)

How to use:
1) Download this ZIP and unzip.
2) Test locally by opening index.html in browser (double-click).
3) To publish free: upload all files to GitHub repository and enable Pages (branch: main, folder: /).
   Or drag-and-drop the folder to Netlify (https://app.netlify.com/drop).
4) Payment integration:
   - PayPal: You can use client-side PayPal Buttons for quick setup (replace client-id in script tag).
     For selling digital goods, PayPal payouts go to your PayPal account — from PayPal you can transfer to your bank.
   - Razorpay (India): Recommended for INR payments and direct settlement to your bank.
     **Note**: Razorpay requires server-side order creation using your secret key. For a secure flow:
       a) Create Razorpay merchant account and complete KYC.
       b) On server, create an order with amount and return order_id to client.
       c) On client, use Razorpay checkout to pay. After successful payment, verify webhook on server and allow download.
5) For demo purposes this package uses a simulated purchase flow (click Buy -> OK -> Download unlocks).
6) Replace placeholder templates in templates/ with your actual .zip files for real downloads.

Need help integrating Razorpay/PayPal or creating a backend? Reply and I will provide server code (Node/Express) and step-by-step.
