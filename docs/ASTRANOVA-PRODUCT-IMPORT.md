# Astranova product import workflow

Use this checklist for every supplier product before changing its status from Draft.

## 1. Images

- Upload supplier images to Shopify Files first. Do not depend on external image URLs.
- Add at least three useful images: clean hero, detail or scale, and use-case or feature view.
- Prefer square images at 1200 × 1200 px or larger.
- Use short descriptive alt text without keyword stuffing.
- Keep the first image clean because it becomes the featured image in product cards.

## 2. Native Shopify fields

- Title: customer-friendly product name, not the supplier listing title.
- Description: one clear introductory paragraph and three to five verified benefits.
- Vendor: real manufacturer when known; otherwise `Astranova Curated`.
- Product type: a stable customer-facing category.
- SKU: `AST-{supplier}-{supplier SKU}`.
- Cost per item: supplier price converted to EUR, then add shipping, duties and handling before final pricing.
- Status: always `Draft` during review.

## 3. Required metafields

Populate these whenever the information exists:

- `custom.brand`
- `custom.model`
- `custom.compatibility`
- `custom.material`
- `custom.size`
- `custom.color`
- `custom.power`
- `custom.warranty`
- `custom.package_contents`
- `custom.delivery`
- `custom.technical_specifications`
- `custom.promise_headline`
- `custom.benefit_1`
- `custom.benefit_2`
- `custom.benefit_3`
- `custom.product_details`
- `custom.size_and_materials`
- `custom.care_and_use`
- `custom.shipping_and_returns`

The theme hides optional empty sections. Product type and SKU remain as safe specification fallbacks.

## 4. Compliance gate

Keep `compliance-pending` and `cost-review` tags until all checks are complete.

- Verify supplier identity and EU responsible person.
- Collect CE declaration of conformity where required.
- Confirm RED, RoHS, WEEE and battery documentation where applicable.
- Check app availability, privacy terms and operating-system support.
- Confirm package contents, plug type, manuals and warranty handling.
- Order and test a sample.
- Replace the provisional cost with landed cost.

## 5. Activation

Only remove review tags and change the product to Active after:

- all customer-facing claims are verified;
- inventory or supplier stock synchronization is configured;
- landed margin is acceptable;
- delivery and returns text matches the actual fulfillment route;
- the product page has been checked on desktop and mobile.
