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
| email | hello@goldcoastcabinetmaker.com.au |
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
| supabase site_id | dac96949-0195-4911-830c-7715c22dab9c (slug gold-coast-cabinet-maker), created by migration 037 in rank-and-rent-backend, commit 60db2fb (pushed), applied 20 October 2026. `supabase migration list --linked` shows 037 applied on the remote. Before it, 035 and 036 were listed unapplied though their changes were already live (launched_on with its backfill and comment; the four leads.ai_* columns), so `db push` failed on 035 with "column launched_on already exists"; both were marked applied with `supabase migration repair --status applied 035 036` and not re-run. `select` on the remote returns the row with twilio_number +61756513804, inbound_email and forward_from_email hello@goldcoastcabinetmaker.com.au, ga4_property_id 559772207, a 32-character ingest_secret, timezone Australia/Brisbane, launched_on null |
| ingest url | https://bnfgnglzswtrvzfqkgjh.functions.supabase.co/ingest-form |
| ingest secret location | `sites.ingest_secret` on the Gold Coast row (32 hex characters, set by migration 037 in the backend repo). It is the form's hidden field, so it is also placed in `config.js` as `ingestSecret` at T16 |
| inbound email | hello@goldcoastcabinetmaker.com.au, Cloudflare Email Routing rule Active, action is the Worker rank-and-rent-email-ingest (seen on Brad's screenshot, 20 October 2026). Catch-all is Disabled (Drop). Public check through 1.1.1.1, 20 October 2026 04:20 UTC: MX route1/2/3.mx.cloudflare.net, apex TXT v=spf1 include:_spf.mx.cloudflare.net ~all, and cf2024-1._domainkey returns a DKIM key. Not yet tested by sending a message: that is the T14 and T28 check |
| resend domain | goldcoastcabinetmaker.com.au, region apne1 (Tokyo), to name in privacy copy. DNS records seen in Cloudflare on Brad's screenshot, 20 October 2026, all DNS only. Public check through 1.1.1.1 at 04:26 UTC: TXT resend._domainkey returns the DKIM key; CNAME rsend gives rsend-apne1.forge.rmta.net and send gives send.forge.rmta.net. Verified in Resend (DKIM, rsend and send all Verified; sending enabled, receiving off), seen on Brad's screenshot, 20 October 2026. DMARC _dmarc TXT v=DMARC1; p=none; added the same day: returned through 1.1.1.1 at 04:28 UTC |
| forward from email | hello@goldcoastcabinetmaker.com.au, set on the site row by migration 037 |
| storage regions | Supabase: ap-northeast-1, Tokyo (project "Rank&Rent", ref bnfgnglzswtrvzfqkgjh), read from `supabase projects list` on 20 October 2026, to be named on the privacy page. Resend sends from apne1 (Tokyo), seen in its rsend CNAME. Cloudflare: nothing stored at rest, the shared email Worker has no storage bindings (carried from the Perth Tiling Specialists and Cairns records, not re-checked here). Twilio, GitHub Pages and Google are not pinned to a region; the privacy page says they may store data outside Australia |
| retention rule | `prune-storage` runs monthly and deletes voicemail audio and email attachments older than 12 months (`RETENTION_MONTHS = 12` in `supabase/functions/prune-storage/index.ts`, read 20 October 2026). The leads and call_events rows are kept, because they are the invoicing evidence. GA4 event data is kept 14 months |

## Positioning

| field | value |
|---|---|
| level | 2 |
| voice rule | "We" for the business throughout. First person singular for Brad's own section on About. Naming the individual is allowed, as on Cairns Cabinet Makers, Perth Tiling Specialists, Canberra Tile Layers and Perth Limestone Group, and matches "Brad, first name only" in Identity |
| renter signed | N |

Claim restriction list, written out in full rather than referenced:

- No claim that we do the work. The site takes enquiries and passes them on.
- No invented reviews, star ratings, photos of work, years in business or job counts. Generated illustrative images are allowed as long as nothing presents them as our work or a renter's work: no caption, no "our projects" wording, alt text that describes the illustration (carried from Cairns, Brad, 13 October 2026).
- No licence number and no "licensed" wording before a renter is signed (PLAYBOOK R14). Instead, every page carries the QBCC value statement: "Gold Coast Cabinet Maker cannot perform building work valued in excess of $3,300. For work above that value, discuss it with the cabinet maker who quotes your job." This is the Cairns answer to the same QBCC question, with the brand changed. The $3,300 figure is carried from Cairns and gets its primary source at T20 (R2).
- No response-time promise.
- No pricing presented as ours. A Gold Coast cost source is still open (R10; job-value item in `05-log.md`), so no cost figures until one is in `03-plan.md`. The Sydney benchmark is not used.
- No "free quote". This site does not quote, and no draft says the cabinet maker's quote is free.
- No showroom, workshop or street address, and no "visit us". The T05 teardown found buyers expect a visit; that is the renter's to offer, not this site's.
- Commercial disclosure on About: the cabinet maker pays, we do not take a cut.
- `schema.type` stays `Organization`. No premises, no hours, no reviews.

Drafted at T16, 20 October 2026, from the Cairns positions Brad approved on 13 October 2026. Approved by Brad, 20 October 2026.

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

No spam and no obligation. Your details go to a local cabinet maker so they can quote your job, and the cabinet maker pays for the enquiry. We never add you to a marketing list. [How we handle your information](privacy.html).

**Voicemail greeting** (`sites.greeting_text` and the MP3 at
`sites.greeting_audio_url`, both columns, same words):

Hi, thanks for calling Gold Coast Cabinet Maker. Leave your name, location and job details after the tone. We will pass your enquiry on to a local cabinet maker who can quote the job, and the cabinet maker pays for the enquiry.

Drafted at T12, 20 October 2026, from the Cairns Cabinet Makers wording Brad approved on 13 October 2026 (including "location", not "suburb"), with only the brand changed, so both sites say the same thing (R11). Both name the trade, say the enquiry goes to that trade in the present tense, and say the cabinet maker pays for the enquiry (R3, R4). The form text carries the privacy link, which cannot be spoken. Neither says "licensed": that waits on the QBCC item in `05-log.md`. Both texts approved by Brad, 20 October 2026, as drafted. The MP3 (T13) must say the greeting words exactly.

| field | value |
|---|---|
| mp3 recorded | Y, uploaded by Brad to the Greetings bucket as GoldCoastCabinetMaker.mp3 (final file name, T13 note); https://bnfgnglzswtrvzfqkgjh.supabase.co/storage/v1/object/public/Greetings/GoldCoastCabinetMaker.mp3 returns HTTP 200, audio/mpeg, 185,294 bytes, checked 20 October 2026 07:39 UTC. The words in it are not yet checked by ear: T28 does that on a real call |
| greeting_audio_url set | Y. https://bnfgnglzswtrvzfqkgjh.supabase.co/storage/v1/object/public/Greetings/GoldCoastCabinetMaker.mp3, set by migration 037; read back from the remote 20 October 2026 |
| greeting_text set | Y, on the site row, the approved T12 words exactly (migration 037; read back from the remote 20 October 2026) |
| greeting heard on a real call | N, owed at T28 |

## Search Console

| field | value |
|---|---|
| property verified | Y. Brad's Search Console screenshot, 20 October 2026, shows the goldcoastcabinetmaker.com.au Domain property (globe icon) open on Overview, "Processing data"; Search Console only opens a property once it is verified. Settings > Users and permissions (Brad's second screenshot, same day) shows Brad Dack, Owner, Verified, and the reporting service account leads-reporting@local-abbey-420810.iam.gserviceaccount.com as Restricted, as the backend README requires for the digest. GA4 Viewer access for that account on property 559772207 not seen |
| method | DNS TXT (Domain property). `nslookup -type=TXT goldcoastcabinetmaker.com.au` through 1.1.1.1 and 8.8.8.8 on 20 October 2026 07:49 UTC returns google-site-verification=AlW0Yt49Qk-VSH06RwGYY7fBK4bOwcCq-49qx0b6gP4 beside the SPF record |
| date | 20 October 2026 |
| gsc_site_url set on the site row | N, owed at T29 |
