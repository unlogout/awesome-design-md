---
name: design-md
description: "Use when creating, adapting, or reviewing UI and visual design with this bundled brand-inspired design reference pack. Use for websites, landing pages, dashboards, apps, decks, artifacts, style exploration, visual direction, or when the user names a style folder such as apple, stripe, linear.app, nike, vercel, tesla, claude, wise, zapier, or similar. Select the relevant folder, read its DESIGN.md, and adapt the design language without claiming official affiliation or copying protected assets."
---

# Design MD

This skill is a style-reference router for the bundled `design-md` resource pack. Each style folder contains a `DESIGN.md` reference, and most folders also contain a `README.md`. The goal is to pick the right visual direction quickly, load only the relevant reference files, and translate the design language into practical UI, layout, typography, color, and component decisions.

This is not an instruction to clone a brand. Treat every folder as an "inspired by" design system. Do not imply official affiliation, do not use protected logos or proprietary assets unless the user has rights, and do not reproduce a brand identity wholesale.

## When to Use

Use this skill when the task involves:

- Creating or improving a visual design, UI, landing page, dashboard, app screen, artifact, deck, poster, or markdown design spec.
- Choosing a visual direction from the bundled reference styles.
- Translating a named style such as `apple`, `stripe`, `linear.app`, `nike`, `vercel`, `tesla`, `wise`, `zapier`, `claude`, or `x.ai` into implementable design rules.
- Reviewing whether an existing design matches a desired style reference.
- Producing design tokens, component rules, layout guidance, or a high-level visual system.

Do not use this skill for purely backend work, generic debugging, simple text edits, or tasks where no visual/design decision is needed.

## Core Workflow

1. Identify the target surface: website, landing page, dashboard, app UI, documentation, deck, markdown artifact, poster, or another format.
2. Select 1-3 candidate style folders from the index below. Prefer the user's explicitly named folder if provided.
3. Read the selected folder's `DESIGN.md`. Use `README.md` only as a quick companion when needed.
4. Extract the usable design rules: color roles, typography hierarchy, spacing/radius, imagery, layout rhythm, component patterns, and motion/interaction cues.
5. Adapt the style to the user's product and constraints. Preserve any existing product design system unless the user explicitly asks for a redesign.
6. If implementing frontend code, combine this with the frontend-design workflow and translate the selected reference into concrete CSS variables, components, and responsive layout rules.
7. Before finalizing, check that the output is recognizably guided by the selected style without copying trademarks, logos, proprietary imagery, or exact brand claims.

## Selection Rules

- If the user names a folder, use that folder first.
- If the user names a company or brand-like style, map it to the closest folder in the index.
- If the user describes a mood, pick by design traits: dark technical, editorial warm, luxury automotive, playful consumer, finance-grade, docs-first, command-palette, cinematic, or magazine-like.
- If multiple styles fit, pick one primary style and optionally one secondary influence. Avoid mixing more than two strong visual systems unless the user asks for exploration.
- If a folder does not match the target medium, still borrow its transferable rules, such as typography, color, layout density, and component shape.

## Style Index

