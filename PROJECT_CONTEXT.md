# Project Context

Quick reference for session continuity. Auto-maintained by skills — you do not need to edit this manually.

## Project Overview

**Repository**: Unilever case study project
**Type**: Individual case study repository
**Version**: 3.1.0
**Course**: ITEC-617, American University Kogod School of Business, Spring 2026
**Purpose**: Develop an HBR-style MBA case study on Unilever's Google Cloud partnership

## Current Status

**Phase**: Draft package complete, final verification and publication hardening in progress

**Agentic Tool Paths**:
- [x] Claude Code — 16 `/slash-commands` via `.claude/skills/`
- [x] VS Code + GitHub Copilot — Agent Mode via `.github/copilot-instructions.md`
- [x] Chat Tools — Starter prompt via `STARTER_PROMPT.md`

**Documents**:
- [x] Additional Sources - structured bibliography, quote themes, data exhibit, and timeline completed (`case-study/01-Additional-Sources.md`)
- [x] Main Case - full draft completed with discussion questions and instructor cold-call opener (`case-study/02-Main-Case.md`)
- [x] Technical Supplement - completed with market context, competitive landscape, frameworks, and glossary (`case-study/03-Technical-Supplement.md`)
- [x] Quality Verification Log - completed with fact-check outcomes and correction register (`case-study/04-Quality-Verification-Log.md`)
- [ ] Teaching Note - not started

## Source Quality

**Source Registry**: Populated and expanded with financial, transcript, trade, and analyst sources
**Tier Breakdown**: T1: 10 | T2: 0 | T3: 0
**Last Assessment**: 2026-04-21
**Assessment Result**: AMBER (sufficient for draft-quality case, with residual publication blockers on selected claim/date precision)

## Verification Debt

**Open Items**: 3 flagged precision risks (see verification tracker)
**Last Updated**: 2026-04-21
See `verification-debt.yaml` for details.

## Key Decisions Made

- v3.0.0: Conversation-first, skill-driven architecture with 16 slash commands
- v3.1.0: Added VS Code + GitHub Copilot as second agentic path (free via GitHub Education)
- Copilot instructions mirror CLAUDE.md behavioral guidance with skill equivalents table
- README Step 3 presents three options: Option A (Claude Code), Option B (VS Code + Copilot), Option C (Chat Tools)

## Testing History

- Rob Silverman (beginner): Chat tool path tested — exposed UX issues fixed in v3.0.0
- Leif's Moderna case (power-user): Full Claude Code path tested — exposed verification and bias issues fixed in v3.0.0
- Copilot Agent Mode (v3.1.0): Two tests passed — status check and source assessment both used correct terminology and process model

## Next Steps

1. Close remaining flagged claims or maintain explicit caveats for publication
2. Complete publication-date metadata for any remaining local PDFs that still lack recoverable date evidence
3. Draft `case-study/05-Teaching-Note.md` aligned to Exhibits A-D and verification controls
