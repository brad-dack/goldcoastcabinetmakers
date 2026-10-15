# 01 Market read

Status: DRAFT | [NEEDS INPUT: set to GO or NO-GO with the date at T06]

Written by T01 to T06. Read by T07 and T17. See PLAYBOOK.md.

## Candidates considered

T01. Every candidate looked at, not just the winner. The remote-execution
column is the one that is easy to skip: supplier relationships, sponsorships
and local PR do not work remotely as designed.

| niche | city | renters | volume | competitor strength | remote penalty | verdict |
|---|---|---|---|---|---|---|
| cabinet makers | Gold Coast, QLD | 174 Maps listings; 109 after cleaning, plus 12 Tweed-side (NSW); 34 small, active, weak-web operators (see Renter evidence) | head group 390/mo located in Gold Coast; ~660/mo targetable across two pages | contested head term: 8 of top 10 are specialists, top 3 at 49-267 referring domains; kitchens page 49-112; joinery softest | QBCC licence required over $3,300; buyers expect a showroom or workshop visit, so the renter needs a visitable address | CHOSEN |
| interior decorator | Adelaide, SA | 54 (workbook) | 260 | 2.56 (workbook) | not assessed beyond the workbook | RUNNER-UP: opportunity 3.81, gap 1.44, rental $800 |
| concreting | Adelaide, SA | 194 (workbook) | 590 | 2.56 (workbook) | not assessed beyond the workbook | not chosen: opportunity 3.57, gap 1.44, rental $800 |
| tiling | Perth, WA | 211 (workbook) | 1,300 | 2.63 (workbook) | not assessed beyond the workbook | not chosen: opportunity 3.87, gap 1.37, rental $800 |
| cabinet makers | Sunshine Coast, QLD | 142 (workbook) | 260 | 2.66 (workbook) | not assessed beyond the workbook | not chosen: opportunity 3.71, gap 1.34, rental $1,120 |
| concreting | Gold Coast, QLD | 183 (workbook) | 390 | 2.70 (workbook) | not assessed beyond the workbook | not chosen: opportunity 3.72, gap 1.30, rental $800 |
| tiling | Gold Coast, QLD | not captured | not captured | not captured | not assessed beyond the workbook | not chosen: the row sits above this one on the Verdict tab and its values are cut off in Brad's 15 Oct screenshot; note reads "large renter pool, looks like a rent&rank at number 1" |

Workbook rows from Brad's `Stage 3: Verdict` screenshot of 15 October 2026. All
are BUILD, both gates PASS, planned effort 4, "Strong. Top 3 realistic."

## Chosen

T01. Name the runner-up and the one reason it lost. This is the only record of
why this build happened.

Cabinet makers, Gold Coast QLD.

Runner-up: interior decorators, Adelaide SA (gap 1.44, opportunity 3.81). It
lost on job value and renters: $800 average rental against $1,120, and a renter
pool of 54 against 174. Concreting Adelaide tied it on gap (1.44). Four other
BUILD rows sat within 0.26 of the chosen gap; all are in Candidates
considered.

On the workbook's own numbers, cabinet makers Gold Coast has the highest gap
(1.56) and the lowest average competitor strength (2.44) of the visible rows,
and ties the highest rental ($1,120). It is not the top row on opportunity
(tiling Perth 3.87, interior decorators Adelaide 3.81) or on volume (tiling
Perth 1,300, concreting Adelaide 590).

Why this one won, in Brad's words (15 October 2026): high search volume, high
job cost, and lower competitor strength than the others. This is a comparative
judgement against the close rows on the workbook's own scores. The 15 October
checks qualify two of the three parts: competitor strength reads higher than
the workbook's 2.44 (head term top 3 at 49 to 267 referring domains, against
26 to 57 for Cairns), and job cost is not yet sourced (open item in
`05-log.md`). Volume is confirmed at 390.

Workbook file and tab used: Brad's niche workbook (Google Sheets), tab
`Stage 3: Verdict`, row "Cabinet Makers | Gold Coast": opportunity 3.72, renter
pool 174 (PASS), 7 competitors analysed, average competitor strength 2.44,
monthly volume 390, average rental $1,120, planned effort 4, gap 1.56 (PASS),
"Strong. Top 3 realistic.", final verdict BUILD. The local `dfseo/Workbook*`
copies do not carry this row; the values are from Brad's screenshot of 15
October 2026.

