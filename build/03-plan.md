# 03 Page plan

Status: SIGNED-OFF | Brad, 20 October 2026
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
| index.html | / | pages.home | 1, built first | cabinet makers gold coast | cabinet maker gold coast, cabinetmakers gold coast, cabinetmaker gold coast, cabinet maker, cabinet maker near me, joinery gold coast, joiners gold coast, joinery near me, custom cabinets gold coast, custom cabinets, wardrobes gold coast, built in wardrobes gold coast, custom wardrobes gold coast, walk in wardrobe gold coast | fits: `pages.home.blocks` renders Home from the block system (wardrobe and joinery sections, the job outline, the disclosure, a `form` block, a `faqs` block for FAQPage schema). Stock how-it-works, testimonials and the services grid do not render on a block Home |
| kitchens-gold-coast.html | /kitchens-gold-coast | services[0] | 1 on volume | kitchens gold coast | kitchen cabinets gold coast, custom kitchens gold coast, kitchen makers gold coast, kitchen manufacturers gold coast, kitchen design gold coast, kitchen benchtops gold coast, flat pack kitchens gold coast, outdoor kitchens gold coast | fits: `services[0]` with `page: "kitchens-gold-coast.html"` and name "Kitchens" takes the block copy; a `form` block with `presetService` puts the enquiry form on the page and suppresses the compact how-it-works strip; a `faqs` block feeds FAQPage schema; the Service schema names the provider as Organization. The JPEG takes `widths`; the SVG needs none |
| about.html | /about | pages.about | 3 | n/a | cabinet maker quote gold coast | fits: `pages.about.blocks` carries headed sections (what we do and do not do, how it is paid for, service area) and the contact section, then the engine's own form |
| privacy.html | /privacy | pages.privacy | 3 | n/a | n/a | fits: `pages.privacy.blocks` replaces the stock text, which describes the wrong data flow (no voicemail recording, no Supabase in Tokyo, Resend, Twilio or 12-month retention) |

Two money pages, as `01-market.md` planned (about 660 targetable searches a
month): the home page owns the head group (390) and takes joinery and wardrobes
as sections; the kitchens page owns the kitchen terms. Everything else is a
section on one of them or no page, per the Keyword table: wardrobes (110 plus
long tail) and joinery (40, plus 30 for "joinery near me") are sections on Home;
kitchen design, benchtops, flat pack and outdoor kitchens are sections on the
kitchens page; kitchen renovations, kitchen resurfacing, vanities, shopfitting,
stone benchtops, entertainment units, laundry cabinets, "kitchens robina" and
every null term get no page. Nerang, Burleigh Heads and Southport appear only in
service-area copy, and Tweed Heads (NSW) not at all.

The kitchens page takes "kitchens gold coast" (110) as primary, not "kitchen
renovations gold coast" (260): T03 found renovation builders and a franchise
own that SERP (decision of 15 October 2026 in `05-log.md`). The page may mention
renovation once, as context, and does not target it. "kitchen cabinets gold
coast" (50) is the strongest secondary: its top 3 carry 87, directory-scale and
39 referring domains.

Joinery is the softest query read (two contact pages and an Instagram profile
in the top 3), so the Home joinery section is written to answer that query on
its own, and the Home title names joinery.

Contact is not a page. It is a section inside About, with the enquiry form on
Home, the kitchens page and About, as on Cairns and Perth Tiling Specialists.

Template fit is `fits`, `engine change: <reason>`, or `dropped`. A page whose
fit is unknown does not get drafted. On Perth Tiling Specialists, whether a
contact page could exist at all was settled by dropping the page rather than
by reading the engine.

**Template fit, T18, 20 October 2026.** Read against this repo's `bake.js` and
`config.js` (the template as of c06f4b9). Every change Cairns had to make to its
own engine on 13 October 2026 is now a config switch in the template, so this
build plans **no engine changes**:

1. **Header nav.** `navFromServices: true` gives Home, then each `services[]`
   page, then About, with a single footer "Pages" column plus Privacy. With one
   service named "Kitchens", that is the planned Home, Kitchens, About.
