# KU Design Competitions and Events

Student design competitions, design conferences and portfolio events for University of Kansas design students (VISC, IXD, illustration, animation, industrial design). Maintained by Titus Smith.

**Live site:** https://titusmith.github.io/ku-comps/

- `index.html`: the student site, synced from the board where it's edited on claude.ai. Don't edit it by hand; changes get overwritten on the next sync.
- `tools/sync_site.py`: makes `index.html` from the board's HTML, leaving out the Suggested and Watch list queues and instructor-only notes.

To refresh: `python3 tools/sync_site.py <saved board HTML> index.html`, then commit and push.

Feedback: open an issue or email Titus.
