# CLAUDE.md

Agent context for working on the `spii-1a-values-and-principles` repository.

## What this repo is

The feedback and issue tracker for SPII deliverable 1A, Values and Principles — and, since
2026-09-17, also the home of the deliverable's actual content: `index.html` carries the outcome
table (three values, five principles, version July 8, 2026), a journalistic story on how it was
formed from a July 1, 2026 national consultation, the earlier draft maturity matrix this
framework grew out of, and a full transparency archive of every source file under
`data/consultation/` (originals plus converted `.md`/`.csv`/`.pdf` copies). See
`data/consultation/README.md` for what's in the archive and how the conversions were made, and
`data/README.md` for the maturity-matrix CSV's own provenance. Application code beyond this
static page is still out of scope.

## Issue template

`.github/ISSUE_TEMPLATE/feedback.yml` collects name, organisation, role, and "representing
infrastructure" alongside the feedback itself, so the origin of each issue stays traceable. See
`AGENTS.md` for how to process incoming issues.

## Way of working

See the "Way of working" section on
[spii-overview](https://surf-ori.github.io/spii-overview/#way-of-working) for the full process: a
curator triages each issue and records the outcome (accepted, rejected, or already covered)
directly on the issue with a short rationale before closing it. Curators are not yet assigned for
this deliverable. Until one is, leave issues open for a human curator rather than closing them on
your own judgement.

## AI-generated content

If an agent drafts a closing comment or decision on an issue here, that comment is
public-interest text about a policy deliverable. Follow the `eu-ai-act-transparency-label-for-ai-generated-content` skill:
say plainly in the comment that it was drafted with AI assistance, mirroring the disclosure
already on the spii-overview page. `index.html` itself carries the same kind of disclosure
(`.ai-disclosure` badge in the hero) for its own AI-drafted "how these were formed" story — update
its wording, not remove it, once a named person has actually reviewed that text end to end.

## Conventions

- English throughout.
- No code changes are expected in this repo beyond `.github/` configuration and these context
  files.
