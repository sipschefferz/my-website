# SCHefferz responsive website

This is a static responsive website based on the uploaded Home.fig homepage design language. It uses the Figma export's visual assets and the supplied product can renders.

## Pages
- Home
- Shop all drinks
- Original Tonic Water
- Elderflower Tonic Water
- Pink Grapefruit Tonic Water
- Merchandise / SCHefferz Goods
- Our Story
- Journal
- Contact
- Wholesale
- Find Us
- FAQs
- Shipping & Returns
- Privacy Policy (draft)
- Terms & Conditions (draft)
- Bag / demo cart
- Checkout placeholder

## Preview locally
Open `index.html` in a browser. For a local server, run `python3 -m http.server 8080` from this folder and visit `http://localhost:8080`.

## Important launch notes
- No prices are invented. Product prices and product details must be confirmed.
- Cart is a demo using localStorage. Checkout does not accept payment or create real orders.
- Contact and wholesale forms open the visitor's email application; submissions are not stored.
- Newsletter form currently opens an email draft; connect an email marketing provider before launch.
- Merchandise is shown as Coming Soon.
- Privacy and terms are draft placeholders and require review before launch.
- The website is not deployed to schefferz.com from this package.

## Deployment
Upload the contents of this folder to a static host such as Cloudflare Pages. Connect `schefferz.com` only after preview testing.
