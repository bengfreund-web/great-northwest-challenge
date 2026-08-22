# Great Northwest Challenge

Static site for the **Great Northwest Challenge** high school rugby tournament - Saturday 26 and
Sunday 27 June 2027, Montana State University, Bozeman, Montana. An event of the Montana Institute
of Sport.

Same static HTML/CSS/JS format as the Montana Invitational / National 10s sites (pinned video
hero, loader, scroll reveals, spec-sheet + card sections). Rebranded to the GNC teal + sunset-orange
palette with the GNC 2027 shield logo.

- Local: `~/great-northwest-challenge`
- Palette: teal `#005462` + orange `#F08A1E` (tokens at the top of `css/styles.css`)
- Pages: `index.html` (long page) + `referee.html`. Run `python3 scripts/bump-assets.py` before
  pushing css/js changes.

## Content sources
Dates/venue/format/divisions/cost/teams/contacts all taken from greatnorthwestchallenge.com
screenshots (Aug 2026): Sat 26 - Sun 27 June 2027, Montana State University Bozeman, $1,450/team,
XVs 22.5-min halves + 5-min HT, 4 guaranteed matches, 6 divisions (HS Boys D1/D2, HS Girls D1/D2,
U16 Boys D1/D2). Confirmed teams are 2026 state/regional sides by division.

## Open items (confirm before launch)
1. **Google Form URLs** - best-effort mapping, CONFIRM which is which:
   - Team Interest / EOI: `...SfTl5DZF21dP4FiCC82ohGkLK4kZoKW5X2aRMUZjILlYgGOSA`
   - Free Agent Player: `...SflP28g_c4hWg50Fubb-oufr5qup2ah4dnUHIQUdzXqm3Oi3Q`
   - Referee (referee.html): `...SfToKQF6PEyOvOHgH4zi5qV2puAaNfzpQunRT38aSJAh2N7ww`
   - Also available (not yet placed): College/University form `...SfdY3gaBdC-UCsrIKJz4AbKg7tOJulZNEi3Xo-xW_Q8XR_6jA`
2. **Register & Pay** points to `xplorer.rugby/great-northwest-challenge`. If a Zeffy checkout is
   preferred, swap the two hero/entry buttons.
3. **Sponsors** - only Bozeman Chamber + Montana Institute of Sport tiles are in; Kenyon Noble and
   Different Stroke Motorsports logos still needed.
4. **Hero video** is the reused Bozeman flyover (native GNC footage). Higher-res reel welcome.
5. **Subpages not yet built** (exist on the live Squarespace site): College Recruiters, Vendors &
   Partners, Tournament Packet, Player Age Bands, USA Rugby TiD Day, Fixtures & Results, Venue.
6. Contact: Tournament Director JD Stephenson jstephenson@montanainstituteofsport.org / (314) 954-7194;
   Coordinator Allison Schrichte aschrichte@montanarugby.org / (406) 241-1480.

## Deploy
GitHub Pages from repo root on `main`. Eventual custom domain: greatnorthwestchallenge.com.
