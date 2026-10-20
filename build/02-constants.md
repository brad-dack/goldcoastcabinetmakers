# 02 Constants

Status: DRAFT | [NEEDS INPUT: set to FROZEN with the date at T16]

Written by T07 to T16. Read by T12, T16, T21, T25 and T27. See PLAYBOOK.md.

**G1 blocks `node bake.js` while this file is missing, not FROZEN, carries any
`[NEEDS INPUT` token, or disagrees with `config.js`.** Do not set FROZEN to
unblock a bake. Fill the value instead. See PLAYBOOK.md rule R1.

Field labels in the two tables below are read by G1. Keep them exactly as
written.

## Identity

| field | value |
|---|---|
| brand | Gold Coast Cabinet Maker |
| domain | https://goldcoastcabinetmaker.com.au |
| entity | Sole trader. Brad, trading as Gold Coast Cabinet Maker (business name to be registered with ASIC before the domain) |
| abn | 78 538 005 810 |
| published name | Brad, first name only, on About and Privacy |
| email | [NEEDS INPUT: or the literal word none until an inbox exists] |
| phone e164 | +61756513804 |
| phone display | (07) 5651 3804 |

## Naming history

T07. Every name considered, so a rejected name is never re-litigated. Perth
Tiling Specialists revisited a rejected domain twice in one session.

T07 checks run 15 October 2026:

- **ASIC:** substring search (`ILIKE '%...%'`) of the ASIC Business Names
  dataset on data.gov.au (resource `55ad4b1c-5eeb-44ea-8b29-d410da431be3`,
  refreshed 13 October 2026), via `datastore_search_sql`. Control: "%cairns
  cabinet%" returned Cairns Cabinet Makers (ABN 78 538 005 810) and CAIRNS
  CABINET WORKS. The dataset holds business names only, not company names, so
  ABN Lookup covers the companies.
- **ABN Lookup:** abr.business.gov.au active-ABN name search (`ResultsActive`),
  looking for an active entity with a conflicting name. Control: "Cairns
  Cabinet Makers" returned Brad's own registration first.
- **Registrar:** the .au registry's RDAP service (`rdap.cctld.au/rdap/`); the
  .com was checked with Verisign RDAP. 404 means not registered. Controls
  goldcoastcabinets.com.au, goldcoastjoinery.com.au and
  currumbincabinets.com.au returned 200, and a junk domain returned 404. A
  second pass at 09:50 was rate limited (429), so each 404 is re-confirmed at
  registration (T09).
- **auDA:** the same route as Cairns: allocation by exact match to a business
  name registered with ASIC on Brad's ABN, registered before the domain. The
  close and substantial connection route is not relied on.

