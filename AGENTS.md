# Repository Instructions

This repository follows WG Tech Labs' Clean Workflow. Ship through `dev`; keep
`main` stable.

## Branches and pull requests

- Create short-lived `feature/*`, `fix/*`, `docs/*`, `chore/*`, `test/*`, or
  `refactor/*` branches from `dev`.
- Open feature pull requests against `dev`. Squash-merge them after required
  checks pass and review is complete.
- Do not commit directly to `main` or `dev`.
- When `dev` is ready, open a release pull request from `dev` to `main`. Use a
  meaningful Clean Commit release title and a regular merge commit.
- Delete feature branches after merge and rebase or update them against `dev`
  before review.
- Apply labels that already exist in the repository before requesting review
  or merging. Do not create labels as part of routine work.

## Commit messages

Use the Clean Commit format:

```text
<emoji> <type>: <description>
<emoji> <type> (<scope>): <description>
```

Use the exact emoji and lowercase type, present tense, a lowercase description,
and no ending period. Keep messages under 72 characters when possible. Valid
types are `new`, `update`, `remove`, `security`, `setup`, `chore`, `test`,
`docs`, and `release`. Use `!` after the type only for a breaking change and
only with `new`, `update`, `remove`, or `security`.

## Plugin changes

- Keep the plugin name, skill name, and marketplace entry aligned as
  `clean-ui-ux`.
- Keep the bundled guidance self-contained. Inspiration links are attribution;
  do not add runtime or installation dependencies on those source projects.
- Describe and validate accessibility and reduced-motion behavior where
  relevant. Motion guidance covers interface interactions, not standalone
  motion graphics.
- Keep plugin metadata valid JSON and skill instructions in
  `skills/clean-ui-ux/SKILL.md`.
- Do not add dependencies or build tooling for this instruction-only plugin
  without a concrete need.
- Never commit credentials, tokens, or local configuration containing secrets.
