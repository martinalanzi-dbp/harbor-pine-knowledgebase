---
title: "Project Overview (Pre-Kickoff) — Harbor & Pine"
layer: product
owner: "Nacho Dominguez"
status: draft
last_updated: 2026-10-20
relates_to: []
sources:
  - layers/layer-0-business/raw-inputs/pre-kickoff-harbor-and-pine.md
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/01-whiteboard-day-of-tour.png
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-0-business/raw-inputs/05-competitor-overview-getyourguide.pdf
  - layers/layer-0-business/raw-inputs/H&P Knowledge base.md
---

# Project Overview (Pre-Kickoff) — Harbor & Pine

Layer 1 · Product · intermediate · `status: draft`. A catch-up read built from the six source files in `layers/layer-0-business/raw-inputs/`, added by Marti Lanzi in commit 1e71aaf. The compiled digest was used only for the cross-check in §12. Despite the title, much of the material post-dates the May 8 notes: it includes the May 12 kickoff and the May 13–14 interviews. It adds no analysis and no recommendations beyond what those sources say. `relates_to` is empty because Layer 0 `latest/` holds only unfilled templates. Nothing here is consensus.

Citations use `[file:line]` for Markdown sources, `[file:pN]` for PDF pages and `[01-whiteboard-day-of-tour.png:img]` for the whiteboard image. File names are literal. The folder is `layers/layer-0-business/raw-inputs/`; the transcript and guide notes are in `Meetings/`. The May 8 notes are cited as `pre-kickoff-harbor-and-pine.md`, the kickoff as `02-kickoff-transcript.md`, and the guide notes as `04-guide-interview-notes.md`.

---

## 0. What you must know

Each point shows its tag and label (legend in §1). A label says whether the point was stated first-hand and not disputed. It never means the client agreed to build it.

1. **Signed scope is design only.** Phase 1 (Strategy and Solution Design) is 550 hours across a Product Manager, Product Designer and Tech Lead for discovery, ideation, scope and high-fidelity design, with technical feasibility input. Development is a separate later phase. [pre-kickoff-harbor-and-pine.md:12] [pre-kickoff-harbor-and-pine.md:50] [00-harbor-and-pine-prd-v0.9.pdf:p1] [02-kickoff-transcript.md:169] · team-inferred · confirmed by the team, but the SOW itself is not in the folder.
2. **The eight-week date is live and unresolved.** The Executive Lead wants bookings, payments, vouchers, day-of support, something for guides and a first AI experience "running in Lisbon and Barcelona by then". [02-kickoff-transcript.md:172] The Tech Lead said "I cannot confirm a live launch in that window." [02-kickoff-transcript.md:175] Product said "We have not agreed the implementation scope or launch date today." [02-kickoff-transcript.md:181] · client-stated (Exec Lead) · unconfirmed.
3. **"confirm straight away" is a relayed client line with unknown scope.** The May 8 notes pass on, under Notes from Sales, "We should be able to confirm straight away." [pre-kickoff-harbor-and-pine.md:54] and add "I do not know whether that means every activity." Operations said "We can confirm immediately when availability is connected." [02-kickoff-transcript.md:52] and, on whether payment alone reserves a place, "Not always." [02-kickoff-transcript.md:58] · Sales-relayed (client quote) vs client-stated (Ops) · unconfirmed; narrowed by Operations.
4. **First launch is traveler-facing; hotels should not delay it.** The Executive Lead: "The first launch is still traveler-facing." [02-kickoff-transcript.md:76] Product noted the pilot brief has English and Spanish only [02-kickoff-transcript.md:160] and the Executive Lead said "Start with the pilot brief." [02-kickoff-transcript.md:166] Sales floated hotels as a possible first audience [02-kickoff-transcript.md:73] and wanted to "revisit" the hotel material later [02-kickoff-transcript.md:85] · client-stated (Exec Lead), Sales-relayed · confirmed as the Executive Lead's statement; the PRD says what belongs in the pilot "remains open" [00-harbor-and-pine-prd-v0.9.pdf:p3].
5. **The AI may recommend, but may not change a paid booking on its own.** [02-kickoff-transcript.md:112] Who approves a change is open: "That depends on the change." [02-kickoff-transcript.md:118] The first AI experience is not chosen: "Hard to pick before seeing it." [02-kickoff-transcript.md:106] · client-stated (Exec Lead, Ops) · confirmed for the limit, unconfirmed for the approver and the first AI feature.
6. **Platform shape.** No required download, critical information that works on a weak connection, no account to book, and the itinerary on the phone after booking on a laptop. [02-kickoff-transcript.md:133] [02-kickoff-transcript.md:148] · client-stated (Exec Lead) · confirmed as stated wishes. What counts as critical information, and how recovery works, are open.
7. **The client side stresses different problems.** The Executive Lead: "I still need more people to book. We need both sides to work." [02-kickoff-transcript.md:91] Operations: "Discovery is not where most of my team spends time." [02-kickoff-transcript.md:88] · client-stated · unconfirmed; no source ranks them. The PRD says priority "has not been validated". [00-harbor-and-pine-prd-v0.9.pdf:p1]
8. **Decision rights are unassigned.** "The Executive Lead appears to be the sponsor." [pre-kickoff-harbor-and-pine.md:41] On who resolves a conflict between customer expectation and operator policy, Operations said "We usually escalate, but it is not always the same person." [02-kickoff-transcript.md:199] · team-inferred, client-stated (Ops) · unconfirmed.
9. **What is missing.** There is no file 03 (files run 00, 01, 02, 04, 05). The transcript is an excerpt that stops at 25:00. The SOW, a systems inventory and any KPI baseline are not in the folder. [02-kickoff-transcript.md:1] [02-kickoff-transcript.md:100] [00-harbor-and-pine-prd-v0.9.pdf:p1]

---

## 1. Sources and how to read this

**Date scope.** Everything through May 14, 2026 is covered. §9 separates what the May 8 notes assumed from what later material showed.

