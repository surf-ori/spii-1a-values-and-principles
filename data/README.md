# Data

## `original-maturity-matrix.csv`

The original SPII values maturity matrix, extracted verbatim from
[tillbey/open-science-maturity](https://github.com/tillbey/open-science-maturity)
(commit `1a4e16f`), the draft that later became deliverable 1B's
[maturity assessment tool](https://github.com/surf-ori/spii-1b-maturity-assessment-tool).

It scores 13 subprinciples, grouped under 4 values (Open, Autonomy, Sustainable, Usable), each
on a 5-point scale: 0 (not yet assessed) plus 4 defined maturity levels.

This was an early, unfinished draft (marked "DRAFT – WORK IN PROGRESS" in the source) — most
level descriptions are still placeholder text (`...` or "Maturity level N"), and typos in the
original (e.g. "forseeable", "Structually", "Continously") are kept as-is for faithful
extraction rather than corrected. Consult the source repo before citing any of its content as
final.

Columns: `group`, `group_note`, `subprinciple`, `subprinciple_note`, then `level_N_name` /
`level_N_description` pairs for N = 1–4.

Rendered as a table on this repo's [index.html](../index.html#original-maturity-matrix).
