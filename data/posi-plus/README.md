# POSI+ v0.5 (draft proposal)

A proposal to present the SPII principles as an extension of the Principles of Open Scholarly
Infrastructure (POSI v2.0) instead of as a separate set, drafted on 2026-09-29 at the request of
SPII's principles subgroup. The background is told in the "From SPII to POSI+" part of the story on
[the 1A page](https://surf-ori.github.io/spii-1a-values-and-principles/#how-these-were-formed); the
analysis, proposal and matrix are rendered in the
[POSI+ v0.5](https://surf-ori.github.io/spii-1a-values-and-principles/#posi-plus) and
[maturity matrix](https://surf-ori.github.io/spii-1a-values-and-principles/#posi-plus-maturity-matrix)
sections.

**AI-assisted.** Both files were drafted with AI (Claude) and have not yet been reviewed by the
SPII team. Treat every verdict, mapping and drafted text as a proposal for curator review.

## `overlap-analysis-v0.5.csv`

34 rows, one per SPII item: the subprinciples of the 1A outcome (version 2026-07-08), the actions
and v0.3 matrix subprinciples that carry a distinct idea, compared with their nearest POSI v2.0
principle.

Columns: `SPII item`, `SPII source` (`1A 1.1` = subprinciple 1.1 of the July 8 outcome; `v0.3` =
[`original-maturity-matrix.csv`](../original-maturity-matrix.csv)), `POSI v2.0 counterpart`,
`Verdict` (`covered` / `partly` / `missing`), `Where it lands in POSI+`.

## `posi-plus-v0.5.csv`

The POSI+ v0.5 framework and its four-level maturity matrix: 37 principles in 8 sections — POSI's
own Governance, Sustainability and Insurance (20 principles, text verbatim from POSI v2.0), then
SPII+ Openness, Autonomy, Sustainability, Interoperability and Researcher-centric (17 SPII
additions, text drafted from the 1A outcome and the v0.3 matrix).

Columns: `Order`, `Section`, `Origin` (`POSI v2.0` or `SPII addition`), `Id`, `Principle`, `Text`,
`SPII counterparts`, `Level 1`–`Level 4`, `Level source`, `Improvement action`,
`Concepts reused from other frameworks`.

`Level source` says, per principle, which level texts are verbatim from the v0.3 matrix (kept
unchanged, typos included — see [`../README.md`](../README.md)) and which were drafted with AI. Drafted
levels follow [`.claude/skills/spii-maturity-levels/SKILL.md`](../../.claude/skills/spii-maturity-levels/SKILL.md).
`Concepts reused` names the framework in deliverable 1B's
[Principles Alignment Tool](https://surf-ori.github.io/spii-1b-principles-alignment-tool/) whose ideas
informed the wording (GORC, FAIR, BD, OSR, 7GPRI), where any did.

## Sources

- POSI Adopters (2025). *The Principles of Open Scholarly Infrastructure* (v2.0).
  [doi.org/10.14454/G8WV-VM65](https://doi.org/10.14454/G8WV-VM65), as transcribed in
  [`posi-v2.0.json`](https://github.com/surf-ori/spii-1b-principles-alignment-tool/blob/main/data/frameworks/posi-v2.0.json).
- SPII values and principles, version 2026-07-08:
  [`values-and-principles-2026-07-08.md`](../consultation/04-consultation-outcome-framework/values-and-principles-2026-07-08.md).
- SPII maturity matrix v0.3 (CC-BY): [`original-maturity-matrix.csv`](../original-maturity-matrix.csv),
  [`maturity-matrix-v0.3.pdf`](../maturity-matrix-v0.3.pdf).