| name | domain | ASIC | ABN Lookup | registrar | auDA eligibility | verdict and reason |
|---|---|---|---|---|---|---|
| Gold Coast Cabinet Makers | goldcoastcabinetmakers.com.au | clean: the only "%gold coast cabinet%" name is GOLD COAST CABINETRY SALES (Townsville 4817) | no identical name; nearest is GOLD COAST ASSEMBLED CABINETS (ABN 71 613 591 290, Biggera Waters 4216) | registered (RDAP 200), parked on ns1/ns2.secureparkme.com, last changed 15 Aug 2026 | n/a | REJECTED: the .com.au is taken and parked. Aftermarket price unknown; Brad can make an offer if he wants the exact match |
| Gold Coast Cabinet Makers (.com) | goldcoastcabinetmakers.com | as above | as above | available (Verisign RDAP 404) | not needed for .com | REJECTED as the main domain: whoever holds the parked .com.au could take traffic and trust from the brand. Worth holding as a defensive registration if the singular below is chosen |
| Cabinet Makers Gold Coast | cabinetmakersgoldcoast.com.au | clean | no identical name | registered (RDAP 200), GoDaddy nameservers, last changed 15 Aug 2026 | n/a | REJECTED: taken |
| Gold Coast Cabinet Maker | goldcoastcabinetmaker.com.au | clean (as for the plural). ASIC Check Name Availability, Brad's screenshot shared 19 Oct 2026: "GOLD COAST CABINET MAKER is currently available"; similar existing names listed: GOLD COAST CABINETS PTY LTD, GOLD COAST CABINETRY SALES | no identical name; nearest GOLD COAST ASSEMBLED CABINETS (4216) and the COASTAL CABINETS entities (4208, 4211) | available (RDAP 404) | ok once "Gold Coast Cabinet Maker" is registered with ASIC on Brad's ABN | **CHOSEN at T08 by Brad, 15 October 2026.** Brad confirmed it available and ABN-clean the same day. Clean on all four checks, the singular of the head group (390 a month, grouped), and the same pattern as Cairns Cabinet Makers. Risk: the parked plural .com.au exists and its owner is unknown |
| Cabinet Maker Gold Coast | cabinetmakergoldcoast.com.au | clean | no identical name; generic "CABINETMAKER" trading names at 4216 (ABNs 52 459 257 865, 26 295 041 097) | available (RDAP 404) | ok once registered with ASIC | candidate, fallback: the same keyword match. Reads less like a business name |
| Gold Coast Cabinet Making | goldcoastcabinetmaking.com.au | clean | no identical name; nearest Coast Cabinets (VIC) and the COASTAL CABINETS entities (QLD) | available (RDAP 404) | ok once registered with ASIC | candidate, not preferred: clean, but a weaker keyword match than Cabinet Maker |
| Gold Coast Custom Cabinets | goldcoastcustomcabinets.com.au | clean | no identical name; Gold Coast Kustoms (4212) and Gold Coast Customs (NSW) are nearest | available (RDAP 404) | ok once registered with ASIC | candidate, not preferred: matches only "custom cabinets gold coast" (20 a month), and sits near customcabinets.net.au (#6 head) |
| GC Cabinet Makers | gccabinetmakers.com.au; also cabinetmakersgc.com.au | **GC Cabinet Makers is registered** (ABN 95 639 867 701); also GC Cabinets & Stone (ABN 75 201 403 006) | as ASIC | both available (RDAP 404) | blocked: the name is someone else's | REJECTED: an existing registered business name |
| Gold Coast Cabinetry | goldcoastcabinetry.com.au | GOLD COAST CABINETRY SALES registered (ABN 17 988 568 457) | as ASIC | registered (RDAP 200) | n/a | REJECTED: taken, and next to a registered name |
| Gold Coast Cabinet Co | goldcoastcabinetco.com.au | clean | close to GOLD COAST ASSEMBLED CABINETS and Coast Cabinets | available (RDAP 404) | not assessed | REJECTED: too close to Gold Coast Cabinets (goldcoastcabinets.com.au, #3 for "kitchen cabinets gold coast") |
| Gold Coast Kitchen Makers | goldcoastkitchenmakers.com.au | clean | GOLD COAST KITCHENS PTY LTD (ABN 88 611 832 403, Burleigh Heads 4220) | available (RDAP 404) | not relied on | REJECTED: collides with Gold Coast Kitchens Pty Ltd and goldcoastkitchensaustralia.com (#4 "kitchens gold coast"), and kitchens is not the home page's query |
| Gold Coast Custom Joinery | goldcoastcustomjoinery.com.au (also goldcoastjoinerymakers.com.au) | clean | Gold Coast Joinery Pty Ltd (ABN 50 149 117 377, 4213) | both available (RDAP 404) | not relied on | REJECTED: built on Gold Coast Joinery's name, the #1 result for "joinery gold coast" |

## Infrastructure

| field | value |
|---|---|
| registrar | GoDaddy |
| hosting | GitHub Pages, from brad-dack/goldcoastcabinetmakers, branch main |
| dns provider | Cloudflare (nameservers evan.ns.cloudflare.com, thea.ns.cloudflare.com). .au registry RDAP shows both, last changed 2026-10-18T22:29Z; public resolvers (router and 1.1.1.1) still returned ns13/ns14.domaincontrol.com at 22:30Z, pending propagation |
| proxy status | DNS-only |
| workers_dev | n/a, this is a GitHub Pages build |
| dns verified | 18 October 2026, 22:38 UTC (19 October AEST), through 1.1.1.1 and 8.8.8.8 (identical): `nslookup -type=NS` gives evan.ns.cloudflare.com and thea.ns.cloudflare.com; `nslookup -type=A` on the apex gives 185.199.108.153, .109.153, .110.153, .111.153; `nslookup www.goldcoastcabinetmaker.com.au` gives alias to brad-dack.github.io, which resolves to the same four addresses. Queried at evan.ns.cloudflare.com directly, the apex returns the GitHub addresses, not Cloudflare's, so DNS-only holds. www to apex redirect not yet checkable: GitHub Pages and its custom domain are not set up (T26) |
| twilio number | +61756513804, friendly name "Gold Coast Cabinet Maker", Local, Queensland, number SID PN88bfc011788fc2cd23a0045e134cf62a. Seen on Brad's Twilio screenshot, 20 October 2026 (Twilio displays it as +61 (756) 513-804) |
| twilio voice webhook | https://bnfgnglzswtrvzfqkgjh.functions.supabase.co/twilio-voice, POST, primary and backup both set to it. Same screenshot, active region Australia (AU1) |
| twilio status webhook | https://bnfgnglzswtrvzfqkgjh.functions.supabase.co/twilio-status, POST; caller name lookup disabled. Same screenshot. Not yet tested by a call: that is the T14 and T28 check |
| ga4 measurement id | G-GLJW8055PP |
| ga4 settings | 20 October 2026. Measurement ID from the gtag snippet Brad pasted, and the same ID shown on the internal-traffic screenshot. Web stream ID 1616284832 (typed by Brad). Internal traffic rule "internal", traffic_type "internal", match "IP address equals" 180.150.80.120, listed as rule 1 (Brad's screenshot, 20 October 2026). Property details screenshot, 20 October 2026: name Gold Coast Cabinet Maker, currency Australian Dollar. Brad reports the stream URL (apex), 14-month retention and the filter in Testing done (not seen). The reporting time zone read "(GMT+08:00) Perth Time" on that screenshot; Brad reports it changed to (GMT+10:00) Brisbane Time the same day (not seen) |
| ga4 property id | 559772207 (web stream id 1616284832), per Brad's Property details screenshot, 20 October 2026 |
| turnstile site key | 0x4AAAAAAEHD1tLftcrbDXIx |
| turnstile hostname added | Y. Shared widget "Rank and Rent forms" (Managed mode), seen on Brad's screenshots, 20 October 2026: goldcoastcabinetmaker.com.au is in the hostname list, which re-sorted alphabetically on the second screenshot (saved). 6 of 10 hostnames now used. Site key read from the same page; it matches the Cairns record. Not yet checked live: T28 |
| supabase site_id | [NEEDS INPUT: T14] |
| ingest url | [NEEDS INPUT: T14, the shared ingest-form function URL] |
| ingest secret location | [NEEDS INPUT: where it is set, never the value] |
| inbound email | [NEEDS INPUT: T11, and the Cloudflare routing rule it points at] |
| forward from email | [NEEDS INPUT: T14, after the Resend domain is verified] |
| storage regions | [NEEDS INPUT: Supabase and Cloudflare regions, named in privacy copy] |
| retention rule | [NEEDS INPUT: what is deleted, after how long, and by what] |

## Positioning

| field | value |
|---|---|
| level | [NEEDS INPUT: 1, 2 or 3] |
| voice rule | [NEEDS INPUT: including the named-individual decision] |
| renter signed | [NEEDS INPUT: Y or N] |

Claim restriction list, written out in full rather than referenced:

[NEEDS INPUT: what may not be said at this level]

## Privacy position

Standing portfolio position: **PLAYBOOK.md Appendix A, R3.** Not reopened.

Do not summarise R3 into this file. A one-line summary here is exactly what
caused a drafting session to re-derive the position from scratch and ship a
different answer. If it ever is reopened, replace this line with the date, who
decided, and why, and log it in `build/05-log.md` Decisions.

## Collection notices

T12. Both channels carry the same notice. See PLAYBOOK.md rule R4. G8 checks
the form notice against `config.js` and checks that this section's greeting
text carries the notice.

**Form notice** (`contact.reassurance` in `config.js`, rendered above every
form):

[NEEDS INPUT: exact text, naming the trade, saying the trade pays, linking the privacy policy]

**Voicemail greeting** (`sites.greeting_text` and the MP3 at
`sites.greeting_audio_url`, both columns, same words):

[NEEDS INPUT: exact text]

| field | value |
|---|---|
| mp3 recorded | [NEEDS INPUT: T13, Y or N] |
| greeting_audio_url set | [NEEDS INPUT: T14, Y or N] |
| greeting_text set | [NEEDS INPUT: T14, Y or N] |
| greeting heard on a real call | [NEEDS INPUT: T28, date] |

## Search Console

| field | value |
|---|---|
| property verified | [NEEDS INPUT: T15, Y or N] |
| method | [NEEDS INPUT: DNS TXT] |
| date | [NEEDS INPUT: T15] |
| gsc_site_url set on the site row | [NEEDS INPUT: T29, Y or N] |