2. **Call-to-action band.** `contact.ctaBandAction` replaces "request your free
   quote online" (for example "send an enquiry online"), so no page says "free
   quote".
3. **How-it-works section.** `howItWorksSection` returns nothing when
   `howItWorks` is empty, so the stock "within 24 hours" and "Get it done" steps
   never render. Any process copy goes in blocks, once sourced.
4. **Job-type picker.** `contact.jobTypes` sets the options (for example
   Kitchens, Wardrobes, Joinery, Other) instead of the service names.
5. **QBCC value statement on every page.** `licence.required: true` with
   `licence.preRenterStatement` set to the Positioning wording renders it in
   the footer; G11 checks it while "renter signed" is N, and that no licence
   number shows.
6. **Not needed:** no new schema type (Service with an Organization provider is
   what the engine emits), no new image handling, no area pages (`areas` stays
   empty), no separate Contact page, no 404 change. The template's five demo
   service pages are removed in config, leaving one.

Because nothing in `bake.js`, `js/main.js`, `css/styles.css` or the page shell
is planned to change, T30's Backport table should read "none". If a later task
finds real copy that does not fit, that is an engine change to raise with Brad
first (CODE-SESSION-START rules), not something to make quietly. On Perth Tiling Specialists, whether a
contact page could exist at all was settled by dropping the page rather than
by reading the engine.

## Head

T17. Character counts include spaces. Title 60 or under, meta 155 or under.
The H1 is literal, including its local term, and is approved here rather than
polished later.

No head says "licensed", "free", a price, a years claim or a response time
(Positioning claim restrictions, R11). The Home H1 is plural, as Cairns settled
on 13 October 2026, so it reads as a route to cabinet makers and not as a claim
that we do the work. The brand itself is singular.

| file | title | chars | meta | chars | h1 |
|---|---|---|---|---|---|
| index.html | Cabinet Makers Gold Coast \| Kitchens, Wardrobes, Joinery | 56 | Looking for a Gold Coast cabinet maker? Tell us about your kitchen, wardrobe or joinery job and we pass it to a local cabinet maker who can quote it. | 149 | Cabinet Makers on the Gold Coast for Kitchens, Wardrobes and Joinery |
| kitchens-gold-coast.html | Kitchens Gold Coast \| Custom Kitchen Cabinets and Design | 56 | Custom kitchens on the Gold Coast: what a new kitchen involves, cabinet, benchtop and layout choices, and how to get a local cabinet maker to quote. | 148 | Kitchens on the Gold Coast: Custom Cabinets, Benchtops and Design |
| about.html | About Gold Coast Cabinet Maker \| How This Site Works | 52 | What Gold Coast Cabinet Maker is, the area we cover, what happens when you enquire, how the service is paid for, and how to get in touch. | 137 | About Gold Coast Cabinet Maker |
| privacy.html | Privacy Policy \| Gold Coast Cabinet Maker | 41 | What Gold Coast Cabinet Maker collects when you make an enquiry or call, who your details go to, how long they are kept, and how to have them removed. | 150 | Privacy Policy |

## Nav

T17. Ordered. Footer-only pages listed separately.

Ordered: Home, Kitchens, About. No Services item and no dropdown. The call
button sits beside them. Footer-only: Privacy. The footer mirrors the nav plus
Privacy and the QBCC value statement (Positioning), and carries a licence line
only once a renter is signed (R14).

## Cannibalisation map

T17. See PLAYBOOK.md rule R12.

| page | owns | must not expand into | sends readers to |
|---|---|---|---|
| index.html | routing the reader, how the site works, a short outline of how a cabinet job runs, joinery and wardrobes as sections that each answer their own query, service-area suburbs in copy, commercial disclosure in brief | any cost figure, kitchen detail beyond a summary, benchtop or design detail, kitchen renovation as a topic | kitchens page, About |
| kitchens-gold-coast.html | kitchen cabinets, layout and design, benchtops, flat pack against custom, outdoor kitchens in brief, how a kitchen job runs and what affects how long it takes, QBCC contract and deposit basics (each only once sourced) | wardrobes, joinery, vanities, shopfitting, stone benchtops as a trade, kitchen renovation as a target, any Gold Coast cost figure until a source is in "Cost figures" | Home for other rooms and joinery, About |
| about.html | who runs this, what the business does and does not do, the service area (Gold Coast, with Nerang, Burleigh Heads and Southport named in copy only), how it is paid for, contact | service detail, prices | Home, kitchens page |
| privacy.html | collection, disclosure, retention, access | commercial explanation beyond what disclosure needs | About |

