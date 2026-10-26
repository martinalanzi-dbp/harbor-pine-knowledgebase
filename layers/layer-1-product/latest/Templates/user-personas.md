---
title: "User Personas"
layer: product
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-0-business/latest/Templates/business-overview.md
  - layers/layer-0-business/latest/Templates/stakeholder-map.md
sources:
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# User Personas

The people the Harbor & Pine product serves. Each persona states its evidence base. Only the guide persona comes from direct user research (two remote interviews). The others are built from the PRD and from what the Executive Lead, Operations and Sales said, and need validation.

---

## Traveler — "The Group Booker"

*Evidence: PRD, kickoff, Operations follow-up, and second-hand reports from the guide interviews. No traveler research yet.*

### Identity

**Role / Title:** A visitor to Lisbon or Barcelona who books local activities, sometimes for a whole group.

**Context:** Browses and books mostly on a phone, sometimes on a laptop before the trip. On the day, they are on the move in an unfamiliar city, often with a weak connection. No app download and no account are assumed to suit them. This is the Executive Lead's and Sales' direction, not traveler research.

### Goals

- Know exactly what they are booking: inclusions, restrictions, cancellation terms and a price close to the final one.
- Get a clear confirmation quickly after paying.
- Have the itinerary on their phone even if they booked on a laptop, and share it with the group.
- Find the meeting point easily on the day, even with poor reception.
- Hear about changes in time and get a good alternative if something is cancelled.

### Pain Points

- Waiting for confirmation after paying when the operator still has to accept. Assumed: the Executive Lead says "we lose people when they have to wait."
- Outdated meeting points and missed update messages. One group went to the meeting point in their original email after their tour had moved. Reported by Operations.
- Being unsure they are in the right place, and sending the guide screenshots to check. One group waited on the other side of the square. Guide-reported.
- ⚠️ Open: what each member of a group receives, since the voucher represents the reservation.

### Behaviors

They browse and compare activities by destination, date, interests and price, then book for themselves and others. Today they rely on emails and messages from Harbor & Pine, operators and guides. Before the activity they look for the meeting point; when unsure, they message the guide with photos or screenshots. According to one guide, they sometimes recognize a landmark in a photo more easily than an address. How often these problems occur has not been measured.

### Relationship to the Product

They are occasional, high-stakes users: they use the product intensively around one booking and on the day of the activity. What matters most is booking clarity, confirmation status, the voucher, meeting-point instructions and timely updates. They judge the product by whether they got a clear answer quickly and arrived at the right place at the right time. A forced download, a long checkout or a confirmation that later turns out to be wrong would push them away.

---

## Guide — "The Multi-Operator Guide"

*Evidence: two remote interviews (Lisbon, May 13; Barcelona, May 14), kickoff, Operations follow-up. No tour was observed; frequency of issues was not measured.*

### Identity

**Role / Title:** A guide leading tours in Lisbon or Barcelona who works for several operators.

**Context:** Works on the street with the group in front of them, often on an older Android phone with limited battery and patchy reception. Receives group lists from different operators through different tools, mostly messaging. Comfortable with messaging apps; little patience for forms.

### Goals

- Open the current group list quickly, with names, group size, language and relevant needs.
- Have the meeting point, group details and emergency contact available without a connection.
- Record arrivals and no-shows fast, and report a delay without typing a long explanation.
- Know about recommendations or changes before travelers receive instructions that change the plan.

### Pain Points

- Conflicting lists. In one case a list of 8 people was followed by a list of 10, and the guide had to call Operations to check.
- The last list sometimes arrives while they are already on the way.
- Travelers waiting in the wrong place, or asking by screenshot whether they are in the right spot.
- Battery drain from keeping many apps open.
- Route or plan changes made without notice.

### Behaviors

They check the list the night before and again before leaving, and identify the latest version by the time of the message and who sent it. They mark arrivals on a list and keep track of split groups from memory. When there is a problem they call or message Operations, and they change routes on the spot when needed (for example, a blocked street). Messaging is their most reliable channel; a downloaded list is their fallback when reception drops, and a saved address or photo works when a map does not load.

### Relationship to the Product

They are daily users on activity days. What matters most is the offline group list, the meeting point, attendance, delay reporting and change notices. They adopt the tool only if it opens fast, needs little typing and earns their trust; until then they keep messaging in parallel. Forms with the group waiting, battery drain or out-of-date data would make them stop using it.

---

## Operations Team Member

*Evidence: kickoff (Operations speaker), Operations follow-up email, PRD. No observation of Operations work.*

### Identity

**Role / Title:** A member of Harbor & Pine's Operations team covering Lisbon and Barcelona.

**Context:** Works between travelers, guides and operators, using spreadsheets, email, messaging and separate support and payment tools. Handles assignments, changes, incidents, cancellations and refunds.

### Goals

- See problems early enough to act, especially on the day of the activity.
- Get operator acceptance on manual bookings and tell travelers clearly what is happening.
- Approve changes to paid bookings, with clear rules about who approves what.
- Keep manual communication from growing. Every exception should have an owner and a resolution path.

### Pain Points

- Day-of disruption: old meeting points, late guides, weather, travelers who cannot open a message.
- Updated messages that some travelers never see.
- Operators that reply by email or messaging and can take up to 12 hours to accept.
- Escalations that go to "not always the same person."
- Different cancellation rules per operator and activity.

### Behaviors

They can confirm connected availability immediately. For manual inventory, they may authorize payment while they wait for the operator to accept. They escalate conflicts between customer expectations and operator policy case by case, and guides call or message them when a list looks wrong or a problem comes up. ⚠️ Their day-to-day communication workflow has not been observed.

### Relationship to the Product

They are daily internal users and approvers. What matters most is booking status, the exception queue, contacting the right people and approving changes. They judge the product by whether it reduces messages and manual handling. A nice front end that generates more questions for their team would be a failure.

---

## Operator

*Evidence: PRD, kickoff and Operations follow-up, as reported by Operations. No operator has been interviewed.*

### Identity

**Role / Title:** A local business that delivers activities sold by Harbor & Pine.

**Context:** Controls availability, prices, policies and delivery under its own agreement with Harbor & Pine. Only 38% of activities are on synchronized availability; other operators work through spreadsheets, email or WhatsApp. They keep their own systems for now.

### Goals

- Receive clear booking requests and accept or decline them.
- Keep their own cancellation rules and conditions.
- Approve changes that affect their activities.

### Pain Points

⚠️ Not yet researched. Inferred: requests and changes that ignore their conditions, such as being moved to a tour that costs more or has different conditions.

### Behaviors

They reply to requests by email or messaging. Some take up to 12 hours. Private tours depend on guide, language and price validation. They send group lists to guides through their own tools.

### Relationship to the Product

They are occasional, external users or integrations. They are critical for confirmation and paid-booking changes. Operations cannot promise that their systems will change with Harbor & Pine's, so the product has to work with their current agreements and tools.

---

## Future audience: Hotel partner

Not a pilot persona. Hotels recommend activities to their guests and have asked for a branded version in English, Spanish, Portuguese, French and Italian, opened from a link without an app. A persona should be written when the hotel channel is brought into scope.
