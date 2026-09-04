# status

state: active
remote: github-public
updated: 2026-09-04
stale-after-days: 30

## kpi
None - static landing page; live or not is binary, nothing to measure over time.

## now
Live deployment verified 2026-08-20: https://nqwrc.github.io/ returns HTTP 200 serving
the committed index.html byte for byte (git blob 15056c2b), all three project links 200.
Homepage, description, five topics and the MIT license are set; one open item below.
2026-09-04: header card replaced by a full-bleed hero with a canvas-drawn satellite
constellation (planet limb, three orbit shells, drifting satellites with a distance-based
link mesh, ground uplinks). One accent, no external assets, static frame under
prefers-reduced-motion. Card and footer emoji dropped.

## backlog
- commits c31e726 and 07d37a5, already on origin/main, carry text the public-repo
  standard excludes. HEAD is clean; the published history is not. Removing it means
  rewriting the history of a public repo: owner's decision, not taken here
