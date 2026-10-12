# SCHefferz — Premium Mixer Website (Pre-launch build)

This is a responsive static website built around the supplied SCHefferz packaging assets. The provided logo SVGs are copied unchanged. The product packaging images supplied by the brand are used as the product visuals.

## Pages
- `index.html` — Home
- `shop.html` — collection
- `original-tonic-water.html`
- `elderflower-tonic-water.html`
- `pink-grapefruit-tonic-water.html`
- `about.html` — brand story
- `journal.html` — editorial notes
- `contact.html`
- `wholesale.html`
- `find-us.html`
- `faq.html`
- `shipping.html`
- `privacy.html`
- `terms.html`
- `cart.html`, `checkout.html` — pre-launch placeholders

## Current launch status
This is a **public-facing pre-launch website**, not a live order-taking store. Product prices, final ingredient/nutrition information, shipping, stock, payment gateway and order management were not provided, so checkout is intentionally disabled and there are no invented prices or unsupported product claims. The contact form and newsletter form use `mailto:` and do not store submissions in a website database. Phone number is not shown.

## Before accepting orders
1. Confirm final product name, pack size, ingredients, allergens, nutrition values and all required label claims against the final product/label.
2. Confirm pricing, stock availability, shipping zones, delivery estimates, cancellation/return/refund policies.
3. Set up a payment provider and order-management/fulfilment workflow.
4. Replace the temporary `mailto:` forms with a real, consent-aware email marketing/contact service.
5. Review privacy/terms and market-specific legal/compliance requirements.
6. Test mobile layout, product content, domain, analytics and email delivery.

## Deploy on Cloudflare Pages (static site)
1. Extract the ZIP on your computer.
2. In Cloudflare Dashboard, open **Workers & Pages** → **Create application** → **Pages**.
3. Choose **Direct Upload** (or use a connected Git repository if preferred) and upload the extracted `schefferz-launch` folder / its contents as the site output.
4. Confirm the top-level `index.html` is in the deployed output.
5. Once deployed, open the Pages project → **Custom domains** → **Set up a domain**, and add `schefferz.com` and `www.schefferz.com` as needed.
6. Follow the exact DNS steps shown in Cloudflare. Do not delete existing DNS records unless Cloudflare's setup instructions require it.

Official references:
- Static HTML on Cloudflare Pages: https://developers.cloudflare.com/pages/framework-guides/deploy-anything/
- Custom domains: https://developers.cloudflare.com/pages/configuration/custom-domains/

## Notes
- Google Fonts are loaded remotely; local fallback fonts are included.
- Images are optimized WebP versions derived from the uploaded PNG assets. The original logo SVGs are preserved unchanged.
- Product descriptions and brand story are launch copy drafted from the supplied visual/product context. Verify all commercial product statements before publishing.


Visual update: premium editorial lifestyle imagery and a future SCHefferz Goods landing page have been added. Merchandise is a concept section only; no products or checkout are enabled.