| File | Date | What it is | Limits |
|---|---|---|---|
| `pre-kickoff-harbor-and-pine.md` | May 8, 2026 | Product Director's notes after a short handoff with Sales. [pre-kickoff-harbor-and-pine.md:3] | "Client discovery has not started." Every client position in it is secondhand. |
| `00-harbor-and-pine-prd-v0.9.pdf` | May 11, 2026 | Four-page PRD, footer "Draft for alignment". [00-harbor-and-pine-prd-v0.9.pdf:p1] | Team draft. Author not stated (PDF metadata author field reads anonymous). Dated before the kickoff and interviews; its basis is not stated. Not client-confirmed. |
| `01-whiteboard-day-of-tour.png` | Not dated | Photo of a whiteboard: a five-step flow plus sticky notes. | Author and date unknown. Arrow meanings are undocumented. |
| `Meetings/02-kickoff-transcript.md` | May 12, 2026 | Automated transcript excerpt, speakers by role. | "The recording ended before the remaining agenda items were discussed." [02-kickoff-transcript.md:1] Roles only; no names or employers. |
| `Meetings/04-guide-interview-notes.md` | May 13–14, 2026 | Interviewer notes from two remote guide interviews. | "Neither interview included observation of a full tour." [04-guide-interview-notes.md:1] Two guides; not verbatim. |
| `05-competitor-overview-getyourguide.pdf` | Not dated | One-page reference sheet. [05-competitor-overview-getyourguide.pdf:p1] | Author not stated (PDF metadata author field reads Harbor & Pine). It is a prompt for research, not research. |

**Tags.**
- **client-stated** — said first-hand by the Executive Lead or Operations in the kickoff transcript. The transcript labels roles only. I read both as client side because Operations says "our operators". [02-kickoff-transcript.md:40] That reading is team-inferred.
- **Sales-relayed** — Sales' words at kickoff, or the May 8 notes passing on what Sales or the client said.
- **team-inferred** — from the team side, including the team's own first-hand statements: the Product Director's observations, the Product, Design and Tech Lead speakers, and the PRD. The whiteboard and competitor sheet are grouped here only because their authorship is not stated; the competitor PDF's metadata names Harbor & Pine as author.
- **guide-reported** — what a guide said about their own practice, as noted by an interviewer.

**Labels.**
- **confirmed** — stated first-hand by the party the fact concerns, with no other source disagreeing. It means *was said*, not *was agreed as scope*.
- **unconfirmed** — relayed, drafted, only mentioned, or marked open by its own source.
- **contradicted** — another cited source says otherwise.

**File 03 is missing.** Files are numbered 00, 01, 02, 04 and 05. Nothing in the folder says what 03 would be. At the end of the kickoff Product said "I will send a recap for review." [02-kickoff-transcript.md:205] I cannot tell whether that recap is 03.

**What I could not read or check.**
- The PRD and competitor PDFs were read one page at a time as extracted text. Neither contains embedded images (checked with `pdfimages`), so no page content was missed. I did not view rendered page layouts.
- The whiteboard was viewed as an image. All handwriting and sticky text was legible, but its author, date and intended arrow meanings are not stated anywhere.
- No `.docx` originals are in the repo. The compiled digest lists `.docx` for three of the sources (see §12). I could not compare against them.
- A conversation between Sales and Operations on May 11 ("The one we talked about yesterday" [02-kickoff-transcript.md:13]) is not in the folder.
- No audio, and no SOW, contract, brand assets, process examples or current-system documentation.
- I did not open the GetYourGuide links. No competitor research was done.
- The raw-inputs `README.md` is a generic template checklist, not a project source.

---

## 2. Project and SOW

| Claim | Cite | Tag | Status |
|---|---|---|---|
| Harbor & Pine is an existing tours business; the project is a new platform for it. | [pre-kickoff-harbor-and-pine.md:10] | Sales-relayed | Unconfirmed |
| Phase 1 — Strategy and Solution Design: 550 hours for discovery, ideation, scope definition and high-fidelity design, with technical feasibility input. Development is a separate phase. | [pre-kickoff-harbor-and-pine.md:50] [00-harbor-and-pine-prd-v0.9.pdf:p1] | team-inferred | Confirmed (team statement; SOW not in folder) |
| Product at kickoff: "The signed initial phase has 550 hours for discovery, ideation, scope and high-fidelity design, with Tech Lead input." | [02-kickoff-transcript.md:169] | team-inferred | Confirmed (team statement) |
| Team is a Product Manager, Product Designer and Tech Lead. | [pre-kickoff-harbor-and-pine.md:12] [00-harbor-and-pine-prd-v0.9.pdf:p1] | team-inferred | Confirmed (team statement; SOW not in folder) |
| The hours breakdown is "Not allocated yet." | [pre-kickoff-harbor-and-pine.md:12] | team-inferred | Unconfirmed |
| "Implementation and production QA are outside this phase." | [pre-kickoff-harbor-and-pine.md:12] | team-inferred | Unconfirmed |
| Expected deliverables: "Prioritized scope, main journeys, high-fidelity designs and a handoff for development." | [pre-kickoff-harbor-and-pine.md:15] | team-inferred | Unconfirmed |
| Prototype coverage: "Prototype coverage and technical detail to align at kickoff." The kickoff excerpt never mentions a prototype. | [pre-kickoff-harbor-and-pine.md:15] [02-kickoff-transcript.md:169] | team-inferred | Unconfirmed |
| Timeline: "May start expected." The kickoff took place May 12. | [pre-kickoff-harbor-and-pine.md:13] [02-kickoff-transcript.md:1] | Sales-relayed | Unconfirmed (a kickoff was held May 12; no start date is stated) |
| Initial pilot markets are Lisbon and Barcelona. The Executive Lead named both when describing the eight-week outcome. | [00-harbor-and-pine-prd-v0.9.pdf:p1] [02-kickoff-transcript.md:172] | team-inferred; client-stated (Exec Lead) | Confirmed that the Executive Lead named both; not agreed as scope |
| Tech Lead input is needed on integrations and AI feasibility, plus access to operational processes and representative users. | [pre-kickoff-harbor-and-pine.md:53] | team-inferred | Unconfirmed |
| Tech Lead at kickoff: "We have not assessed the systems or estimated implementation." | [02-kickoff-transcript.md:175] | team-inferred | Confirmed (team statement) |
| PRD: "No current-system audit has been completed." | [00-harbor-and-pine-prd-v0.9.pdf:p4] | team-inferred | Confirmed (team statement) |

**The eight-week pilot, in the sources' own words.**

| Where | Wording | Cite |
|---|---|---|
| May 8 notes (Sales-relayed) | "The client mentioned an eight-week pilot; I have not confirmed whether they mean a prototype, a test or a live launch." | [pre-kickoff-harbor-and-pine.md:13] |
| PRD (team-inferred) | "An eight-week pilot has been mentioned by the client." / "Its relationship to design completion, implementation and a live launch is not agreed." | [00-harbor-and-pine-prd-v0.9.pdf:p1] |
| Product to the client | "How are you using the eight-week date?" | [02-kickoff-transcript.md:169] |
| Executive Lead | "I would like to see bookings, payments, vouchers, day-of support, something for guides and a first AI experience running in Lisbon and Barcelona by then." | [02-kickoff-transcript.md:172] |
| Executive Lead | "Bring back a realistic plan, but keep that date in mind." | [02-kickoff-transcript.md:178] |
| Product | "We will assess it." | [02-kickoff-transcript.md:181] |