## Internal link graph

T17. Name the inbound hub and the outbound hub. No orphans.

Inbound hub: the kitchens page, the page outreach would point at and the one
with the clearest weak slots (Airtasker, hipages, Facebook and Instagram on page
1). Outbound hub: Home. No orphans: every page is in the nav except Privacy,
which is in the footer on every page.

| page | inbound anchors | outbound anchors |
|---|---|---|
| index.html | every page's logo and nav "Home" | "kitchens on the Gold Coast" to the kitchens page; "how this site works" to About |
| kitchens-gold-coast.html | nav "Kitchens"; the kitchens block on Home | "wardrobes and joinery" to Home; "how this site works" to About |
| about.html | nav "About"; the call-to-action band | "Gold Coast kitchens" to the kitchens page; "home" to Home |
| privacy.html | footer, every page; the form notice link | "about this site" to About |

## Image direction

T17 writes what each image must show; T24 fills the measured columns. An image
that would make a factual or diagnostic claim is drawn as an SVG, never a
near-miss photo. No captions.

Two kinds of image, as on Cairns (Positioning carries the rule):

- **Illustrative images**, generated at T23, never presented as our work or a
  renter's work: no caption, no "our projects" or "recent work" wording, no
  before and after, no readable business name or logo, and alt text that says
  what is illustrated, not what was done. R10 applies. These are new images:
  the Cairns files are not reused, so the two sites do not share pictures.
- **Diagrams**, drawn as SVG, wherever an image would make a factual claim. Each
  is tied to a sourced Claim register row, or not drawn.

| file | image | shows | photo or diagram | alt text | width | height | KB | widths |
|---|---|---|---|---|---|---|---|---|
| index.html | images/home-hero-gold-coast.jpg | a bright fitted kitchen opening onto a living area with built-in joinery (shelving or a media wall) in a light, airy coastal home; no people, no text | illustrative image (generated) | An illustrated light-filled kitchen and living area with built-in timber joinery | | | | |
| index.html | images/wardrobe-joinery.jpg | a built-in wardrobe or walk-in robe with open shelving and drawers; no people, no text | illustrative image (generated) | An illustrated built-in wardrobe with shelving, drawers and hanging space | | | | |
| kitchens-gold-coast.html | images/kitchens-gold-coast.jpg | a different modern kitchen from a three-quarter angle across an island: cabinetry, stone-look benchtop, overhead cupboards; no people, no text | illustrative image (generated) | An illustrated modern kitchen with an island bench and pale cabinetry | | | | |
| kitchens-gold-coast.html | images/kitchen-cabinet-parts-gc.svg | the named parts of a kitchen base cabinet (benchtop, carcass, shelf, kickboard, hinge, door, edge); labels only, no performance or moisture claim; redrawn in this site's palette rather than copied from Cairns | diagram | Diagram naming the parts of a kitchen base cabinet: benchtop, carcass, shelf, kickboard, hinge, door and edge | 1200 | 800 | | none |

Generation prompts are written at T23, from the Cairns prompts with a coastal
south-east Queensland feel and the same rules (no people, no text, no logos, no
identifiable place, realistic proportions).

## Linkable asset

T17. Which page, and six named outreach targets, or the words
`conversion asset only`. An asset nominated with no named target is a page
nobody will link to.

`conversion asset only`. The page worth linking to would be a Gold Coast
kitchen cost and process guide on the kitchens page, but there is no Gold Coast
or Queensland cost source yet (R10; job-value item in `05-log.md`), so no asset
is nominated and no outreach targets are named. If T20 finds a source, nominate
the kitchens page here and name six targets before drafting. The
remote-execution verdict accepted at T06 expects citations and directories for
the kitchens and joinery terms; that is link work, not an asset.

