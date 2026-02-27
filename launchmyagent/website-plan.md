# Website Plan (Cloudflare Pages + Stripe)

## Goal
Launch a conversion-focused site for digital products priced $20-$30, with optional bundle upsells.

## Sitemap
1. `/` Home
2. `/products` Product catalog
3. `/products/openclaw-24-7-starter`
4. `/products/claude-code-solo-builder`
5. `/products/ai-agent-security-guardrails`
6. `/bundle` Bundle page
7. `/faq`
8. `/terms`
9. `/privacy`
10. `/contact`

## Home Page Sections
1. Hero: "Launch secure AI agents in hours"
2. Pain points: confusion, security risk, setup time
3. Product cards ($20-$30)
4. Trust blocks: clear scope, step-by-step docs, beginner-safe
5. CTA: Buy now / Start with Starter Kit
6. FAQ summary

## Tech Stack
- Frontend: static site (Astro or Next static export)
- Hosting: Cloudflare Pages
- Payments: Stripe Payment Links or Checkout Sessions
- Delivery: Stripe webhook -> email/link delivery (phase 1 manual fallback)

## Launch CTA Copy
- Primary: "Get the Starter Kit ($29)"
- Secondary: "See all kits"

## Conversion Defaults
- Sticky buy button on product pages
- 3 bullets above fold
- Short guarantee text
- FAQ near CTA
