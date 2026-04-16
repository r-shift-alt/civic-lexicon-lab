# Lexicon MVP Implementation Concept Note

## Purpose

This note translates the already locked lexicon MVP into an execution-ready plan.

It exists to answer a practical question:
what exactly should be built next, in what order, and with what stop rules, so the project can reach a first proxy-user review without turning the lexicon into an open-ended research project?

This is not a new scope document.
It assumes the existing boundaries are already set in:
- `11_ARTIFACTS/LEXICON_MVP_SCOPE.md`
- `11_ARTIFACTS/LEXICON_PROOF_OF_VALUE.md`
- `11_ARTIFACTS/LEXICON_ENTRY_WORKSHEET.md`
- `11_ARTIFACTS/LEXICON_INITIAL_SOURCE_BOUNDARY.md`
- `11_ARTIFACTS/LEXICON_MINIMUM_RESEARCH_INPUTS_PILOT_SET.md`

## Working Goal

Produce a small, reviewable German-English political concept lexicon that helps bilingual or translation-adjacent political communicators make better wording, glossing, and framing decisions when direct translation is risky.

The immediate implementation goal is narrower than full MVP completion:
- prepare 3 pilot entries of reviewable quality;
- use those entries to test proof of value with proxy users;
- continue to all 8 entries only if the pilot stays bounded and practically useful.

## What the Artifact Is

The artifact is a manually curated lexicon of politically contested concepts moving between German and English.

Each entry is meant to help a user decide:
- whether a direct translation is safe;
- when a familiar equivalent distorts the source meaning;
- when a gloss or paraphrase is better;
- what framing baggage a term carries in each language context.

The lexicon is not:
- a translation engine;
- a general political ontology;
- a corpus-analysis platform;
- a theory archive;
- a multilingual scale-up project.

## Locked Version-One Boundary

Version one remains locked to:
- one language pair: German ↔ English;
- eight total concepts;
- manual curation;
- traceable public or policy usage examples;
- explicit warnings, guidance, and confidence labels;
- no requirement for a product interface beyond legible repository documents.

Implementation should treat these limits as design constraints, not placeholders.

## Primary User and Job to Be Done

Primary users:
- bilingual or translation-adjacent political communicators;
- policy-adjacent writers;
- editors and researchers who regularly move contested concepts between German and English.

Core user job:
help them choose, annotate, or explain politically contested terms without relying on false equivalence.

A successful entry should improve a real decision such as:
- whether to translate literally in a briefing or article;
- whether to keep the original German and add a gloss;
- whether a target-language term carries the wrong institutional or moral register;
- what warning to attach when a translation is usable but incomplete.

## Minimum Review Object

The first review object is not the full 8-entry lexicon.
It is a 3-entry pilot set:
1. `Solidarität` / `solidarity`
2. `soziale Marktwirtschaft` / `social market economy`
3. `Staatsbürgerschaft` / `citizenship`, with an explicit boundary note on when `Bürgersinn` is the better civic frame

This pilot set is sufficient because it tests three different difficulty types:
- moral and movement language;
- historically loaded institutional language;
- legal-status language that can blur into civic-virtue language.

## Entry Completion Standard

A pilot entry is review-ready when it includes:
- source-language term;
- closest common rendering;
- alternative renderings or paraphrases;
- short mismatch or overlap explanation;
- framing-risk note;
- false-equivalence warning where needed;
- context note;
- at least two traceable usage examples;
- practical recommendation for writers or translators;
- confidence label.

The worksheet in `11_ARTIFACTS/LEXICON_ENTRY_WORKSHEET.md` remains the drafting format.
No pilot entry should be drafted as free-form essay prose.

## Implementation Sequence

## Phase 1: convert research boundary into entry-ready packets

For each of the three pilot concepts, compile only the bounded package defined in `11_ARTIFACTS/LEXICON_MINIMUM_RESEARCH_INPUTS_PILOT_SET.md`:
- one short user-job note;
- one provisional mismatch hypothesis;
- two German sources maximum;
- two English sources maximum;
- one context clarifier;
- one drafting claim check covering overlap, mismatch, and likely advice.

The output of this phase should be a compact packet that makes drafting possible without another open research pass.

## Phase 2: draft the three pilot entries

Use the worksheet to turn each bounded packet into a full draft entry.

Drafting priority should be:
1. `Solidarität`
2. `soziale Marktwirtschaft`
3. `Staatsbürgerschaft`

That order starts with a concept where moral overlap exists but register mismatch is likely, then moves to the historically loaded institutional case, then to the legal-versus-civic-boundary case.

