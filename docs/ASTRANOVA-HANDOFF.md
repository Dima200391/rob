# Astranova — Luminous Horizon handoff

## Current theme

- Base: Astranova Horizon 1.0.0, a block-based Shopify Horizon theme.
- Preserved: collection filters and sorting, product quick add, cart drawer, sticky add-to-cart, related and complementary product recommendations.
- Added: Astranova visual system, homepage sections, product trust and specifications, cart free-shipping progress, bilingual storefront copy and product metafield definitions.
- Live theme was not changed.

## Preview

- Unpublished theme: `Astranova Luminous Horizon`
- Theme ID: `198441861460`
- Signed preview: https://tgdhlcf0dmovfzw8ix8v59xi1ow22-104096366932.shopifypreview.com
- Theme editor: https://v1ps5v-su.myshopify.com/admin/themes/198441861460/editor
- Figma file: https://www.figma.com/design/v0O4RzCjjNHt6ojzePRXyn

## Storefront structure

### Homepage

1. Dark technology hero with primary and secondary CTAs.
2. Five flexible category cards.
3. Featured products carousel with native Horizon product cards and quick add.
4. “Why Astranova” story and trust panel.
5. Customer testimonials.
6. Two-column FAQ.
7. Newsletter and dark footer.

### Product page

- Modern media gallery and sticky product information.
- Button-style variants and swatches.
- Three product benefits.
- Delivery, returns and warranty trust panel.
- Product description, specifications and metafield-powered accordions.
- Complementary “frequently bought together” recommendations.
- Related products below the main section.
- Sticky add-to-cart retained.

### Collections

- Native Horizon filters, sorting and responsive product grid retained.
- Product cards receive Astranova surfaces, radii and hover treatment.
- Native quick add remains enabled.

### Cart

- Existing cart drawer retained.
- Free-shipping progress bar added.
- Checkout, returns and support trust notes added.
- Existing discount and cart-note functionality retained.
- Existing cart-page recommendations can be used for upsell.

## Product metafields created in Shopify

All definitions use namespace `custom`, owner type `PRODUCT`, are pinned and storefront-readable.

- `brand`
- `model`
- `compatibility`
- `material`
- `size`
- `color`
- `power`
- `warranty`
- `package_contents`
- `delivery`
- `technical_specifications`
- `promise_headline`
- `benefit_1`
- `benefit_2`
- `benefit_3`
- `product_details`
- `size_and_materials`
- `care_and_use`
- `shipping_and_returns`

The validated creation operation is stored in `docs/create-product-metafields.graphql`.

## Recommended navigation

- Electronics
  - Audio
  - Charging & Power
  - Smart Devices
  - Mobile Accessories
- Accessories
- Home
- Gifts
- New Arrivals
- Sale
- Support
  - Shipping & Delivery
  - Returns & Refunds
  - Warranty
  - FAQ
  - Contact
  - Track Order

## Starting collections

- Wireless audio
- Chargers and power banks
- Smart watches and wearables
- Phone and tablet accessories
- Smart home
- Desk and workspace
- Travel tech
- Gifts under €50
- New arrivals
- Best sellers

## Email automation

### Welcome

- Email 1 immediately: brand promise, category shortcuts and first-purchase incentive only if margins allow.
- Email 2 after 2 days: best sellers and “Why Astranova”.
- Email 3 after 5 days: buying guide or category education.

### Abandoned checkout

- Email 1 after 1–2 hours: cart reminder and support link.
- Email 2 after 20–24 hours: product benefits, delivery and returns reassurance.
- Email 3 after 48–72 hours: urgency based on real stock or a controlled incentive.

### Post-purchase

- Order education after fulfillment: setup, care or compatibility tips.
- Review request 10–14 days after delivery.
- Cross-sell 14–21 days after delivery, based on the purchased category.

## SEO structure

### Homepage

- Title: `Astranova | Electronics & Modern Everyday Essentials`
- Description: `Discover curated electronics, accessories, home essentials and gifts from Astranova. Clear delivery, easy returns and reliable support.`
- One H1, descriptive category links and organization/store structured data.

### Collection pages

- Title formula: `[Collection] | Astranova`
- Description: 120–160 words explaining use cases, compatibility and buying criteria.
- Unique H1, indexable collection copy, clean filter URLs and internal links to related collections.

### Product pages

- Title formula: `[Product name] – [Primary benefit] | Astranova`
- Unique 150–160 character meta description.
- Descriptive image alt text.
- Complete brand, model, compatibility, warranty and specifications metafields.
- Product, Offer and Review schema supplied by Shopify/theme or the selected review app.

## Recommended Shopify apps

Install only one app per overlapping function to protect speed.

### Reviews

- Start: [Judge.me Product Reviews](https://apps.shopify.com/judgeme) — generous free plan, review requests, photo/video reviews and storefront widgets.
- Premium visual alternative: [Loox](https://apps.shopify.com/loox).

### Upsell and bundles

- Start: [Shopify Bundles](https://apps.shopify.com/shopify-bundles) for fixed bundles and multipacks.
- More advanced: [Selleasy](https://apps.shopify.com/upsell-cross-sell-kit-1) or [Rebuy](https://apps.shopify.com/rebuy). Confirm paid plans before installation.

### Filters and recommendations

- Start: [Shopify Search & Discovery](https://apps.shopify.com/search-and-discovery).
- Large catalog alternative: [Boost AI Search & Filter](https://apps.shopify.com/product-filter-search).

### Email marketing

- Start: [Shopify Messaging](https://apps.shopify.com/shopify-email).
- Scale: [Klaviyo](https://apps.shopify.com/klaviyo-email-marketing) when segmentation and revenue justify the cost.

### Live chat

- Start: [Shopify Inbox](https://apps.shopify.com/inbox).

### SEO

- Audit-focused: [Plug In SEO](https://apps.shopify.com/plug-in-seo).
- Broader automation: [Tiny SEO](https://apps.shopify.com/smart-image-optimizer).

### Image optimization

- [Tiny SEO](https://apps.shopify.com/smart-image-optimizer) for compression, resizing, alt text and image-related SEO.

## English and Russian core copy

### English

- Hero: `Technology. Everyday. Elevated.`
- Body: `Curated electronics and modern essentials for life at home, at work and on the move.`
- Why Astranova: `Curated choices. Designed for real life.`
- Newsletter: `Stay in the orbit. New drops, useful guides and exclusive offers. No noise.`

### Russian

- Hero: `Технологии. Каждый день. На новом уровне.`
- Body: `Отобранная электроника и современные товары для дома, работы и жизни в движении.`
- Why Astranova: `Отобранные решения. Созданы для реальной жизни.`
- Newsletter: `Оставайтесь на орбите. Новинки, полезные материалы и специальные предложения. Без лишнего шума.`

## Shopify Admin tasks still required

1. Add real products and complete the created metafields.
2. Create collections and assign products.
3. Select the featured-products collection in the homepage editor.
4. Upload category imagery or set collection featured images.
5. Configure main and footer menus; translate menu labels with Shopify Translate & Adapt if Russian navigation is needed.
6. Create and verify shipping, returns, warranty, FAQ, contact, about and tracking pages.
7. Configure Markets, shipping rates, taxes and free-shipping rules to match the €75 visual threshold.
8. Add complementary products in Shopify Search & Discovery.
9. Replace sample testimonials with verified reviews from the selected review app.
10. Configure welcome, abandoned checkout and post-purchase automations.
11. Test a real product, cart, discount, shipping rate, payment method and order notification.
12. Remove storefront password and publish only after final approval.
