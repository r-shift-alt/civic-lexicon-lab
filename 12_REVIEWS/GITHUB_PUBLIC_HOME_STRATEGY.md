# GitHub Public Home Strategy

## Purpose

Use GitHub as the project's public home in a way that supports contribution, inspiration, and durable collaboration without collapsing the distinction between internal architecture and public-facing artifacts.

## Trigger

The project should no longer live only as a local planning environment.
It should gain a public home that gives serious heavy-AI practitioners a concrete, inspectable use case they can join.
The GitHub repository should be treated as the ongoing home of the project, not as a one-off publication mirror.

## Strategic Constraint

The existing operating rules still apply:
- do not default to manifesto-writing;
- do not confuse hidden architecture with public-facing outputs;
- prefer bounded artifacts over broad branding;
- let public narrative lag demonstrated usefulness.

## Recommended Public Model

The public repository should be an artifact-first collaboration layer.
That means the repo should foreground:
- current useful artifacts,
- methods,
- contribution pathways,
- review logic,
- explicit scope boundaries.

It should not foreground the full internal ideological or architectural stack.

## What should likely be public first

1. README.md
2. CONTRIBUTING.md
3. bounded artifact specs that external contributors can inspect and improve
4. entry worksheets and review routines
5. selected decision summaries that matter for contributors
6. pilot entries and their evidence trail

## What should likely stay internal for now

1. live session state files used for autonomous continuity
2. next-action queues that are mostly private operator scaffolding
3. broad internal architecture notes that are not yet useful to contributors
4. any premature framing that invites ideology-first reading before artifact usefulness is visible

## Minimum Repository Restructure Before Publishing

1. decide which current files are public-safe as-is
2. separate internal operator files from public collaboration files
3. create a clean root-level repository narrative
4. define the first issues or contribution prompts
5. initialize git and publish only after the public layer is coherent

## Immediate Practical Steps

1. draft public-facing repository documents
2. classify existing files into public, internal, or needs-redaction
3. move or exclude internal state-management files before first push
4. publish the first bounded artifact materials with a clear collaboration ask
5. open contribution around the first three pilot lexicon entries
6. define a lightweight ongoing maintenance rhythm for the public repo: update notes, issue prompts, and visible next contribution surfaces
7. ensure each new internal planning increment can cash out into a public-facing artifact, rationale note, issue, or review packet where appropriate

## Success Condition

A new contributor landing on the repository should be able to understand within a few minutes:
- what the project is,
- what the current artifact is,
- why it matters,
- what remains intentionally non-public,
- and exactly how to help.

## Main Risk

If the repository goes public before this separation is clear, outside readers may encounter hidden-architecture material, planning scaffolding, or ideology-adjacent framing before they encounter practical value.
That would reactivate the manifesto-first trap in a new form.

## Recommended Next Step

Create a file-by-file public/private classification and use it to decide what the first public commit should contain.