---

## 3. Vision

| Claim | Cite | Tag | Status |
|---|---|---|---|
| "The goal is bigger than a nicer website." The aim is for a trip planner to feel helped "Discovery, booking, the actual day, everything." | [02-kickoff-transcript.md:28] | client-stated (Exec Lead) | Confirmed |
| What excited the client most: AI accompanying the traveler from planning through the day of the tour. | [pre-kickoff-harbor-and-pine.md:20] | Sales-relayed | Unconfirmed |
| The Executive Lead's AI idea: it "could listen when someone calls and show the operator relevant tours or questions to ask", learn a new person's interests, then "keep helping during the trip". The PRD does not mention call listening. | [02-kickoff-transcript.md:94] [00-harbor-and-pine-prd-v0.9.pdf:p1] | client-stated (Exec Lead) | Unconfirmed (floated, not scoped) |
| Why the project exists: Sales described an established business wanting a more scalable customer experience. "I do not have a breakdown of the current problems." | [pre-kickoff-harbor-and-pine.md:19] | Sales-relayed | Unconfirmed |
| Operations' examples of today's problems: three tours moved for weather with one group still going to the original meeting point; a guide running late. | [02-kickoff-transcript.md:10] [02-kickoff-transcript.md:16] | client-stated (Ops) | Confirmed |
| Business goals: more completed bookings, fewer avoidable support questions and less manual work, and preparing for future cities and hotel partners. | [00-harbor-and-pine-prd-v0.9.pdf:p1] | team-inferred | Unconfirmed |
| "A branded hotel experience is part of the future vision." | [00-harbor-and-pine-prd-v0.9.pdf:p3] | team-inferred | Unconfirmed |
| Client style: "Enthusiastic and direct." The Product Director has not worked with them before. | [pre-kickoff-harbor-and-pine.md:22] | team-inferred | Unconfirmed |

**Start from scratch — the exact wording.**

| Where | Wording | Cite |
|---|---|---|
| May 8 notes | "The client wants to start from scratch and does not want to show the current website, to avoid influencing the team." | [pre-kickoff-harbor-and-pine.md:10] |
| Executive Lead | "We want to build the new platform from scratch, and I do not want the old screens to bias your thinking. The business already exists, of course." | [02-kickoff-transcript.md:34] |
| Executive Lead | "do not let the current website limit the new direction. We are happy to start fresh." | [02-kickoff-transcript.md:208] |
| Operations | "A new product will still have to work with our operators and their current agreements. I cannot promise that all their systems change with ours." | [02-kickoff-transcript.md:40] |
| PRD | "This is not a decision to replace every operational tool, operator agreement or integration." | [00-harbor-and-pine-prd-v0.9.pdf:p1] |

In every source except Operations' line, the phrase is tied to the current website or old screens. Whether it also covers operators, agreements and tools is not said by the client. See conflict C4 in §10.

---

## 4. Expectations and MVP

No source contains an agreed feature list. The PRD says its candidate scope "is not an approved implementation backlog or a commitment that every item fits within the initial phase." [00-harbor-and-pine-prd-v0.9.pdf:p2] The May 8 notes say "No agreed feature list yet." [pre-kickoff-harbor-and-pine.md:27]

| Topic | Claim | Cite | Tag | Status |
|---|---|---|---|---|
| Outcomes | A simpler booking experience and less work for the team. "Relative priority has not been discussed." | [pre-kickoff-harbor-and-pine.md:26] | Sales-relayed | Unconfirmed |
| MVP mentions | "Sales mentioned booking, an itinerary and an AI assistant." | [pre-kickoff-harbor-and-pine.md:27] | Sales-relayed | Unconfirmed |
| Booking feel | "Booking should feel immediate. Choose an activity, pay, get confirmation. We lose people when they have to wait." | [02-kickoff-transcript.md:43] | client-stated (Exec Lead) | Confirmed as a stated wish; not agreed |
| Abandonment data | Asked how many people abandon because of waiting: "Not as a clean number. It is what I hear from the team." | [02-kickoff-transcript.md:49] | client-stated (Exec Lead) | Confirmed (no clean figure) |
| Confirmation | Operations can confirm immediately when availability is connected; "A lot of operators still reply by email or WhatsApp." Operations has to check how much of the catalog that is. | [02-kickoff-transcript.md:52] | client-stated (Ops) | Confirmed; share unknown |
| Payment and reservation | "We may authorize payment while we wait. The operator still needs to accept the request." Private tours can depend on a guide and a language. | [02-kickoff-transcript.md:58] [00-harbor-and-pine-prd-v0.9.pdf:p2] | client-stated (Ops); team-inferred | Confirmed |
| Pending status | The Executive Lead: "Internally, perhaps. I do not want it to feel uncertain after someone has paid." Later: "Show me options when we get there. I am not choosing wording today." | [02-kickoff-transcript.md:64] [02-kickoff-transcript.md:70] | client-stated (Exec Lead) | Unconfirmed (deferred) |
| Cancellation policy | The Executive Lead asked "Can we just use one cancellation policy for the pilot?" Operations: "We cannot assume one policy without reviewing those." Executive Lead: "I was asking whether it would simplify things." | [02-kickoff-transcript.md:187] [02-kickoff-transcript.md:190] [02-kickoff-transcript.md:193] | client-stated (Exec Lead, Ops) | Unconfirmed (open; Operations asks for a review of agreements) |
| Rescheduling, no-shows, refunds | Operations asked to include them: "Otherwise a nice front end could mean more messages for us." | [02-kickoff-transcript.md:184] | client-stated (Ops) | Confirmed as a stated request |
| Platform | "No required download. Critical information should still work with a weak connection. We can define exactly what that means." | [02-kickoff-transcript.md:133] | client-stated (Exec Lead) | Confirmed; definition open |
| Offline definition | Tech Lead: "does offline mean after they have opened the link once? Those are different requirements." The PRD: "The exact offline dataset and refresh behavior are not defined." | [02-kickoff-transcript.md:130] [00-harbor-and-pine-prd-v0.9.pdf:p3] | team-inferred | Unconfirmed |
| Live map | Sales asked if a live map should be in the first version, then said "I am not saying a live map is a requirement." Operations: "A current photo and a clear address might help more in some locations." | [02-kickoff-transcript.md:136] [02-kickoff-transcript.md:139] [02-kickoff-transcript.md:142] | Sales-relayed; client-stated (Ops) | Unconfirmed |
| Account | "No. Keep checkout short. But if I book on my laptop, I want the itinerary on my phone." | [02-kickoff-transcript.md:148] | client-stated (Exec Lead) | Confirmed |
| Recovery and sharing | Design: "We need a way to recover it securely." The PRD: "A secure recovery mechanism and sharing permissions have not been selected." | [02-kickoff-transcript.md:151] [00-harbor-and-pine-prd-v0.9.pdf:p2] | team-inferred | Unconfirmed |
| Group booking | One person booking for six: Operations said "Today the voucher represents the reservation." | [02-kickoff-transcript.md:154] | client-stated (Ops) | Confirmed |
| AI limit | Operations: "Recommend another one, yes. Move a paid booking, no." The Executive Lead: "I meant with approval. Let us not have it change a paid booking on its own." | [02-kickoff-transcript.md:109] [02-kickoff-transcript.md:112] | client-stated (Ops, Exec Lead) | Confirmed |
| AI first version | "Hard to pick before seeing it. Recommendations are an obvious starting point." | [02-kickoff-transcript.md:106] | client-stated (Exec Lead) | Unconfirmed |
| Languages | Hotels asked for English, Spanish, Portuguese, French and Italian; "I have not promised delivery dates." The pilot brief has English and Spanish only. | [02-kickoff-transcript.md:157] [02-kickoff-transcript.md:163] [02-kickoff-transcript.md:160] | Sales-relayed | Confirmed (Sales); not a pilot requirement |
| Accessibility | "Main flows should meet WCAG 2.2 AA." It appears only in the PRD; the kickoff excerpt never raises accessibility. | [00-harbor-and-pine-prd-v0.9.pdf:p3] | team-inferred | Unconfirmed |
| Success metrics | "More bookings and fewer support requests were mentioned. No baseline or targets provided." Possible measures: booking completion, support contacts per booking, manual handling time and guide adoption. | [pre-kickoff-harbor-and-pine.md:29] [00-harbor-and-pine-prd-v0.9.pdf:p1] | Sales-relayed; team-inferred | Unconfirmed |
| Design references | "GetYourGuide came up as a reference for ease of booking. No visual direction received." | [pre-kickoff-harbor-and-pine.md:30] | Sales-relayed | Unconfirmed |
| Pilot readiness | "These are proposed readiness conditions, not evidence that the pilot has been scoped or approved." | [00-harbor-and-pine-prd-v0.9.pdf:p4] | team-inferred | Unconfirmed |

