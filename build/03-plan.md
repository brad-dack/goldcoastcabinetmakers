# 03 Page plan

Status: SIGNED-OFF | Brad, 20 October 2026
Evidence: CLEAR | 20 October 2026

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
| index.html | images/home-hero-gold-coast.jpg | a bright fitted kitchen opening onto a living area with built-in joinery (shelving or a media wall) in a light, airy coastal home; no people, no text | illustrative image (generated) | An illustrated light-filled kitchen and living area with built-in timber joinery | 1200 | 800 | 140 | 400, 560, 720, 960 |
| index.html | images/wardrobe-joinery.jpg | a built-in wardrobe or walk-in robe with open shelving and drawers; no people, no text | illustrative image (generated) | An illustrated built-in wardrobe with shelving, drawers and hanging space | 1200 | 800 | 144 | 400, 560, 720, 960 |
| kitchens-gold-coast.html | images/kitchens-gold-coast.jpg | a different modern kitchen from a three-quarter angle across an island: cabinetry, stone-look benchtop, overhead cupboards; no people, no text | illustrative image (generated) | An illustrated modern kitchen with an island bench and pale cabinetry | 1200 | 800 | 134 | 400, 560, 720, 960 |
| kitchens-gold-coast.html | images/kitchen-cabinet-parts-gc.svg | the named parts of a kitchen base cabinet (benchtop, carcass, shelf, kickboard, hinge, door, edge); labels only, no performance or moisture claim; redrawn in this site's palette rather than copied from Cairns | diagram | Diagram naming the parts of a kitchen base cabinet: benchtop, carcass, shelf, kickboard, hinge, door and edge | 1200 | 800 | 3 | none |

T24, 23 October 2026. The three Gemini images arrived as `.jpeg` (1264 by 848),
were checked against the list below (no text, no logos, straight lines; the
hero's oven dial was zoomed and carries no brand mark), cropped to 3:2, resized
to 1200 by 800 and saved under the file names above, with `-400`, `-560`,
`-720` and `-960` variants. The originals are kept in `build/source-images/`,
which `_config.yml` keeps off the live site. The SVG was drawn by Code as a
side cutaway in a warm oak and sage palette, so it does not repeat the Cairns
front view, with its own title and description inside the file. Wiring the
image entries into `config.js` is part of T25, with the copy, as on Cairns.

### Generation prompts for T23

Written 21 October 2026, from the Cairns prompts, with new scenes so the two
sites share no pictures. Brad runs these in Gemini and saves the chosen image
into `images/` under the file name shown. Landscape 3:2 (about 1200 by 800 after
T24), subject centred because the hero crops differently on phones. The shared
rules are repeated in each prompt because Gemini forgets them.

**home-hero-gold-coast.jpg** (Home hero)

> A photorealistic photograph of a bright, airy open-plan kitchen and living
> area in a modern coastal Queensland home. Light oak-look and soft white
> cabinetry, a pale stone-look island benchtop, and a built-in timber joinery
> wall with open shelving and a media unit in the living area beyond. Natural
> afternoon light, sheer curtains, a glimpse of greenery through glass sliding
> doors. Eye level, 3:2 landscape, subject centred. No people, no text or
> lettering, no logos or brand names, no signage, no ocean or landmark that
> identifies a place. Realistic proportions: straight cabinet lines, one sink,
> matching handles, nothing duplicated or floating.

**wardrobe-joinery.jpg** (Home, wardrobes section)

> A photorealistic photograph of a built-in bedroom wardrobe with the doors
> open, showing hanging space, open shelving, a bank of drawers and shoe
> shelves, in light timber-look and white finishes. Soft natural daylight from
> one side, a calm coastal bedroom with a neutral palette. 3:2 landscape,
> subject centred. No people, no text or lettering, no logos or brand names, no
> visible clothing labels. Realistic proportions: straight lines, even shelf
> spacing, doors that hang square.

**kitchens-gold-coast.jpg** (Kitchens page hero)

> A photorealistic photograph of a different modern kitchen, seen from a
> three-quarter angle across a large island bench. Muted sage or soft grey
> cabinetry with slim handles, a light stone-look benchtop with a square edge,
> overhead cupboards to the ceiling and a simple tiled splashback, bright
> natural light. A relaxed subtropical feel without palm trees or beach in
> frame. 3:2 landscape, subject centred. No people, no text or lettering, no
> logos or brand names, no signage. Realistic proportions: one sink, one
> cooktop, matching handles, no warped or duplicated objects.

**kitchen-cabinet-parts-gc.svg** (Kitchens page): not a Gemini image. Code draws
it at T24 as an SVG in this site's palette, with labels only (benchtop, carcass,
shelf, kickboard, hinge, door, edge) and no performance or moisture claim.

