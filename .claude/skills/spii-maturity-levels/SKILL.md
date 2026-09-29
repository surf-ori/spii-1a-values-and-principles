---
name: spii-maturity-levels
description: Draft or revise the four-level maturity descriptions (Level 1 to Level 4) for subprinciples in the SPII alignment tool, for example in data/frameworks/spii-alignment-v0.3.json. Use this skill whenever the user asks to write, fill in, complete, tighten or review level descriptions, rubric text, "criteria" or "improvementAction" fields for a maturity matrix, or mentions subprinciples that have no level descriptions yet, even if they do not say "maturity".
---

# SPII maturity level descriptions

This skill helps draft the rubric text that sits under Level 1 to Level 4 for each subprinciple of an Open Science infrastructure in the SPII principles alignment tool. It is based on a comparison of four public maturity frameworks and on the style already present in the repository.

## Where the descriptions live

Each framework is a JSON file under data/frameworks/. In spii-alignment-v0.3.json every subprinciple has an id, a title, a text, and optionally a criteria object with the keys level-1, level-2, level-3 and level-4, plus an improvementAction. Six subprinciples have no criteria yet (Open to participation, Clear responsibilities, Institutionally embedded, Seamless user-experience, Accessible to all, Recognition and rewards). Financially secure has only three levels and needs a Level 4. Several other descriptions are one or two words and could be made more concrete.

## What the four levels mean in general

The scale follows the shared shape of the UK 7 Lenses matrix, the Australian evaluation maturity matrix (Beginning, Developing, Embedded, Leading), the US OMB Enterprise Architecture Assessment Framework and the Veritis DevOps model (Base to Expert). Those frameworks use four or five steps and all move along the same few axes: from ad hoc to planned, from dependent on individuals to embedded in the institution, from internal to open and shared, from unmeasured to evidenced, and from inward looking to a reference for others.

Level 1 is nothing done. There is no practice, no documentation and no owner, or the situation is simply unknown. The description states the situation neutrally and does not blame. It often reads as a negation, such as "X is not available" or "There is no Y".

Level 2 is a start. Something exists, but it is partial, covers only the core, is informal, or depends on one or two people. It works today without a guarantee for tomorrow. The typical signal is "some", "ad hoc" or "one person".

Level 3 is established. The practice is systematic, documented, owned by a named role or body, and applied across the infrastructure. It is usually still bounded: access has restrictions, coverage is mostly rather than fully complete, or the evidence is internal. This is the level a well run infrastructure can realistically reach in a few years.

Level 4 is the vision. It is full, open to everyone, verified from outside (audit, certification, community review), shared with and shaped by the community, and continuously improved. Others take the infrastructure as an example. Level 4 is deliberately ambitious and may be out of reach for most infrastructures today. It describes where the field should be heading, not what is expected now. It should still be concrete enough that a reader can recognise it.

## How to write a good description

Keep the subject of the sentence the same across the four levels so the reader sees one thing getting better and not four different things. Change one or two axes per step, not all at once. Each level must include everything the previous level says, so the steps are cumulative, as in the US framework.

Write observable statements. A reader should be able to tell from evidence, a link or a short conversation whether the description is true. Avoid adjectives such as good, strong or mature without saying what makes them so. Prefer concrete markers: published, documented, reviewed yearly, audited, elected, two-way, open licence, exit plan.

Keep each description to one or two sentences, roughly 25 words at most, in plain English. Match the tone of the existing descriptions, for example "Only proprietary software is used." at Level 1 and "Full engagement in an open source community." at Level 4. Avoid jargon that a curator from another discipline would not know, and write out acronyms on first use.

Use the same vocabulary for the same idea in every subprinciple. Restricted access, mostly, fully, documented, recorded, published, audited and certified should mean the same thing wherever they appear.

Do not invent quantitative thresholds. The US framework can use percentages because it has legal mandates behind them. For SPII, only add a number when the source material or the curators already give one.

## Working procedure

Read the target JSON file and list the subprinciples that lack criteria, have fewer than four levels, or have descriptions of only a word or two. Ask the user which ones to work on if the request is not specific.

For each subprinciple, read its title, text and improvementAction, and read the neighbouring subprinciples in the same section so the wording stays consistent. Check the SPII 1A values and principles repository (surf-ori/spii-1a-values-and-principles) for context on the intended meaning.

Draft the four levels following the general definitions above. Then write or update the improvementAction as one sentence that names the move from the most likely current level toward the next one, in the style of the existing entries.

Do not overwrite existing descriptions unless the user asks for it. The current text was transcribed from a table shared by Till Bey under CC-BY, so keep it verbatim where it exists and propose changes separately, for example as a short list of suggested edits in the pull request description. Mark new text as a proposal for curator review, since the repository has a feedback process in which a curator accepts or rejects changes.

Keep the JSON valid, use the existing key names (level-1 to level-4), keep the file's indentation, and if a section text still says "No explanatory text provided in the source matrix yet" leave it alone unless asked.

When you finish, give the user a compact overview per subprinciple with the four drafted levels, and point out any place where the four levels could not be made cumulative or where the meaning of the subprinciple was unclear and a curator decision is needed.

## Quick self-check before handing over

Read the four descriptions of one subprinciple in order. Level 1 should feel like nothing, Level 2 like a fragile start, Level 3 like something you can rely on, and Level 4 like something you would show at a conference as the example. If two neighbouring levels could be swapped without anyone noticing, rewrite them until the difference is one clear step.

## Sources used for the general scale

The UK Government 7 Lenses of Transformation maturity matrix (five levels, from competing or absent to embedded and leading). The Department of Industry, Science and Resources evaluation maturity matrix for Australia 2024 to 2028 (Beginning, Developing, Embedded, Leading). The US OMB Enterprise Architecture Assessment Framework version 3.1 of June 2009 (five cumulative levels with evidence artifacts). The Veritis DevOps maturity model (Base, Beginner, Intermediate, Advanced, Expert).
