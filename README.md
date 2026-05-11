# Dropship Launch Skill

`dropship-launch` is a Codex skill for turning vague dropshipping ideas into a practical launch workflow.

It is built for early-stage Shopify validation, not for broad theory or marketplace fluff. The skill helps decide which market to start with, which low-risk product to test first, how to structure the product page, how to draft Meta ad angles, and how to run a 7-day first-pass validation cycle.

## What It Does

- chooses a first launch market such as the UK, US, or Brazil
- filters out fragile, regulated, or high-friction product ideas
- recommends low-risk first-wave product directions
- drafts Shopify product page structure and offer framing
- drafts short-form Meta ad hooks and simple UGC angles
- provides a 7-day test workflow with kill rules and scale rules

## Best Use Cases

Use this skill when you want help with:

- picking a first dropshipping market
- choosing a test product
- drafting a single-product Shopify launch
- building Meta ad creative angles
- designing a first validation plan before scaling

This skill is strongest for:

- home organization
- office improvement products
- pet accessories
- other easy-to-demo physical products

## What It Avoids

This skill is not meant for:

- electronics
- batteries
- regulated or claim-heavy products
- fragile items
- complex apparel
- Amazon FBA-specific planning

## Skill Structure

```text
dropship-launch/
|- SKILL.md
|- README.md
|- agents/
|  `- openai.yaml
`- references/
   |- market-selection.md
   |- product-shortlist.md
   |- product-pages.md
   |- ad-scripts.md
   |- test-plan.md
   `- ops-checklist.md
```

## How It Works

The skill follows a simple order:

1. Choose the market first
2. Filter for low-friction products
3. Pick one product before building assets
4. Draft the product page
5. Draft ad hooks and scripts
6. Run a 7-day validation plan

## Install

If you want Codex to auto-discover the skill locally, place the folder under:

```text
$CODEX_HOME/skills/dropship-launch
```

If `CODEX_HOME` is not set, place it under:

```text
~/.codex/skills/dropship-launch
```

On this machine the skill lives at:

```text
C:\Users\Administrator\.codex\skills\dropship-launch
```

## Trigger Example

Example prompt:

```text
Use $dropship-launch to choose a launch market, pick a test product, draft the product page, and build a 7-day Meta ads validation plan.
```

## Repository

GitHub:

- https://github.com/kenchikuliu/dropship-launch-skill