Check each image before saving:

- Handles, taps and appliances are not warped, doubled or fused
- Cabinet lines are straight and doors meet cleanly
- No readable text on any surface, and no brand shapes on appliances
- Nothing in the frame looks like a specific named place or business
- It reads as a plausible home, not a luxury showroom a renter could not build
- It does not look like the Cairns images (different colours and angle)

Gemini's output terms and any generated-image labelling are Brad's to confirm
for his own account. Nothing on the site calls these images work we did.

## Linkable asset

T17, revised 20 October 2026 after T20. **The kitchens page
(kitchens-gold-coast.html)**, built as a linkable asset: the sourced Gold Coast
cost table from "Cost figures" with its method and disagreement explained, the
QBCC contract, deposit and home warranty basics (claim rows 1, 2 and 4), and
what to ask a cabinet maker (row 3). No other page on the Gold Coast SERP
publishes cost guidance (Competitor gaps 1), which is what makes it citable.

**No outreach before a renter is signed** (Brad, 20 October 2026). The page is
built ready, so links can start the day a renter signs. The targets below are
named now so the page is written for real readers, not so they are contacted.

| # | target | why it would cite the page | checked |
|---|---|---|---|
| 1 | Conrad Hyslop (Gold Coast real estate), article "Should You Renovate Before Selling a Property on the Gold Coast?" | a Gold Coast renovation-before-sale article with no cost figures; the table is the missing data | page fetched, HTTP 200, 20 October 2026 |
| 2 | Gold Coast Bulletin, real estate and homes coverage | local paper; a sourced Gold Coast kitchen cost range is a data point for a renovation or property story | site is live but refuses automated fetch (HTTP 403); no article read |
| 3 | realestate.com.au News, renovation and cost features | national property news that covers Gold Coast markets and renovation spend | section fetched, HTTP 200, 20 October 2026 |
| 4 | Domain, Living / Renovating section | national renovation editorial that cites cost sources | refuses automated fetch (HTTP 403); not read |
| 5 | Home Beautiful, Gold Coast home tours (e.g. "Gold Coast penthouse renovation") | runs Gold Coast renovation features with kitchens at the centre and no cost context | page fetched, HTTP 200, 20 October 2026 |
| 6 | LJ Hooker, "Preparing Your Home For Sale" guide for Gold Coast homes | a pre-sale guide for the same homeowners, with no kitchen cost figures | found by search, 20 October 2026; not fetched |

Targets 2 and 4 were not read, so their fit rests on what the outlets are known
to publish. Re-check all six, and look for Gold Coast-specific additions, when a
renter is signed and outreach starts. The cost table's review date (October
2027) applies to the asset too: a stale figure is a reason not to be cited.

## Claim register

T17 lists every safety, regulatory or standards claim and the primary source
required. T20 resolves every row. Status is `sourced` or `dropped`, never
`open`, before Evidence goes CLEAR. See PLAYBOOK.md rule R2.

Rows 1, 2, 4 and 7 were sourced for Cairns on 13 October 2026 from QBCC pages
and re-read for this build on 20 October 2026 (page fetched, wording and figures
checked on the page itself, review dates unchanged). Rows 3, 5 and 6 were
searched again. Where a row is narrowed, the claim column carries the narrowed
wording, which is all the copy may say.

