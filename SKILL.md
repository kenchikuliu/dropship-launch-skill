---
name: dropship-launch
description: Use when the user wants to launch or validate a Shopify dropshipping product, compare launch markets like the UK, US, or Brazil, choose low-risk product directions, draft product pages and Meta ads, or run a 7-day first-test plan for products like home organization, office improvement, pet accessories, and other easy-to-demo physical goods.
---

# Dropship Launch

Use this skill when the user wants to turn a vague dropshipping idea into a practical launch workflow.

This skill is optimized for:

- choosing the first launch market
- picking low-risk products for first validation
- single-product or tightly themed Shopify tests
- product page copy, ad angles, and a 7-day validation workflow

It is not for:

- regulated products
- electronics or certification-heavy products
- Amazon FBA planning
- broad catalog builds before first validation

## Quick Decision Rule

Use this skill if the user is asking any of these:

- what country should I launch first
- what products should I test first
- help me pick a dropshipping product
- write my Shopify product page
- write Meta ads for a product
- make me a 7-day test plan

## Workflow

### 1. Choose the market before the product

Do not assume one market fits all. Pick the market first based on:

- shipping model
- payment and company setup
- language and localization burden
- tax and import friction
- expected delivery speed

Default market logic:

- `United Kingdom`: strong first market for English-language direct tests with light products
- `United States`: stronger if the user has local inventory, 3PL access, or can absorb import friction
- `Brazil`: only if the user can handle stronger localization and local payment expectations

If the user has not decided, default to a recommendation, not a universal claim.

Use [references/market-selection.md](references/market-selection.md) when choosing the first country.

### 2. Lock the launch scope

Default to:

- store model: single-product or tightly themed
- traffic source: `Meta ads`
- product type: low-risk physical goods
- price band: market-adjusted but typically equivalent to `GBP 24.99` to `GBP 39.99`

If the user has not chosen a product, start with a shortlist, not a full store build.

### 3. Filter product directions hard

Only recommend products that pass all of these:

- the problem is obvious in under 3 seconds
- the product is easy to demonstrate in short video
- it is light enough for simple shipping
- it does not depend on complicated sizing, fitment, or compatibility
- it does not require health, safety, or performance claims
- it can support ads, tax, shipping, and refunds

Avoid:

- electronics
- batteries
- medical, health, or beauty claims
- fragile goods
- complex apparel
- car parts with compatibility risk

### 4. Pick one product before writing assets

Do not write full launch assets for three products at once unless the user explicitly wants parallel test assets.

Default first products:

1. under-desk hidden drawer
2. pull-out under-sink organizer
3. reusable pet hair remover roller

Use [references/product-shortlist.md](references/product-shortlist.md) for the first-wave shortlist and scoring logic.

### 5. Build the product page

Draft a page with:

1. headline
2. problem-solution subhead
3. main visual direction
4. three benefit bullets
5. how-it-works
6. before/after or use-case section
7. shipping and guarantee
8. FAQ
9. repeated CTA

Use [references/product-pages.md](references/product-pages.md) for reusable copy structure.

### 6. Build ads around the problem, not the product

Default creative types:

- before/after
- pain-point demo
- simple UGC explanation

For each product, prepare:

- 3 hooks
- 3 short scripts
- 1 creative matrix

Use [references/ad-scripts.md](references/ad-scripts.md).

### 7. Run a 7-day test, not a long debate

The goal is not to prove a business model in theory. The goal is to validate whether the product earns more attention and buyer intent than the next candidate in the chosen market.

Use [references/test-plan.md](references/test-plan.md) for:

- budget ranges
- audience defaults
- price anchors
- kill rules
- scale rules
- day-by-day execution

### 8. Keep operations honest

Before launch, verify:

- supplier reliability
- product dimensions
- shipping expectations
- refund policy
- tracking setup
- mobile checkout
- market-specific tax or payment assumptions

Use [references/ops-checklist.md](references/ops-checklist.md).

## Output Style

When using this skill:

- recommend one primary market and one primary product unless the user asks for multiple
- be explicit about why the market fits the shipping and product model
- be explicit about price, angle, and why the product is testable
- optimize for action, not theory
- separate assumptions from confirmed facts
- avoid pretending the product is validated before the market test

## Files To Read

- `references/market-selection.md`: when choosing the first launch country
- `references/product-shortlist.md`: when choosing products or categories
- `references/product-pages.md`: when drafting a Shopify page
- `references/ad-scripts.md`: when drafting Meta ads or UGC angles
- `references/test-plan.md`: when planning spend, KPIs, and test structure
- `references/ops-checklist.md`: when preparing launch or diagnosing why a product failed
