# Harbor & Pine — Project Documents

Compiled from six source files, in chronological order. Content is kept as written in the originals; only the formatting has been converted to Markdown.

| # | Document | Source file | Date |
|---|---|---|---|
| 1 | [Pre-Kickoff Notes](#1-pre-kickoff-notes) | `pre-kickoff-harbor-and-pine.docx` | May 8, 2026 |
| 2 | [PRD v0.9](#2-prd-v09) | `00-harbor-and-pine-prd-v0_9.pdf` | May 11, 2026 |
| 3 | [Whiteboard: Day of Tour](#3-whiteboard-day-of-tour) | `Whiteboard Image Information/01-whiteboard-day-of-tour.png` | Undated |
| 4 | [Product Kickoff Transcript](#4-product-kickoff-transcript) | `02-kickoff-transcript.docx` | May 12, 2026 |
| 5 | [Guide Interview Notes](#5-guide-interview-notes) | `04-guide-interview-notes.docx` | May 13–14, 2026 |
| 6 | [Competitor Overview: GetYourGuide](#6-competitor-overview-getyourguide) | `05-competitor-overview-getyourguide.pdf` | Undated |

---

## 1. Pre-Kickoff Notes

*May 8, 2026 | Prepared by the Product Director after a short handoff with Sales. Client discovery has not started.*

### 0. Project Overview

- **Client / Project Name:** Harbor & Pine.
- **Client Point of Contact(s):** Executive Lead. Names and meeting availability to be shared by Sales.
- **Sales Lead / AE:** Tourism account team. Individual owner to confirm.
- **Project Type:** New platform for an existing tours business. The client wants to start from scratch and does not want to show the current website, to avoid influencing the team.
- **Budget in hours:** 550 hours total for the initial phase, across the assigned team.
- **Hours Breakdown:** Not allocated yet. Team: Product Manager, Product Designer and Tech Lead. Implementation and production QA are outside this phase.
- **Timeline:** May start expected. The client mentioned an eight-week pilot; I have not confirmed whether they mean a prototype, a test or a live launch.
- **Phase(s) covered in current SOW:** Phase 1 - Strategy and Solution Design. Development follows as a separate phase.
- **Expected Deliverables:** Prioritized scope, main journeys, high-fidelity designs and a handoff for development. Prototype coverage and technical detail to align at kickoff.

### 1. Understanding Client Vision and Motivation

- **What inspired the project?** Sales described an established business that wants a more scalable customer experience. I do not have a breakdown of the current problems.
- **What excited the client most?** AI accompanying the traveler from planning through the day of the tour.
- **Big picture or finer details?** Mostly vision, from the brief conversation I heard.
- **Personality and communication style?** Enthusiastic and direct. I have not worked with them before.

### 2. Client Expectations

- **Most important short-term outcomes?** A simpler booking experience and less work for the team. Relative priority has not been discussed.
- **Must-have features for the MVP?** Sales mentioned booking, an itinerary and an AI assistant. No agreed feature list yet.
- **Target platform?** A link that travelers can open on a phone. Native apps were not committed.
- **Success metrics or KPIs?** More bookings and fewer support requests were mentioned. No baseline or targets provided.
- **Design preferences or references?** GetYourGuide came up as a reference for ease of booking. No visual direction received.

### 3. Previous Experience and Other Insights

- **Previous digital-product experience?** They have a public website and already sell tours. Sales says the new platform should start from scratch. The current site will not be used as a design reference; I do not know its stack or what other tools run the business.
- **Competitors or references?** GetYourGuide. No competitor study from Sales.
- **Brand assets or product materials?** Not received. We can request brand assets, process walkthroughs and examples of booking communications without asking them to show the current website.

### 4. Decision Making and Key Stakeholders

- **Who else is involved?** Operations and Sales are expected at kickoff. Access to guides and operators still needs arranging.
- **Who has the final say?** The Executive Lead appears to be the sponsor. Approval responsibilities for product, operations and booking exceptions have not been agreed.

### 5. Challenges and Concerns

- **Concerns mentioned in Sales?** The client wants to move quickly and talks about AI across the entire journey. Hotels also came up as a possible channel.
- **Known risks?** Current systems, inventory access and client availability are unclear. We do not yet know what the assistant could reliably do.

### 6. SOW and Execution Details

- **Phase Description as per SOW:** Phase 1 - Strategy and Solution Design. A 550-hour initial phase for discovery, ideation, scope definition and high-fidelity design, supported by technical feasibility input. The project then moves to development under a separate phase.
- **Core Objectives:** Understand the problem, identify priority users and define a feasible first version.
- **Core Activities:** Stakeholder conversations, research, workshops, journey definition, prioritization and UX/UI design.
- **Dependencies or Non-Design Deliverables:** Tech Lead input on integrations and AI feasibility. Access to operational processes and representative users.
- **Notes from Sales:** The client said, "We should be able to confirm straight away." I do not know whether that means every activity. Hotel branding and more languages were discussed informally; neither is a signed commitment. Sales expects to introduce Operations next week.

---

## 2. PRD v0.9

*Harbor & Pine / PRD v0.9 / May 11, 2026 — Draft for alignment*

### Product context

#### 2.1 Overview

Harbor & Pine wants to make it easier to discover, book and manage local activities. The proposed product combines a traveler experience, tools for guides and Operations, and an assistant before and during an activity. The initial pilot markets are Lisbon and Barcelona.

#### 2.2 Starting point

The business already sells tours through a public website, staff and partner channels. It uses spreadsheets, email, messaging and separate support and payment tools. There is no shared product view across travelers, guides and Operations.

The client wants a new platform built from scratch and has asked not to show the current website as a design reference. This is not a decision to replace every operational tool, operator agreement or integration. Those dependencies still need assessment.

#### 2.3 Problem framing

Travelers need to know what they are booking, whether it is confirmed, where to meet and what to do when plans change. Guides need current information with little extra administration. Operations needs to see problems early enough to act. The relative priority of these problems has not been validated.

#### 2.4 Goals and possible measures

**Business:** increase completed bookings, reduce avoidable support questions and manual work, and prepare for future cities and hotel partners.

**Experience:** make booking easy to follow, keep critical day-of information available with a weak connection, and communicate changes clearly.

Possible measures include booking completion, support contacts per booking, manual handling time and guide adoption. Reliable baselines and target values have not been supplied.

#### 2.5 Commercial phase

The current SOW covers 550 total hours across a Product Manager, Product Designer and Tech Lead for discovery, ideation, scope definition and high-fidelity design, with technical feasibility input. Development is a subsequent phase.

An eight-week pilot has been mentioned by the client. Its relationship to design completion, implementation and a live launch is not agreed.

### Users and proposed booking scope

#### 2.6 Main users

- **Traveler:** browses and books, usually on a phone; one person may book for a group.
- **Guide:** needs a schedule, group details, attendance and a way to request help.
- **Operations:** handles assignments, changes, incidents, cancellations and refunds.
- **Operator:** controls availability, prices, policies and activity delivery.
- **Hotel partner:** recommends activities through a possible branded channel.

#### 2.7 Product principles

Customers should see what the business can deliver. Ask only for necessary booking details. Critical day-of information should remain accessible with limited connectivity. Automation should reduce repetitive work. Important changes to paid bookings require human approval. Prepare for growth without trying to build the entire vision at once.

#### 2.8 Candidate pilot scope

The following describes a proposed product direction. It is not an approved implementation backlog or a commitment that every item fits within the initial phase.

**Browse and activity details**
Compare activities by destination, date, interests, duration, language, price and accessibility. Show inclusions, restrictions, meeting point and cancellation terms.

**Availability and booking**
Show clear availability and expected total price. Connected inventory may confirm immediately. Other inventory requires operator approval after payment authorization. The customer experience should feel quick; how it communicates the wait remains open.

**Guest checkout and booking access**
An account is not required to book. Travelers should recover their itinerary on another device and share a group booking. A secure recovery mechanism and sharing permissions have not been selected.

**Confirmation and voucher**
Show booking status, voucher and instructions. Some operators check a reservation; others may need individual attendance. Internal statuses may be more detailed than customer-facing statuses. Mapping them needs definition.

### Day of activity and experience requirements

**Day-of experience**
Open meeting-point instructions, voucher, support and updates without a required app download. Critical information should work with limited connectivity. The exact offline dataset and refresh behavior are not defined. The assistant may suggest alternatives; it must not change a paid booking without approval.

**Guide experience**
See schedule and group information, record attendance, report delays and request help. Work on older phones with little typing. Adoption and the relationship with existing messaging need research.

**Operations experience**
See booking status, review exceptions, contact the right people and approve changes. Keep existing tools where that is the simplest pilot approach. Exception ownership and escalation need agreement.

**Hotel channel**
A branded hotel experience is part of the future vision. Sales has requested early consideration; what, if anything, belongs in the pilot remains open.

#### 2.9 Main traveler journey

Browse and compare; review key conditions; provide booking details and authorize payment; receive status and voucher; review preparation and meeting-point details; arrive and check in; complete the activity; receive follow-up and leave feedback.

Also consider manual confirmation, payment failure, weather, guide delays, weak connectivity, split group arrivals, cancellation and refunds. Which exceptions use product support versus a temporary manual process is not yet agreed.

#### 2.10 Early business rules

The first displayed price should be close to the final price. Manual inventory requires operator approval. Cancellation rules may vary by activity. An account is not required to book. Share traveler data only as needed for activity delivery. Who approves each kind of paid-booking change still needs definition.

#### 2.11 Language and accessibility

The pilot brief includes English and Spanish. Sales has requested additional languages for hotels; these are not confirmed pilot requirements. Main flows should meet WCAG 2.2 AA. Review and approval responsibilities are not assigned.

### Dependencies and unresolved questions

#### 2.12 Dependencies

Inventory providers, payments, maps and location services, messaging, translation, legal and privacy review, and access to guides and operators. No current-system audit has been completed.

#### 2.13 Risks

Availability that appears confirmed before acceptance; automation that adds manual work; low guide adoption; incorrect assistant suggestions; different operator policies; unreliable connectivity; and pilot scope that exceeds the available phase.

#### 2.14 Open questions

- When can a manual booking be described as confirmed?
- Which details must be available offline, and how are they updated?
- How can a guest recover and share a booking safely?
- What can the assistant suggest, and what can it execute?
- Who approves changes and handles exceptions?
- What belongs in the hotel channel, and which languages are included?
- Which metrics have a reliable baseline?
- Who approves accessibility and privacy requirements?
- What does the eight-week expectation mean, and what implementation effort follows the current phase?

#### 2.15 Pilot readiness proposal

A traveler should complete the main booking journey, a guide should manage the group and Operations should handle expected exceptions. The team still needs to agree acceptable manual effort, supported exceptions, temporary workarounds and launch criteria. These are proposed readiness conditions, not evidence that the pilot has been scoped or approved.

---

## 3. Whiteboard: Day of Tour

*Transcription of a photo of a whiteboard session. Handwritten in blue, green and red marker with sticky notes. Arrows and positions are described as they appear; their intended meaning was not documented.*

### Main flow (blue)

```
BOOKING → MEETING POINT → CHECK-IN → TOUR → REVIEW
```

| Step | Notes written beneath |
|---|---|
| Booking | — |
| Meeting point | "offline?", "guide late" |
| Check-in | "scan QR", "group split" |
| Tour | "weather?", "change route" (green arrow from here to the **WHATSAPP** sticky) |
| Review | — |

### Lower area (green and red)

- A green circled **"?"** with arrows pointing to:
  - the **NO APP?** sticky, which itself has an arrow pointing up toward Booking / Meeting point;
  - a box labeled **AUTO**, crossed out in red;
  - a long green arrow running right toward the Tour area, ending in a dashed line ("- - -").
- A red arrow leads from the crossed-out **AUTO** box to a red circled **"?"**.

### Sticky notes

| Sticky | Color | Location |
|---|---|---|
| NO APP? | Yellow | Left, below Booking |
| OFFLINE MAP | Pink | Left, below "NO APP?" |
| WHATSAPP | Yellow | Below Tour |
| AI SUGGESTS | Pink | Right column |
| WHO APPROVES? | Green | Right column |
| REFUND? | Pink | Right column |

---

## 4. Product Kickoff Transcript

*May 12, 2026 | Automated transcript excerpt, including the opening conversation. Speakers are identified by role. The recording ended before the remaining agenda items were discussed.*

**00:00 — Sales:** Can everyone hear me? I think Operations is still joining. How was Barcelona last week?

**00:22 — Executive Lead:** Good, apart from the rain. I packed for summer, which was optimistic. Is Lisbon any better?

**00:48 — Operations:** Not really. Sorry, I was on mute. We moved three tours last Friday because of the weather. One group still went to the meeting point in their original email.

**01:20 — Sales:** Was that the group from the hotel? The one we talked about yesterday?

**01:34 — Operations:** Different group. The hotel issue was a guide running late. Friday was an updated message that some people never saw.

**02:02 — Executive Lead:** Exactly the sort of thing an assistant should sort out. Anyway, did anyone actually get a dry weekend?

**02:22 — Design:** A little. Mostly indoors. Before we start, could someone share the agenda? I only have the invitation.

**02:45 — Product:** I have the draft brief. Let me share it. We can start with the goal, then talk about how bookings work today.

**03:10 — Executive Lead:** The goal is bigger than a nicer website. We want someone planning a trip to feel that Harbor & Pine is helping them all the way through. Discovery, booking, the actual day, everything.

**03:42 — Design:** Would it help to walk through the current website first?

**03:50 — Executive Lead:** I would rather not show it. We want to build the new platform from scratch, and I do not want the old screens to bias your thinking. The business already exists, of course.

**04:12 — Product:** Understood. We will still need to understand the process and see examples of what customers and the team receive.

**04:25 — Operations:** Yes, I can share those. A new product will still have to work with our operators and their current agreements. I cannot promise that all their systems change with ours.

**05:00 — Executive Lead:** Booking should feel immediate. Choose an activity, pay, get confirmation. We lose people when they have to wait.

**05:28 — Product:** Do we know how many people abandon because of waiting?

**05:36 — Executive Lead:** Not as a clean number. It is what I hear from the team.

**05:55 — Operations:** We can confirm immediately when availability is connected. A lot of operators still reply by email or WhatsApp. I need to check how much of the catalog that represents.

**06:24 — Sales:** Would payment be enough to reserve the place, though?

**06:31 — Operations:** Not always. We may authorize payment while we wait. The operator still needs to accept the request. Private tours can also depend on a guide and a language.

**07:02 — Product:** So should the customer see a pending status?

**07:10 — Executive Lead:** Internally, perhaps. I do not want it to feel uncertain after someone has paid. Could we keep that complexity behind the scenes?

**07:35 — Design:** We can make it easy to understand, but we need to know what we can actually promise at that point.

**07:54 — Executive Lead:** Fine. Show me options when we get there. I am not choosing wording today.

**08:15 — Sales:** On the hotel side, they have asked for a branded version. It could become bigger than direct sales. Maybe hotels should be the first audience.

**08:43 — Executive Lead:** The first launch is still traveler-facing. Keep the hotel opportunity visible, but it should not delay the pilot.

**09:02 — Sales:** Okay. I would still like something to show those partners soon. Even if it is just a concept.

**09:20 — Product:** Is that a request for this phase or something to discuss separately?

**09:29 — Sales:** Let us revisit it once we know what the main experience looks like.

**10:04 — Operations:** Discovery is not where most of my team spends time. It is the day of the activity: old meeting points, late guides, weather, people who cannot open a message.

**10:35 — Executive Lead:** And I still need more people to book. We need both sides to work.

**11:20 — Executive Lead:** The AI could listen when someone calls and show the operator relevant tours or questions to ask. If the person is new, it could learn their interests first. Then it could keep helping during the trip.

**12:02 — Tech Lead:** What systems hold customer records and call recordings today?

**12:10 — Sales:** I do not have that list. We talked more about the experience than the integration.

**12:35 — Product:** Which part of that would matter most in the first version?

**12:43 — Executive Lead:** Hard to pick before seeing it. Recommendations are an obvious starting point. If a tour is canceled, the assistant could move someone to another one.

**13:14 — Operations:** Recommend another one, yes. Move a paid booking, no. The new tour may cost more or have different conditions.

**13:34 — Executive Lead:** I meant with approval. Let us not have it change a paid booking on its own.

**13:52 — Product:** Whose approval: the traveler, Operations or the operator?

**14:02 — Operations:** That depends on the change. We need to talk through it. I cannot give you one rule for everything today.

**14:30 — Design:** Will travelers need to install an app?

**14:38 — Sales:** Hotel guests will not. They want a link that opens right away.

**14:55 — Operations:** But guides and travelers need the important details when the connection is poor.

**15:10 — Tech Lead:** Which details, and does offline mean after they have opened the link once? Those are different requirements.

**15:30 — Executive Lead:** No required download. Critical information should still work with a weak connection. We can define exactly what that means.

**16:02 — Sales:** Should we put a live map in the first version? That could help with the meeting point.

**16:16 — Operations:** A current photo and a clear address might help more in some locations. Live location is useful only if it is accurate.

**16:40 — Sales:** Fair enough. I am not saying a live map is a requirement.

**17:10 — Product:** Do travelers need an account to book?

**17:18 — Executive Lead:** No. Keep checkout short. But if I book on my laptop, I want the itinerary on my phone.

**17:40 — Design:** We need a way to recover it securely. And if one person books for six people, what does everyone else receive?

**17:56 — Operations:** Today the voucher represents the reservation. Some groups arrive together; some do not. Guides handle that differently.

**18:22 — Sales:** Hotels asked for English, Spanish, Portuguese, French and Italian.

**18:34 — Product:** The pilot brief only has English and Spanish. Are the other three launch requirements?

**18:42 — Sales:** That is what the hotels want. I have not promised delivery dates.

**19:02 — Executive Lead:** Start with the pilot brief. We can revisit the hotel languages when we revisit that channel.

**20:00 — Product:** I also want to separate the commercial phase from the pilot. The signed initial phase has 550 hours for discovery, ideation, scope and high-fidelity design, with Tech Lead input. Development follows separately. How are you using the eight-week date?

**20:30 — Executive Lead:** I would like to see bookings, payments, vouchers, day-of support, something for guides and a first AI experience running in Lisbon and Barcelona by then.

**20:56 — Tech Lead:** We have not assessed the systems or estimated implementation. I cannot confirm a live launch in that window.

**21:18 — Executive Lead:** Understood. Bring back a realistic plan, but keep that date in mind.

**21:32 — Product:** We will assess it. We have not agreed the implementation scope or launch date today.

**22:04 — Operations:** Please include rescheduling, no-shows and refunds in the discussion. Otherwise a nice front end could mean more messages for us.

**22:24 — Executive Lead:** Can we just use one cancellation policy for the pilot?

**22:32 — Operations:** Different operators already have different agreements. We cannot assume one policy without reviewing those.

**22:50 — Executive Lead:** Okay, review it. I was asking whether it would simplify things.

**23:18 — Product:** Who makes the final call if the customer expectation conflicts with an operator policy?

**23:30 — Operations:** We usually escalate, but it is not always the same person. I can bring examples.

**24:05 — Sales:** I have another call in five minutes. Do we have enough to get started?

**24:14 — Product:** Enough to identify the next questions. We still need the inventory picture, process examples, user access and approval responsibilities. I will send a recap for review.

**24:45 — Executive Lead:** Good. And do not let the current website limit the new direction. We are happy to start fresh.

**25:00 — Operations:** I will follow up after checking Lisbon and Barcelona. There may be a few assumptions in the draft that we need to revisit.

---

## 5. Guide Interview Notes

*May 13 and 14, 2026 | Notes from two short remote interviews with active guides. These are interviewer notes, not a verbatim transcript. Neither interview included observation of a full tour.*

### Guide A — Lisbon — May 13

- **Context:** Works for several operators. Different operators send information through different tools. The guide showed a recent group chat but no formal training material.
- **Before a tour:** "I check the list the night before, then again before I leave. Sometimes the last list arrives while I am already on the way." Asked how they identify the latest one: usually the time of the message and who sent it.
- **Example:** Last week a list had eight people, then another had ten. The guide called Operations to check whether the two extra people were confirmed. No count of how often this happens was collected.
- **Phone use:** "I do not mind a new tool if I can open the list quickly. I do not want to fill in a form while people are waiting." A downloaded list is useful when reception drops. The guide did not specify how updates should reach that list.
- **During the route:** Described changing a route because a street was blocked. Wants to know about recommendations before travelers receive instructions that change the plan.
- **Traveler information:** Asked why a guide would need the full customer profile. Says names, group size, language and relevant delivery needs are useful. Did not define a complete access policy.
- **Other comments:** Spent several minutes discussing busy-season traffic and favorite stops. Mentioned that tourists sometimes recognize a landmark in a photo more easily than an address.
- **Not covered:** Refund decisions, formal approval responsibilities and the steps for partial group arrival.

### Guide B — Barcelona — May 14

- **Context:** Uses an older Android phone. Tries to avoid keeping many apps open because the battery does not last all day. No device benchmark or network test was conducted.
- **Before meeting the group:** "People send me screenshots and ask if they are in the right place." Uses a photo and a short message as a fallback. One recent group waited on the other side of the square.
- **Updates:** The guide checks messaging frequently. Said it is the most reliable channel for their own work; travelers do not always see a later message. Asked whether a new tool would replace messaging: "Maybe, but I would keep it until I trust the new thing."
- **Attendance:** Marks arrivals using a list. "If a couple booked together and one arrives first, I remember the other one is coming." Wants a quick way to record who did not arrive. The interviewer did not ask every operator about its check-in rules.
- **Incidents:** Calls or messages Operations when there is a problem. Would like a quick way to report a delay without typing a long explanation. Emergency handling was not explored in detail.
- **Suggestions:** Likes suggestions for nearby alternatives, but does not want the tour or route changed without notice. Did not discuss who should authorize a new paid booking.
- **Connection:** Wants to keep the meeting point and group details available when reception drops. Said a map is helpful when it loads; a saved address or photo is still useful.
- **Other comments:** Discussed favorite neighborhoods and crowded weekends. Suggested a better meeting-point photo might be more valuable than another screen.
- **Not covered:** Account recovery, payment flow, hotel requirements and the frequency of the issues described.

---

## 6. Competitor Overview: GetYourGuide

*A starting point for reviewing how a large marketplace presents, sells, and supports tours and activities.*

| | |
|---|---|
| **Company** | GetYourGuide |
| **Category** | Tours and activities marketplace |
| **Purpose** | Reference for further research |

### Why it is relevant

GetYourGuide is useful for understanding common marketplace patterns. It should not be treated as a complete model for Harbor & Pine, which also needs to coordinate guides, operators, and day-of exceptions.

### Areas to review

- Discovery by destination, date, activity type, and availability.
- Activity details, including duration, language, accessibility, and restrictions.
- Booking confirmation, vouchers, meeting points, changes, and cancellations.
- Differences between the traveler experience and supplier operations.
- How policies are communicated at the activity level rather than as one universal rule.

### Research questions

- How does the product communicate booking certainty?
- What information is prioritized before and after payment?
- How are day-of instructions and meeting points explained?
- How are exceptions handled when the voucher is not the final ticket?
- What operational responsibilities remain with the supplier?

### Starting points

- Public marketplace: <https://www.getyourguide.com/>
- Traveler help center: <https://www.getyourguide.com/contact/>
- Supplier help center: <https://supplier-support.getyourguide.com/>
- General terms: <https://www.getyourguide.com/c/general-terms-and-conditions/>