| # | claim as it will appear | page | primary source required | status | source | edition | url | date checked |
|---|---|---|---|---|---|---|---|---|
| 1 | In Queensland, building work valued over $3,300 needs a QBCC licence, and the Cabinet making licence class covers installing, refurbishing, restoring or repairing kitchen, bathroom, laundry and other fitted cabinets | kitchens, About | QBCC Act and the QBCC's own guidance | sourced | QBCC, "Who must hold a QBCC licence" and the "Cabinet making" licence page (scope: "Install, refurbish, restore or repair kitchen, bathroom, laundry and other fitted c[abinets]") | licence page last reviewed 16 April 2026; cabinet making page last reviewed 30 August 2021 | https://www.qbcc.qld.gov.au/my/node/7081 ; https://www.qbcc.qld.gov.au/licences/apply-licence/available-licences/other-trade/cabinet-making | 20 October 2026 |
| 2 | For building work over $3,300 the QBCC says a written, dated and signed contract is essential and must include advice about a cooling-off period; the maximum deposit is 10% of the contract price from $3,301 to $19,999 and 5% above $20,000, with up to 20% allowed where more than half the price (labour, materials and GST) is made-to-measure work done off site, kitchen modules and cabinetry being an example the QBCC gives | kitchens | QBCC Act, domestic building contracts provisions | sourced | QBCC, "Contracts and payments" and "Deposits and progress payments". The QBCC is the licensing authority; the Act itself was not read | contracts page last reviewed 14 May 2026; deposits page last reviewed 27 June 2025 | https://qbcc.qld.gov.au/node/1331 ; https://www.qbcc.qld.gov.au/home-owner-hub/build-renovate/contracts-payments/deposits-progress-payments | 20 October 2026 |
| 3 | Practical advice: ask what the carcass is made of, whether it is a moisture-resistant (MR) grade, and whether cut edges are sealed. Board makers sell MR melamine-faced particleboard recommended for interior areas with high humidity, such as kitchen cupboards and vanities. **No standard, no board class and no performance figure is named in the copy** | kitchens | a board manufacturer's technical data, or Standards Australia for the board standard | sourced | ForestOne, DesignerOne MR Particleboard technical data sheet: "recommended for interior applications subject to high humidity conditions ... kitchen cupboards". One manufacturer, so the copy says "board makers sell", not that all MR board performs the same | TDS dated April 2025 (file revision July 2025) | https://forest.one/media/sparsh/product_attachment/ForestOne_DesignerOne_MR_Particleboard-TDS_07.25.pdf | 20 October 2026 |
| 4 | Queensland Home Warranty insurance applies to most residential building work valued over $3,300 including materials, labour and GST, and the QBCC lists replacing or refitting fixtures or fittings in a kitchen or bathroom among it. Cabinetry is not named, so the copy does not name it | kitchens, About | QBCC home warranty scheme page | sourced | QBCC, "What work requires insurance" | last reviewed 1 August 2024 | https://www.qbcc.qld.gov.au/my/node/2886 | 20 October 2026 |
| 5 | None. The copy says to ask for a written timeline, and whether a quoted time covers cabinet and benchtop manufacture or only the work on site, with no durations | kitchens, Home | a peak body (Master Builders, HIA) or a named published source, not a competitor | dropped | no Master Builders, HIA or government timeline found; every duration came from renovation builders and templated guide pages, and they disagree (3 to 5 weeks against 6 to 12 weeks) | n/a | n/a | 20 October 2026 |
| 6 | Published Gold Coast kitchen renovation ranges, shown as source data in a table by publisher type, never as our price or a quote: see "Cost figures" | kitchens | a Gold Coast or Queensland source (R10) | sourced | one independent cost-guide site and three Gold Coast renovation builders; see Cost figures for each | October 2026 and earlier, per row | see Cost figures | 20 October 2026 |
| 7 | Every page carries: "Gold Coast Cabinet Maker cannot perform building work valued in excess of $3,300. For work above that value, discuss it with the cabinet maker who quotes your job." The first sentence is one of the QBCC's own example value statements | all pages | the QBCC's advertising guidance (whether it is legally required stays with a solicitor) | sourced | the QBCC advertising page says unlicensed contractors must state the value of work they can do, with the example "Cannot perform building work valued in excess of $3,300". It does not say whether a pre-rental referral site is such an advertiser, which is the legal question | last reviewed 30 August 2021, last published 30 June 2025 | https://www.qbcc.qld.gov.au/running-your-business/advertising | 20 October 2026 |

## Dropped claims

T20. The claim text and why it went. A dropped claim is deleted from the copy,
not just from this table.

| claim | reason |
|---|---|
| Any kitchen or cabinet job duration or stage timeline (register row 5) | No peak body or government source; builder and templated-guide figures disagree (3 to 5 weeks against 6 to 12 weeks) |
| Any standard, board class or performance figure for cabinet board (narrowed in row 3) | The copy keeps the practical advice and the manufacturer's stated use; the standard and the test values are not repeated |

## Traps found

T20. Claims that search results assert but primary sources do not support. The
Western Australian waterproofing licence is the worked example: every source
asserting it traced back to training provider marketing, and the licence
belongs to a different state.

- **The standard named in search summaries was the wrong part.** A search
  summary tied MR particleboard to AS/NZS 1859.1. The manufacturer's own data
  sheet cites AS/NZS 1859.2 for its moisture resistance and substrate
  properties, and 1859.3 for the decorative surface. No part is named in copy.
- **A Queensland cost page priced cabinets per linear foot.** gcbconstructions
  .com.au gives "$100 - $300/linear ft" stock and "$500 - $1,200/linear ft"
  custom cabinets, a US convention, with no Gold Coast source. Excluded.
- **Templated "guide" pages are not sources.** Several kitchen cost and timing
  results were near-identical pages on sitesau.github.io for Brisbane and the
  Gold Coast, with no publisher named. Excluded, as were directory and
  lead-generation pages.
