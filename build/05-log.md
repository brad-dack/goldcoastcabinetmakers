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
| 2026-10-30 | T22 | Copy after the 30 Oct SEO audit review: About v1.2 ("Who runs this" ends "...but I will pass your enquiry to a cabinet maker who can quote it."), Home v1.2 (TV units in the joinery list; cabinetmaker and cabinet builder in the joiner FAQ), kitchens v1.1 (kitchen shapes paragraph, enquiry link after the cost ranges, in-body links to Home and About per the Internal link graph, a $10,000 or $30,000 FAQ from the cost table, "cupboards" in one H2 and one FAQ). About Contact wording left as v1.1 by Brad's choice | Brad | About and Home v1.1 (27 Oct 2026), kitchens v1 (21 Oct 2026) | Audit rows 1 and 3 to 9 picked by Brad; no new claim or source, heads unchanged |
| 2026-10-27 | T22 | Copy v1.1 on Home and About, in Brad's words: "Where we cover" ends "we will try our best!"; About "Who runs this" ends "I cannot build a kitchen - but I will help send someone who is great at them!"; Contact drops "Calls are not answered live" for "If your call goes to voicemail, leave a message and it will be passed on with your enquiry." | Brad | v1 copy approved 21 Oct 2026 (index.md, about.md) | Post-launch wording change; G5 heads unchanged |
| 2026-10-20 | T17 | Linkable asset: the kitchens page, built ready with the T20 cost table and QBCC basics; six outreach targets named; no outreach until a renter is signed | Brad | `03-plan.md` Linkable asset "conversion asset only" (T17 draft, signed off at T19) | T20 found Gold Coast cost sources, which the signed plan named as the trigger; Brad will not build links before renting but wants the page ready |
| 2026-10-20 | T16 | Positioning level 2 and the claim restriction list, carried from Cairns. QBCC position before rental: no licence number or "licensed" wording; every page carries "Gold Coast Cabinet Maker cannot perform building work valued in excess of $3,300. For work above that value, discuss it with the cabinet maker who quotes your job." | Code, accepted by Brad | none | Same conservative answer Cairns adopted on 13 Oct 2026; the $3,300 figure gets its primary source at T20 (R2) |
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
| Gold Coast job value for custom kitchens not sourced; the $1,120 rent case leans on a Sydney benchmark | T20 | Code | 2026-10-15 | a sourced Gold Coast or QLD figure is cited in `build/03-plan.md` evidence | 2026-10-20 | `03-plan.md` Cost figures: mid-range Gold Coast kitchen $24,500 to $44,100 (cost-guide site, updated 10 Oct 2026), $25,000 to $45,000 and $25,000 to $40,000 (two Gold Coast builders); register row 6 sourced, G4 passes. Supports the $1,120 rent case: jobs in the tens of thousands |
| QBCC advertising rules for a lead-gen site before rental (see Cairns Cabinet Makers `build/01-market.md`) | T21 | Me | 2026-10-15 | a written position on pre-rental copy is recorded under Decisions | 2026-10-20 | Decisions row 2026-10-20 T16: no licence wording, QBCC value statement on every page, approved by Brad |
| Directory renter check not read: hipages refuses web fetch; Oneflare 301s to Airtasker, whose category URL 404s | none | Me | 2026-10-15 | named Gold Coast cabinet makers seen on hipages or Airtasker are listed in `01-market.md` Renter evidence | | |
| gcacabinets.com classified "exclude, trade supplier / flatpack" by name, but its site sells custom work to homeowners | none | Code | 2026-10-15 | `renter-pool-classified-2026-10-15.csv` row re-judged and the 109 count updated or confirmed in `01-market.md` | | |

## QA

T27 and T28. Status goes PASS only when every row below has a result and its
evidence. **G7 fails `--check` if Status is PASS with a required row missing.**
Keep the check names in the first column exactly as written.

Status: PASS | 25 October 2026

