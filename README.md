# inventeer-knowledge-public

Inventeer's published company knowledge: ratified product and area content that anyone may read.

Everything in this repository is public. It holds only the base tier of Inventeer's knowledge classification, and its confidentiality check refuses a folder classified above it. Knowledge that is not public lives in Inventeer's restricted knowledge repository.

## How a change lands

- Every change arrives by pull request into `main`.
- The code owner of each folder the change touches approves it. `.github/CODEOWNERS` names them.
- The confidentiality check must pass. A pull request opened from a fork is not checked; a maintainer pushes its branch here first.

## Classification

Every folder is classified by the nearest `.knowledge-manifest.yaml` above it. A folder with no manifest above it is unclassified, and the check blocks it.