---

## 5. Stakeholders and decision rights

**Who is who.** The May 8 notes list the Executive Lead as the client point of contact, with "Names and meeting availability to be shared by Sales." [pre-kickoff-harbor-and-pine.md:8] The Sales lead is "Tourism account team. Individual owner to confirm." [pre-kickoff-harbor-and-pine.md:9] No source gives a name or employer for any speaker. The PRD also lists Operator (who "controls availability, prices, policies and activity delivery") and Hotel partner as users. [00-harbor-and-pine-prd-v0.9.pdf:p2]

| Decision | What the sources say | Cite | Status |
|---|---|---|---|
| Overall sponsor | "The Executive Lead appears to be the sponsor." | [pre-kickoff-harbor-and-pine.md:41] | Unconfirmed |
| Launch audience and languages | The Executive Lead set the direction: traveler-facing first, "Start with the pilot brief." Sales said "Let us revisit it once we know what the main experience looks like." | [02-kickoff-transcript.md:76] [02-kickoff-transcript.md:166] [02-kickoff-transcript.md:85] | Confirmed (Exec Lead statement); Sales position differs |
| Who approves a paid-booking change | Product asked "Whose approval: the traveler, Operations or the operator?" Operations: "I cannot give you one rule for everything today." | [02-kickoff-transcript.md:115] [02-kickoff-transcript.md:118] | Unconfirmed |
| Customer expectation vs operator policy | "We usually escalate, but it is not always the same person. I can bring examples." | [02-kickoff-transcript.md:199] | Unconfirmed |
| Exceptions and approvals generally | "Approval responsibilities for product, operations and booking exceptions have not been agreed." "Exception ownership and escalation need agreement." | [pre-kickoff-harbor-and-pine.md:41] [00-harbor-and-pine-prd-v0.9.pdf:p3] | Unconfirmed |
| Accessibility and privacy approval | "Review and approval responsibilities are not assigned." | [00-harbor-and-pine-prd-v0.9.pdf:p3] | Unconfirmed |
| Pending-status wording | The Executive Lead deferred it: "I am not choosing wording today." | [02-kickoff-transcript.md:70] | Unconfirmed |
| Hotel material for partners | Sales: "I would still like something to show those partners soon. Even if it is just a concept." Product asked whether it is for this phase or separate; Sales deferred it. | [02-kickoff-transcript.md:79] [02-kickoff-transcript.md:82] [02-kickoff-transcript.md:85] | Unconfirmed |

**Actions offered or committed at kickoff.** "I will send a recap" [02-kickoff-transcript.md:205] and "I will follow up" [02-kickoff-transcript.md:211] are commitments; the others are offers without a date.

| Owner | Action | Cite |
|---|---|---|
| Product | "I will send a recap for review." | [02-kickoff-transcript.md:205] |
| Operations | Share process examples and examples of what customers and the team receive. | [02-kickoff-transcript.md:37] [02-kickoff-transcript.md:40] |
| Operations | "I need to check how much of the catalog that represents." | [02-kickoff-transcript.md:52] |
| Operations | "I can bring examples." (escalation cases) | [02-kickoff-transcript.md:199] |
| Operations | "I will follow up after checking Lisbon and Barcelona." | [02-kickoff-transcript.md:211] |
| Sales | Names and meeting availability. (The May 8 note expected Sales to introduce Operations the following week; Operations was at the May 12 kickoff.) | [pre-kickoff-harbor-and-pine.md:8] [pre-kickoff-harbor-and-pine.md:54] |
| Not assigned | List of systems holding customer records and call recordings: Sales said "I do not have that list." | [02-kickoff-transcript.md:97] [02-kickoff-transcript.md:100] |

---

## 6. Risks