| Folder | Best For | Signature Direction |
|---|---|---|
| `airbnb` | Consumer marketplaces, hospitality, local services | Warm white canvas, generous cards, rounded search, Rausch red accent, photo-led trust. |
| `airtable` | Workflow tools, databases, ops software | Sober editorial SaaS, dark-ink pills, white canvas, full-bleed signature color cards. |
| `apple` | Premium product marketing, hardware, polished launches | Museum-like product gallery, SF typography, light/dark tiles, single blue interaction color. |
| `binance` | Crypto, trading, high-energy fintech | Deep near-black finance UI with Binance yellow, dense trading/product panels. |
| `bmw` | Corporate automotive, premium enterprise mobility | Cream-white corporate layout, BMW blue, dark navy hero bands, precise photography. |
| `bmw-m` | Motorsport, performance products, racing pages | Near-black performance system, uppercase type, track photography, M-color energy. |
| `bugatti` | Ultra-luxury, scarcity, high-end editorial commerce | Austere black luxury, restrained white type, heroic full-bleed automotive imagery. |
| `cal` | Scheduling, productivity SaaS, lightweight B2B | Minimal calendar SaaS, white canvas, black CTAs, clean Cal Sans rhythm. |
| `claude` | AI assistants, thoughtful tools, editorial product pages | Warm cream canvas, serif display, calm coral CTAs, dark navy product surfaces. |
| `clay` | GTM, sales intelligence, data enrichment | Vibrant workflow software, saturated cards, white canvas, dark navy CTAs. |
| `clickhouse` | Databases, analytics infra, performance tools | Near-black engineering system, electric yellow accent, technical density. |
| `cohere` | Enterprise AI, model platforms, trust-heavy B2B | Controlled white editorial system, deep green-black bands, mineral surfaces. |
| `coinbase` | Crypto onboarding, institutional finance | Clean white exchange UI, Coinbase blue, high-trust fintech components. |
| `composio` | Developer integrations, agent tooling | Dark developer interface, electric blue intensity, code/product surfaces. |
| `cursor` | AI coding tools, editors, developer productivity | Warm-cream editor aesthetic, near-black ink, product screenshot focus. |
| `elevenlabs` | Voice AI, audio tools, creative AI | Editorial voice-AI look, off-white canvas, warm near-black, soft atmospheric imagery. |
| `expo` | Developer platforms, React Native apps | Clean dev platform, white canvas, sky-blue gradients, docs/product balance. |
| `ferrari` | Luxury automotive, cinematic launches | Near-black cinematic stage, selective white sections, premium motion/vehicle imagery. |
| `figma` | Design tools, collaboration, creative software | Monochrome editorial frame, oversized pastel blocks, product-collaboration energy. |
| `framer` | Website builders, creative tools, portfolios | Dark builder canvas, pure black, blue accent, polished product surfaces. |
| `hashicorp` | Enterprise infrastructure, cloud/platform ops | Black enterprise infra base, product-specific accents, technical authority. |
| `ibm` | Enterprise, data, governance, serious B2B | Carbon-like system, square corners, IBM blue, grid discipline, restrained UI. |
| `intercom` | Customer support, SaaS messaging | Cream customer-service interface, orange accent, conversational product warmth. |
| `kraken` | Crypto exchanges, professional trading | White trusted exchange UI, Kraken purple, rounded 12px buttons, subtle shadows. |
| `lamborghini` | Supercar, luxury nightlife, theatrical campaigns | Pure black cathedral, gold CTAs, massive uppercase type, cinematic video heroes. |
| `linear.app` | Product management, issue tracking, modern SaaS | Near-black product focus, lavender-blue accent, hairline panels, dense screenshots. |
| `lovable` | AI app builders, approachable dev tools | Warm parchment canvas, humanist Camera Plain type, opacity-based neutral system. |
| `mastercard` | Payments, corporate editorial, financial services | Warm cream, huge radii, circular/orbit motifs, black CTAs, signal orange accents. |
| `meta` | Consumer product ecosystems, social/platform pages | White merchandising, optimistic product cards, clean app showcase composition. |
| `minimax` | AI infrastructure, model platforms | Premium white/black AI infra, black pill CTAs, gradient product cards. |
| `mintlify` | Documentation, developer portals, API docs | Sky-gradient docs hero, dense documentation surfaces, clean developer onboarding. |
| `miro` | Collaboration, whiteboards, team creativity | Playful visual workspace, canary yellow, pastel tints, friendly collaboration UI. |
| `mistral.ai` | AI labs, research/product hybrid pages | Warm cream/yellow, sunset gradients, mountain imagery, European AI lab feel. |
| `mongodb` | Databases, developer data platforms | Dark teal hero plus white docs, MongoDB green, practical product screenshots. |
| `nike` | Commerce, sports, lifestyle campaigns | Photography-first commerce, extreme uppercase display, black/white/gray, pill CTAs. |
| `notion` | Productivity, knowledge bases, team workspaces | Illustration-rich workspace, deep navy hero, soft purple pill accents. |
| `nvidia` | AI hardware, GPUs, technical launches | Black/white engineering marketing, NVIDIA green accent, dense product authority. |
| `ollama` | Open-source tools, local AI, minimal docs | README-like simplicity, white canvas, black pill CTA, mascot-friendly minimalism. |
| `opencode.ai` | Terminal-native dev tools, OSS utilities | Warm cream, Berkeley Mono, command-line rhythm, text-first engineering feel. |
| `pinterest` | Discovery, inspiration, visual marketplaces | Photography-first masonry, warm cream, red CTAs, visual browsing density. |
| `playstation` | Gaming, console launches, entertainment | Black/white/blue sections, cinematic trailers, product reveal rhythm. |
| `posthog` | Developer analytics, playful B2B tools | Warm cream, hand-drawn mascots, olive-gray UI, intentionally quirky product pages. |
| `raycast` | Command palettes, productivity utilities | Near-black command UI, screenshot chrome, precise Inter typography, app-like polish. |
| `renault` | Automotive launches, mainstream mobility | Black-white automotive stage, Sunlight Yellow, editorial brand blocks. |
| `replicate` | AI model labs, developer APIs | Warm-cream AI lab/dev tools, hot-orange CTA, large display type. |
| `resend` | Email APIs, developer infrastructure | Near-black dev tool mood, editorial serif headline, clean technical UI. |
| `revolut` | Consumer fintech, banking apps | Black fintech base, cobalt/violet energy, saturated product color moments. |
| `runwayml` | Creative AI, video generation, creator tools | Minimal black/white creative-lab aesthetic, cinematic media, sharp editorial pacing. |
| `sanity` | Content platforms, CMS, structured content | Developer/content platform look, strong red accent, clean docs and studio surfaces. |
| `sentry` | Observability, debugging, dev tooling | Deep purple-violet midnight, electric lime, illustrated technical storytelling. |
| `shopify` | Commerce, merchants, online stores | Cinematic near-black plus admin white, commerce cards, green commerce confidence. |
| `slack` | Collaboration, internal tools, team comms | Aubergine brand base, cream-lavender gradients, blue links, friendly pills. |
| `spacex` | Aerospace, frontier tech, mission pages | Pure black stage, full-bleed rockets/Mars, D-DIN uppercase, cinematic restraint. |
| `spotify` | Music, audio platforms, creator/media pages | Black/green audio identity, bold cards, high-contrast media and playlist energy. |
| `starbucks` | Retail, food/beverage, loyalty programs | Green/cream brand warmth, editorial product photography, rounded retail components. |
| `stripe` | Fintech, payments, API platforms | Deep navy/white infra, electric indigo, gradient mesh, tabular financial typography. |
| `supabase` | Open-source databases, dev platforms | White/near-black, emerald CTA, dense product UI mockups, clean technical surfaces. |
| `superhuman` | Productivity, premium SaaS, email tools | Dark indigo editorial hero, quiet white body, polished high-end productivity tone. |
| `tesla` | EVs, hardware launches, clean tech | Minimal black/white automotive product pages, large vehicle imagery, restrained CTAs. |
| `theverge` | Media, tech news, editorial portals | High-energy editorial grid, bold publication voice, sharp contrast and story modules. |
| `together.ai` | AI infrastructure, model serving, dev platforms | AI infra product language, technical surfaces, model/platform credibility. |
| `uber` | Mobility, logistics, service platforms | Black-white utilitarian minimalism, strong grid, direct copy, service-first clarity. |
| `vercel` | Developer platforms, deployment, infra | White minimalist infra, Geist Sans/Mono, shadow-as-border, workflow accents. |
| `vodafone` | Telecom, consumer services, carrier portals | Red/white telecom system, bold offers, service cards, direct conversion UI. |
| `voltagent` | Agent frameworks, developer tools | Agent/dev tooling style, energetic technical accenting, product-code composition. |
| `warp` | Terminals, AI dev environments | Dark terminal-native interface, gradient energy, code/command surfaces. |
| `webflow` | Website builders, no-code tools, creator platforms | Bold builder platform look, blue/black/white contrast, polished marketing/product UI. |
| `wired` | Editorial, magazines, technology journalism | Newsprint white, black serif headlines, mono labels, almost no gradients. |
| `wise` | Fintech, payments, global money products | Lime-green fintech, huge Wise Sans weight 900 headlines, pill CTAs, confident tone. |
| `x.ai` | AI labs, technical research, dark minimal sites | Dark brutalist minimalism, GeistMono display, white-only interface, no decoration. |
| `zapier` | Automation, SMB SaaS, approachable ops tools | Warm cream canvas, Degular display, orange accent, border-forward structure. |

