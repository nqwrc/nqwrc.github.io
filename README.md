# nqwrc.github.io

Nicola's (nqwrc) personal portfolio landing page — a single static `index.html` with five
projects in two sections: `warehouse-kpi-dashboard`, `transport-performance-analysis` and
`qa-reporting-pipeline` under Data & Supply Chain, then `glowbind` and `3d-anatomy` under
Software & Tools.

## goal
Give a recruiter one URL that explains what the projects are and links to each, with every
claim on the page traceable to the repository it points at.

## kpi
None — static landing page; live or not is binary, nothing to measure over time.
Declared deviation from the 1-3 KPI rule.

## kill
The portfolio direction changes, or this page is replaced by a different landing site.

## how
Single `index.html`, no build step. Deploys as GitHub Pages once pushed to `main` on the
`nqwrc/nqwrc.github.io` repo (a `<username>.github.io` repo auto-publishes).

Two details worth knowing before editing:

- The favicon is an inline SVG data URI, not a file, so the page stays one document. It
  draws the same orrery the hero animates.
- `og.jpg` is the only asset in the repository: a 1200x630 frame of the hero at 2x,
  captured in headless Chrome. Reshoot it the same way if the hero changes.
