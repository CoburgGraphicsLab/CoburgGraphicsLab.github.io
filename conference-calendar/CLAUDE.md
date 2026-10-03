# Conference calendar — notes for Claude

The page is a single self-contained file: `conference-calendar/index.html`.
All data lives in the `<script>` block near the top:

- `V`: one object per venue.
  - `sub` submission deadline, `dec` (conditional) decision, `fin` optional final decision,
    `cs`/`ce` conference start/end, all as "YYYY-MM-DD".
  - `est`: flags for estimated dates, e.g. `{sub:1, dec:1, conf:1}`. Remove a flag once the official date is known.
  - `kind`: "paper" or "small" (posters, surveys, workshops).
  - `status`: optional label such as "Submitted, under review".
- `URLS`: website per venue id.
- `CONT`: continent per venue id ("eu", "na", "as", "oc", "tba").
- `KW`: call-for-papers topics per venue id, `[source, [keywords...]]`.
- The journals table is plain HTML below the conference table.

When updating:
1. Check the official call for papers before changing a date, and remove the matching `est` flag.
2. Add next year's edition as a new entry; drop editions whose conference is over.
3. Keep everything in this one file (no build step). Test by opening it in a browser, then commit and push.
