# About: /about

Status: DRAFT v1 | [NEEDS INPUT: APPROVED with Brad's date at T22]

## Head

| field | value |
|---|---|
| file | about.html |
| title | About Gold Coast Cabinet Maker \| How This Site Works |
| meta | What Gold Coast Cabinet Maker is, the area we cover, what happens when you enquire, how the service is paid for, and how to get in touch. |
| h1 | About Gold Coast Cabinet Maker |

## Blocks

1. `h2`: Who runs this

2. `p`: Gold Coast Cabinet Maker is run by Brad, trading as Gold Coast Cabinet Maker. ABN 78 538 005 810. I run this website and I am a sole trader.

3. `h2`: What this site does

4. `p`: This is a referral site. You tell us about a kitchen, wardrobe or joinery job, and we pass your enquiry to a local cabinet maker who can quote it. The cabinet maker then contacts you directly.

5. `h2`: What we do not do

6. `p`: We do not make cabinets, install them or quote for them, and we do not set prices. The [kitchens](kitchens-gold-coast.html) page shows price ranges that other publishers have put out, labelled as theirs, but your price depends on your room, and only the cabinet maker can see the room. If you are asking whether a job can be done or what it will cost, that is a question for the cabinet maker who receives your enquiry.

7. `h2`: What happens after you enquire

8. `p`: Your enquiry goes to a local cabinet maker who can quote the job. They contact you directly to talk through what you want, and usually to arrange a time to see the room. If we do not have a cabinet maker for your area or your kind of job, we will tell you rather than pass your details anywhere.

9. `p`: A whole-kitchen renovation is often a larger job than a single piece of joinery. The cabinet maker will tell you if your enquiry is outside what they do.

10. `h2`: Your details

11. `p`: When you send an enquiry we collect your name, your phone number, your suburb and what you want done. We pass these to the cabinet maker so they can contact you about the job. We do not sell them, and we do not add you to a marketing list. The [privacy policy](privacy.html) has the full account, including who else handles your details and how long they are kept.

12. `h2`: How the service is paid for

13. `p`: The cabinet maker who receives your enquiry pays for it. You do not pay anything to send an enquiry, and we do not take a cut of the work. A cabinet maker who pays for enquiries has a reason to look at yours.

14. `h2`: Where we cover

15. `p`: The Gold Coast, including Southport, Nerang and Burleigh Heads. If you are somewhere else in south-east Queensland, tell us where and we will say straight away whether we can find someone.

16. `h2`: Contact

17. `p`: Phone: (07) 5651 3804. Calls are not answered live. They go to voicemail, and if you leave a message it is recorded and passed on with your enquiry. Email: hello@goldcoastcabinetmaker.com.au.

The engine then renders About's own quote section: heading from `contact.formHeadline` ("Send an enquiry"), the collection notice (`contact.reassurance`), then the form, with the job picker from `contact.jobTypes`. No `form` block here, because `validateForms` forbids one on About (Cairns T25 note, 13 October 2026).

## Changes from plan

- Titles, meta and H1 match `build/03-plan.md`.
- "What we do not do" differs from Cairns: this site shows published price ranges on the kitchens page, so the line is "we do not set prices", with the ranges named as other publishers'.

## Markers outstanding

None.

## Operator notes

Live as `/* TODO (Brad) */` comments in `config.js`:

- Every sentence in "Who runs this" must be true of Brad specifically. If any is not, cut it rather than soften it. Nothing about years, volumes or numbers of clients, and nothing about other businesses.
- "Calls are not answered live" is true while no renter is attached. When a renter is signed and calls forward, change this line and the voicemail greeting together.
- "We do not take a cut" is the commercial disclosure in the Positioning claim restrictions. It stays true only while the model is a flat payment for enquiries (R3, and its note on per-lead pricing).
- "Your details" is kept in step with the privacy page's "Why we collect it" and "Who we share it with". If either changes, change both.
- The phone and email lines follow `business.phone`, `business.phoneDisplay` and `business.email` in `config.js`; change them there first.
- The licence statement shown in the footer is separate from this page (`licence.preRenterStatement`).

## Decisions locked on this page

- Enquiry-flow wording stays in the present tense. See PLAYBOOK.md Appendix A, R11.
- The named individual is deliberate (Positioning voice rule, approved by Brad 20 October 2026).
- No "free quote" anywhere: this site does not quote.
