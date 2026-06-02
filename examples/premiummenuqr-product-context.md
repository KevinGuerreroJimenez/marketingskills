# PremiumMenuQR Product Context

> External context file for using `marketingskills` against the private `PremiumMenuQR` repository.
>
> Keep this file in the marketing skills repo. Do not copy it into the app unless you explicitly want repo-local agent context.

_Last updated: 2026-06-02_

## How this should be used

This file is not a skill. It is a reusable product context brief.

Use it when prompting an AI coding/marketing agent to audit or improve `KevinGuerreroJimenez/PremiumMenuQR` with the marketing skills in this repository.

Recommended workflow:

1. Open the `marketingskills` repo as the strategy/prompt source.
2. Open the `PremiumMenuQR` repo as the product/codebase to analyze.
3. Give the agent this file as context.
4. Ask it to apply specific skills such as `cro`, `copywriting`, `signup`, `onboarding`, `pricing`, `analytics`, `programmatic-seo`, `site-architecture`, `cold-email`, `prospecting`, `sales-enablement` or `seo-audit`.
5. Apply the resulting implementation changes in `PremiumMenuQR` only after reviewing them.

## Product overview

**Product name:** PremiumMenuQR / CartaQR

**One-liner:** Carta digital premium con QR, vídeo, multidioma y analítica para restaurantes en España.

**What it does:** PremiumMenuQR helps restaurants create a mobile-first public QR menu, manage categories and products from a dashboard, show dishes with photos/videos, enable multiple languages, generate QR access, and measure menu usage.

**Product category:** B2B SaaS for restaurants; QR menu software; digital restaurant menu; visual restaurant menu; multilingual menu.

**Business model:** Subscription SaaS with a 14-day trial through Stripe. Potential high-touch service layer for setup, menu migration, photography/video recording and content upload.

## Current pricing hypothesis

- **Core:** 39 €/month. Up to 10 videos, 1 language, standard support.
- **Pro:** 69 €/month. Up to 30 videos, 3 languages, priority support.
- **Potential add-on:** setup/content production package for restaurants that do not have good photos/videos.

## Target audience

### Primary ICP

Independent restaurants, gastronomic bars, premium cafes, hotels with restaurants, beach clubs, tourist restaurants and hospitality businesses in Spain that want a better mobile menu than a PDF.

### Best initial markets

- Girona
- Costa Brava
- Barcelona
- Tourist-heavy Spanish cities and coastal areas

### Decision makers

- Restaurant owner
- General manager
- Marketing/communications person
- Small restaurant group owner

## Jobs to be done

1. “I want customers to scan a QR and see a fast, clear, attractive menu.”
2. “I want to update dishes, prices and availability without remaking PDFs.”
3. “I want to show dishes visually so customers understand and desire them.”
4. “I want to highlight dishes that I want to sell more.”
5. “I want the menu in multiple languages for tourists.”
6. “I want to know what customers actually view in the menu.”

## Pain points

- Existing QR menus are often just static PDFs.
- PDFs can be heavy, ugly, hard to update and poor on mobile.
- Restaurants depend on designers, printers or manual file edits for menu changes.
- Multilingual menus are painful to maintain.
- Restaurants do not know which dishes customers view most.
- Visual food content is underused in the ordering decision.
- Many restaurants have good Instagram content but a poor menu experience.

## Differentiation

PremiumMenuQR should not be positioned as “another QR menu”.

Strategic position:

> A visual digital menu that helps restaurants sell better dishes, not just display a PDF.

Core differentiators:

- Menu with video, not only QR/PDF.
- Mobile-first public menu experience.
- Multilingual support for tourist restaurants.
- Analytics for scans, opens, product views and video plays.
- Dashboard for menu, design, languages, videos, QR, analytics and subscription.
- Potential done-for-you setup and visual content service.
- Built for Spanish restaurants first.

## Messaging angles

### Strong angles

- “Convierte tu carta QR en una herramienta visual de venta.”
- “Actualiza tu carta sin rehacer PDFs.”
- “Destaca tus platos estrella y tus platos de mayor margen.”
- “Una carta multilingüe para clientes locales y turistas.”
- “Mide escaneos, visitas, platos vistos y reproducciones de vídeo.”
- “Del PDF estático a una carta móvil premium.”

### Avoid

- Overusing “SaaS” in customer-facing copy.
- Overexplaining technical architecture.
- Claiming guaranteed sales lift without proof.
- Selling it as “just a QR”.

## Objections and answers

### “Ya tengo un QR con PDF.”

That solves access, not selling. PremiumMenuQR improves mobile experience, makes the menu editable, helps highlight dishes and gives usage data.

### “No tengo fotos ni vídeos.”

The product can work with basic content, but the commercial opportunity is offering setup/content creation as an add-on.