## Category Shortcuts

- Consumer and marketplace: `airbnb`, `pinterest`, `nike`, `spotify`, `starbucks`, `uber`.
- Finance and crypto: `stripe`, `coinbase`, `binance`, `kraken`, `revolut`, `wise`, `mastercard`.
- Developer and infrastructure: `vercel`, `linear.app`, `cursor`, `raycast`, `warp`, `opencode.ai`, `resend`, `supabase`, `clickhouse`, `mongodb`, `hashicorp`, `sentry`, `posthog`, `replicate`, `together.ai`, `composio`, `voltagent`, `ollama`, `mintlify`, `expo`.
- AI and productivity: `claude`, `cohere`, `mistral.ai`, `elevenlabs`, `runwayml`, `minimax`, `x.ai`, `lovable`, `superhuman`, `notion`, `airtable`, `miro`, `cal`, `intercom`, `slack`, `zapier`.
- Automotive, luxury, and frontier tech: `tesla`, `bmw`, `bmw-m`, `bugatti`, `ferrari`, `lamborghini`, `renault`, `spacex`, `playstation`, `nvidia`.
- Editorial and media: `wired`, `theverge`, `apple`, `mastercard`, `zapier`, `claude`.
- Commerce and brand platforms: `shopify`, `webflow`, `figma`, `sanity`, `meta`, `vodafone`.

## Output Expectations

When using this skill, include the chosen style folder and the reason for choosing it. For design guidance, prefer this structure:

1. Chosen style direction.
2. What to borrow from the reference.
3. What not to copy.
4. Concrete design rules: colors, typography, spacing, components, layout, imagery, motion.
5. Implementation notes or CSS/token suggestions when relevant.

For implementation work, convert the selected reference into usable artifacts instead of only describing it. Examples: CSS variables, Tailwind tokens, component layout rules, markdown design specs, or code changes in the target app.

## Guardrails

- Use "inspired by" internally as a style reference; do not state or imply official partnership.
- Do not use brand logos, proprietary imagery, exact trademarks, or protected assets unless the user confirms rights.
- Do not blindly copy color systems if they conflict with accessibility. Adjust contrast while preserving the visual direction.
- Do not overmix styles. A single strong style usually beats a collage of references.
- Do not read every folder for routine tasks. Read only the folders needed for the requested direction.
- If the user's product already has a design system, adapt the reference to that system rather than replacing it.
