# 05 Log

Every task appends here. Every session reads it first. See PLAYBOOK.md.

## Decisions

Every decision, and every reversal of one, with what it supersedes. Written in
the same commit as the change it describes. Without the supersedes column, a
later session reads the newest note as if nothing came before it, which is how
the same three questions were reopened across four sessions on Perth Tiling
Specialists.

`by` is `Brad`, or `Code, accepted by Brad` where Brad agreed to a proposal.

| date | task | decision | by | supersedes | reason |
|---|---|---|---|---|---|
| 2026-10-15 | T01 | Candidate: cabinet makers, Gold Coast QLD, from the workbook Verdict tab (BUILD, opportunity 3.72) | Brad | none | Strongest BUILD row Brad wanted to pursue; inputs checked in 01-market.md Chosen |
| 2026-10-15 | T00 | Repo created from template c06f4b9 as "Gold Coast Cabinet Makers" | Brad | none | Brad asked for T00 before the T05 teardown and T06 decision; repo name is a working name, brand is T08 |
| 2026-10-15 | T02 | "kitchen renovations gold coast" (260) gets no page | Code, accepted by Brad | none | T03: renovation builders and a franchise own the SERP, not cabinet makers (differs from Cairns) |
| 2026-10-15 | T02 | "kitchens robina" (210) dropped | Code, accepted by Brad | none | T03: the SERP is "The Kitchens" food precinct at Robina Town Centre |
| 2026-10-15 | T01 | Reason the build won over the close runners-up: high search volume, high job cost, lower competitor strength than the others | Brad | none | Workbook scores ranked several BUILD rows closely; recorded in `01-market.md` Chosen with the 15 Oct checks beside it |
| 2026-10-15 | T01 | Runner-up: interior decorators, Adelaide SA (gap 1.44, opportunity 3.81); lost on rental ($800 vs $1,120) and renter pool (54 vs 174) | Code, accepted by Brad | none | Next highest gap on the Verdict tab rows in Brad's 15 Oct screenshot |
| 2026-10-15 | T08 | Brand "Gold Coast Cabinet Maker", domain goldcoastcabinetmaker.com.au | Code, accepted by Brad | T00 working name "Gold Coast Cabinet Makers" (repo name only) | Both exact-match plural .com.au domains were registered and parked on 15 Aug 2026; the singular is clean on ASIC, ABN Lookup and RDAP (`02-constants.md` Naming history) |
| 2026-10-20 | T12 | Collection notices approved: Cairns wording with the brand changed, form and greeting | Code, accepted by Brad | none | R3, R4, R11; same words across sites |
| 2026-10-19 | T09 | Hosting: GitHub Pages from brad-dack/goldcoastcabinetmakers, DNS-only on Cloudflare | Brad | none | Same as Cairns Cabinet Makers |
| 2026-10-19 | T08 | Entity: sole trader, Brad, ABN 78 538 005 810; published name Brad, first name only, on About and Privacy | Brad | none | Same structure as Cairns Cabinet Makers |
| 2026-10-15 | T06 | GO: cabinet makers, Gold Coast QLD | Brad | none | T01 to T05 checks pass; see `01-market.md` Commercial thesis |
| 2026-10-15 | T06 | Remote-execution ceiling accepted: kitchens and joinery reachable by remote links; head-term top 3 may need local or supplier links; near me and bare terms need the renter's GBP | Brad | none | Proposed in `01-market.md` Remote-execution verdict |
| 2026-10-15 | T05 | Teardown set: the five ranking sites from SERP ownership, plus Brad's own list (gcacabinets, thecabinetryco, qualitycabinetsgc, signaturejoinery, lanbuild) as a lighter non-ranking pass | Code, accepted by Brad | none | Brad's list overlapped the ranking set on only currumbincabinets and coastalcabinets; the thesis must cite the SERP table |

## Open items

Anything owed, by anyone. `blocks` names the task ID it blocks, or `launch`,
or `none`. `closes when` names the check that will close it, written when the
item is opened. `closing evidence` is that check's output, and stays empty
until it has actually been run. An item never closes because someone says it
is done.

**G7 fails `--check` while an item with `blocks` set to `launch` has no
closing evidence.**