### “No tengo tiempo para configurar esto.”

Offer a simple onboarding for self-serve users and a done-for-you setup for local/high-touch customers.

### “39/69 €/mes es caro para una carta.”

Do not sell it as a static menu. Sell it as a visual, multilingual and measurable sales asset. The customer only needs a small improvement in promoted dishes or operational time saved to justify the monthly cost.

### “Mis clientes no necesitan vídeo.”

Video is optional, but it is the differentiator for visual dishes, cocktails, desserts, tasting menus and high-margin items.

## Skills to use

### `product-marketing`

Use to refine positioning, ICP, competitive differentiation, customer language and objections.

### `cro`

Use to audit and improve the public landing page, pricing section, CTAs, demo flow and contact/setup offer.

### `copywriting`

Use to rewrite hero, subhero, feature blocks, pricing copy, FAQ, demo page and outbound landing pages.

### `signup` + `onboarding`

Use to optimize the flow:

1. Landing CTA
2. Signup
3. Restaurant created
4. Brand/language configured
5. Plan selected
6. Checkout started/completed
7. First category created
8. First product created
9. QR generated
10. Public menu opened

### `analytics`

Use to plan funnel events and product events. Existing product analytics should support events such as:

- `qr_scan`
- `menu_open`
- `product_view`
- `video_play`

Suggested additional funnel events:

- `landing_cta_click`
- `signup_started`
- `signup_completed`
- `onboarding_started`
- `restaurant_created`
- `brand_configured`
- `plan_selected`
- `checkout_started`
- `checkout_completed`
- `first_category_created`
- `first_product_created`
- `qr_generated`
- `first_public_menu_opened`

### `pricing`

Use to evaluate Core vs Pro, trial length, video/language limits, content-production add-ons, annual plans and local setup fees.

### `programmatic-seo` + `site-architecture`

Use to plan SEO pages around:

- carta digital restaurantes
- menú QR restaurantes
- carta QR restaurantes
- carta digital con vídeo
- menú digital multilingüe restaurantes
- carta digital restaurantes Girona
- menú QR restaurantes Costa Brava
- carta digital restaurantes Barcelona

Avoid thin pages. Each page must target a distinct intent and include demo, screenshots, FAQs, objections and CTA.

### `cold-email` + `prospecting` + `sales-enablement`

Use for outbound to restaurants with poor PDF menus, no QR menu, menus only on Instagram, tourist demand or strong visual dishes.

## Example prompts

### Full audit

```text
Use the marketingskills repo as the source of marketing workflows. Use examples/premiummenuqr-product-context.md as product context. Then analyze the PremiumMenuQR codebase and give me a prioritized plan to improve CRO, signup/onboarding, pricing, analytics, SEO architecture and outbound strategy. Do not edit files yet. Include exact files you would edit and why.
```

### Landing CRO

```text
Use the cro and copywriting skills from marketingskills. Use examples/premiummenuqr-product-context.md as context. Review the PremiumMenuQR landing page and rewrite the messaging to differentiate it from generic QR/PDF menus. Focus on restaurants in Spain, visual selling, multilingual menus and analytics. Return a before/after copy plan and exact component edits.
```

### Signup/onboarding

```text
Use signup, onboarding and analytics skills from marketingskills. Use examples/premiummenuqr-product-context.md as context. Audit the PremiumMenuQR signup and onboarding flow from landing CTA to first public menu open. Identify friction, missing activation steps and missing tracking events. Return a prioritized implementation checklist.
```

### SEO architecture

```text
Use site-architecture, programmatic-seo, seo-audit and schema from marketingskills. Use examples/premiummenuqr-product-context.md as context. Build a SEO architecture for PremiumMenuQR around carta digital, menú QR, carta con vídeo and carta multilingüe for Spanish restaurants. Avoid cannibalization and thin pages. Return page map, URL slugs, intent, H1, title tag, internal links and schema recommendations.
```

### Outbound campaign

```text
Use cold-email, prospecting and sales-enablement from marketingskills. Use examples/premiummenuqr-product-context.md as context. Create a direct outreach system for restaurants in Girona/Costa Brava that currently use PDF menus or poor mobile menus. Include ICP, lead scoring, personalization variables, call script, WhatsApp message, email sequence and objection handling.
```

## Recommended operating model

Keep `marketingskills` as the reusable strategy layer.

Keep `PremiumMenuQR` as the product implementation layer.

For each marketing task:

1. Use `marketingskills` to generate diagnosis, prompts, copy, strategy or implementation plan.
2. Review the output manually.
3. Apply only the selected changes to `PremiumMenuQR`.
4. Measure the result before scaling more changes.

This avoids mixing repositories and keeps the product repo cleaner.
