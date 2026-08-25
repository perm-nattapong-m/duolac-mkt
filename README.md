# DUOLAC Thailand Marketing Generation Brain

Centralized brand, product, evidence, marketplace, and visual resources for generating DUOLAC Thailand marketing content and designs.

## Purpose

This repository is the source of truth that an LLM should read before generating:

- Shopee and Lazada Mall product content
- Product descriptions, selling points, captions, and FAQs
- Marketplace image copy and design briefs
- Campaign concepts and social media content
- Image-generation prompts and visual direction

## Repository map

```text
docs/                 Brand and generation guidance
  brand/              Brand background, identity, tone, positioning
  products/           Product facts and SKU information
  marketplace/        Shopee/Lazada requirements and content rules
  research/           Deep-research notes and source summaries
  claims/             Claim status, evidence, and approval tracking
resources/            User-provided images, logos, packaging, references
templates/            Reusable briefs and output templates
outputs/              Generated campaign/content packages
```

## Source-of-truth rules

1. Do not invent product facts, health claims, certifications, prices, or marketplace policies.
2. Treat every claim as `verified`, `pending_verification`, or `not_for_publication`.
3. Use the product files and approved claims before general research notes.
4. Separate facts, marketing interpretation, and creative suggestions.
5. Keep Thai-first customer-facing content; use English only when it supports the brand's premium positioning.
6. Every generated visual should include its intended platform, aspect ratio, product SKU, and required disclaimer status.

## Initial setup checklist

- [ ] Add official logo files to `resources/brand/logo/`
- [ ] Add packaging and product photos to `resources/products/`
- [ ] Add approved brand guidelines to `docs/brand/`
- [ ] Complete the product catalog in `docs/products/product-catalog.md`
- [ ] Verify all numeric and scientific claims in `docs/claims/claim-register.md`
- [ ] Add official marketplace policy references in `docs/marketplace/`
- [ ] Add deep-research sources and dates in `docs/research/`

## Recommended LLM workflow

```text
Read brand rules
  -> Read product/SKU facts
  -> Read approved claims
  -> Read platform requirements
  -> Inspect relevant images
  -> Create brief
  -> Generate content/design
  -> Run factual, claim, and marketplace checks
```

## Status

Project scaffold initialized. Product-specific facts, images, legal review, and marketplace details must be completed before public use.
