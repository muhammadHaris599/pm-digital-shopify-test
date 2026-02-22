# PM Digital Design – Shopify & CRO Test Task

## Overview
This repository contains the custom "Bundle Banner" Shopify section built for the Revive PDP scenario. The section replicates the "After – V1" Figma design and is built to be fully responsive at both 1440px and 390px breakpoints.

## File Structure
/sections
  bundle-banner.liquid

## Installation
1. Upload `bundle-banner.liquid` to the Shopify theme under the /sections directory.
2. Open the product template (product.json).
3. Add the Bundle Banner section to the PDP.
4. Configure heading, subheading, CTA, images, and links via the theme editor.

## Development Approach
- Mobile-first CSS (no frameworks used)
- Semantic HTML structure
- Editor-friendly schema fields
- CTA fully configurable
- Designed to render cleanly on any PDP without affecting layout

## A/B Test Strategy (Option B – Written Spec)

### Hypothesis
Replacing the generic hero on PDPs with a benefit-led bundle banner highlighting 30% savings will increase add-to-cart rate and average order value by surfacing the bundle value proposition earlier.

### Targeting Rules
URL contains: /products/
Excluded: homepage, collections, cart pages

### Traffic Split
50/50 control vs variation

### Primary Metric
Add-to-cart rate

### Secondary Metrics
Revenue per session  
Average order value

### QA Plan
- Confirm variant only fires on PDP
- Validate event tracking
- Test mobile and desktop separately
- Ensure no layout shift or double rendering

## AI Usage
AI tools were used selectively to speed up CSS refactoring and validate Liquid structure. Layout implementation, CRO reasoning, and test logic were handled manually.