| Risk | Raised by | Cite | Tag | Status |
|---|---|---|---|---|
| "Current systems, inventory access and client availability are unclear." | May 8 notes | [pre-kickoff-harbor-and-pine.md:46] | team-inferred | Unconfirmed |
| "The client wants to move quickly and talks about AI across the entire journey." Hotels also came up as a possible channel. | May 8 notes | [pre-kickoff-harbor-and-pine.md:45] | Sales-relayed | Unconfirmed |
| "We do not yet know what the assistant could reliably do." | May 8 notes | [pre-kickoff-harbor-and-pine.md:46] | team-inferred | Unconfirmed |
| PRD risk list: availability that appears confirmed before acceptance; automation that adds manual work; low guide adoption; incorrect assistant suggestions; different operator policies; unreliable connectivity; "pilot scope that exceeds the available phase". | PRD | [00-harbor-and-pine-prd-v0.9.pdf:p4] | team-inferred | Unconfirmed |
| A front end that adds work for Operations: "Otherwise a nice front end could mean more messages for us." | Operations | [02-kickoff-transcript.md:184] | client-stated (Ops) | Confirmed |
| Operators' systems will not all change: "I cannot promise that all their systems change with ours." | Operations | [02-kickoff-transcript.md:40] | client-stated (Ops) | Confirmed |
| Updated messages that people never see. | Operations | [02-kickoff-transcript.md:16] | client-stated (Ops) | Confirmed |
| Conflicting group lists: a list of eight people, then another of ten. | Guide A | [04-guide-interview-notes.md:9] | guide-reported | Confirmed for that guide; frequency unknown |
| Older phone and battery limits. | Guide B | [04-guide-interview-notes.md:23] | guide-reported | Confirmed for that guide |
| Guide adoption: "Maybe, but I would keep it until I trust the new thing." | Guide B | [04-guide-interview-notes.md:27] | guide-reported | Confirmed for that guide |
| Live-launch feasibility: the Tech Lead cannot confirm it. | Tech Lead | [02-kickoff-transcript.md:175] | team-inferred | Confirmed (team statement) |

---

## 7. Users and day-of-tour reality

**Users as the PRD frames them.** Traveler, Guide, Operations, Operator and Hotel partner. [00-harbor-and-pine-prd-v0.9.pdf:p2] The PRD says "The relative priority of these problems has not been validated." [00-harbor-and-pine-prd-v0.9.pdf:p1] (team-inferred · unconfirmed)

**Operations.** "Discovery is not where most of my team spends time. It is the day of the activity: old meeting points, late guides, weather, people who cannot open a message." [02-kickoff-transcript.md:88] (client-stated, Ops · confirmed)

**Guides — what they reported.** Two interviews, not observations, both guide-reported. Each row is confirmed for that guide only.

| Topic | Guide A (Lisbon, May 13) | Guide B (Barcelona, May 14) |
|---|---|---|
| Context | Works for several operators; different operators send information through different tools. [04-guide-interview-notes.md:5] | "Uses an older Android phone." "No device benchmark or network test was conducted." [04-guide-interview-notes.md:23] |
| Before the tour | "I check the list the night before, then again before I leave. Sometimes the last list arrives while I am already on the way." [04-guide-interview-notes.md:7] | "People send me screenshots and ask if they are in the right place." One recent group waited on the other side of the square. [04-guide-interview-notes.md:25] |
| Lists and counts | A list of eight people, then another of ten; the guide called Operations. "No count of how often this happens was collected." [04-guide-interview-notes.md:9] | "If a couple booked together and one arrives first, I remember the other one is coming." Wants a quick way to record who did not arrive. "The interviewer did not ask every operator about its check-in rules." [04-guide-interview-notes.md:29] |
| New tool | "I do not mind a new tool if I can open the list quickly. I do not want to fill in a form while people are waiting." [04-guide-interview-notes.md:11] | Asked whether a new tool would replace messaging: "Maybe, but I would keep it until I trust the new thing." [04-guide-interview-notes.md:27] |
| Connection | A downloaded list is useful when reception drops; how updates should reach it was not specified. [04-guide-interview-notes.md:11] | Wants the meeting point and group details available when reception drops; "a saved address or photo is still useful." [04-guide-interview-notes.md:35] |
| Changes and suggestions | Changed a route because a street was blocked; wants to know about recommendations before travelers get instructions. [04-guide-interview-notes.md:13] | Likes suggestions for nearby alternatives but does not want the tour or route changed without notice. "Did not discuss who should authorize a new paid booking." [04-guide-interview-notes.md:33] |
| Incidents | Called Operations about a list discrepancy (see Lists and counts); no other incident topic is recorded. [04-guide-interview-notes.md:9] | Calls or messages Operations; wants a quick way to report a delay. "Emergency handling was not explored in detail." [04-guide-interview-notes.md:31] |
| Traveler data | Names, group size, language and relevant delivery needs are useful. "Did not define a complete access policy." [04-guide-interview-notes.md:15] | Not recorded as a topic. |
| Photos | Tourists sometimes recognize a landmark in a photo more easily than an address. [04-guide-interview-notes.md:17] | "Suggested a better meeting-point photo might be more valuable than another screen." [04-guide-interview-notes.md:37] |
| Not covered | "Refund decisions, formal approval responsibilities and the steps for partial group arrival." [04-guide-interview-notes.md:19] | "Account recovery, payment flow, hotel requirements and the frequency of the issues described." [04-guide-interview-notes.md:39] |

**Whiteboard (author and date unknown · team-inferred · unconfirmed).** What is on the board, as read from the image:
- A blue flow in five boxes: BOOKING → MEETING POINT → CHECK-IN → TOUR → REVIEW. [01-whiteboard-day-of-tour.png:img]
- Blue notes under the steps: "offline?" and "guide late" under MEETING POINT; "scan QR" and "group split" under CHECK-IN; "weather?" and "change route" under TOUR. [01-whiteboard-day-of-tour.png:img]
- Sticky notes: NO APP? and WHATSAPP (yellow); OFFLINE MAP, AI SUGGESTS and REFUND? (pink); WHO APPROVES? (light green). [01-whiteboard-day-of-tour.png:img]
- A green circled question mark with green arrows (one to NO APP?, one to AUTO, one long arrow ending in a dashed line), a green arrow from NO APP? toward MEETING POINT, a green arrow from TOUR to WHATSAPP, and a box labeled AUTO that is crossed out in red with a red arrow to a second circled question mark. [01-whiteboard-day-of-tour.png:img]
- The meaning of the arrows, the crossed-out AUTO box and the question marks is not written anywhere. QR scanning appears on the whiteboard and nowhere else in the sources.

---

## 8. Competitor

