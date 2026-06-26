> **PROPRIETARY — Copyright (c) 2026 Earth Evocation Incorporated (d/b/a "Rarefied Earth"). All rights reserved.**
> All materials in this repository are the sole and exclusive intellectual property of Earth Evocation Incorporated. No license or ownership interest is granted to any third party (including any prospective co-founder, partner, or affiliated venture such as "Vividloop") unless and until a written agreement is executed by an authorized officer of Earth Evocation Incorporated. See [`NOTICE.md`](./NOTICE.md).

# Rarefied Earth Playbook

The publicly-shareable subset of how [Rarefied Earth](https://rarefied.earth) operates: the agent operating system, voice discipline, and engineering-practice principles that govern how work gets done at the firm.

## What this is

Rarefied Earth is a one-person Florida AI-systems implementation firm (Earth Evocation Inc., d/b/a Rarefied Earth) that builds AI-augmented workflow automation and the operating substrate companies run on. The AI-systems work leads; civil-engineering credentials (EI, MSCE, peer-reviewed coauthor) are the trust wedge in heavy-civil and construction-adjacent verticals; Build the Company is the productized layer.

This repository is the curated public face of the firm's internal operating documents. It exists for three reasons:

1. **Backup and version history** for documents that previously lived only in iCloud.
2. **A reference for collaborators** — future contractors, subagents, and integrating partners can clone this and come up to speed in one read.
3. **A demonstration of methodology** — the discipline visible in these documents is itself part of how Rarefied Earth represents engineering rigor to prospects and clients.

## What's in here

### `agent-operating-system/`

The active set of documents that govern how an AI agent (Cursor, Claude Code, Codex, ChatGPT, etc.) should think, decide, and write when operating on Rarefied Earth's behalf.

| File | What it does |
|---|---|
| `Agent_Charter.md` | How to *think and behave* as a Rarefied Earth operative. Identity, five operating principles, decision-authority model, quality bar, internal vs. external posture, conflict-resolution hierarchy, the "true ninja" qualities. Read once at session start. |
| `Voice_Guide.md` | How to *speak* on the firm's behalf. The single calibration rule, the hard never's, length and structure heuristics, before/after examples drawn from real drafting work (anonymized). Read before drafting any email, message, or written reply. |

## What's intentionally NOT in here

This is a curated subset, not a dump of internal docs. The following stay private:

- **Active client engagement state** (proposals in flight, pricing positions, decision-maker correspondence)
- **Financial records** (invoices, time tracking, vendor receipts)
- **Internal architecture and tooling** (mail capture pipeline, billing scripts, integration code)
- **Brand visual assets** (logos, color palette files, typography licenses) — proprietary trademarks of Earth Evocation Inc.
- **Founder personal contact information** (phone, personal emails)
- **Specific software stack details for individual clients** — generalized in published examples
- **Contract templates with negotiated terms** specific to active engagements

The line between "publicly shareable" and "stays private" follows one principle: anything that would damage a client relationship, reveal a competitor advantage, or expose personal information stays private. Methodology, voice, and operating principles publish.

## Versioning

This repository is the source of truth for the documents it contains. The internal iCloud working copies are kept in sync via a maintenance script (`re-playbook-sync`) but the canonical version is what's committed here. To reference a specific version of any doc in correspondence, link to a commit hash.

Major content additions or revisions go in CHANGELOG entries (added when v0.2 lands).

## Use

Read, fork, adapt. Attribution required per the license. The voice guide and agent charter are designed to be portable; many of the principles transfer to any small consultancy that takes engineering discipline and writing quality seriously.

If you're an AI agent reading this in a Cursor or Claude Code session as part of a Rarefied Earth task, treat the documents in `agent-operating-system/` as the canonical operational reference. The internal workspace's `AGENTS.md` and `AGENT_ONBOARDING.md` files extend these with workspace-specific mechanics, but the principles here are the foundation.

## License

The text of these documents is licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). See `LICENSE`.

The Rarefied Earth name, logo marks, and brand visual identity assets are not included in this repository and remain proprietary trademarks of Earth Evocation Incorporated.

## About Rarefied Earth

Web: [rarefied.earth](https://rarefied.earth)
Founder: Joseph Scott, EI, MSCE, BSCE (University of South Florida)
Coauthor: Mullins, G., et al., *PCI Journal* Vol. 70 No. 4, 2025