| check | result | evidence | date |
|---|---|---|---|
| no-js crawl | PASS | `python` fetch of each live URL with a non-JS user agent, scripts, styles, noscript, header, footer and nav removed to count body words: `/` 1,072, `/kitchens-gold-coast` 1,655, `/about` 516, `/privacy` 881. Each returns HTTP 200 with its own H1 in the served HTML. The nav (`/`, `/kitchens-gold-coast`, `/about`, the tel link) and the footer with the Privacy link are in the served HTML on every page | 2026-10-24 |
| console errors | PASS | Browser pane, https://goldcoastcabinetmaker.com.au/, `/kitchens-gold-coast`, `/about`, `/privacy` loaded at 375, 768 and 1280 wide: `read_console_messages` returns one entry, a 404 for the deliberate request to `/nonexistent-page` that tested the 404 page; `read_network_requests` shows every other request 200. The Turnstile widget rendered on `/about` with no console error (T26) | 2026-10-24 |
| layout | PASS | Browser pane emulation, `document.documentElement.scrollWidth` against `innerWidth`: 375 wide, 375 on all four pages and the 404 page, nav toggle shown, no broken images; 768 wide, 753 on all four (the scrollbar), nav toggle shown; 1280 wide, 1265 on all four (the scrollbar), nav toggle hidden. Home hero loads `home-hero-gold-coast-560.jpg` at 450 px; the cabinet-parts diagram renders at 720 by 480; the cost table fits its wrapper at 1280 and scrolls inside it (overflow auto) at 375 | 2026-10-24 |
| pagespeed | PASS | pagespeed.web.dev, mobile, Lighthouse 13.5.0, 25 Oct 2026 06:45 and 06:47 AEST (the anonymous API was over quota). Kitchens (the heaviest page, 1,655 words, two images and a table): Performance 98, Accessibility 100, Best Practices 100, SEO 100; FCP 0.9 s, LCP 2.4 s, TBT 30 ms, CLS 0, Speed Index 1.1 s. Home (1,072 words, two images): 100, 100, 100, 100; FCP 0.8 s, LCP 1.2 s, TBT 60 ms, CLS 0, Speed Index 0.9 s | 2026-10-24 |
| internal links | PASS | Every same-site `href` on the four live pages: `/`, `/about`, `/kitchens-gold-coast` and `/privacy` all return 200; none broken. One external link, https://www.oaic.gov.au, on Privacy, not fetched. Each page has inbound links from the other three, so no orphans | 2026-10-24 |
| sitemap | PASS | `https://goldcoastcabinetmaker.com.au/sitemap.xml` lists `/`, `/kitchens-gold-coast`, `/about`, `/privacy`. The `.html` files on disk, excluding `404.html`, are `index`, `kitchens-gold-coast`, `about` and `privacy`. They match one to one. robots.txt serves ("User-agent: * / Allow: /") and names the sitemap | 2026-10-24 |
| notice above form | PASS | Served HTML on `/`, `/kitchens-gold-coast` and `/about`: one `<form>` each, and the `reassurance` paragraph carrying "Your details go to a local cabinet maker so they can quote your job, and the cabinet maker pays for the enquiry" sits 209 characters before it. `/privacy` has no form. Seen rendered above the job picker on the live About page (T26 screenshot) | 2026-10-24 |
| preflight on deployed commit | PASS | `gh api .../pages/builds/latest` commit e2bb09a8015488d5479099333f1ddb1ba5a856e3 (built 2026-10-24T22:42:27Z) equals `git rev-parse HEAD`. A fresh `git clone` of GitHub at that commit, `node bake.js --check`: "Preflight passed with 1 warning(s)", exit 0, the warning being that this QA Status is not PASS yet | 2026-10-24 |
| form end to end | PASS | Brad sent a real test enquiry from the live Home page on his phone, 25 Oct 2026 00:02:41 UTC. `select` on the remote `leads` table: id c577ffc3-cdd3-4a21-a845-3a64948c6056, site_id dac96949-0195-4911-830c-7715c22dab9c (gold-coast-cabinet-maker), channel form, contact_name "T28 Test", fields service Kitchens, suburb Burleigh Heads, message "Test enquiry for T28, please ignore"; spam_status clean, forward_status held (034 holds all forms), ai_label for_owner. Sent from `/`, Landed on `/`, Came from empty (`_page`, `_landing`, `_referrer` in raw_payload): correct, because Brad typed the address and sent from Home (his answer, same day). A visit whose landing and sending pages differ was not exercised | 2026-10-25 |
| turnstile widget | PASS | Renders on https://goldcoastcabinetmaker.com.au/about with no console error (T26, 24 Oct 2026). Token issued: the test lead's raw_payload carries `cf-turnstile-response` of 730 characters, and the ingest function accepted it (spam_status clean) | 2026-10-25 |
| call routes and logs | PASS | Brad rang (07) 5651 3804 from his mobile by tapping the site's Call button, 25 Oct 2026. `call_events` for the Gold Coast site_id: 00:01:21 UTC call_status ringing, inbound to +61756513804; 00:01:44 completed, 22 s; 00:01:46 recording event, 7 s, recording_path CA0052c969936d725f782b3dd748f6d7e9.mp3. A voicemail lead row was created (id 8f45af54-fcb8-4c35-bf64-6834715d2f78, forward_status pending, no renter yet) | 2026-10-25 |
| greeting_audio_url | PASS | `curl -I` https://bnfgnglzswtrvzfqkgjh.supabase.co/storage/v1/object/public/Greetings/GoldCoastCabinetMaker.mp3: HTTP 200, Content-Type audio/mpeg, 185,294 bytes, 25 Oct 2026 00:05 UTC. Heard on Brad's test call the same day; he confirmed it says the approved words exactly | 2026-10-25 |
| greeting_text | PASS | `select greeting_text from sites where slug = 'gold-coast-cabinet-maker'` returns the T12 words exactly ("Hi, thanks for calling Gold Coast Cabinet Maker. Leave your name, location and job details after the tone. We will pass your enquiry on to a local cabinet maker who can quote the job, and the cabinet maker pays for the enquiry."), the same words Brad heard on the recording | 2026-10-25 |
| ga4 realtime | PASS | Brad's GA4 Realtime screenshots, property Gold Coast Cabinet Maker, 25 Oct 2026: Event count by Event name shows page_view 4, click_to_call 1, form_start 1, first_visit 4, session_start 4, user_engagement 2, scroll 1; Views by Page title shows the Home title | 2026-10-25 |
| single indexable hostname | PASS | `curl -sI https://brad-dack.github.io/goldcoastcabinetmakers/` 301 to https://goldcoastcabinetmaker.com.au/; www 301 to the apex; http 301 to https | 2026-10-24 |
| operator files not served | PASS | 404 on PLAYBOOK.md, README.md, bake.js, CODE-SESSION-START.md, TEMPLATE_SUMMARY.md, New site prompt.txt, build/02-constants.md, build/source-images/ and _config.yml | 2026-10-24 |