| Claim | Cite | Tag | Status |
|---|---|---|---|
| The sheet is "A starting point for reviewing how a large marketplace presents, sells, and supports tours and activities." Its purpose is "Reference for further research". | [05-competitor-overview-getyourguide.pdf:p1] | team-inferred (author unconfirmed) | Unconfirmed |
| "It should not be treated as a complete model for Harbor & Pine, which also needs to coordinate guides, operators, and day-of exceptions." | [05-competitor-overview-getyourguide.pdf:p1] | team-inferred (author unconfirmed) | Unconfirmed |
| Areas to review: discovery, activity details, confirmation and vouchers, traveler experience vs supplier operations, and how policies are communicated per activity. | [05-competitor-overview-getyourguide.pdf:p1] | team-inferred (author unconfirmed) | Unconfirmed |
| Research questions include "How does the product communicate booking certainty?" and "How are exceptions handled when the voucher is not the final ticket?" | [05-competitor-overview-getyourguide.pdf:p1] | team-inferred (author unconfirmed) | Unconfirmed |
| No competitor study came from Sales, and GetYourGuide "came up as a reference for ease of booking". Nothing says it is a design direction. | [pre-kickoff-harbor-and-pine.md:35] [pre-kickoff-harbor-and-pine.md:30] | Sales-relayed | Unconfirmed |

The sheet contains no findings about GetYourGuide itself, and this overview adds none.

---

## 9. What the May 8 notes assumed vs what later materials showed

| Topic | May 8 notes (cite) | Later materials (cite) | Where it stands |
|---|---|---|---|
| Eight-week pilot | Unknown if prototype, test or live launch. [pre-kickoff-harbor-and-pine.md:13] | Executive Lead describes a running experience in two cities; Tech Lead cannot confirm; Product says not agreed. [02-kickoff-transcript.md:172] [02-kickoff-transcript.md:175] [02-kickoff-transcript.md:181] | Expectation clearer; meaning still open |
| Immediate confirmation | "We should be able to confirm straight away." [pre-kickoff-harbor-and-pine.md:54] | Only where availability is connected; operator acceptance otherwise. [02-kickoff-transcript.md:52] [00-harbor-and-pine-prd-v0.9.pdf:p2] | Narrowed by Operations; share of catalog unknown |
| Hotels | "Hotels also came up as a possible channel." [pre-kickoff-harbor-and-pine.md:45] | Sales floated hotels first; Executive Lead said the first launch is traveler-facing. [02-kickoff-transcript.md:73] [02-kickoff-transcript.md:76] | Executive Lead: should not delay the pilot; Sales wants to revisit |
| Languages | "Hotel branding and more languages were discussed informally; neither is a signed commitment." [pre-kickoff-harbor-and-pine.md:54] | Five languages requested by hotels; pilot is English and Spanish. [02-kickoff-transcript.md:157] [02-kickoff-transcript.md:166] | Consistent: not committed |
| AI scope | AI "from planning through the day of the tour". [pre-kickoff-harbor-and-pine.md:20] | Adds call-listening for operators and recommendations; no autonomous change to paid bookings. [02-kickoff-transcript.md:94] [02-kickoff-transcript.md:112] | One idea added (call listening); limit stated by Executive Lead (the PRD already stated it) |
| MVP | Booking, an itinerary and an AI assistant were mentioned. [pre-kickoff-harbor-and-pine.md:27] | No agreed list; candidate scope is not a backlog. [00-harbor-and-pine-prd-v0.9.pdf:p2] | Still unagreed |
| Platform | "A link that travelers can open on a phone. Native apps were not committed." [pre-kickoff-harbor-and-pine.md:28] | "No required download." [02-kickoff-transcript.md:133] | Stated by the Executive Lead |
| Start from scratch | Tied to not showing the current website. [pre-kickoff-harbor-and-pine.md:10] | Operations and the PRD add that operators, agreements and tools are not all replaced. [02-kickoff-transcript.md:40] [00-harbor-and-pine-prd-v0.9.pdf:p1] | Qualified |
| Current tools | "I do not know its stack or what other tools run the business." [pre-kickoff-harbor-and-pine.md:34] | PRD lists spreadsheets, email, messaging and separate support and payment tools, without a stated source. [00-harbor-and-pine-prd-v0.9.pdf:p1] | Partly filled; origin of the list unknown |
| Cities | Not mentioned. | Lisbon and Barcelona. [00-harbor-and-pine-prd-v0.9.pdf:p1] [02-kickoff-transcript.md:172] | New |
| Where the problem is | "A simpler booking experience and less work for the team." [pre-kickoff-harbor-and-pine.md:26] | Booking conversion (Executive Lead) vs day of activity (Operations). [02-kickoff-transcript.md:91] [02-kickoff-transcript.md:88] | Different emphasis inside client; not ranked |
| Approvals | Not agreed. [pre-kickoff-harbor-and-pine.md:41] | Still not agreed; Operations cannot give one rule. [02-kickoff-transcript.md:118] | Unchanged |
| KPIs | "No baseline or targets provided." [pre-kickoff-harbor-and-pine.md:29] | "Not as a clean number." [02-kickoff-transcript.md:49] | Unchanged |
| Access to guides | "Access to guides and operators still needs arranging." [pre-kickoff-harbor-and-pine.md:40] | Two guides were interviewed May 13–14. [04-guide-interview-notes.md:1] | Partly done |
| Process examples and brand assets | "Not received." [pre-kickoff-harbor-and-pine.md:36] | Product asked for process and examples of what customers and the team receive; Operations said "Yes, I can share those." [02-kickoff-transcript.md:37] [02-kickoff-transcript.md:40] Brand assets were not discussed in the excerpt. | Process examples promised, not yet seen; brand assets unaddressed |

---

## 10. Conflicts between sources

