# Landing Page Program

## Current strategy

Das Group is pausing broad programmatic SEO for app landing pages.

The current goal is simple:

- Keep one strong canonical landing page per priority app.
- Make each page easy to understand for humans, search engines, and answer engines.
- Wait for real traffic or revenue signal before expanding into broader page sets.

## What we are optimizing for now

- Clean canonical URLs under `/apps/[app]/`
- Truthful product positioning
- Light on-page SEO
- Lightweight AEO / GEO support through direct-answer copy and short FAQs
- Clear CTA on every page
- Sitemap discipline so only intentional pages are indexed

## What we are not doing now

Do not create new:

- use-case pages
- integration pages
- comparison pages
- industry pages
- city or geography pages
- topical programmatic SEO clusters
- MCP / ACP infrastructure pages that are not directly tied to a current app page

## Canonical page rule

Each priority app gets exactly one canonical landing page on `dasgroupllc.com`.

Current priority canonicals:

- `/apps/resolveai-shopify/`
- `/apps/resolveai-zendesk/`
- `/apps/profitpulse-ai-shopify/`
- `/apps/specbot/`
- `/apps/ground-truth/`
- `/apps/thoughtlint/`
- `/apps/courtfile/`
- `/apps/citeclear/`

Legacy duplicates should either:

- 301 redirect to the chosen canonical page where the host supports redirects
- or carry a canonical tag and `noindex` if they remain as supporting assets

## Page requirements

Every canonical app page should include:

- unique title tag
- meta description
- canonical tag
- Open Graph title and description
- one clear H1
- concise explanation of what the product does
- prominent platform or channel framing
- one simple CTA
- lightweight FAQ with 3 to 5 direct questions

## Copy guidance by app type

### Marketplace-driven apps

Applies to:

- ResolveAI for Shopify
- ResolveAI for Zendesk
- ProfitPulse AI for Shopify

Focus on:

- what the app does inside Shopify or Zendesk
- merchant or support-team conversion clarity
- screenshots or video support when available
- fast comprehension for marketplace reviewers and buyers

### Dev / AI-native apps

Applies to:

- SpecBot
- Ground Truth

Focus on:

- explanatory copy
- direct-answer paragraphs
- workflow clarity

Ground Truth may mention MCP because it is directly relevant to product positioning.

Do not expand Ground Truth into a broader MCP or ACP page network until traction exists.

### Niche / prosumer / legal apps

Applies to:

- ThoughtLint
- CourtFile
- CiteClear

Focus on:

- clear problem
- clear solution
- clear audience
- simple CTA
- short FAQ

## Sitemap rule

`sitemap.xml` should include only:

- the home page
- the current canonical priority app pages
- core evergreen site pages that should remain indexed, such as privacy and terms

Do not include:

- duplicate pages
- thin legacy pages
- experimental subdomain URLs
- demo pages
- supporting assets

## Robots rule

`robots.txt` should stay permissive for canonical app pages unless there is a specific crawl issue to solve.

Do not block the canonical `/apps/[app]/` pages.

## Expansion trigger

Broader SEO expansion should happen only after meaningful traction exists.

Examples of valid traction signals:

- sustained organic traffic to canonical product pages
- repeated branded search demand
- active marketplace conversion
- consistent revenue or qualified pipeline from the product

Until then, prefer improving the existing canonical pages over creating new page sets.
