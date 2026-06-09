# Brand Identity

> The publicly-shareable subset of Rarefied Earth's brand specification. Internal entity details (EIN, registered address, banking, insurance) and operational specifics (file paths, internal email aliases, contact phone numbers) are intentionally excluded; those live in the private workspace.

## Names

| Type | Value |
|---|---|
| Operating name | **Rarefied Earth** |
| Legal entity | Earth Evocation Inc. (S-corporation) |
| Full formal style | Earth Evocation Inc. d/b/a Rarefied Earth |

## Pronunciation

- **Rarefied** = RARE-uh-fide
- "Rarefied Earth"; two words, capitalized as shown
- The double-r in "Rarefied" carries a deliberate paradox; the name encodes premium positioning by definition

## Positioning thesis

Rarefied Earth is an **AI-systems implementation firm for operating SMBs, run with civil-engineering discipline**. Three layers, one identity:

1. **Top layer (broad):** AI-augmented workflow automation, agent systems, and the operating substrate companies run on. This is the lead framing on every client-facing artifact.
2. **Middle layer (specialty):** civil-engineering credentials (EI, MSCE, peer-reviewed coauthor) create asymmetric trust in heavy-civil and construction-adjacent verticals. The credentials are a wedge, not a fence; they buy domain trust where they apply and do not constrain the market where they don't.
3. **Bottom layer (productized):** Build the Company, a deployable operating-substrate package, field-tested on Rarefied Earth itself before any client installation.

The layers compound; they don't compete. Lead with the broad framing, qualify with the specialty when the vertical makes it relevant, surface the productized layer as leverage.

The distinctive position rests on the founder's combination (see `Founder.md`):

- A licensed civil engineer with production bridge engineering experience under FDOT Design Manual / AASHTO LRFD, forensic investigation experience for insurance carriers and legal counsel, and hands-on geotechnical field operation experience
- With **published research** in *PCI Journal* on prestressed-concrete pile-bent restoration
- Who **also** operates the field equipment (FAA Part 107 commercial UAS for inspection; AAUS scientific research diver for underwater structural inspection)
- And develops the software systems himself (Python / FastAPI / Linux / cloud, integrating Anthropic and OpenAI APIs into autonomous decision-making and workflow tooling)

This order is rare. Most engineers can't deploy a Linux service. Most software people can't draft a bridge calc, let alone get peer-reviewed in a journal of record. Rarefied Earth's deliverables land as engineering work first (credible to clients in the industry, priced as engineering services) and run in production as software second (because they were actually built, not slide-decked).

**What this looks like in client work:** engineering deliverables that include custom internal tools, AI-assisted workflows, document-intake automation, decision-support dashboards, field-data ingestion pipelines, and bid-leveling / spec-search systems. Built specifically for civil and construction firms with real workflows and real document chaos. Scoped and built by a civil engineer who knows what construction estimating, scheduling, and field operations actually look like.

**What it is NOT:** a generic "AI strategy" practice; an outsourced dev shop; a body-shop staffing model; a "we do everything" generalist consultancy. Buyers should expect to be talking to an engineer who ships production software, not to a software company with industry talking points.

## Tagline

**`Engineering-grade AI for operating companies.`**

Period at the end. Reads as a complete sentence, not a slogan. Encodes the positioning thesis directly: *Engineering-grade* (the credential wedge) *AI* (the work) *for operating companies* (the market).

Use everywhere the firm name is introduced for the first time: page `<title>` tags, business card, capability statement header, email-signature secondary line, deck cover, letterhead sub-line.

**Civil-vertical alternate** (used in civil/construction-vertical artifacts where the specialty layer leads): *Civil engineering, with the systems built in.*

## Brand direction: Engineering-Editorial

Selected after a cohesive branding research pass that benchmarked engineering firms (Arup, AECOM, Bechtel, Mott MacDonald, Kiewit) and AI/tech brands (Anthropic, Stripe, Linear, Vercel) against the position Rarefied Earth wants to occupy. The conclusion: lead with editorial-grade typography and engineering gravitas, supported by Stripe-quality technical clarity and Anthropic's color discipline.

Reads like Arup with Stripe-quality technical clarity and Anthropic's color discipline. Captures engineering gravitas + technical credibility + anti-cliché differentiation simultaneously.

## Colors

Verified directly from the vector source files. These are exact, not sampled approximations.

