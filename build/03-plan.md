# 03 Page plan

Status: DRAFT | [NEEDS INPUT: FITS at T18, then SIGNED-OFF with the date at T19]
Evidence: OPEN | [NEEDS INPUT: set to CLEAR at T20]

Written by T16a to T20. Read by T21, T24 and T25. See PLAYBOOK.md.

**G3 blocks `node bake.js` once real page copy exists and this file is not
SIGNED-OFF, or its Head table disagrees with `config.js`.** G4 fails
`--check` while Evidence is not CLEAR or any claim register row is still open.

Both tables below are keyed by the page's file name. Keep the column headings
as written; G3 reads them.

## Reference sites

T16a. Example sites Brad supplies, fetched and recorded, with what the fetch
showed. Structure and approach only: no copy is carried over, and a site ranking
elsewhere is not evidence that its features are why. Record rankings and links
only if they were actually checked.

List: the 15 sites from the Cairns Cabinet Makers T16a review (Brad's list of
cabinet makers he thinks rank well in their markets), reused for this build by
Brad's choice, 20 October 2026. Re-fetched the same day (home pages only, static
HTML, no script run), so the outcomes below are this build's own. 14 of 15
fetched: precisioncabinets.com.au timed out twice (it loaded for Cairns on 13
October); middletondesign.com.au, blocked with HTTP 403 for Cairns, now loads.
Word counts are a rough tokenised count of visible text, not comparable with the
Cairns figures. The "notable" column carries the Cairns reading of each page
where this fetch agrees with it, plus what this fetch found. No rankings, links or
Google Business Profiles were checked.

| site | market | home words | notable on the home page |
|---|---|---|---|
| tailoredinteriorsqld.com.au | Brisbane | 800 | services by room; process; testimonials; showroom; footer carries ABN and QBCC number |
| atcabinetmakers.com.au | Brisbane south | 1,455 | suburb names in the H1; five-step process with "free in-home consultation"; reviews; years in business |
| northsidejoinery.au | Brisbane north | 743 | architectural and commercial joinery; named owner with years of experience; showroom wording |
| huskandco.com.au | Sydney | 301 | awards and TV features; gallery |
| myjoinery.com.au | Sydney | 801 | services by room; reviews |
| middletondesign.com.au | Sydney | 1,098 | first read this build: H1 "Cabinet Maker Sydney", then residential and timber joinery headings; services by room (bathrooms, robes); named owner "over 25 years"; "fully licensed & insured"; reviews |
| perfectfitinterior.com.au | Melbourne | 5,262 | long page; FAQ; warranty; free quote; showroom; the only dollar figures are an online shop of wardrobe units ($1,650 to $2,450), not job prices |
| cosinteriors.com.au | Melbourne | 295 | trade clients (builders, architects); recent work |
| melbournecabinetmakers.com.au | Melbourne | 690 | process; FAQ; warranty |
| customcabinets.com.au | not stated | 484 | room-by-room service blocks; process; workshop wording |
| winterfields.com.au | Adelaide | 1,781 | years in business; room-by-room services; process; FAQ; showroom; testimonial |
| spacecraftjoinery.com.au | Adelaide | 195 | gallery; finance offer |
| precisioncabinets.com.au | Perth | not read | connection timed out, 20 October 2026, twice |
| colraycabinets.com.au | Perth | 4,142 | awards (dollar figures are HIA award price categories); team; gallery; showroom; reviews |
| willettoncabinets.com.au | Perth | 2,208 | process; a $200 in-home consultation and CAD fee, credited to the project; reviews; showroom |

| pattern | seen on | verdict | reason |
|---|---|---|---|
| Services shown by room (kitchens, bathrooms, laundry, wardrobes) | most | adopt, as sections of the two planned pages | matches the keyword table: wardrobes as a section on index.html, design and benchtops as sections on the kitchens page; no extra pages, so no cannibalisation |
| A step-by-step process | Tailored, A&T, Melbourne CM, Custom Cabinets, Winterfields, Willetton | adopt once sourced | on the Gold Coast BJF (5 steps), Gold Coast Joinery (7) and Quality Cabinets (3) already show steps, but none gives a lead time (Competitor gaps 2); a general sequence and timing drivers need a real source under R10 |
| FAQ block | Perfect Fit, Melbourne CM, Winterfields | adopt once sourced | none of the ten Gold Coast sites has one (Competitor gaps 3); answers on cost drivers, timing and licensing each need a source (R2, R10) |
| Suburb or region names for the service area | A&T (in the H1) | adopt, in copy only | the keyword table puts Nerang, Burleigh Heads and Southport in service-area copy, no pages; only BJF names suburbs locally (Competitor gaps 7) |
| Job-cost guidance | none of the 14 read | adopt once sourced, as cost drivers | no reference site and no Gold Coast competitor publishes a job price; figures wait on a Gold Coast cost source (R10; claim restrictions) |
| Warranty explained | Perfect Fit, Melbourne CM | adopt once sourced | nine of ten Gold Coast sites say nothing (Competitor gaps 5); a statutory warranty statement needs its primary source at T20 (R2), and nothing may read as our own warranty |
| Licence number, "licensed & insured" | Tailored, Middleton | cannot claim | no licence wording before a renter is signed (R14, G11); the QBCC value statement goes on every page instead (Positioning) |
| Reviews and testimonials | most | cannot claim | the claim restriction list forbids invented reviews and we have none |
| Awards, years in business, named owner's experience | A&T, Colray, Husk, Winterfields, Middleton, Northside | cannot claim | forbidden: years in business and job counts; the site does not do the work |
| Gallery and recent work | most | cannot claim | no photos of work (claim restrictions); a gallery waits for the renter |
| "Free in-home consultation" and "free quote" | A&T, Perfect Fit | cannot claim | forbidden: this site does not quote |
| Showroom, workshop wording, hours | Tailored, Northside, Perfect Fit, Winterfields, Colray, Willetton | cannot claim | forbidden before a renter has premises; `schema.type` stays Organization. The T05 teardown says buyers expect a visit: that is for the renter to offer |
| Paid design or consultation fee, credited to the job | Willetton (and BJF locally) | skip | the renter's commercial policy, not ours to state |
| Finance offer | SpaceCraft (and Pinnacle locally) | skip | not ours to offer |
| Online shop of ready-made units | Perfect Fit | skip | a product business, not a lead-generation page |
| Long home pages (over 2,000 words) against short ones (195 to 301) | both kinds | skip | the sample shows no link between length and the sites chosen; length is not a reason |