## Claim register

T17 lists every safety, regulatory or standards claim and the primary source
required. T20 resolves every row. Status is `sourced` or `dropped`, never
`open`, before Evidence goes CLEAR. See PLAYBOOK.md rule R2.

Rows 1, 2, 4 and 7 were sourced for Cairns on 13 October 2026 from QBCC pages.
They are Queensland-wide, so they apply here, but T20 re-reads each page and
re-dates it before this build relies on it. Status stays `open` until then.

| # | claim as it will appear | page | primary source required | status | source | edition | url | date checked |
|---|---|---|---|---|---|---|---|---|
| 1 | In Queensland, building work valued over $3,300 needs a QBCC licence, and the Cabinet making licence class covers installing, refurbishing or repairing kitchen and other fitted cabinets on site | kitchens, About | QBCC Act and the QBCC's own guidance | open | Cairns read: QBCC, "Who must hold a QBCC licence" and the "Cabinet making" licence page | | https://www.qbcc.qld.gov.au/my/node/7081 ; https://www.qbcc.qld.gov.au/licences/apply-licence/available-licences/other-trade/cabinet-making | |
| 2 | For domestic building work over $3,300 the QBCC says a written contract is essential, with cooling-off advice; maximum deposits by contract value, with a higher limit where most of the price is made-to-measure work done off site (cabinetry is the QBCC's example) | kitchens | QBCC Act, domestic building contracts provisions | open | Cairns read: QBCC, "Contracts and payments" and "Deposits and progress payments" | | https://qbcc.qld.gov.au/node/1331 ; https://www.qbcc.qld.gov.au/home-owner-hub/build-renovate/contracts-payments/deposits-progress-payments | |
| 3 | Practical advice only: ask what the carcass is made of, whether it is a moisture-resistant grade, and whether cut edges are sealed. No standard or board class is named unless a primary source is read | kitchens | a board manufacturer's technical data, or Standards Australia for the board standard | open | Cairns dropped the standard (no readable primary source; the particleboard classes differ by edition) | | | |
| 4 | Queensland Home Warranty insurance applies to residential building work valued over $3,300 including materials, labour and GST, and the QBCC lists replacing or refitting fixtures or fittings in a kitchen among it. Cabinetry is not named, so the copy does not name it | kitchens, About | QBCC home warranty scheme page | open | Cairns read: QBCC, "What work requires insurance" | | https://www.qbcc.qld.gov.au/my/node/2886 | |
| 5 | Any duration for a kitchen or cabinet job, or a lead-time range | kitchens, Home | a peak body (Master Builders, HIA) or a named published source, not a competitor | open | Cairns found none and dropped it. The T05 gap (no competitor states a lead time) makes it worth one more search | | | |
| 6 | Any Gold Coast or Queensland kitchen or cabinetry cost figure | kitchens | a Gold Coast or Queensland source (R10) | open | none in hand. The $1,120 rent case leans on a Sydney benchmark, which is not used in copy | | | |
| 7 | Every page carries: "Gold Coast Cabinet Maker cannot perform building work valued in excess of $3,300. For work above that value, discuss it with the cabinet maker who quotes your job." The first sentence follows the QBCC's own example wording | all pages | the QBCC's advertising guidance (whether it is legally required stays with a solicitor) | open | Cairns read: QBCC advertising page | | https://www.qbcc.qld.gov.au/running-your-business/advertising | |

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

20 October 2026. Brad signed off the plan as drafted in the Code session: the inventory (Home, kitchens-gold-coast, About, Privacy), the Head table (titles, metas and H1s as written, including the plural Home H1), the nav (Home, Kitchens, About; Privacy in the footer), the cannibalisation map, the link graph, the image direction (new generated images, not the Cairns files) and `conversion asset only`. The template fit (T18: no engine changes) was in the file at sign-off. The plan is the record; a later change to a title, meta, H1 or the nav needs this section re-signed.
