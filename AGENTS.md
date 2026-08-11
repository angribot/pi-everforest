## Agent skills

### Issue tracker

Issues live in GitHub Issues, managed via the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default vocabulary: `needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: `CONTEXT.md` + `docs/adr/` at the repo root. See `docs/agents/domain.md`.

## Conventions

- **Commits**: conventional commit messages (`feat:`, `fix:`, `docs:`, …).
- **Version bump**: on "bump to x.y.z" — update the `version` in `package.json`, move the `[Unreleased]` entries into a new dated `## [x.y.z] - YYYY-MM-DD` section (leaving `[Unreleased]` empty), commit as `chore(release): x.y.z`, then show the proposed tag (`vx.y.z` + the commit it points at) and wait for confirmation before tagging.
- **Changelog**: decide per change whether it is notable — user-visible changes (new schemes, palette/color adjustments, packaging) get an entry; internal-only changes (docs typos, refactors) don't.
- **Release automation**: none yet — no workflow, no `npm publish`; conventional commits keep the release-please option open.
