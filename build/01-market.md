# 01 Market read

Status: GO | 2026-10-15, Brad

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

## Winnability

Stage 1.4, added 16 November 2026 after launch (plan C7). Scored every
distinct job people search for on the Gold Coast, not just the head term. A
job is **winnable** when all three hold:

- (a) city volume is 20 or more a month, or its close variants add up to 20;
- (b) at least one of its top 3 organic results is a small specialist site
  with under 100 referring domains (not a directory, marketplace, national
  brand or government site);
- (c) keyword difficulty is 30 or under, or not shown.

Source: the Niches tab scan of 16 November 2026 (Google Ads volume located in
Gold Coast, Labs difficulty for Australia, mobile page 1 located in Gold
Coast, referring domains from DataForSEO Backlinks; $1.12, after a first run
of $0.77 whose grouping was faulty and is not used). Every job is in
`build/data/niche-scan-gold-coast-2026-11-16.csv`. Close variants that Google
Ads gives one shared figure are merged (kitchen renovations, kitchen reno and
kitchen remodel gold coast are one 260). Top 3 counts are referring main
domains. wheree.com, yellowpages.net and goldcoastdirectory.com are
directories although the scan gave them a count; it changes no verdict below.

| job | city volume | top 3 domains | small specialist under 100 RD in top 3? | difficulty | winnable | intended page |
|---|---|---|---|---|---|---|
| cabinet makers gold coast / cabinet makers gold coast qld | 390 | wheree.com (directory), capriqld.com.au 177, craftsmanbuilt.com.au 210 | no | 0 | no (b) | index.html |
| kitchen renovations gold coast / kitchen reno / kitchen remodel gold coast | 260 | Localsearch, Reddit, MapQuest | no, directories only | 9 | no (b) [an all-directory page 1 can be an opening; the October read found renovation builders here, so Brad to judge] | kitchens-gold-coast.html, secondary only |
| bathroom vanities gold coast | 140 | earlysettler.com.au 1,411, hipages, bcw.net.au 69 | yes (bcw.net.au 69) | 0 | yes, narrowly; a furniture retailer and a directory hold the rest, so most of these searchers may want a vanity off the shelf | no page; Brad to decide |
| kitchens gold coast / kitchens goldcoast / best kitchens gold coast | 120 | Reddit, yellowpages.net (directory), vertokitchens.com.au 120 | no | 2 | no (b) | kitchens-gold-coast.html |
| wardrobes gold coast / wardrobes gold coast qld | 120 | shop.moderndesignwardrobes.com.au (not looked up), onwardjoinery.com.au 41, Localsearch | yes (onwardjoinery 41) | 0 | yes | candidate wardrobes page; Brad to decide |
| shopfitting store gold coast / shopfittings store gold coast | 120 | shopfittingsstore.com.au 646, siretail.com 251, bjfjoinery.com.au 275 | no | 27 | no (b); shop fittings retail | no page |
| shopfitting gold coast | 110 | Localsearch, elitecj.com.au 38, MapQuest | yes (elitecj 38) | 1 | yes; commercial buyers, a different renter from a home cabinet maker | no page; Brad to decide |
| stone benchtops gold coast | 110 | cdkstone.com.au 742, customstonesolutions.com.au 167, mjgstone.com.au 50 | yes (mjgstone 50); stonemasons | 0 | yes | section on kitchens-gold-coast.html (stonemason segment) |
| joinery gold coast | 90 | Yellow Pages, MapQuest, finnmeg.com.au 37 | yes (finnmeg 37) | 3 | yes | index.html (a section today) |
| kitchen shops gold coast | 90 | kitchenwarehouse.com.au 2,691, rewardhospitality.com.au 862, robinskitchen.com.au 1,284 | no; cookware retail | 24 | no (b) | no page |
| outdoor kitchens gold coast | 70 | theoutdoorcook.com.au 114, australianoutdooralfrescokitchen.com 55, Instagram | yes (55) | 1 | yes | section on kitchens-gold-coast.html today |
| cabinetry gold coast | 50 | capriqld.com.au 177, dandsjoinery.com.au 53, Localsearch | yes (dandsjoinery 53) | 0 | yes | index.html |
| kitchen showroom gold coast | 50 | dreamdoorskitchens.com.au 292, mintdk.com.au 114, thepinnaclekitchen.com.au 72 | yes (pinnacle 72) | 0 | yes; these searchers want a showroom to visit, which only a renter has | no page until a renter |
| shop fitting store gold coast | 50 | MapQuest, MapQuest, ABR | no, directories only | 27 | no (b) | no page |
| kitchen displays gold coast | 50 | Reddit, kitchensbyalliance.com.au (not looked up), yellowpages.net | no | 2 | no (b) | no page |
| kitchen cabinets gold coast | 40 | MapQuest, Facebook, emeraldkitchenrenos.com 62 | yes (emerald 62) | 0 | yes | kitchens-gold-coast.html |
| kitchen benchtops gold coast | 40 | Instagram, Reddit, granitebenchtops.com.au 35 | yes (35); stonemasons | 0 | yes | section on kitchens-gold-coast.html (stonemason segment) |
| kitchen cupboards gold coast | 40 | goldcoastdirectory.com, wheree.com, goldcoastdirectory.com (all directories) | no, directories only | 0 | no (b) | kitchens-gold-coast.html |
| wardrobe doors gold coast | 40 | designerwardrobes.com.au, wdc.com.au, glass and door sites (not looked up) | not known | 0 | no (b): no count read for any of the three | candidate wardrobes page |
| wardrobe sliding doors gold coast | 40 | asw-online.com.au, goldcoastwardrobedoors.online, glasshouseau.com (not looked up) | not known | 0 | no (b): no count read for any of the three | candidate wardrobes page |
| just wardrobes nerang / just wardrobes gold coast | 260 | not used | n/a | 0 | no: a business's name (justwardrobes.com.au), not a job | no page |
| designer wardrobes gold coast, banks benchtops gold coast, a team kitchens gold coast, polytec gold coast | 30, 20, 20, 20 | not read | n/a | 0 to 6 | no: business or product names, not jobs | no page |
| 17 jobs at 20 to 40 not read (scan limit of 20 page 1 reads): benchtops 40, built in wardrobes 30, laminate benchtops 30, cabinet makers nerang 30, gold coast shop fittings 30, kitchen design 20, kitchen designers 20, kitchen cabinet makers 20, flat pack kitchens 20, custom wardrobes 20, custom cabinets 20 (difficulty 41), cut to size cabinets 20 (35), kitchen company 20 (35), kitchen bathroom renovations 20, shopfitter 20, cabinet makers burleigh / burleigh heads 20 each | 20 to 40 | not read | not read | 0 to 41 | no: not read, counted as no until read | sections where the October table places them |
| 77 jobs at 10 a month | 10 each | not read | not read | various | no (a) | no page |