| # | Topic | Source A | Source B | Type | Status |
|---|---|---|---|---|---|
| C1 | Confirmation | May 8 notes relay "We should be able to confirm straight away." [pre-kickoff-harbor-and-pine.md:54] | Operations: "Not always." [02-kickoff-transcript.md:58] PRD: "Other inventory requires operator approval after payment authorization." [00-harbor-and-pine-prd-v0.9.pdf:p2] | Cross-source | Unconfirmed; narrowed by Operations |
| C2 | Eight-week date | Executive Lead wants the experience "running in Lisbon and Barcelona by then". [02-kickoff-transcript.md:172] | Signed scope is design only, with development separate [pre-kickoff-harbor-and-pine.md:50]; Tech Lead: "I cannot confirm a live launch in that window." [02-kickoff-transcript.md:175] | Client vs scope | Open |
| C3 | Hotels as first audience | Sales: "Maybe hotels should be the first audience." [02-kickoff-transcript.md:73] | Executive Lead: "The first launch is still traveler-facing." [02-kickoff-transcript.md:76] | Sales vs Exec Lead | Executive Lead stated a direction; Sales to revisit [02-kickoff-transcript.md:85] |
| C4 | Start from scratch | Executive Lead: "We are happy to start fresh." [02-kickoff-transcript.md:208] | Operations: "I cannot promise that all their systems change with ours." [02-kickoff-transcript.md:40] | Intra-client constraint | Open |
| C5 | Emphasis | Executive Lead: "I still need more people to book." [02-kickoff-transcript.md:91] | Operations: "Discovery is not where most of my team spends time." [02-kickoff-transcript.md:88] | Intra-client, different emphasis | Open (not ranked) |
| C6 | Cancellation policy | Executive Lead: "Can we just use one cancellation policy for the pilot?" [02-kickoff-transcript.md:187] | Operations: "Different operators already have different agreements." [02-kickoff-transcript.md:190] | Intra-client | Open pending review |
| C7 | Customer view of a pending booking | Executive Lead: "Could we keep that complexity behind the scenes?" [02-kickoff-transcript.md:64] | Design: "we need to know what we can actually promise at that point." [02-kickoff-transcript.md:67] PRD: "how it communicates the wait remains open." [00-harbor-and-pine-prd-v0.9.pdf:p2] | Client vs team | Open |
| C8 | AI moving a booking | Executive Lead: "If a tour is canceled, the assistant could move someone to another one." [02-kickoff-transcript.md:106] | Operations: "Move a paid booking, no." [02-kickoff-transcript.md:109] | Intra-client | Limit stated ("with approval"); approver open [02-kickoff-transcript.md:112] [02-kickoff-transcript.md:118] |
| C9 | AI scope | PRD describes "an assistant before and during an activity". [00-harbor-and-pine-prd-v0.9.pdf:p1] | Executive Lead adds an AI that "could listen when someone calls". [02-kickoff-transcript.md:94] | Cross-source | Open (not in the PRD) |
| C10 | Live map | Sales: "Should we put a live map in the first version?" [02-kickoff-transcript.md:136] | Operations: "Live location is useful only if it is accurate." [02-kickoff-transcript.md:139]; Sales withdrew it as a requirement. [02-kickoff-transcript.md:142] | Sales vs client | Sales withdrew it as a requirement; no one else decided |
| C11 | Immediacy | Executive Lead: "Booking should feel immediate. Choose an activity, pay, get confirmation." [02-kickoff-transcript.md:43] | Operations: "Not always." [02-kickoff-transcript.md:58] PRD: "how it communicates the wait remains open." [00-harbor-and-pine-prd-v0.9.pdf:p2] | Client vs client | Open |

---

## 11. Open questions

Owners are the roles the sources point to; for Q14 and Q18–Q22 the owner is my assignment, not stated in a source. The question column is the wording to use in the meeting.

| # | Owner | Question to ask | Why it is open |
|---|---|---|---|
| Q1 | Executive Lead | When you say "an eight-week pilot", what must exist at week eight: a prototype, a test with real travelers, or a live launch in Lisbon and Barcelona? | [pre-kickoff-harbor-and-pine.md:13] [02-kickoff-transcript.md:172] |
| Q2 | Executive Lead, Product | What implementation effort follows the current phase, and who carries it? | [00-harbor-and-pine-prd-v0.9.pdf:p4] |
| Q3 | Operations | What share of the catalog is on connected availability, and what share replies by email or WhatsApp? | [02-kickoff-transcript.md:52] |
| Q4 | Sales | Which activities did the client mean by "We should be able to confirm straight away"? | [pre-kickoff-harbor-and-pine.md:54] |
| Q5 | Executive Lead, Operations | For each kind of change to a paid booking, who approves: the traveler, Operations or the operator? | [02-kickoff-transcript.md:115] [02-kickoff-transcript.md:118] |
| Q6 | Operations | Who makes the final call when a customer expectation conflicts with an operator policy, and which examples can you bring? | [02-kickoff-transcript.md:196] [02-kickoff-transcript.md:199] |
| Q7 | Operations | What do the current operator agreements say about cancellation, rescheduling, no-shows and refunds? | [02-kickoff-transcript.md:184] [02-kickoff-transcript.md:190] |
| Q8 | Executive Lead | When will you review options for how a paid but unconfirmed booking is shown to the traveler? | [02-kickoff-transcript.md:70] |
| Q9 | Executive Lead, Tech Lead | Which details must work on a weak connection, and does that mean after the link has been opened once? | [02-kickoff-transcript.md:130] [02-kickoff-transcript.md:133] |
| Q10 | Sales | Which systems hold customer records and call recordings today, and who at the client can list them? | [02-kickoff-transcript.md:97] [02-kickoff-transcript.md:100] |
| Q11 | Executive Lead | Which AI behavior do you want to see first: recommendations, help for operators during calls, or help during the trip? | [02-kickoff-transcript.md:94] [02-kickoff-transcript.md:106] |
| Q12 | Sales, Executive Lead | Is a hotel concept to show partners part of this phase, or a separate discussion, and when? | [02-kickoff-transcript.md:79] [02-kickoff-transcript.md:82] [02-kickoff-transcript.md:85] |
| Q13 | Sales | Are any of the five hotel languages a launch requirement, or do we start with English and Spanish? | [02-kickoff-transcript.md:157] [02-kickoff-transcript.md:166] |
| Q14 | Product Director | Is the "pilot brief" the PRD v0.9 dated May 11, or another document? | [02-kickoff-transcript.md:160] [00-harbor-and-pine-prd-v0.9.pdf:p3] |
| Q15 | Operations | Which assumptions in the draft do you expect to revisit after checking Lisbon and Barcelona? | [02-kickoff-transcript.md:211] |
| Q16 | Executive Lead, Operations | Which numbers exist today for completed bookings, abandonment, support contacts and manual handling time? | [02-kickoff-transcript.md:49] [00-harbor-and-pine-prd-v0.9.pdf:p1] |
| Q17 | Operations | How do operators check in a group, and what happens when part of a group arrives late? | [02-kickoff-transcript.md:154] [04-guide-interview-notes.md:19] [04-guide-interview-notes.md:29] |
| Q18 | Product Director | Does the signed SOW list a prototype and a development handoff among the deliverables? | [pre-kickoff-harbor-and-pine.md:15] |
| Q19 | Sales | What are the names and availability of the client contacts, and who is the Sales owner? | [pre-kickoff-harbor-and-pine.md:8] [pre-kickoff-harbor-and-pine.md:9] |
| Q20 | Marti Lanzi | Who drew the whiteboard, when, and what do the crossed-out AUTO box and the QR scan refer to? | [01-whiteboard-day-of-tour.png:img] |
| Q21 | Executive Lead | Is WCAG 2.2 AA a requirement, and who approves accessibility and privacy requirements? | [00-harbor-and-pine-prd-v0.9.pdf:p3] [00-harbor-and-pine-prd-v0.9.pdf:p4] |
| Q22 | Design, Operations | When one person books for six, what does everyone else receive? | [02-kickoff-transcript.md:151] [02-kickoff-transcript.md:154] |
| Q23 | Product | What user access, inventory picture, process examples and approval responsibilities are still needed before next steps? | [02-kickoff-transcript.md:205] |
| Q24 | Sales | What was discussed with Operations on May 11 about the hotel group and the guide running late? | [02-kickoff-transcript.md:13] [02-kickoff-transcript.md:16] |
| Q25 | Operations | When can you share the process examples and examples of customer and team messages? | [02-kickoff-transcript.md:37] [02-kickoff-transcript.md:40] [pre-kickoff-harbor-and-pine.md:36] |

