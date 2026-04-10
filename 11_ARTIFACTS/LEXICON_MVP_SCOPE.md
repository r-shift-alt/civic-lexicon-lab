# Lexicon MVP Scope

## Purpose

This document defines the minimum viable scope of the first artifact: a German-English concept lexicon with framing notes for translation-adjacent political communicators and policy-adjacent writers.

The goal of version one is not broad coverage. The goal is to produce a small, credible, clearly useful artifact that helps users handle politically contested concepts across German and English with less distortion.

## Primary User Group

Primary users:
- bilingual or translation-adjacent political communicators;
- policy-adjacent writers;
- editors or researchers who regularly move concepts between German and English.

Core job to be done:
- help users choose, explain, and annotate politically contested terms across German and English without relying on false equivalence or flattening context.

Typical use moments:
- translating an op-ed, briefing, campaign note, or policy explainer;
- deciding whether a direct translation is safe or misleading;
- explaining why one apparent equivalent carries different baggage in the other language;
- choosing between literal translation, contextual paraphrase, or explicit gloss.

## Version-One Design Constraint

Version one must be small enough that:
- all entries can be manually reviewed;
- evidence quality can be checked entry by entry;
- maintenance remains realistic without a full data pipeline;
- usefulness is visible from a short pilot review cycle.

If the artifact grows beyond those constraints, it is no longer an MVP.

## Locked Initial Language Pair

Version one language pair:
- German ↔ English

Why this pair:
- it matches the selected primary user group;
- it is narrow enough for disciplined manual curation;
- it supports later comparative expansion without requiring multilingual infrastructure now;
- it has many politically charged near-equivalents where direct translation creates strategic distortion.

## Initial Concept Set

Version one should start with 8 concepts.

Selected initial concept set:
1. Solidarity / Solidarität
2. Social market economy / soziale Marktwirtschaft
3. Redistribution / Umverteilung
4. Welfare state / Sozialstaat
5. Citizenship / Staatsbürgerschaft / Bürgersinn depending on context
6. Integration / Integration
7. Security / Sicherheit
8. Freedom / Freiheit

Why this concept set:
- each term is politically contested rather than purely technical;
- the set mixes institutional, economic, civic, and value-laden concepts;
- the terms are common enough to matter in real communication work;
- the set is small enough to make full manual completion plausible.

Selection rule for keeping or replacing concepts:
- a concept should stay in version one only if it creates a real translation or framing dilemma between German and English;
- if a concept proves too broad or too trivial, replace it rather than expanding the MVP.

## What Counts as a Complete Entry

A version-one entry is complete only if it contains all required fields below.

Required fields:
1. Concept label in the source language
2. Closest common rendering in the target language
3. Alternative renderings or paraphrases
4. Short plain-language explanation of the mismatch or overlap
5. Framing risk note
6. False-equivalence warning, if applicable
7. Context note describing where the term is commonly used or misunderstood
8. At least two real usage examples, with at least one from each language if feasible
9. Translator or writer recommendation
10. Confidence label

An incomplete entry may be kept internally as draft material, but it does not count toward MVP completion.

## Entry Template

### Entry Header
- Entry ID
- Source language term
- Target language renderings
- Domain tags
- Status: draft / review / complete

### Core Meaning Block
- concise working definition in source-language context
- concise working definition in target-language context
- overlap summary
- mismatch summary

### Framing Block
- why the term is politically contested
- likely framing baggage in German usage
- likely framing baggage in English usage
- when literal translation is safe
- when literal translation is misleading

### Guidance Block
- recommended rendering by context
- when to preserve the original term and gloss it
- when to paraphrase instead of translating literally
- short warning sentence a writer or translator could reuse

### Evidence Block
- example quote or usage from German context
- example quote or usage from English context
- source metadata for each example
- reviewer note
- confidence label: high / medium / low

## Acceptable Evidence Types

Acceptable evidence for version one:
- public speeches
- party programs or policy documents
- major newspaper or magazine usage
- think-tank or NGO reports
- government or parliamentary texts
- reputable commentary where the usage itself is illustrative

Preferred evidence rule:
- use examples that show actual public or policy usage, not only dictionary definitions.

Minimum evidence threshold per entry:
- at least two real usage examples;
- at least one explanatory synthesis written by the project;
- enough source detail that another reviewer can trace the examples.

Nice-to-have but not required in version one:
- more than two examples per language;
- corpus frequency data;
- systematic diachronic analysis;
- formal academic literature review for every entry.

## Evidence Standards

Each complete entry should meet these standards:
- examples must be attributable to a named source or publication;
- the mismatch claim must be tied to evidence, not asserted rhetorically;
- uncertainty must be labeled where the term is context-dependent;
- recommendations should be practical enough that a user could act on them immediately.

## Explicit Version-One Exclusions

Version one will not attempt:
- more than one language pair;
- more than 8 complete concepts;
- exhaustive definitions of national political traditions;
- a full ontology of left, liberal, or nationalist vocabulary;
- automated translation suggestions;
- a dashboard, API, or full public interface;
- quantitative discourse analysis;
- universal style rules detached from context;
- a complete ethical persuasion framework.

## Maintenance Boundary

To keep maintenance realistic, version one assumes:
- manual curation;
- static or slow-moving entries rather than constant updates;
- versioned revisions only when a substantial clarification is needed;
- no obligation to track every new media usage.

Recommended maintenance stance:
- better a small stable lexicon with credible notes than a large unstable one.

## MVP Completion Condition

The MVP is complete when all of the following are true:
- 8 entries are complete according to the required fields;
- each entry has traceable evidence;
- each entry contains at least one clear translation or framing warning;
- the artifact can be reviewed by at least a small set of proxy users without needing additional architecture to understand it.

## Immediate Follow-On Tasks

After scope is locked, the next tasks are:
1. define the proof-of-value threshold for the first review cycle;
2. create a lightweight review routine for proxy users;
3. create the first entry worksheet or template file;
4. define the minimum source list for the 8 concepts.

## Fallback Rule

If the first 2 or 3 entries reveal that the concept mismatch logic is too diffuse, too subjective, or too maintenance-heavy to keep bounded, stop expansion and switch to the campaign knowledge transfer template as the safer first artifact.

## Current Recommendation

Proceed with the German-English lexicon MVP exactly as a bounded manual artifact, not as the beginning of a general multilingual platform.
