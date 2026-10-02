# Domain Docs

## Layout

Single-context: `GLOSSARY.md` and `docs/adr/` at the repo root.

## Before exploring

Read `GLOSSARY.md` and ADRs in `docs/adr/` relevant to the work.

If either is absent, proceed silently. The `/domain-modeling` skill
creates domain documentation lazily as terms or decisions are resolved.

## Vocabulary

Use the glossary's terms in issue titles, proposals, hypotheses, and
test names. Respect explicitly avoided synonyms.

If a needed concept is missing, reconsider whether it belongs to the
domain; note genuine gaps for `/domain-modeling`.

## ADR conflicts

Explicitly flag proposals that contradict an existing ADR, naming the
ADR and explaining why the decision is worth reopening.
