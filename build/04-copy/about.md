# About: /about

Status: APPROVED | v1.3, Brad, 15 November 2026. v1.2 30 October 2026, v1.1 27 October 2026, v1 approved 21 October 2026

Why this version exists: sentences on this page also appeared, word for word apart from the place name, on Cairns Cabinet Makers. Cairns went live first (13 October; Gold Coast 25 October), so Gold Coast's copy is the one rewritten (plan section 7a). Head, structure, headings and claims are unchanged. Only the wording of shared sentences is new.

## Head

| field | value |
|---|---|
| file | about.html |
| title | About Gold Coast Cabinet Maker \| How This Site Works |
| meta | What Gold Coast Cabinet Maker is, the area we cover, what happens when you enquire, how the service is paid for, and how to get in touch. |
| h1 | About Gold Coast Cabinet Maker |

## Blocks

1. `h2`: Who runs this

2. `p`: Gold Coast Cabinet Maker is run by Brad, trading as Gold Coast Cabinet Maker. ABN 78 538 005 810. I run this website and I cannot build a kitchen, but I will pass your enquiry to a cabinet maker who can quote it.

3. `h2`: What this site does

4. `p`: This is a referral site. When you send us the details of a kitchen, wardrobe or joinery job, we pass them to a local cabinet maker who can quote the work. The cabinet maker then contacts you directly.

5. `h2`: What we do not do

6. `p`: Making, installing and quoting for cabinets is not something we do, and we do not set prices. The [kitchens](kitchens-gold-coast.html) page shows price ranges that other publishers have put out, labelled as theirs, but your price depends on your room, and only the cabinet maker can see the room. Questions about whether something can be built, or what it will cost, are best answered by the cabinet maker your enquiry goes to.

7. `h2`: What happens after you enquire

8. `p`: Each enquiry is sent on to a local cabinet maker able to quote that kind of work. They get in touch with you to go over the job and, in most cases, to book a time to look at the room. Where we have no cabinet maker for your suburb or for that type of work, we say so, and your details are not passed to anyone.

9. `p`: Renovating a whole kitchen is often a bigger undertaking than one piece of joinery. If your job falls outside the work they take on, the cabinet maker will let you know.

10. `h2`: Your details

11. `p`: An enquiry gives us your name, phone number and suburb, and a description of the job. These go to the cabinet maker so they can get in touch about your job. Your details are not sold, and you are not put on a marketing list. For the complete picture, including the other services that handle your details and how long they are held, see the [privacy policy](privacy.html).

12. `h2`: How the service is paid for

13. `p`: The enquiry is paid for by the cabinet maker it goes to. Sending an enquiry costs you nothing, and we take no cut of the work itself. Paying for enquiries gives the cabinet maker a reason to take yours seriously.

14. `h2`: Where we cover

15. `p`: The Gold Coast, including Southport, Nerang and Burleigh Heads. If you are somewhere else in south-east Queensland, tell us where and we will try our best!

16. `h2`: Contact

17. `p`: Phone: (07) 5651 3804. If your call goes to voicemail, leave a message and it will be passed on with your enquiry. Email: hello@goldcoastcabinetmaker.com.au.

The engine then renders About's own quote section: heading from `contact.formHeadline` ("Send an enquiry"), the collection notice (`contact.reassurance`), then the form, with the job picker from `contact.jobTypes`. No `form` block here, because `validateForms` forbids one on About (Cairns T25 note, 13 October 2026).

## Changes in v1.3

Rewritten, same meaning, to remove sentences shared with Cairns Cabinet Makers: blocks 4 (second sentence), 6 (first and last), 8, 9, 11, 13. H2 headings are unchanged (same structure). Block 8 and block 13 keep R11's present-tense flow: the enquiry goes to a local cabinet maker, and the cabinet maker pays. No block, heading or claim added or removed. "We take no cut of the work" keeps the commercial disclosure named in the operator notes, and "Your details" still matches the privacy page in substance (collected, passed to the cabinet maker, not sold, no marketing list).

## Changes from plan

- v1.1, Brad, 27 October 2026, after launch, in Brad's words: "Who runs this" ends "I run this website and I cannot build a kitchen - but I will help send someone who is great at them!" (was "...and I am a sole trader."; the sole-trader statement stays on the privacy page). "Where we cover" ends "tell us where and we will try our best!" (was "...we will say straight away whether we can find someone."), matching Home. Contact drops "Calls are not answered live." and reads "If your call goes to voicemail, leave a message and it will be passed on with your enquiry."
- v1.2, Brad, 30 October 2026, from the 30 Oct SEO audit review: "Who runs this" ends "I cannot build a kitchen, but I will pass your enquiry to a cabinet maker who can quote it." (was "...but I will help send someone who is great at them!", a quality claim about a cabinet maker not yet signed).
- Titles, meta and H1 match `build/03-plan.md`.
- "What we do not do" differs from Cairns: this site shows published price ranges on the kitchens page, so the line is "we do not set prices", with the ranges named as other publishers'.

## T25 transcription notes

v1.3 transcribed 15 November 2026 by script: each changed line was swapped in config.js, matched exactly once inside this page's section. Transcribed 23 October 2026 by script (17 blocks). The quote section after the blocks is the engine's own, headed by `contact.formHeadline` ("Send an enquiry").

## Markers outstanding

None.

## Operator notes

Live as `/* TODO (Brad) */` comments in `config.js`:

- Every sentence in "Who runs this" must be true of Brad specifically. If any is not, cut it rather than soften it. Nothing about years, volumes or numbers of clients, and nothing about other businesses.
- Contact now says "If your call goes to voicemail" (v1.1). While no renter is attached every call goes to voicemail, which the privacy page still states; when a renter is signed and calls forward, check this line, the privacy page and the voicemail greeting together.
- "We do not take a cut" is the commercial disclosure in the Positioning claim restrictions. It stays true only while the model is a flat payment for enquiries (R3, and its note on per-lead pricing).
- "Your details" is kept in step with the privacy page's "Why we collect it" and "Who we share it with". If either changes, change both.
- The phone and email lines follow `business.phone`, `business.phoneDisplay` and `business.email` in `config.js`; change them there first.
- The licence statement shown in the footer is separate from this page (`licence.preRenterStatement`).

## Decisions locked on this page

- Enquiry-flow wording stays in the present tense. See PLAYBOOK.md Appendix A, R11.
- The named individual is deliberate (Positioning voice rule, approved by Brad 20 October 2026).
- No "free quote" anywhere: this site does not quote.
