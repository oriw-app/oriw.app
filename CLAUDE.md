# Oriw website: notes for Claude

This repository is the public website, served by GitHub Pages from `index.html` on `main` at oriw-app.github.io/oriw.app (oriw.app once the domain is bought; then add `CNAME`).

## Rules for this repo

- Product first, one idea per section, large visuals, few words. Never mention or compare with other products.
- Light theme only, using `oriw-design` tokens.
- Prices and pricing promises must match the public parts of the business model; ask before changing any price.
- Every claim about speed or features must be true of the current release or labelled as a target.
- Check the page at 1280 px and 390 px wide with no sideways scrolling before pushing.

## How we work

This repository uses the **issuewright** plugin from [oriw-app/dev-plugins](https://github.com/oriw-app/dev-plugins), switched on in `.claude/settings.json` and configured in `.claude/issuewright.json`. GitHub issues are the spec; the owner accepts intent, spec and plan; work follows DDD + BDD + TDD with hexagonal architecture and CQS. The full guide is the plugin's `WORKFLOW.md` (the `issuewright` skill). Releases are the milestones in `oriw`; planning happens on the **Oriw Roadmap** project.

## Oriw rules
- **DDD + BDD + TDD, with hexagonal architecture and strict CQS**, as set out in `oriw/docs/ENGINEERING.md` and `oriw/docs/ARCHITECTURE.md`. Here that means acceptance criteria are written as Given / When / Then, wording matches the glossary in `oriw/docs/DOMAIN.md`, and checkable behaviour (layout at 1280 and 390 px, working links) is checked before pushing.
- Never commit secrets. Never put salaries, costs, revenue or customer names in a public repository; they belong in `oriw-company`.
- The repositories are the source of truth: designs in `oriw-design/mocks/`, decisions in the repository they affect. Claude artifacts are previews only.
- Commits are authored by the person running the session; keep the trailers the session adds.

## Things Claude gets wrong

- Nothing recorded yet. Add a line here whenever Claude makes the same mistake twice.
