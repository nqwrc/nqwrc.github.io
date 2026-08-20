# status

state: active
remote: github-public
updated: 2026-08-20
stale-after-days: 30

## kpi
None - static landing page; live or not is binary, nothing to measure over time.

## now
Live deployment verified 2026-08-20: https://nqwrc.github.io/ returns HTTP 200 serving
the committed index.html byte for byte (git blob 15056c2b), all three project links 200.
The public-repo close check ran the same day; its four open items are below.

## backlog
- set the repository homepage to https://nqwrc.github.io/ - empty as of 2026-08-20
  while a live URL exists
- add repository topics - none set as of 2026-08-20, unlike the three data repos
- license: MIT added locally on 2026-08-20; GitHub still reports none until the
  commit is pushed
- commits c31e726 and 07d37a5, already on origin/main, carry text the public-repo
  standard excludes. HEAD is clean; the published history is not. Removing it means
  rewriting the history of a public repo: owner's decision, not taken here
