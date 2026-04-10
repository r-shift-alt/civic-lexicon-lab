# GitHub Repo Bootstrap

## Proposed Repository
- GitHub owner: `r-shift-alt`
- Proposed repo name: `civic-lexicon-lab`
- Proposed URL: `https://github.com/r-shift-alt/civic-lexicon-lab`

## Why this name
The name is descriptive without sounding like ideology-first branding.
It stays close to the current first artifact while leaving room for the project to grow into a broader public-interest communication infrastructure project.

It works because:
- `civic` keeps the public-interest orientation visible;
- `lexicon` reflects the current bounded artifact honestly;
- `lab` signals an active workshop and contribution surface rather than a finished doctrine.

## Recommended Public Repo Shape
The first public repo should include:
- `README.md`
- `CONTRIBUTING.md`
- `11_ARTIFACTS/LEXICON_MVP_SCOPE.md`
- `11_ARTIFACTS/LEXICON_PROOF_OF_VALUE.md`
- `11_ARTIFACTS/LEXICON_ENTRY_WORKSHEET.md`
- `11_ARTIFACTS/LEXICON_INITIAL_SOURCE_BOUNDARY.md`
- `10_RESEARCH/CONTRIBUTOR_RESEARCH_PROMPTS.md`
- `12_REVIEWS/PUBLIC_DECISIONS_SUMMARY.md`
- `12_REVIEWS/LEXICON_PROXY_REVIEW_ROUTINE.md`
- `12_REVIEWS/GITHUB_PUBLIC_HOME_STRATEGY.md`
- `12_REVIEWS/PUBLIC_PRIVATE_FILE_CLASSIFICATION.md`
- `12_REVIEWS/PUBLIC_REPO_OPERATING_RHYTHM.md`

The internal planning files remain local for now via `.gitignore`.

## Current Technical Status
- local git repository: should be initialized in `./dot-r`
- branch name: `main`
- remote name: `origin`
- remote target: `git@github.com:r-shift-alt/civic-lexicon-lab.git` or `https://github.com/r-shift-alt/civic-lexicon-lab.git`

## Remaining Requirement
To actually create the GitHub repository and push the first commit, authenticated GitHub access is still required on this machine.

If `gh` is unavailable and no GitHub token is configured, the remaining steps are:
1. provide a GitHub token with repo permissions, or authenticate git/gh on this machine;
2. create the remote repository;
3. push the prepared local repository to `main`.
