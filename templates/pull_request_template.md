## What and why

<!-- The change in one or two sentences, the reason, and a link to the issue. -->

## Evidence that it works

<!-- Tick at least one and attach it. Pick what fits the change. -->

- [ ] Recording or screenshots (UI)
- [ ] Request and response logs, or traces (service, API)
- [ ] Commands and their output (CLI, scripts, jobs)
- [ ] New or changed tests, with the run's results
- [ ] State chart or diagram (flows with states and transitions)
- [ ] Benchmark before and after (performance-sensitive code)

## Checks

- [ ] Lint, types and tests pass in CI
- [ ] No new lint suppressions, and no comments that justify a workaround
- [ ] No new use of a banned API, and no import across a forbidden boundary
- [ ] Old instances of any pattern this PR replaces are removed, or a follow-up is linked
- [ ] Any correction made while writing this PR that could recur is now a check (lint rule, type or test)

## Risk and rollback

<!-- What could break, who would notice, and how to revert. -->

## For the reviewer

<!-- Where to look first, and what you are unsure about. -->
