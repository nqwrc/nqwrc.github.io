# status

state: active
remote: github-public
updated: 2026-09-15
stale-after-days: 30

## kpi
None - static landing page; live or not is binary, nothing to measure over time.

## now
Live at https://nqwrc.github.io/: one static index.html plus og.jpg, no build step.
The hero is a Keplerian orrery over a deep-field sky, two canvases sharing one loop,
the sky fixed behind the document and drifting 240px on scroll; cards are translucent
glass. Static frame under prefers-reduced-motion, no asset beyond Google Fonts. Eight
projects in two sections: four data/domain projects (warehouse KPI, transport
performance, QA reporting, CER Motore), then four tools (Tironian, glowbind,
3D Anatomy, suckless-harness).
2026-09-15: GoatCounter added (cookieless page-view tracking, feeds board/board's
online arena via its stats API); three public repos that existed but were missing
from the page - Tironian, CER Motore, suckless-harness - added with copy sourced
from each repo's own README/STATUS, CER Motore's pre-v0.1 status stated plainly.
Checked for a mobile overflow bug at narrow widths (a DOM-level scrollWidth vs
clientWidth probe, not just a screenshot): none found, `offenders=[]`.
2026-09-10: three claims corrected against the repositories they point at. The
transport card said "real carrier data" where the repo generates 4,593 deliveries;
the QA card claimed a scheduled run and listed SQL, and that repo has no scheduler,
no .sql file and no sqlite import. The section subtitle now declares the datasets
synthetic, which is what the three project READMEs already say.
Also: inline SVG favicon (the last console error), canonical, og:url, og:image,
theme-colour, and the LinkedIn profile linked in the footer - pandolfi-nicola, not
nicola-pandolfi, which belongs to a different person.
Verified in headless Chrome after the change: 5 requests (page plus three font
files), no /favicon.ico request, 0 console errors, 0 failed responses.

## backlog
- commits c31e726, 07d37a5 and now 87d20a4 and b73325b, all on origin/main, carry
  text the public-repo standard excludes: the last two are messages written on
  2026-09-10 that quote private career documents, the same mistake made again.
  HEAD is clean; the published history is not. Removing it means rewriting the
  history of a public repo: owner's decision, not taken here
