# Step 5: Quality and Accuracy Verification Log (Exhibit D)

## Status

Prepared on 2026-04-21.

This log documents fact-checking, error detection, corrections, and verification methods used before treating the case package as publication-ready.

## AI Methodology and Verification Disclaimer

This verification log was AI-assisted in drafting structure and language, with source validation performed against repository and cited public materials.

- Scope limit: this log reflects checks run during the documented drafting window and may not cover later edits unless updated.
- Evidence rule: only claims with traceable source support are treated as verified.
- Blocker rule: any claim marked flagged or unresolved in [verification-debt.yaml](../verification-debt.yaml) remains non-publishable unless caveated or newly verified.
- Cross-document control: this log should be used jointly with [case-study/01-Additional-Sources.md](01-Additional-Sources.md) and [case-study/02-Main-Case.md](02-Main-Case.md).

---

## 1. Verification Method

### 1.1 Scope Reviewed
- Main narrative: `case-study/02-Main-Case.md`
- Additional sources package: `case-study/01-Additional-Sources.md`
- Technical supplement: `case-study/03-Technical-Supplement.md`
- Verification tracker: `verification-debt.yaml`

### 1.2 Source Priority Rule
Claims were accepted only when traceable to:
1. Primary documents in repository (annual report, earnings transcript, local PDFs).
2. Official Unilever pages with dated content.
3. Clearly identified trade/analyst sources where attribution was explicit.

Any claim lacking traceable support was either:
- removed,
- explicitly caveated, or
- retained in verification debt as unresolved.

---

## 2. Factual Claim Checks and Outcomes (Exhibit D1)

| Claim Category | Example Claim | Verification Result | Action Taken |
|---|---|---|---|
| Financial baseline | FY2025 turnover EUR 50.5B; underlying operating profit EUR 10.1B | Verified | Retained in Main Case and Additional Sources tables |
| Segment margins | Beauty and Wellbeing 19.2%; Personal Care 22.6%; Home Care 14.9% | Verified | Retained with transcript attribution |
| Cost program | EUR 800M productivity program on track for 2026 completion | Verified | Retained with transcript wording |
| Leadership transition | Esi stood down 31 Dec 2025, left 31 Jan 2026; Leandro appointed CMO | Verified | Updated narrative and source tables to exact dates |
| Sketch Pro disclosure | AI-powered design capabilities via Sketch Pro | Verified | Upgraded from unresolved to verified and retained |
| Agentic shopping deployment scope | Framed as active operational reality everywhere | Not fully verified as scaled rollout | Reframed as strategic intent; retained with caveat |
| Google Cloud mention in FY2025 annual report | Explicit mention in annual report | Not found | Marked flagged; prevented misuse as annual report fact |
| 23,000 trained / 500+ AI projects / go wide and go deep | Internal AI scale claims | Not verified in current source base | Excluded from case narrative and retained as unresolved debt |

---

## 3. Fabricated or Potentially Fabricated Details Caught

### 3.1 Items Caught and Corrected

1. Sketch Pro originally treated as unverified.
- Initial state: marked as not found.
- Correction: verified in annual report text and status updated to verified.

2. CMO transition date originally inferred from publication windows.
- Initial state: inferred from article dates.
- Correction: replaced with exact annual report personnel dates.

3. CEO timing wording risk (late 2025/early 2026).
- Initial state: phrasing risked date inaccuracy.
- Correction: claim flagged; exact appointment date left unresolved pending explicit appointment source.

4. Agentic shopping language overstretch risk.
- Initial state: could be read as broad deployment proof.
- Correction: reframed as strategy direction, not confirmed enterprise-wide execution.

### 3.2 Items Removed or Not Used Due Verification Risk
- 23,000 employees trained on GenAI.
- 500+ AI projects globally.
- "Go wide and go deep" framework language.

---

## 4. Narrative-Reality Consistency Check

### 4.1 Check Question
Does the case narrative reflect what sources actually say, without forcing a cleaner story than evidence supports?

### 4.2 Result
Mostly aligned after corrections.

What was adjusted to maintain reality alignment:
- Kept unresolved strategic tensions open rather than implying solved execution outcomes.
- Preserved ambiguity where evidence supports intent but not scaled proof.
- Anchored quantitative claims to named documents and dates.
- Separated verified outcomes (for example Lighthouse metrics) from directional ambition (agentic commerce narrative).

Residual risk:
- Some trade/analyst framing language is interpretive by nature; these sources are used as perspective, not as sole evidence for core financial or governance claims.

---

## 5. Error and Correction Register (Exhibit D2)

| ID | Issue Found | Where Found | Correction | Verification Basis |
|---|---|---|---|---|
| QC-01 | Sketch Pro treated as unresolved | Verification debt and AI research notes | Marked verified and used with citation | Annual report text on Sketch Pro |
| QC-02 | CMO transition date inferential | Leadership timeline | Replaced with exact effective and exit dates | Annual report personnel updates |
| QC-03 | Google Cloud in FY2025 annual report assumption risk | Additional sources verification list | Marked flagged as not present | Full-text search outcome + publication timing |
| QC-04 | Agentic shopping interpreted as deployed state | Main case strategy section | Reworded to strategy intent/caveat | Q4 transcript language context |
| QC-05 | Unverified AI scale metrics contamination risk | Draft notes and research synthesis | Excluded from final narrative | No traceable source found |

---

## 6. Current Publication Readiness View

### 6.1 Ready
- Main Case narrative with caveated strategy statements.
- Technical Supplement with frameworks, trends, and glossary.
- Additional Sources with structured bibliography, quote themes, data table, and timeline.

### 6.2 Still Open (Must remain caveated or be resolved)
- 23,000 employees trained claim.
- 500+ projects claim.
- "Go wide and go deep" phrase.
- Exact formal CEO appointment date (if needed for final publication precision).

---

## 7. Verification Control Rule for Next Drafting Steps

Before adding any new statistic, quote, or date:
1. Identify exact source document and date.
2. Confirm language is direct or clearly labeled as interpretation.
3. Record unresolved items immediately in `verification-debt.yaml`.
4. If not verifiable, remove from narrative rather than soften with vague phrasing.

This rule is intended to prevent plausible-but-unsourced drift in subsequent supplements and teaching note drafts.