- **"$3,300" has different bases on different QBCC pages**, as Cairns found: the
  home warranty page counts materials, labour and GST, the licence page does not
  say. The copy states the figure only as each page states it.
- **Search summaries are not sources.** Every figure here was re-read on the
  page itself on 20 October 2026.

## Cost figures

T20, where the build publishes figures. Reader-facing copy uses the publisher
type, never the business name. Peak bodies may be named.

Method, in the words that will appear on the page:

These are published price ranges for a kitchen renovation on the Gold Coast,
from one independent cost-guide site and three Gold Coast renovation builders,
read in October 2026. They are not our prices and not a quote. Each publisher
defines its tiers differently, and a renovation figure usually includes work
beyond the cabinets, such as demolition, plumbing, electrical and appliances.
The cabinet maker who quotes your job prices it on your kitchen.

| item | low | high | publisher type | source name | url | date |
|---|---|---|---|---|---|---|
| cosmetic refresh (new door faces and paint) | $7,850 | $19,600 | cost-guide site | What's The Damage? (Gold Coast kitchen renovation cost guide) | https://whatsthedamage.com.au/kitchen-renovation-cost-gold-coast/ | updated 10 October 2026 |
| budget renovation with new cabinetry | $11,750 | $24,500 | cost-guide site | What's The Damage? | same | same |
| mid-range renovation | $24,500 | $44,100 | cost-guide site | What's The Damage? (mid-range total quoted as $34,300) | same | same |
| custom joinery, premium finishes | $44,100 | $78,400 | cost-guide site | What's The Damage? | same | same |
| budget kitchen | $15,000 | $25,000 | renovation builder | Design Science | https://designscience.com.au/renovation-costs-gold-coast-2026-complete-guide/ | modified 10 September 2026 |
| mid-range kitchen | $25,000 | $45,000 | renovation builder | Design Science | same | same |
| premium kitchen | $45,000 | $80,000+ | renovation builder | Design Science | same | same |
| straight replacement, same layout | $25,000 | $40,000 | renovation builder | Orange Projects | https://orangeprojects.au/blog/kitchen-renovation-cost-gold-coast | 22 September 2026 |
| custom joinery, larger island | $40,000 | $60,000 | renovation builder | Orange Projects | same | same |
| premium or open plan | $60,000 | $80,000 | renovation builder | Orange Projects | same | same |
| cosmetic refresh (new doors, benchtop, splashback) | $15,000 | $30,000 | renovation builder | CD Construct (from its own Gold Coast projects, past 12 months) | https://www.cdconstruct.com.au/blog/gold-coast-renovation-costs-complete-guide | 17 March 2026 |
| mid-range full renovation, same layout | $35,000 | $55,000 | renovation builder | CD Construct | same | same |
| high-end full renovation, layout changes | $55,000 | $80,000 | renovation builder | CD Construct | same | same |

Convergence and disagreement: three of the four put a mid-range Gold Coast
kitchen at roughly $25,000 to $45,000 (What's The Damage? $24,500 to $44,100,
Design Science $25,000 to $45,000, Orange Projects $25,000 to $40,000 for a
same-layout replacement). Premium tops out around $78,000 to $80,000+ in all
four. CD Construct is higher at every tier ($35,000 to $55,000 mid-range), and
says its figures come from its own projects and include demolition, appliances,
painting and project management, which the lower tiers may not. The cosmetic
tier diverges most ($7,850 against $15,000 at the bottom) because the
publishers scope it differently (door faces and paint against doors, benchtop
and splashback).

Gaps: no peak body (Master Builders, HIA) or government kitchen cost figure for
the Gold Coast or Queensland; no cabinetry-only figure (every range is a whole
renovation); no figure for wardrobes or joinery, so the Home page carries none.

Review date: October 2027, 12 months from compilation.

## Sign-off

T19. H1 map and nav signed off by Brad in this file, not in a message.

20 October 2026. Brad signed off the plan as drafted in the Code session: the inventory (Home, kitchens-gold-coast, About, Privacy), the Head table (titles, metas and H1s as written, including the plural Home H1), the nav (Home, Kitchens, About; Privacy in the footer), the cannibalisation map, the link graph, the image direction (new generated images, not the Cairns files) and `conversion asset only`. The template fit (T18: no engine changes) was in the file at sign-off. The plan is the record; a later change to a title, meta, H1 or the nav needs this section re-signed.

Changed after sign-off, 20 October 2026, by Brad: the Linkable asset moved from `conversion asset only` to the kitchens page, built ready, with no outreach before a renter (see Linkable asset and `05-log.md` Decisions). No title, meta, H1 or nav changed, so no re-sign was needed.