Totals: Winnable jobs: 10. Searches a month: 820 (140 + 120 + 110 + 110 + 90 + 70 + 50 + 50 + 40 + 40). Estimated monthly value: $5,740,000 (820 searches x $7,000 job value from the Niches tab; a ceiling that assumes every search is a job, for comparison between sites only, not a forecast). Of the 10, two are stonemason work (stone and kitchen benchtops, 150), one is commercial (shopfitting, 110), one needs a renter's showroom (50) and one is probably retail (vanities, 140). The cabinet-maker core is 5 jobs and 370 searches: wardrobes 120, joinery 90, outdoor kitchens 70, cabinetry 50, kitchen cabinets 40. The head term (390) and kitchens gold coast (120) are not winnable: strong businesses and directories hold them.

## Winnability reference

There is no pass mark (Brad, 14 Nov 2026). Read the totals above against the
existing sites. Copied from the template's reference table of 14 November
2026, with Cairns updated from its own scan the same day; not re-measured here.

| site | winnable jobs | outcome at 14 Nov 2026 (site age) |
|---|---|---|
| Perth Limestone | 10+ (backtest) | avg position 24.9, 8 leads a month (day 102) |
| Perth Brickwork | 10+ (backtest) | avg position 48.6, 5 leads a month (day 103) |
| Cairns Cabinet Makers | 6 by its 16 Nov scan; cabinet-maker core 3 jobs, 370 searches | avg position 69.3, no leads yet (day 32) |
| Gold Coast Cabinet Makers | 10 by this scan; cabinet-maker core 5 jobs, 370 searches; head term not winnable | avg position 66.7, no leads yet (day 20) |
| Perth Tiling Specialists | head terms held by directories | avg position 74.4, no leads (day 63) |
| Canberra Tile Layers | head terms held by directories; volumes mostly 10 or fewer | avg position 70.9, no leads (day 75) |

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
Profile, which needs the renter's address.

Accepted by Brad at T06, 15 October 2026. The ceiling is taken knowingly: the
rent case rests on organic top 3 for the head, kitchens and joinery queries,
not on the local pack.

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
| build/data/niche-scan-gold-coast-2026-11-16.csv | Niches tab, Cabinet Makers / Gold Coast, Scan again (admin-action niche_scan_start, version 40), exported from niche_jobs with `supabase db query --linked -o csv` | 2026-11-16 |

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