| item | blocks | surface | opened | closes when | closed | closing evidence |
|---|---|---|---|---|---|---|
| Name the runner-up and the one reason it lost (workbook Verdict tab). Reason recorded 15 Oct; the close rows are still owed | T01 | Me | 2026-10-15 | `build/01-market.md` Chosen names a runner-up with no `[NEEDS INPUT` | 2026-10-15 | `[NEEDS INPUT` count in Candidates and Chosen: 0; Chosen line 8: "Runner-up: interior decorators, Adelaide SA (gap 1.44, opportunity 3.81)" |
| No known control in either referring-domains pull | T04 | Code | 2026-10-15 | a pull in `build/data/` includes a domain of known strength, listed in Data files | 2026-10-15 | `refdomains-control-2026-10-15.csv` (listed in Data files): hipages 3,771 (11 Oct: 3,730), localsearch 9,163 (9,057), dreamdoorskitchens 283 (273), fnqkitchens 32 (26) |
| Referring domains not pulled for kitchenbuildersqueensland.com.au and goldcoastcabinets.com.au (#1 and #3, kitchen cabinets gold coast, 50/mo) | none | Code | 2026-10-15 | both have counts in the SERP ownership table | 2026-10-15 | SERP ownership, kitchen cabinets gold coast: "87, directory-scale, 39"; 'not pulled' count in the section: 0 |
| Gold Coast job value for custom kitchens not sourced; the $1,120 rent case leans on a Sydney benchmark | T20 | Code | 2026-10-15 | a sourced Gold Coast or QLD figure is cited in `build/03-plan.md` evidence | | |
| QBCC advertising rules for a lead-gen site before rental (see Cairns Cabinet Makers `build/01-market.md`) | T21 | Me | 2026-10-15 | a written position on pre-rental copy is recorded under Decisions | | |
| Directory renter check not read: hipages refuses web fetch; Oneflare 301s to Airtasker, whose category URL 404s | none | Me | 2026-10-15 | named Gold Coast cabinet makers seen on hipages or Airtasker are listed in `01-market.md` Renter evidence | | |
| gcacabinets.com classified "exclude, trade supplier / flatpack" by name, but its site sells custom work to homeowners | none | Code | 2026-10-15 | `renter-pool-classified-2026-10-15.csv` row re-judged and the 109 count updated or confirmed in `01-market.md` | | |

## QA

T27 and T28. Status goes PASS only when every row below has a result and its
evidence. **G7 fails `--check` if Status is PASS with a required row missing.**
Keep the check names in the first column exactly as written.

Status: [NEEDS INPUT: PASS or FAIL at T28]

| check | result | evidence | date |
|---|---|---|---|
| no-js crawl | [NEEDS INPUT] | word count per page, with the command | |
| console errors | [NEEDS INPUT] | | |
| layout | [NEEDS INPUT] | mobile, tablet, desktop | |
| pagespeed | [NEEDS INPUT] | the two heaviest pages | |
| internal links | [NEEDS INPUT] | no orphans | |
| sitemap | [NEEDS INPUT] | matches disk | |
| notice above form | [NEEDS INPUT] | rendered, on every page with a form | |
| preflight on deployed commit | [NEEDS INPUT] | `node bake.js --check` output | |
| form end to end | [NEEDS INPUT] | row landed against the right site_id | |
| turnstile widget | [NEEDS INPUT] | renders on the live hostname with no console error, and a token is issued | |
| call routes and logs | [NEEDS INPUT] | call_events row | |
| greeting_audio_url | [NEEDS INPUT] | `curl -I` on the URL returns 200 audio/mpeg, and heard on the call | |
| greeting_text | [NEEDS INPUT] | column set, same words | |
| ga4 realtime | [NEEDS INPUT] | pageview and click_to_call | |
| single indexable hostname | [NEEDS INPUT] | platform hostname fetched directly | |
| operator files not served | [NEEDS INPUT] | 404 on PLAYBOOK.md and README.md | |

## Index log

T29.

| field | value |
|---|---|
| sitemap submitted | [NEEDS INPUT: date] |
| sitemap last read | [NEEDS INPUT: date Search Console reports] |
| pages requested | [NEEDS INPUT] |
| review dates set | [NEEDS INPUT: what, and when it falls due] |
| link inventory | [NEEDS INPUT: the named pre-renter linkable assets] |
| outreach targets and status | [NEEDS INPUT] |

## Backport

T30. One row per `###` heading under "Divergence from the template" in this
site's `README.md`. **G6 fails `--check` while a heading has no row here.**
Either the change is in the template, or there is a written reason it cannot
be. See PLAYBOOK.md rule R7.

| divergence | template commit | or reason it stays here |
|---|---|---|
| [NEEDS INPUT: or "none"] | | |
