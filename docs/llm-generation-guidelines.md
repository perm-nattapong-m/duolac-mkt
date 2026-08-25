# LLM Generation Guidelines

Before generating any Thai customer-facing content or design, read files in this order:

1. docs/brand/brand-background.md
2. docs/products/product-catalog.md
3. docs/claims/claim-register.md
4. docs/marketplace/thailand-regulatory-guardrails.md
5. docs/marketplace/shopee-lazada-content-rules.md
6. docs/research/2026-08-25-research-index.md and the relevant research note
7. Relevant image references and approved product-label files

## Required behavior

- Cite the source file for every factual or numerical claim in the internal output.
- If a required fact is missing, ask for it or mark [NEEDS VERIFICATION].
- Never infer a product benefit from an ingredient, strain, technology, foreign product, or research pipeline alone.
- Never convert research findings into a public claim without claim-register approval.
- Treat probiotics as strain-, formulation-, dose-, population-, and outcome-specific.
- Use only claim-register wording marked verified or restricted; comply with any restrictions.
- Preserve the exact Thailand SKU, dosage, count, label language, and storage information.
- Separate final-ready copy from review-needed copy.
- Offer 2–3 creative directions when the brief is ambiguous.

## Design output format

Return:

1. Concept and objective
2. Layout and visual hierarchy
3. Exact on-image copy
4. Caption/listing copy
5. Image-generation prompt, if needed
6. Source mapping
7. Claim and Thailand-regulatory risk checklist

## Hard stops

Do not produce final Thai publishing copy if the exact SKU, Thai label/registration status, or required claim approval is missing. Produce a concept draft labeled [NEEDS VERIFICATION] instead.