Checks on those inputs, 15 October 2026:

- Renter pool 174 overstates the market by about 40% but the gate holds: 109
  real Gold Coast operators (see Renter evidence).
- Volume 390 is confirmed and is not inflated by job seekers (~60 non-buyer
  searches against ~800 of cabinet-maker intent).
- Average competitor strength 2.44 looks optimistic for the head term, whose
  specialists carry 49 to 267 referring domains (Cairns: 26 to 57). Effort 4
  is the right setting, not lower.
- $1,120 a month is defensible: ~660 targetable searches, top-3 click share of
  20 to 30% gives ~130 to 200 clicks, and ~5% gives 6 to 10 enquiries a month
  on jobs likely in the tens of thousands (job value not yet sourced, R10).

## Keyword table

T02. Grouped duplicates are recorded as grouped, never summed. A term that
returns null decides what does **not** get a page.

Volume is located in Gold Coast (no national pull this build). CPC is AUD.
Scope "local" means the term carries a Gold Coast-area modifier; "bare" means
no location in the term.

| term | volume | cpc | scope | null? | intended page, section on X, or no page |
|---|---|---|---|---|---|
| cabinet makers gold coast / cabinet maker gold coast / cabinetmakers gold coast / cabinetmaker gold coast (grouped) | 390 | 7.54 | local | no | index.html |
| cabinet maker / cabinet makers (grouped) | 210 | 4.85 | bare | no | index.html; SERP not read, assumed pack-only like near me |
| cabinet maker near me / cabinet makers near me (grouped) | 140 | 3.07 | bare | no | index.html; organic not localised, local pack only |
| joinery gold coast / joiners gold coast (grouped) | 40 | 3.63 | local | no | index.html |
| joinery near me | 30 | 10.36 | bare | no | index.html |
| custom cabinets gold coast / custom cabinetry gold coast (grouped) | 20 | 4.40 | local | no | index.html |
| custom cabinets | 40 | 3.76 | bare | no | index.html |
| kitchens gold coast | 110 | 14.12 | local | no | kitchens page |
| kitchen cabinets gold coast | 50 | 6.10 | local | no | kitchens page |
| kitchen design gold coast | 20 | 9.57 | local | no | section on kitchens page |
| custom kitchens gold coast | 10 | - | local | no | kitchens page |
| kitchen makers gold coast | 10 | - | local | no | kitchens page |
| kitchen manufacturers gold coast | 10 | - | local | no | kitchens page |
| flat pack kitchens gold coast | 20 | 3.09 | local | no | section on kitchens page (DIY intent likely) |
| outdoor kitchens gold coast | 70 | 5.15 | local | no | section on kitchens page; SERP not read |
| kitchen benchtops gold coast | 40 | 5.40 | local | no | section on kitchens page |
| kitchen renovations gold coast | 260 | 12.13 | local | no | no page (T03: renovation builders own this SERP); secondary mention on kitchens page only |
| kitchen renovations | 170 | 9.46 | bare | no | no page |
| kitchen resurfacing gold coast | 50 | 4.04 | local | no | no page |
| kitchen renovation cost gold coast | null | - | local | yes | no page |
| wardrobes gold coast | 110 | 3.82 | local | no | section on index.html (T03: wardrobe specialists and a chain) |
| built in wardrobes gold coast | 30 | 3.45 | local | no | section on index.html |
| custom wardrobes gold coast | 20 | 3.93 | local | no | section on index.html |
| walk in wardrobe gold coast | 10 | 3.42 | local | no | section on index.html |
| built in wardrobes | 140 | 1.64 | bare | no | section on index.html |
| bathroom vanities gold coast | 140 | 1.59 | local | no | no page (retail intent, as in Cairns; SERP not read) |
| custom vanities gold coast | null | - | local | yes | no page |
| laundry cabinets gold coast | 10 | 0.05 | local | no | no page |
| entertainment units gold coast | 10 | 1.35 | local | no | no page |
| shopfitting gold coast / shopfitters gold coast (grouped) | 110 | 3.29 | local | no | no page; commercial segment |
| commercial joinery gold coast | 10 | - | local | no | no page; commercial segment |
| stone benchtops gold coast | 110 | 3.23 | local | no | no page; segment likely stonemasons |
| kitchens robina | 210 | 4.77 | local | no | no page: "The Kitchens" food precinct at Robina Town Centre (T03) |
| cabinet makers nerang | 30 | 4.72 | local | no | no page; service-area copy only |
| cabinet makers burleigh heads | 20 | 3.57 | local | no | no page; service-area copy only |
| cabinet makers southport | 10 | 7.45 | local | no | no page; service-area copy only |
| cabinet makers tweed heads | 10 | 3.89 | local | no | no page (NSW) |
| kitchens burleigh heads | 10 | 5.45 | local | no | no page |
| kitchens tweed heads | 10 | - | local | no | no page |
| cabinet makers robina, cabinet makers coomera, joinery burleigh heads | null | - | local | yes | no page |
| cabinet maker jobs gold coast | 40 | 3.54 | local | no | no page; job seekers |
| cabinet maker salary, cabinet maker jobs | 10, 10 | - | bare | no | no page; job seekers |
| cabinet maker apprenticeship gold coast, cabinet making course gold coast | null | - | local | yes | no page |