## Index log

T29.

| field | value |
|---|---|
| sitemap submitted | 2026-10-30: https://goldcoastcabinetmaker.com.au/sitemap.xml, Search Console property goldcoastcabinetmaker.com.au (Brad's screenshot, 30 Oct 2026) |
| sitemap last read | 2026-10-30, status Success, 4 discovered pages (all four sitemap URLs) |
| pages requested | [NEEDS INPUT] |
| review dates set | Cost figures table on the kitchens page (`03-plan.md` Cost figures, claim row 6): October 2027. QBCC claims, rows 1, 2, 4 and 7 (licence threshold, contracts and deposits, home warranty, value statement): re-read the QBCC pages at each maintenance review and by April 2027, six months after T20. GA4 internal traffic IP 180.150.80.120 (20 Oct 2026): re-check at each maintenance review and after any outage (T29 note). GitHub Pages certificate expires 23 January 2027 and renews automatically: confirm HTTPS still serves after that date. Turnstile shared widget: 6 of 10 hostnames used; check capacity before the next build |
| link inventory | One pre-renter linkable asset: the kitchens page (`/kitchens-gold-coast`), with the sourced Gold Coast cost table and QBCC basics, six outreach targets named in `03-plan.md` Linkable asset. No links built and no outreach before a renter is signed (Brad, 20 Oct 2026). Citations and directories for the kitchens and joinery terms (remote-execution verdict, T06) also wait for a renter |
| outreach targets and status | Six named in `03-plan.md` Linkable asset (Conrad Hyslop, Gold Coast Bulletin, realestate.com.au News, Domain Renovating, Home Beautiful, LJ Hooker). Status: none contacted, by decision, until a renter is signed |

## Backport

T30. One row per `###` heading under "Divergence from the template" in this
site's `README.md`. **G6 fails `--check` while a heading has no row here.**
Either the change is in the template, or there is a written reason it cannot
be. See PLAYBOOK.md rule R7.

| divergence | template commit | or reason it stays here |
|---|---|---|
| [NEEDS INPUT: or "none"] | | |
