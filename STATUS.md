# status

state: active
remote: github-public
updated: 2026-09-08
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
2026-09-05: satellite scene replaced by two canvases sharing one loop - a Keplerian
orrery in the hero over a deep-field sky fixed behind the whole document, drifting
240px across the page on scroll. Section borders removed and the hero scrim turned
into one page-wide fixed gradient, so the page reads as a single surface. Cards are
translucent glass (blur 18px, 40% fill) with display titles, repo slug, tech chips.
Verified locally: parallax reaches exactly -240px at the foot, no console errors.
2026-09-08: the warehouse-kpi-dashboard card carries a Live demo link to the Streamlit
Cloud deployment, https://warehouse-kpi-dashboard-6ujlbodc9l7cyxbetmzmcw.streamlit.app/,
which renders for a visitor with no Streamlit login.
2026-09-08 (later): feature/satellite-hero merged into main, so the orrery redesign is
what the live page serves. The card wording is the redesign's - Repository and Live demo.

## backlog
- commits c31e726 and 07d37a5, already on origin/main, carry text the public-repo
  standard excludes. HEAD is clean; the published history is not. Removing it means
  rewriting the history of a public repo: owner's decision, not taken here