What the sample suggests, as for Cairns: most of what these sites lean on is
trust from an operating business (reviews, years, awards, showrooms, licence
numbers), which this site cannot claim before a renter is signed. What is open
to us is structure (rooms, process, FAQ, service-area suburbs) and the answers no
Gold Coast competitor gives (cost drivers, lead time, licensing, warranty), each
only once sourced under R2 and R10.

## Inventory

T17, with the Template fit column filled at T18.

| file | route | config key | priority | primary keyword | secondary keywords | template fit |
|---|---|---|---|---|---|---|
| [NEEDS INPUT: e.g. index.html] | | | | | | |

Template fit is `fits`, `engine change: <reason>`, or `dropped`. A page whose
fit is unknown does not get drafted. On Perth Tiling Specialists, whether a
contact page could exist at all was settled by dropping the page rather than
by reading the engine.

## Head

T17. Character counts include spaces. Title 60 or under, meta 155 or under.
The H1 is literal, including its local term, and is approved here rather than
polished later.

| file | title | chars | meta | chars | h1 |
|---|---|---|---|---|---|
| [NEEDS INPUT: one row per inventory row] | | | | | |

## Nav

T17. Ordered. Footer-only pages listed separately.

[NEEDS INPUT: nav order, then footer-only pages]

## Cannibalisation map

T17. See PLAYBOOK.md rule R12.

| page | owns | must not expand into | sends readers to |
|---|---|---|---|
| [NEEDS INPUT: one row per page] | | | |

## Internal link graph

T17. Name the inbound hub and the outbound hub. No orphans.

[NEEDS INPUT: inbound hub, outbound hub, then per-page inbound and outbound anchors]

## Image direction

T17 writes what each image must show; T24 fills the measured columns. An image
that would make a factual or diagnostic claim is drawn as an SVG, never a
near-miss photo. No captions.

| file | image | shows | photo or diagram | alt text | width | height | KB | widths |
|---|---|---|---|---|---|---|---|---|
| [NEEDS INPUT: one row per image] | | | | | | | | |

## Linkable asset

T17. Which page, and six named outreach targets, or the words
`conversion asset only`. An asset nominated with no named target is a page
nobody will link to.

[NEEDS INPUT: page, then targets]

## Claim register

T17 lists every safety, regulatory or standards claim and the primary source
required. T20 resolves every row. Status is `sourced` or `dropped`, never
`open`, before Evidence goes CLEAR. See PLAYBOOK.md rule R2.

| # | claim as it will appear | page | primary source required | status | source | edition | url | date checked |
|---|---|---|---|---|---|---|---|---|
| [NEEDS INPUT: one row per high-risk claim] | | | | | | | | |

## Dropped claims

T20. The claim text and why it went. A dropped claim is deleted from the copy,
not just from this table.

[NEEDS INPUT: or "none"]

## Traps found

T20. Claims that search results assert but primary sources do not support. The
Western Australian waterproofing licence is the worked example: every source
asserting it traced back to training provider marketing, and the licence
belongs to a different state.

[NEEDS INPUT: or "none found"]

## Cost figures

T20, where the build publishes figures. Reader-facing copy uses the publisher
type, never the business name. Peak bodies may be named.

Method, in the words that will appear on the page:

[NEEDS INPUT: the method paragraph]

| item | low | high | publisher type | source name | url | date |
|---|---|---|---|---|---|---|
| [NEEDS INPUT: one row per figure] | | | | | | |

Convergence and disagreement: [NEEDS INPUT: what agrees, what diverges, why]

Gaps: [NEEDS INPUT: figures wanted but not found]

Review date: [NEEDS INPUT: 12 months from compilation]

## Sign-off

T19. H1 map and nav signed off by Brad in this file, not in a message.

[NEEDS INPUT: date]