Each draft should aim to produce:
- one clear mismatch summary;
- one concrete warning sentence;
- one positive recommendation;
- two traceable examples;
- one explicit uncertainty note.

## Phase 3: internal quality check against proof-of-value criteria

Before any review packet is prepared, check whether the three entries actually satisfy the proof-of-value object:
- all core fields are present;
- at least two entries count as high-friction cases rather than easy dictionary cases;
- the entries contain practical wording guidance rather than internal analysis only;
- a reviewer could understand how to use the entry without verbal explanation.

If they fail this check, revise the entries before expanding the contribution surface.

## Phase 4: proxy-user review packet

Once the three entries are draft-ready, package them for the first proxy-user review using `12_REVIEWS/LEXICON_PROXY_REVIEW_ROUTINE.md`.

The review packet should ask reviewers to identify:
- whether the problem feels real;
- what parts were actually useful;
- what changed their wording or translation judgment;
- what should be cut for being analytical but not useful;
- whether they would want more entries in the same format.

## Phase 5: continue, revise, or stop

After the first review:
- continue if the success threshold in `11_ARTIFACTS/LEXICON_PROOF_OF_VALUE.md` is met;
- revise if the problem is real but the format is too dense or uneven;
- stop or demote the lexicon if utility is weak or drafting shows chronic scope drift.

## Bounded Research Rule

Research is allowed only to the extent needed to support:
- one plain-language mismatch summary;
- one framing-risk note;
- one warning;
- one practical recommendation;
- two traceable examples.

If a concept keeps demanding:
- long historiography;
- extensive ideological mapping;
- large source expansion;
- adjacent concept essays just to remain coherent,
then the correct response is to tighten the claim or question the concept's fit for version one, not to keep reading indefinitely.

## Shared Source Strategy

To keep the pilot set legible and maintainable, use a shared-source-first approach.

Preferred reusable source classes:
- German institutional or party materials;
- German journalism or commentary;
- English institutional, policy, or explanatory materials;
- English journalism or commentary.

Entry-specific sources should be added only when the shared pool cannot support an honest claim.

## Drafting Guidance by Pilot Concept

## `Solidarität`

The draft should focus on whether the term is being used as:
- institutional social obligation;
- labor-linked cohesion;
- welfare-state justification;
- movement rhetoric.

The likely implementation challenge is not dictionary meaning but register mismatch.
The entry should help a writer see when `solidarity` is close enough and when it sounds too movement-coded, too moralized, or too thin for the German use.

## `soziale Marktwirtschaft`

The draft should treat this term as a historically loaded institutional formula, not as a generic label for moderated capitalism.

The entry should clarify:
- when literal translation is necessary;
- why the English phrase is often insufficient on its own;
- what minimum gloss preserves the missing context.

The implementation challenge here is preserving historical and institutional baggage without forcing a full economic-history detour.

## `Staatsbürgerschaft`

The draft should keep legal membership separate from broader civic language.

The entry should clarify:
- when `citizenship` is a clean rendering;
- when adjacent discourse is really about civic ethos or public-mindedness;
- why `Bürgersinn` should appear as a boundary note rather than be merged casually into the same English label.

The implementation challenge here is avoiding collapse between status and virtue language.

## Practical Output Standard

At the end of the pilot drafting sequence, the repository should contain:
- this implementation concept note;
- three draft entries using the worksheet structure;
- enough reviewer-facing material to run the first proxy-user review;
- clear contributor-facing follow-on work derived from the drafts.

That is the smallest meaningful package that can test whether the lexicon deserves continuation as the lead artifact.

## Public-Repo Implication

This concept note is public-facing enough to live in the repository because it does three useful things for contributors:
- explains what the project is building now;
- makes the immediate execution path legible;
- clarifies where outside help can become concrete next.

It should be followed by public contribution surfaces tied to the pilot entries, not by more abstract planning notes.

## Immediate Next Tasks Implied by This Note

1. Create the bounded research-and-drafting packet for `Solidarität`.
2. Draft the `Solidarität` pilot entry using the worksheet.
3. Repeat for `soziale Marktwirtschaft` and `Staatsbürgerschaft`.
4. Convert the resulting pilot set into issue-ready contribution prompts and a compact review packet.

## Working Conclusion

The lexicon now has enough scope, evidence, and review structure to move from planning into bounded production.
The next risk is no longer lack of framing.
The next risk is failure to turn the bounded design package into actual pilot entries.

So the implementation rule from here is simple:
use the minimum research boundary, draft the three pilot entries, and let the first review cycle decide whether the lexicon continues to earn expansion.
