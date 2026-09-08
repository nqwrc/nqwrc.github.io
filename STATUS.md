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

2026-09-08: the warehouse-kpi-dashboard card carries a Live Demo link to the Streamlit
Cloud deployment, https://warehouse-kpi-dashboard-6ujlbodc9l7cyxbetmzmcw.streamlit.app/,
which renders for a visitor with no Streamlit login. The same link was put on
feature/satellite-hero so the pending redesign does not drop it.

## backlog
- commits c31e726 and 07d37a5, already on origin/main, carry text the public-repo
  standard excludes. HEAD is clean; the published history is not. Removing it means
  rewriting the history of a public repo: owner's decision, not taken here
