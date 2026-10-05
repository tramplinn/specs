# Tramplin Specs

Code lives in `backend`, `frontend`, `email-service`, `mcp-server`, and `infra`.
This repository explains *why* it exists and *who* it's for.

## Structure

```text
specs/
  product/
    business-value.md   problems, benefits, metrics
    products.md         products and their boundaries
    use-cases.md        use cases by role
  changes/
    localization.md     RU/EN interface and content
    projects.md         user projects in public profiles
```

## Upcoming changes

- [RU/EN localization](changes/localization.md) — language switch, separate
  content per language, auto-translation, acceptance criteria.
- [User projects](changes/projects.md) — project cards in public profiles; draft.

## Rules

- One document per topic; use relative links.
- Mark hypotheses and target metrics as such.
- Technical PRDs stay next to the code; this repo is for product decisions.