---

## 12. Digest vs originals

I diffed `H&P Knowledge base.md` against the originals with `.context/scripts/digest_diff.py`, comparing sentence by sentence on text normalized for Markdown markup, timestamp prefixes, bullet glyphs and heading numbers. The digest states "Content is kept as written in the originals; only the formatting has been converted to Markdown." [H&P Knowledge base.md:3] That holds for the five text sources. The differences are in structure and metadata.

| # | Silent difference | Detail |
|---|---|---|
| D1 | Body text | After normalization, no sentence differs between the digest and the pre-kickoff notes, PRD, kickoff transcript, guide notes or competitor sheet. |
| D2 | File names | The digest source table lists `.docx` for the pre-kickoff notes, kickoff transcript and guide notes. The repo holds `.md` for all three. |
| D3 | PRD file name | Digest: `00-harbor-and-pine-prd-v0_9.pdf`. Repo: `00-harbor-and-pine-prd-v0.9.pdf`. |
| D4 | PRD structure | Sections 1–15 are renumbered 2.1–2.15 under a new "2. PRD v0.9" heading. [H&P Knowledge base.md:73] Page boundaries are lost, so page-level citation is impossible from the digest. |
| D5 | Transcript and guide notes | Speakers are recased, headings and bullets are restructured, and curly quotes become straight quotes. |
| D6 | Dates | The whiteboard and competitor sheet are listed "Undated"; this matches the sources. [H&P Knowledge base.md:9] [H&P Knowledge base.md:12] |
| D7 | Conversion artifacts | Line 1 of the transcript and guide notes contain a literal backslash-pipe separator, while the May 8 notes use a plain pipe. This is consistent with a Word-to-Markdown conversion. |
| D8 | Whiteboard | The digest section is a transcription, not a copy. It adds its own caption ("their intended meaning was not documented" [H&P Knowledge base.md:195]), colors and locations for each sticky, and arrow targets. I compared it with the image by eye. The visible text is all present. The WHO APPROVES? sticky is shown as green; in the photo it reads light green. The caption is the digest author's and is not on the board. |

---

## 13. Verification record

- **Quote check.** `.context/scripts/verify_quotes.py` checks that every double-quoted string appears verbatim in a source cited on the same line (Markdown: cited line ±1; PDF: cited page) and that every cited line or page exists. Typographic quotes and Markdown bold are normalized before matching. Result: 305 citations parsed, 0 invalid; 188 quoted strings, 182 matched, 6 whiteboard quotes not machine-checkable. The script proves wording, not that the right speaker or claim is attached to a quote.
- **Digest diff.** `.context/scripts/digest_diff.py` produced §12 D1.
- **db90-audit.** Applied by hand to this file: frontmatter fields present, `last_updated` not in the future, `status` valid, `layer: product` matches the path, all `sources` exist, `relates_to` empty (Layer 0 `latest/` holds only templates). No blockers. Not applicable: cross-link, cascade, journey, feature-spec and L1/L2 mirror checks.
- **skill-review-adversarial.** Run by an independent reviewer who was given the document and sources but not my conclusions. It returned 32 findings. I corrected the ones I verified: over-strong *contradicted* and *resolved* labels, the tag on the sponsor line, three rows that were gaps and not conflicts (removed), missing open questions (group booking, user access, the May 11 Sales–Operations conversation), the §11 owner claim, and several quotes that dropped a caveat. I did not change: the *Where it stands* column and the §11 question wording, which stay as light summaries the brief asked for; and the process notes in §12–§15, which the brief asked for.

**Checks I could not run.**
- Quotes attributed to the whiteboard image cannot be string-checked; I checked them by eye.
- `db90-audit` is written for a `final/` folder and the status value `established`. This repo uses `latest/`, and the skill is not wired to this repo's layout. I applied its checks by hand to this one file.
- `.companion.yaml` does not exist, so no role-based tailoring was applied.
- `companion/hooks/update-metadata.sh` applies to `latest/` documents only and was not run.
- No comparison with the `.docx` originals, the SOW, or any recording.
- No external validation yet: Marti Lanzi, the Product Director, a cold reader and the client meeting are the checks that remain.

---

## 14. Three questions for Marti Lanzi or the Product Director

1. Files are numbered 00, 01, 02, 04 and 05. Is there a file 03? If so, what is it and why is it not in commit 1e71aaf? (Product promised a recap at [02-kickoff-transcript.md:205]; I cannot tell whether that is 03.)
2. The compiled digest lists `.docx` files for the pre-kickoff notes, kickoff transcript and guide notes, but the repo holds `.md`. Are the `.md` files faithful conversions, and can the `.docx` originals be added?
3. A kickoff transcript dated May 12 is in the folder. Which meeting is the pre-kickoff meeting this overview is for, and does it come before or after that session?

## 15. Five questions a cold reader should be able to answer from this document

1. What does the signed scope cover, how many hours is it, and what follows it? (§0, §2)
2. What did the Executive Lead want by the eight-week date, and how did the Tech Lead and Product respond? (§0, §2, §10)
3. Which statements about confirming bookings, changing paid bookings and cancellation policy are settled, and which are still open? (§4, §10)
4. Who is likely the sponsor, and which approvals have no owner yet? (§5)
5. What did the two guides say goes wrong on the day of a tour, and what did the interviews not cover? (§7)
