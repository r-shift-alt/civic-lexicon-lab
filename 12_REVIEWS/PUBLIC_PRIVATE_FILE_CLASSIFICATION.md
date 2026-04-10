# Public / Private File Classification

## Purpose

This note defines which current files should be public in an initial GitHub repository, which should remain internal, and which need editing before publication.

The goal is to make the first public commit useful to contributors while keeping internal operator scaffolding and premature hidden-architecture material out of the default public surface.

## Classification Rules

### Public
Safe to publish because the file is either contributor-facing, artifact-facing, or necessary for repository comprehension.

### Internal
Should stay local for now because it is mainly autonomous operator scaffolding, live state management, or broader hidden architecture that does not yet help outside contributors.

### Needs Redaction / Split
Potentially publishable later, but should first be edited, excerpted, or split into a contributor-facing version and an internal version.

## File-by-File Classification

### Public now
- `README.md`
- `CONTRIBUTING.md`
- `11_ARTIFACTS/LEXICON_MVP_SCOPE.md`
- `11_ARTIFACTS/LEXICON_PROOF_OF_VALUE.md`
- `11_ARTIFACTS/LEXICON_ENTRY_WORKSHEET.md`
- `11_ARTIFACTS/LEXICON_INITIAL_SOURCE_BOUNDARY.md`
- `12_REVIEWS/LEXICON_PROXY_REVIEW_ROUTINE.md`
- `12_REVIEWS/GITHUB_PUBLIC_HOME_STRATEGY.md`

### Internal for now
- `00_MISSION.md`
- `01_VISION.md`
- `02_MASTERPLAN.md`
- `03_OPERATING_RULES.md`
- `04_RISKS.md`
- `05_DECISION_LOG.md`
- `06_STATE.md`
- `07_NEXT_ACTIONS.md`
- `08_IDEA_ARCHIVE.md`
- `12_REVIEWS/AUTONOMOUS_MODE_LOG.md`
- `12_REVIEWS/HERMES_HANDOFF_SUMMARY.md`

### Needs redaction or split before publication
- `10_RESEARCH/INITIAL_RESEARCH_QUESTIONS.md`
  - likely useful later, but should be reduced to contributor-relevant research prompts rather than exposing all exploratory breadth
- `11_ARTIFACTS/FIRST_ARTIFACT_OPTIONS.md`
  - contains useful context, but should be converted into a short public rationale note rather than exposing the full internal comparison history
- `12_REVIEWS/FIRST_STRATEGIC_REVIEW.md`
  - contains valuable reasoning, but should be rewritten as a contributor-facing project rationale or retrospective
- `05_DECISION_LOG.md`
  - some decisions are contributor-relevant, but the file should become a curated public decisions summary instead of a full internal log

## Recommended First Public Commit Shape

### Root
- `README.md`
- `CONTRIBUTING.md`

### Public artifact folder
- `11_ARTIFACTS/LEXICON_MVP_SCOPE.md`
- `11_ARTIFACTS/LEXICON_PROOF_OF_VALUE.md`
- `11_ARTIFACTS/LEXICON_ENTRY_WORKSHEET.md`
- `11_ARTIFACTS/LEXICON_INITIAL_SOURCE_BOUNDARY.md`

### Public review / method folder
- `12_REVIEWS/LEXICON_PROXY_REVIEW_ROUTINE.md`
- `12_REVIEWS/GITHUB_PUBLIC_HOME_STRATEGY.md`

## Recommended Pre-Publish Edits

1. create a short public decisions summary derived from internal decision log entries
2. create a contributor-facing research prompts note derived from `10_RESEARCH/INITIAL_RESEARCH_QUESTIONS.md`
3. decide whether internal files should be moved into a clearly non-public folder or excluded via `.gitignore` before repo publication
4. prepare the first three pilot-entry issue prompts so contributors land on concrete work immediately

## Main Publication Risk

If internal files such as `06_STATE.md`, `07_NEXT_ACTIONS.md`, or broad hidden-architecture notes are published too early, outside readers may misread operator scaffolding as the product itself.

## Recommended Next Operational Step

Create the first public decisions summary and a minimal `.gitignore` or repository split plan before initializing the public repository.
