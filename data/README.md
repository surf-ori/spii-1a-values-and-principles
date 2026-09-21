# Data

## `original-maturity-matrix.csv`

The SPII values maturity matrix, now at version 0.3, extracted verbatim from
[`maturity-matrix-v0.3.pdf`](maturity-matrix-v0.3.pdf) (Till Bey, CC-BY licensed), shared by
email on 2026-09-21. It supersedes the earlier draft extracted from
[tillbey/open-science-maturity](https://github.com/tillbey/open-science-maturity)
(commit `1a4e16f`) — the same lineage that later became deliverable 1B's
[Principles Alignment Tool](https://github.com/surf-ori/spii-1b-principles-alignment-tool).

It scores 17 subprinciples, grouped under 4 values (Openness, Autonomy, Sustainable, Researcher
centric), each on a 5-point scale: 0 (not yet assessed) plus 4 defined maturity levels.

This is still an unfinished draft — six subprinciples (Open to participation, Clear
responsibilities, Institutionally embedded, Seamless user-experience, Accessible to all,
Recognition and rewards) have no level descriptions yet at all, and several others are only
partly filled in (`...` or "Maturity level N" placeholders). Typos in the source (e.g.
"forseeable", "Continously") are kept as-is for faithful extraction rather than corrected.
v0.3 also dropped a few level descriptions the earlier draft had started (e.g. "Structually
funded" for Financially secure's level 4, and the elaboration on Interconnected's level 2) —
that's a change in the source itself, not an extraction error. Consult Till Bey before citing
any of its content as final.

Columns: `group`, `group_note`, `subprinciple`, `subprinciple_note`, then `level_N_name` /
`level_N_description` pairs for N = 1–4.

Rendered as a table on this repo's [index.html](../index.html#original-maturity-matrix).
