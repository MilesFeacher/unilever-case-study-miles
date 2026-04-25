# Source Registry

Central registry of all source materials for the case study, with quality tier classification.

> **Note**: This file is auto-maintained by `/add-sources`. You do not need to edit it manually.
>
> If you previously used `Source_Links.md`, that file is kept for reference. This registry replaces it.

---

## Source Summary

| Tier | Count | Description |
|------|-------|-------------|
| T1 — Primary | 10 | Full-text source in `sources/` folder |
| T2 — Partial | 3 | Partial text, search-derived, or paywalled |
| T3 — Referenced | 0 | Cited but not in repo; unverified |
| **Total** | **13** | |

### Tier Definitions

- **Tier 1 (T1)**: Full-text primary source physically present in the `sources/` folder. Can be read and quoted directly. Examples: full transcript, downloaded PDF, complete article text.
- **Tier 2 (T2)**: Partial text available — extracted quotes, search snippets, or paywalled content where only key passages were captured. Source exists but cannot be fully verified.
- **Tier 3 (T3)**: Referenced only — cited in the case but the full source is not in the repository. May be from AI general knowledge, web search results, or sources that could not be downloaded. Requires verification before publication.

---

## Primary Interviews & Transcripts

| # | Source | Tier | Date | Speakers | Local File | Key Content |
|---|--------|------|------|----------|------------|-------------|
| 1 | Sam Kini – Global CIO at Unilever – Leading IT globally while prioritising sustainability | T1 | 2022-11-22 | Sam Kini; Hendrick Deckers | YouTube URL: https://www.youtube.com/watch?v=OdETG8ALFGo | Sustainability as performance driver; cloud migration; operating model simplification; application BMI; partner consolidation |

---

## Financial Sources

| # | Source | Tier | Date | Type | Local File | Key Data |
|---|--------|------|------|------|------------|----------|
| 1 | Unilever Annual Report and Accounts 2025 | T1 | 2025-11-21 | SEC Filing / Annual Report | `sources/financial/unilever-annual-report-and-accounts-2025.pdf` | Full-year 2025 financial results, P&L, balance sheet, cash flows, segment performance, executive commentary |
| 2 | Unilever Q4 & Full Year 2025 Results Transcript and Q&A | T1 | 2026-02-13 | Earnings Call Transcript | `sources/financial/q4-2025-video-transcript.pdf` | Q4 and full-year 2025 earnings call; executive commentary on performance, strategy, Google Cloud partnership context |

---

## News Coverage

| # | Source | Tier | Date | Publication | Author | Key Content |
|---|--------|------|------|-------------|--------|-------------|
| 1 | Google Cloud supplants Azure as Unilever cloud of choice | T2 | 2026-02-17 | Computer Weekly | Antony Adshead | Five-year cloud contract; Google Cloud becomes destination for Unilever's consolidated cloud/data platform; Vertex AI and agentic-commerce framing |
| 2 | Unilever to Work With Google Cloud on Five-Year AI, Data Partnership | T2 | 2026-02-17 | Consumer Goods Technology | Liz Dominguez | Five-year AI-first digital backbone; Vertex platform; agentic workflows and AI-driven commerce |
| 3 | How data and AI can boost supply chain efficiency and sustainability | T2 | 2024 | Financial Times partner content | Google Cloud / FT partnercontent | Unilever uses Google Cloud and geospatial data to monitor deforestation and support supply-chain resilience |

---

## Industry & Analyst Reports

| # | Source | Tier | Date | Publisher | Local File | Key Data |
|---|--------|------|------|-----------|------------|----------|
| 1 | Unilever Taps Google's AI To Reinvent How We Shop Everyday Brands | T1 | 2026-02-17 | Benzinga | `sources/reports/Unilever Taps Google's AI To Reinvent How We Shop Everyday Brands.pdf` | Partnership framing and expected consumer impact |
| 2 | Unilever targets agentic AI with Google Cloud deal | T1 | 2026-02-17 | CIO Dive | `sources/reports/Unilever targets agentic AI with Google Cloud deal _ CIO Dive.pdf` | Agentic AI positioning and enterprise implementation angle |
| 3 | Google Cloud collab pioneers next-gen consumer goods tech | T1 | 2026-02-17 | Unilever | `sources/reports/Google Cloud collab pioneers next-gen consumer goods tech _ Unilever.pdf` | Company-stated goals, capabilities, and transformation narrative |
| 4 | Unilever adjusts marketing to respond faster to consumer trends | T1 | 2026-03-25 | MarketingTech | `sources/reports/Unilever adjusts marketing to respond faster to consumer trends.pdf` | Marketing speed and responsiveness claims |
| 5 | Unilever Customer Hub Page | T1 | Date not recoverable from local artifact | Google Cloud | `sources/reports/Unilever Customer Hub Page  _  Google Cloud.pdf` | Vendor case summary and partnership highlights; metadata blocker until canonical page/date is captured |
| 6 | Unilever changes its brand discovery calculus with Google Cloud AI pact | T1 | 2026-02-17 | Marketing Dive | `sources/reports/Unilever changes its brand discovery calculus with Google Cloud AI pact _ Marketing Dive.pdf` | Brand discovery and marketing use-case claims |
| 7 | Google Cloud and Unilever Map the Future of AI-Powered Business | T1 | 2026-02-23 | Cloud Wars | `sources/reports/Google Cloud and Unilever Map the Future of AI-Powered Business - Cloud Wars.pdf` | Strategic narrative on AI-enabled operating model shifts |

---

## Other Sources

| # | Source | Tier | Date | Type | URL/File | Key Content |
|---|--------|------|------|------|----------|-------------|

---

## Source Credibility Notes

| Source Type | Typical Credibility | Typical Tier | Notes |
|-------------|-------------------|--------------|-------|
| SEC Filings | Highest | T1 | Legally required accuracy |
| Direct Interviews | High | T1 | First-hand accounts, verify transcript accuracy |
| Earnings Calls | High | T1-T2 | Official statements; T1 if full transcript available |
| Major Publications | Medium-High | T1-T2 | T1 if full text downloaded; T2 if paywalled |
| Company Blog/PR | Medium | T1-T2 | Self-reported; useful for quotes and dates |
| Industry Reports | Medium-High | T1-T2 | T1 if full report; T2 if excerpts only |
| Social Media | Low | T3 | Verify independently before citing |
| AI-generated claims | Unverified | T3 | Must be sourced before publication |

---

*Updated by agent workflow. Last updated: 2026-04-21.*

---

## AI Methodology and Verification Disclaimer

This registry is part of an AI-assisted case development workflow and is intended to improve transparency, not replace source-level judgment.

- Compilation method: source entries are assembled from files stored in this repository and from explicitly captured public URLs.
- Tiering method: T1/T2/T3 labels reflect source availability and verification confidence, not claim truth by themselves.
- Evidence rule: factual claims should be treated as publishable only when traceable to a dated source and corroborated in the case verification workflow.
- Publication control: unresolved metadata items (for example, missing publication dates) are treated as blockers until independently confirmed.
- Cross-check requirement: use this registry together with [verification-debt.yaml](../verification-debt.yaml), [case-study/01-Additional-Sources.md](../case-study/01-Additional-Sources.md), and [case-study/04-Quality-Verification-Log.md](../case-study/04-Quality-Verification-Log.md) before final publication.
