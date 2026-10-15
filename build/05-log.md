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
| Name the runner-up and the one reason it lost (workbook Verdict tab) | T01 | Me | 2026-10-15 | `build/01-market.md` Chosen names a runner-up with no `[NEEDS INPUT` | | |
| No known control in either referring-domains pull | T04 | Code | 2026-10-15 | a pull in `build/data/` includes a domain of known strength, listed in Data files | | |
| Referring domains not pulled for kitchenbuildersqueensland.com.au and goldcoastcabinets.com.au (#1 and #3, kitchen cabinets gold coast, 50/mo) | none | Code | 2026-10-15 | both have counts in the SERP ownership table | | |
| Gold Coast job value for custom kitchens not sourced; the $1,120 rent case leans on a Sydney benchmark | T20 | Code | 2026-10-15 | a sourced Gold Coast or QLD figure is cited in `build/03-plan.md` evidence | | |
| QBCC advertising rules for a lead-gen site before rental (see Cairns Cabinet Makers `build/01-market.md`) | T21 | Me | 2026-10-15 | a written position on pre-rental copy is recorded under Decisions | | |

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