| Use | PMS | Hex | RGB | Notes |
|---|---|---|---|---|
| **Primary** (navy) | PMS 540 | `#003057` | (0, 48, 87) | Anchor color across the visual identity. Use for headers, primary CTAs, accent strokes, body links. |
| **Secondary** (steel gray) | PMS Cool Gray 9 | `#76777B` | (118, 119, 123) | Use for secondary type, dividers, icons, supporting UI. |
| **Neutral** (light gray) | PMS Cool Gray 9 20% | `#E2E2E3` | (226, 226, 227) | Use for section backgrounds, subtle dividers, card surfaces. |
| **Accent** (warm tan) | PMS 7504 | `#96785E` | (150, 120, 94) | Use for ~10% of the palette: italic emphasis in editorial layouts, section dividers, hover states, secondary CTAs. Ties visually to "Earth" in the firm name. |
| **Accent tint** (50% PMS 7504) | PMS 7504 50% | `#CABAAB` | (202, 186, 171) | Soft accent fill; large background panels where full saturation would overwhelm. |
| **Text** (charcoal) | n/a | `#1a1a1a` | (26, 26, 26) | High-contrast body copy on light backgrounds. |
| **Background** (white) | n/a | `#ffffff` | (255, 255, 255) | Default canvas. |

### Tailwind config

```js
colors: {
  brand: {
    primary:   '#003057', // PMS 540 navy
    secondary: '#76777B', // PMS Cool Gray 9 steel
    neutral:   '#E2E2E3', // PMS Cool Gray 9 20% tint
    accent:    '#96785E', // PMS 7504 warm tan
    tan:       '#CABAAB', // PMS 7504 50% (soft accent fill)
  },
}
```

## Typography

| Use | Font | Notes |
|---|---|---|
| Display headlines | **Source Serif 4** (free, Google Fonts) | Used for hero, section H2s, manifesto quotes. Premium upgrade path: Tiempos Headline (Klim Type Foundry). |
| Body text | **Inter** (free, Google Fonts) | Geometric sans, the de facto B2B technical-product UI standard. Premium upgrade path: Söhne (Klim). |
| Captions / labels / monospace | **JetBrains Mono** (free, Google Fonts) | Editorial captions in uppercase letterspacing, code blocks, schema diagrams, technical data labels. Premium upgrade path: Berkeley Mono. |

All three loaded via Google Fonts CDN with `display=swap` for fast first paint.

## Voice and tone

- **Professional but human.** Not corporate-speak. Not overly casual.
- **Direct.** Says what it means. Doesn't pad.
- **Honest about limits.** Names what's known and what's uncertain.
- **Engineering-grade.** When precision matters, be precise. When it doesn't, don't pretend.
- **No buzzwords for buzzwords' sake.** "AI-powered" is fine when there's actual AI; otherwise drop it.

The full voice discipline (calibration heuristics, hard never's, before/after examples) lives in `Voice_Guide.md`.

## Logo

The logo is the heritage primary lockup: navy + steel gray, anchored by the original 2018 mark plus the RE wordmark and "RAREFIED EARTH" tagline. Variants exist (warm alternate, monochrome navy, monochrome black) for specialized use cases.

The logo asset files themselves are NOT included in this public repository. The Rarefied Earth name, logo marks, and brand visual identity assets remain proprietary trademarks of Earth Evocation Incorporated. To request use of the marks for legitimate business purposes (case study, partnership announcement, vendor catalog), contact the firm through the channels at [rarefied.earth](https://rarefied.earth).

## Public-facing surfaces

| Surface | Address |
|---|---|
| Primary domain | [rarefied.earth](https://rarefied.earth) |
| Primary email | joseph.scott@rarefied.earth |

## Maintenance

This file is a curated public version of the firm's internal brand identity document. Updates land here through the `re-playbook-sync` workflow only after passing sanitization checks. The internal master copy may evolve faster than this public version reflects.

Last meaningful update: 2026-06-09 (positioning thesis and tagline brought to the three-layer model and "Engineering-grade AI for operating companies." canonical tagline; the 2026-04-29 civil tagline retained as the civil-vertical alternate). Earlier 2026-04-29: initial public publication; locked Engineering-Editorial direction, PMS 540 navy + PMS Cool Gray 9 steel + PMS 7504 warm tan accent palette, free Google Fonts typography stack.
