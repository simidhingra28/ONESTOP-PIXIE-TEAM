# Segmenting note: who gets which version

Blocked on: customer list in board/inputs/. Not there as of 2026-10-26. Fields I need: first name, phone, email, last service, last job date, opt-out flag, area/address, job feedback (if any). Drop the file and I will tag by row.

## Remove first (everyone)
1. Opted out of texts or email. Skip that channel.
2. Open job, open complaint, or negative feedback. Do not contact. Flag to Mushroom.
3. Missing phone or email: send only on the channel they have.
4. Duplicates.

## Segments
| Segment | Rule | Gets |
|---|---|---|
| 1. Likely moving | Past customer whose list notes say move, rental, tenant, landlord or turnover. Only if the list says so. | Version A (move-out), 3 steps |
| 2. Lapsed 3+ months, everything else | Last job over 3 months ago, any service | Version B (holiday deep clean), 3 steps |
| 3. Never booked cleaning | Past customer, last service not cleaning | Version B. Add one line referencing [LAST_SERVICE], e.g. "Thanks again for the [LAST_SERVICE]." |
| 4. Happy customers | Job in last 3 months, positive feedback or a good review | Referral ask only. No sequence. Not also in A or B. |
| 5. Unknown / no feedback data | Cannot tell | Version B. No referral ask. |

## Rules
- One message stream per person. Never send A and B together.
- Default is B when unsure. Do not guess who is moving.
- Texts only where the list shows consent. Emails always carry an unsubscribe line.
- Send times: Tue 10-27, Wed 10-28, Thu 10-29 mornings. Stop on booking, reply, or opt-out.
- Only the move-out hook has a hard date (Oct 31). If a person books after Thu, fold them into Version B follow-up.
