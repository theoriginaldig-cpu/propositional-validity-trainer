# Validity Trainer

A browser-based practice tool for general claims about validity in propositional logic, such as:

> Is it the case that if *P*₁, *P*₂ ⊨ (*Q* ∨ *R*), then either *P*₁, *P*₂ ⊨ *Q* or *P*₁, *P*₂ ⊨ *R*?

Here *P*₁, *P*₂, *Q* and *R* stand for any statements of PROP. Students first decide whether the claim holds in general.

- **If it holds**, they put together a proof from shuffled steps. The steps reason about an arbitrary valuation *v*. At Medium and Hard, some of the steps on offer are invalid and must be left out. The app checks that every step comes after the steps it depends on.
- **If it doesn't hold**, they build a counterexample. They choose actual statements for the letters, built from elementary statements *A*, *B* and *C*. Then they say which validity claims hold for those statements, and give a valuation for each one that fails. The app checks all of this with truth tables.

Every question has a model answer: a written proof, or a counterexample with its truth table. The same reasoning works for any logic that extends classical propositional logic, with "model" in place of "valuation".

## Using it

Open the site's link in any web browser. Nothing needs to be installed, and no sign-in is required. Scores are kept only in the student's own browser, and no data is collected or sent anywhere.

## Files

- `index.html`: the whole app, in a single self-contained file.

## Updating

Upload a new `index.html` to replace the old one. The site's address stays the same.