## SERP ownership

T03. **One row for every intended page**, not just the head term. A gate closed
on the head term alone reversed itself two sessions later on Perth Tiling
Specialists, after the remedial SERPs were finally read.

Segment owner is one of: the trade itself, specialists, directories, another
trade.

Pulled 15 October 2026 by `serp_adhoc.py`, mobile, located in Gold Coast QLD.
Raw files: `build/data/serp-goldcoast-2026-10-15.csv` and
`build/data/serp-goldcoast-2-2026-10-15.csv`.

| query | ads (count, who) | local pack | AIO | top 3 domains | top 3 ref domains | segment owner | winnable? |
|---|---|---|---|---|---|---|---|
| cabinet makers gold coast | 0 | KW Cabinets; Flawless Cabinets; BJF Joinery | no | currumbincabinets.com.au, bjfjoinery.com.au, airtasker.com | 49, 267, directory-scale | specialists (8 of top 10; Airtasker #3, Localsearch #9) | yes, contested: specialists with exact-match titles; #1 has only 49 |
| cabinet maker near me | 0 | KW Cabinets; Flawless Cabinets; M & J Cabinets | yes | yellowpages.com.au (South Brisbane), mikedesign.com.au (Brisbane), craftbuilt.com.au (Brisbane) | directory-scale, 175, 306 | directories and Brisbane cabinet makers; organic not localised to Gold Coast | no: local pack only, needs a Google Business Profile |
| kitchens gold coast | 0 | Kitchens U Build; Verto Kitchens; Kitchen Builders Queensland | no | airtasker.com, coastalcabinets.com.au, thepinnaclekitchen.com.au | directory-scale, 112, 67 | specialists, with Airtasker, Facebook x2, hipages and Reddit in the top 10 | yes: four weak results on page 1 |
| kitchen cabinets gold coast | 0 | KW Cabinets; Cut To Size Ashmore; Flawless Cabinets | no | kitchenbuildersqueensland.com.au, airtasker.com, goldcoastcabinets.com.au | 87, directory-scale, 39 | specialists, with Airtasker, hipages and an Instagram profile (#6) | yes: three weak slots |
| custom kitchens gold coast | 0 | James Kitchens; Bertelli Custom Kitchens; ORSM Designs | no | goldcoastjoinery.com.au, houzz.com.au, thepinnaclekitchen.com.au | 49, directory-scale, 67 | the trade itself (cabinet makers) | yes, but 10 a month |
| kitchen renovations gold coast | 0 | Kitchen Builders Queensland; ORSM Designs; Verto Kitchens | no | houzz.com.au, kitchenu.com.au, hasl.com.au | directory-scale, 119, 120 | another trade: renovation builders (Hasl suburb pages x3, Varli), plus a franchise (Kitchen U) | no page: not a cabinet-maker SERP |
| joinery gold coast | 0 | BJF Joinery; Gold Coast Joinery; Acme Joinery | no | goldcoastjoinery.com.au ("Contact Us"), acmejoinery.com.au ("Contact"), instagram.com (Smart Joinery) | 49, 78, n/a | the trade itself, weakly: contact pages, Instagram, Localsearch x2 | yes: softest query read |
| wardrobes gold coast | 1 (ozwardrobes.com.au) | Designer Wardrobes; Just Wardrobes; Oz Wardrobes | no | wardrobeconnection.com.au, facebook.com, justwardrobes.com.au | 112, directory-scale, 185 | specialists (wardrobe makers and a chain), with Facebook threads and hipages | section only |
| kitchens robina | 0 | none | no | robinatowncentre.qicre.com, instagram.com (The Kitchens), tripadvisor.com.au | n/a: shopping-centre and directory sites, row dropped | another trade: food precinct | no, dropped |

Referring-domain counts are raw totals from the bulk endpoint, not filtered for
quality (`build/data/refdomains-2026-10-15.csv`,
`build/data/refdomains-kitchens-2026-10-15.csv`,
`build/data/refdomains-control-2026-10-15.csv`). Airtasker (16,742), Houzz
(6,722), hipages (3,771), Yellow Pages (16,841) and Localsearch (9,163) are
directory-scale and excluded from the bar.
Outliers: goldcoastkitchensaustralia.com (1,376, #4 kitchens gold coast) and
burleighkitchens.com (1,393, September near-me control only, not in the
October top 10).

Other counts pulled: coastalcabinets 112 (#4 head), flatpaxcuttosize 78 (#5
head, trade supplier), customcabinets.net.au 84 (#6), craftsmanbuilt 210 (#7),
germancraft 148 (#10), shoresidekitchens 32 (#6 kitchens), houzkitchens 32 (#7
custom kitchens), bmgcabinets 35 (#8 head, #9 joinery), cuisinekitchens 111
(#4 custom kitchens). Control pull: kitchenbuildersqueensland 87 and
goldcoastcabinets 39 (#1 and #3 kitchen cabinets), mikedesign 175 and
craftbuilt 306 (Brisbane, near me), kitchenu 119 and hasl 120 (kitchen
renovations), wardrobeconnection 112 and justwardrobes 185 (wardrobes).

Bars: head term top-3 specialists 49 to 267; kitchens page 39 to 112;
joinery 49 to 78. For comparison, Cairns (a GO) read 26 to 57 on its head term
and 35 to 89 on kitchens; Perth Tiling Specialists 4 to 74.

Control, 15 October 2026: four domains already counted in the Cairns pull of
11 October 2026 were re-pulled with the Gold Coast gaps. hipages 3,730 to
3,771, localsearch 9,057 to 9,163, dreamdoorskitchens 273 to 283 (all within
4%), fnqkitchens 26 to 32. The endpoint is consistent across runs. On small
sites, read a difference of about 6 referring domains as noise, so #1 on the
head term (49) and the top of Cairns' range (57) are not meaningfully apart.

Read: the home query here is held by specialists doing real SEO, unlike Cairns
where hipages and Facebook filled page 1. Zero ads on 8 of 9 queries despite
$7 to $14 CPC, so the CPC does not prove anyone is paying for these clicks on
mobile. Two small operators (KW Cabinets, Flawless Cabinets) already hold the
head-term pack.

## Competitor gaps

T05. What none of the top three publish.

Home pages read by web fetch on 15 October 2026. Two sets, by Brad's choice
(see `05-log.md` Decisions): the five ranking sites from the SERP ownership
table, and the five other sites on Brad's own list, which rank in none of the
nine October queries. Brad's list also included currumbincabinets and
coastalcabinets, which are in the first set.

**Ranking sites** (position from the SERP ownership table and the Other counts
line):

| site | ranks | ref domains | pricing | process / lead time | QBCC shown | warranty | FAQ | suburbs named | reviews on page | showroom / visit |
|---|---|---|---|---|---|---|---|---|---|---|
| currumbincabinets.com.au | #1 cabinet makers gold coast | 49 | none | none / none | yes (15187590) | none | none | none ("Surfers Paradise to Southern Tweed") | none | address only |
| bjfjoinery.com.au | #2 cabinet makers gold coast; pack | 267 | none; paid design consult, fee refundable | 5 steps / "timelines may vary" | yes (1286518) | none | none | 27, with 3 location pages | ~22 testimonials, ~35 project pages | showroom by appointment, Mon to Fri |
| coastalcabinets.com.au | #4 cabinet makers gold coast; #2 kitchens gold coast | 112 | none | none / none | no | none | none | none | 4 testimonials | factory address only |
| thepinnaclekitchen.com.au | #3 kitchens gold coast; #3 custom kitchens | 67 | none; interest-free finance, 36 and 48 months both stated | page linked, none on home / none | yes (15097253) | warranty page; "100% satisfaction guarantee" | none | none | none | showroom page, no hours |
| goldcoastjoinery.com.au | #1 joinery gold coast ("Contact Us"); #1 custom kitchens | 49 | none | 7 steps / none | no | none | none | none | 1 snippet; Best of Houzz 2018 | factory hours Mon to Fri 8 to 5, no showroom |

Notes on the ranking set:

- BJF is the only site doing deliberate local SEO: service pages per segment
  (including `/cabinet-makers-gold-coast/` and `/kitchen-renovations-gold-coast/`),
  suburb pages, style pages and a blog. It states that it does not take
  one-off cabinets or refacing, only complete kitchen renovations.
- Gold Coast Joinery holds #1 for joinery with a thin static site whose title
  and H1 are "Kitchens Gold Coast". The joinery query is won by a page that is
  not about joinery.
- Pinnacle's home-page contact form renders "Error: Contact form not found",
  and its finance offer contradicts itself.
- Brand logos (Blum, Laminex, Caesarstone, Polytec, Hafele, Quantum Quartz)
  are common. No site explains the choice between board and finish types.

**Brad's other five** (not in the top 10 for any October query):

| site | what it is | pricing | process | QBCC shown | reviews on page | renter fit |
|---|---|---|---|---|---|---|
| gcacabinets.com (Gold Coast Assembled Cabinets, Biggera Waters) | "ready-to-go cabinets to custom builds", aimed at homeowners; design, assemble, supply, deliver | none | none | no ("Licensed Supplier" badge, no number) | none; Google badge | excluded as flat pack by name on 15 Oct; the site reads as homeowner custom work too. Open item |
| thecabinetryco.com.au (Ormeau) | custom kitchens, bathrooms, wardrobes | none | none | no | none | not in the Maps pull (Ormeau, northern edge); thin site, two paragraphs |
| qualitycabinetsgc.com.au (Nerang, 29 Maps reviews) | custom kitchens, bathrooms, laundries, entertainment, alfresco | none | 3 steps; reply in 1 business day | no | none on page; links to Google | plausible: in the 109, homeowner-focused; the displayed email and the mailto target differ |
| signaturejoinery.net.au (Burleigh Heads, 5 Maps reviews) | supplier to builders, also retail; own factory; names melamine, 2-pac, thermolaminate | none | CAD, factory, install / none | no | none; ~30 uncaptioned photos | plausible: in the 109, but builder work is its main line |
| lanbuild.com.au (Carrara) | builder and insurance repairer with a cabinet division; the URL is a Broadbeach Waters project page | none | none | yes (15198335) | 1 | stays excluded: a builder, not a cabinet maker |

**Gaps, across all ten:**

1. **Cost.** None of the ten publishes a price, a range or a cost driver.
   BJF only says its design fee is refundable. Any price guidance on this site
   needs a sourced figure first (R2; job-value item in `05-log.md` Open items).
   Without one, the gap is filled with cost drivers, not numbers.
2. **Lead time.** None states how long a kitchen or a cabinet job takes from
   measure to install.
3. **FAQ.** None of the ten has one.
4. **Licensing.** Six of ten show no QBCC number, and none explains when a
   licence is needed. The rule itself waits on the QBCC item (T21) and a
   primary source (R2).
5. **Warranty.** Nine of ten are silent. The one that isn't (Pinnacle) puts it
   on a separate page. Any statutory warranty claim needs a primary source at
   T20.
6. **Materials.** No site compares board, door finishes or benchtop types for
   a buyer. Signature Joinery lists materials without comparing them.
7. **Suburbs.** Only BJF names suburbs. Every other site says "Gold Coast".
8. **Smaller jobs.** BJF rules out one-off cabinets and refacing. The sites
   that take wardrobes, laundries and vanities (Currumbin, Coastal) give each
   a thin page.
9. **Joinery.** The top 3 for "joinery gold coast" are two contact pages and
   an Instagram profile. No ranking page is about joinery.

## Commercial thesis

T05. One paragraph. **Must cite rows from the SERP ownership table above.** A
thesis resting on CPC alone is not done: high CPC on a remedial term can be
plumbers and leak detection bidding, not the trade this site serves.

The site wins on substance, not authority: it would be the only page-one
result that answers a buyer's cost-driver, time, process and licensing
questions. On **cabinet makers gold coast** (390), #1 Currumbin (49 referring
domains) and #4 Coastal (112) publish no process, lead time, FAQ or price
guidance, and Airtasker holds #3 with a directory list. #2 BJF (267) is the
real SEO operator, but it serves complete kitchen renovations only. On
**kitchens gold coast** (110) and **kitchen cabinets gold coast** (50),
Airtasker, hipages, Facebook threads, Reddit and an Instagram profile hold
five and three page-one slots respectively, which a substantive kitchens page
can displace. On **joinery gold coast** (40),
the top 3 are two contact pages and an Instagram profile, which is the softest
entry and the first link-building target. CPC ($7.54 head, $14.12 kitchens) is
not part of the case: there were zero ads on 8 of the 9 queries, and the one
advertiser, Oz Wardrobes on **wardrobes gold coast**, sells wardrobes only.
The ceiling is also explicit. **cabinet maker near me** is local-pack only and
needs the renter's Google Business Profile, and **kitchen renovations gold
coast** belongs to renovation builders, so the rent case rests on organic
top 3 for the head, kitchens and joinery queries (~660 a month). Two of the
gaps it leans on, cost and licensing, can only be filled from primary sources
at T20. If those sources can't be found, the page leans on process, lead-time
drivers, materials and suburbs.

## Renter evidence

T05. Named businesses seen paying for leads, and the count.

Paying for leads, observed in the 15 October 2026 SERP pull: Oz Wardrobes Gold
Coast runs a Google ad on "wardrobes gold coast", the only ad across nine
queries. Airtasker and hipages category pages rank on the head and kitchens
queries, but no named Gold Coast cabinet maker's profile page was seen ranking.
Count: 1 named.

Directory check, 15 October 2026: hipages refuses web fetch, so its Gold Coast
cabinet maker listings were not read. Oneflare's Gold Coast cabinet maker URL
now 301-redirects to Airtasker, and Airtasker's category URL returns 404 when
fetched directly. Open item in `05-log.md`; it does not block T06.

From the teardown: Quality Cabinets (Nerang, 29 reviews) and Signature Joinery
(Burleigh Heads) are plausible renters from Brad's list. Neither shows a QBCC
number, and both run a site that ranks for none of the nine queries.

Renter pool, from the 174 Google Maps listings pulled 21 August 2026
(`build/data/renter-pool-maps-2026-08-21.csv`), classified by name and
category on 15 October 2026, not visited one by one
(`build/data/renter-pool-classified-2026-10-15.csv`):

| bucket | count |
|---|---|
| Gold Coast cabinet, kitchen and joinery operators | 109 |
| Tweed side, NSW (no QBCC licence) | 12 |
| not a cabinet business (glass, CNC and laser, timber yard, drafting, handyman) | 23 |
| commercial or shopfit | 14 |
| trade supplier, flat pack, cut to size | 9 |
| chain (Wardrobe Connection x5, OPPEIN) | 6 |
| duplicate | 1 |

Of the 109: 3 established (60+ reviews), 36 with no website or only Instagram
or Google Sites, 34 small operators with 5+ reviews.

Plausible renters, active with no real website: Triple M Cabinets (32 reviews,
Instagram), Flawless Cabinets (27, Google Sites; already in the head-term
pack), Hammer Joinery (25), Allen Kitchens and Joinery (21), A Team Kitchens
(15), Gemstone Joinery (14), Cymbal Kitchen & Joinery (13), Eldhös Modern
Cabinetry (11), One Time Cabinets (9). Small with their own site: South East
Kitchens, Milano Interiors, Celtic Design Cabinet Makers, McCabe Carpentry &
Joinery, Coastline Joinery, Acme Joinery. Count: 15 named.

## Remote-execution verdict

T01. Either the link phases can be executed from here, or the ceiling is
accepted knowingly.

Proposed: joinery (49 to 78) and the kitchens page (49 to 112) are within
reach of remotely executable links such as citations, directories and content
assets. The head term's top 3 (49 to 267, with a 2-4x higher field than
Cairns) may need supplier or local links that do not work remotely; #1 at 49
suggests it is reachable, but not quickly. The local pack, and so "near me"
and probably bare "cabinet maker", is out of reach without a Google Business
Profile, which needs the renter's address. [NEEDS INPUT: accepted or rejected
by Brad at T06]

## Data files

T02, T04. Every pull lands here as a file in `build/data/`, with the command
that produced it. G2 fails if a file listed here is missing from disk.

Commands were run from `C:\Users\bjdac\dfseo`. Input files are copied
alongside here as `build/data/keywords.txt`, `serp-queries.txt`,
`serp-queries-2.txt`, `refdomains-targets.txt` and
`refdomains-targets-kitchens.txt`.

| file | command that produced it | date |
|---|---|---|
| build/data/volume-goldcoast-2026-10-15.csv | `python volume_adhoc.py --keywords gold_coast_cabinet_makers.txt --locations "Gold Coast,Queensland,Australia" --output gc_cabinet_local.csv` | 2026-10-15 |
| build/data/serp-goldcoast-2026-10-15.csv | `python serp_adhoc.py --queries gold_coast_serp.txt --location "Gold Coast,Queensland,Australia" --output gc_serp.csv` | 2026-10-15 |
| build/data/serp-goldcoast-2-2026-10-15.csv | `python serp_adhoc.py --queries gc_serp_kitchens2.txt --location "Gold Coast,Queensland,Australia" --output gc_serp_kitchens2.csv` | 2026-10-15 |
| build/data/refdomains-2026-10-15.csv | `python refdomains_adhoc.py --domains domains_gc_cabinet.txt --output refdomains_gc_cabinet.csv` | 2026-10-15 |
| build/data/refdomains-kitchens-2026-10-15.csv | `python refdomains_adhoc.py --domains domains_gc_kitchens.txt --output refdomains_gc_kitchens.csv` | 2026-10-15 |
| build/data/refdomains-control-2026-10-15.csv | `python refdomains_adhoc.py --domains domains_gc_control.txt --output refdomains_gc_control.csv` (input copied as `refdomains-targets-control.txt`; run by Brad) | 2026-10-15 |
| build/data/renter-pool-maps-2026-08-21.csv | workbook renter-pool run (`fill_renters_maps.py`), Gold Coast cabinet rows extracted from `renter_pool.csv` | 2026-08-21 |
| build/data/renter-pool-classified-2026-10-15.csv | `python classify_gc_renters.py` (exclusion lists by business name, hand-judged) | 2026-10-15 |
| build/data/serp-batch-goldcoast-2026-09-01.csv | workbook SERP batch (`dfseo.py serp`), Gold Coast cabinet rows extracted from `serp_batch_log.csv`; source of the refdomains target list | 2026-09-01 |

## Future niche log

Segments found that belong to a different trade, so they are not rediscovered
next build.

- Kitchen renovations, Gold Coast: 260 a month at $12 CPC, held by renovation
  builders (Hasl suburb pages, Varli) and the Kitchen U franchise, not cabinet
  makers. Unlike Cairns.
- Shopfitting, Gold Coast: 110 a month, commercial. SERP not read. 14
  commercial and shopfit businesses in the Maps pull.
- Stone benchtops, Gold Coast: 110 a month, likely stonemasons. SERP not read.
- Bathroom vanities, Gold Coast: 140 a month, likely retail bathroomware (as in
  Cairns). SERP not read.
- Wardrobes, Gold Coast: 110 a month plus ~60 long-tail, held by wardrobe
  specialists and the Wardrobe Connection chain; Oz Wardrobes is buying ads.
  A possible standalone build.
- Outdoor kitchens, Gold Coast: 70 a month. SERP not read.
