# Credit on UPI — Designing for Invisible Borrowers
## A PM Case Study
### By Mrunal Ghode | Aspiring Product Manager

---

## Why This Problem Matters

500 million Indians use UPI every day.
But 190 million of them have never accessed
formal credit — not because they're bad borrowers,
but because the system has no data on them.

No CIBIL score. No credit card history.
No loan repayment record.

They are invisible to the formal credit system.
But they are not invisible to UPI.

---

## 1. The One Line Problem Statement

First-time borrowers in Tier 3 India are excluded
from formal credit not because they are
untrustworthy — but because traditional credit
scoring systems cannot see them.

UPI transaction data can.

---

## 2. The Real Scale of This Problem

| Metric | Value | Source |
|---|---|---|
| Monthly UPI transactions | 22.64 billion (March 2026) | NPCI |
| Active UPI users | 500+ million | NPCI |
| Users without formal credit history | ~190 million | RBI estimates |
| Rural UPI adoption | 38% | CoinLaw 2026 |
| Fintech app annual retention | Only 16% | LinkedIn Research |
| India fintech market size | $125 billion (2025) | Precisa 2026 |

**The insight:**
190 million Indians transact on UPI daily but
cannot access credit because CIBIL has no data
on them. Their UPI history is a goldmine of
creditworthiness signals — completely unused
by traditional lenders.

---

## 3. Meet Sneha — The Invisible Borrower

Sneha is 22 years old. She lives in Latur,
Maharashtra and works at a local textile shop.

- Income: ₹12,000/month — same amount, same date,
  every month via UPI
- Spending: Pays rent, electricity, and groceries
  consistently on time via UPI
- Savings: Always has ₹2,000–3,000 left at
  month end — never break even
- Credit history: Zero. Never taken a loan.
  Never had a credit card.
- CIBIL score: Does not exist
- Digital literacy: Comfortable with UPI and
  WhatsApp. Limited English.
- Biggest fear: Being trapped in debt she
  doesn't understand

**Why Sneha and not an urban user?**
Urban users already have credit cards, personal
loans, and BNPL options fighting for their
attention. Sneha has nobody designing for her.
She is the next 100 million.

---

## 4. The Trigger Moment

Sneha is at a medical store.
Her mother needs medicines urgently.
Total bill: ₹3,200.
Her account balance: ₹1,800.
Salary comes in 4 days.

She has three options:
1. Call a friend — awkward, slow, uncertain
2. Go to a bank — takes 3–7 days, useless now
3. Use Credit on UPI — instant, in the app
   she already trusts

This is the moment the product must nail.
Everything depends on the next 30 seconds.

---

## 5. Root Cause Analysis

### Why can't Sneha access credit today?

**Root Cause 1 — No CIBIL score**
Traditional lenders require a credit history
to assess risk. Sneha has never borrowed
formally so she doesn't exist in the system.

**Root Cause 2 — Wrong data being used**
CIBIL measures formal borrowing behaviour.
But Sneha's UPI data shows savings behaviour,
payment consistency, and income stability —
three strong signals of creditworthiness
that traditional systems completely ignore.

### Why I focused on Root Cause 2
Root Cause 1 cannot be solved quickly —
building a CIBIL score takes years of
formal credit history.

Root Cause 2 can be solved today — the
data already exists inside UPI transaction
history. The problem is nobody is using
it the right way.

---

## 6. CIRCLES Framework Analysis

### C — Comprehend the Situation
**Goal:** Enable first-time borrowers in Tier 3
India to access instant credit through UPI
at the exact moment they need it

**Platform:** Mobile — Android, regional
language support, low-end devices

**Business context:** India's fintech sector
is shifting from payments to credit. Credit
on UPI is the single biggest opportunity
in Indian fintech in 2026. The companies
that crack Tier 3 credit will build the
next decade's giants.

---

### I — Identify the User
**Primary user:** Sneha — the invisible borrower

22 years old. Latur, Maharashtra.
Fixed income. Consistent bill payer.
Saves every month. Zero credit history.
Trusts UPI. Fears debt traps.

**Why Sneha?**
Urban users are already served. Sneha
represents 190 million Indians the system
has left behind. Whoever designs for Sneha
wins the next wave of Indian fintech.

---

### R — Report the User's Needs

**Need 1 — Be seen as creditworthy**
Sneha IS a good borrower. She saves, she
pays on time, she has stable income. She
needs a system that can see that — without
requiring a CIBIL score she'll never have.

**Need 2 — Understand exactly what she's
agreeing to**
Sneha's biggest fear is a debt trap. She
needs to know exactly how much she's
borrowing, exactly how much she'll repay,
and exactly when. No jargon. No fine print
surprises. In her language.

**Need 3 — Feel safe enough to tap yes
in 30 seconds**
The medical store moment doesn't allow
for 10 minutes of reading terms. The
product needs to build trust instantly —
through transparency, simplicity, and
the ability to reverse the decision
if she changes her mind.

---

### C — Cut Through Prioritisation

| Need | User Impact | Business Impact | Effort | Priority |
|---|---|---|---|---|
| Be seen as creditworthy | High | High | High | 🔴 P0 |
| Understand what she's agreeing to | High | High | Low | 🟡 P1 |
| Feel safe enough to tap yes | High | High | Medium | 🟢 P2 |

**Prioritising Need 1 — Alternative credit scoring**
Needs 2 and 3 are UX problems — solvable in
weeks. Need 1 is an infrastructure problem.
Without a way to assess Sneha's creditworthiness,
the product cannot exist at all. Solve the
foundation first.

---

### L — List Solutions

**Solution 1 — UPI Alternative Credit Score**
Build a credit scoring model using three UPI
signals instead of CIBIL:

Signal 1 — Savings behaviour:
Does the user consistently have money left
over at month end? Never always break even?

Signal 2 — Payment consistency:
Does the user pay bills, rent, and regular
commitments on time every month via UPI?

Signal 3 — Income stability:
Does the user receive a regular fixed amount
from the same source on a consistent date?

These three signals — observable entirely
from UPI transaction history — predict
repayment behaviour more accurately for
first-time borrowers than CIBIL.

---

**Solution 2 — Contextual Credit Offer Screen**
Design the credit offer for the medical store
moment — not for a loan application form.

Bad version:
"Pre-approved credit limit: ₹10,000.
Interest rate: 24% per annum.
Processing fee: 2%. T&C apply."

Good version:
"You're ₹1,400 short.
Borrow exactly ₹1,400 now.
Repay ₹483 over 3 months.
No hidden charges.
Cancel before midnight if you change
your mind."

Four design principles:
1. Contextual amount — show only what
   she's short, not a generic limit
2. Plain language repayment — monthly
   amount not annual interest rate
3. Radical transparency — no hidden
   charges, stated upfront
4. Reversible commitment — cancel window
   removes fear of being trapped

---

**Solution 3 — Vernacular First Interface**
The entire credit flow in Marathi.
Not translated — designed in Marathi.
Voice confirmation option for low
literacy users.
Simple iconography over text wherever
possible.

---

### E — Evaluate Tradeoffs

**Ship in three phases:**

**Phase 1 — UPI Alternative Credit Score**
(8–12 weeks)
Build the scoring model using UPI transaction
data. Partner with an NBFC for lending capital.
Start with a small cohort — 10,000 users in
Maharashtra. Validate repayment rates before
scaling.

Risk: Regulatory approval from RBI needed
for alternative credit scoring models.
Mitigation: Partner with an existing RBI
licensed NBFC who already has approval
infrastructure.

**Phase 2 — Contextual Credit Offer Screen**
(4–6 weeks)
Design and ship the four-principle offer
screen. A/B test plain language repayment
vs traditional interest rate display.
Measure tap-through rate and completion rate.

Risk: Users may still not trust the offer.
Mitigation: Add a "How does this work?"
explainer in 60 seconds — in Marathi.

**Phase 3 — Vernacular Interface**
(6–8 weeks)
Launch full Marathi credit flow.
Add voice confirmation for low literacy users.
Measure adoption lift in Tier 3 Maharashtra
vs control group.

Risk: Translation quality feels robotic.
Mitigation: Work with native Marathi speakers
for copy — not Google Translate.

---

### S — Summarise

190 million Indians transact on UPI daily
but cannot access formal credit because
CIBIL has no data on them.

I'd solve this in three phases:

1. Build an alternative credit score using
   three UPI signals — savings behaviour,
   payment consistency, income stability
2. Design a contextual credit offer screen
   built for the medical store moment —
   plain language, transparent, reversible
3. Launch a vernacular-first interface in
   Marathi — designed in the language,
   not translated into it

Start with Phase 2 — ships fastest, costs
least, validates user trust immediately.
Then Phase 1 to unlock the scoring model.
Then Phase 3 to crack Tier 3 adoption.

---

## 7. Success Metrics — HEART Framework

| Framework | Metric | Target |
|---|---|---|
| Happiness | CSAT after first credit experience | Above 4.4/5 |
| Happiness | % users who felt the offer was clear | Above 80% |
| Engagement | % users who open credit offer screen when shown | Above 50% |
| Adoption | % new-to-credit users who complete first borrowing | Above 35% |
| Retention | % users who repay on time and borrow again within 90 days | Above 60% |
| Task Success | % of credit transactions completed without user dropping off | Above 75% |

---

## 8. The Bigger Vision

Credit on UPI for Sneha is not just a
lending product. It is financial inclusion
infrastructure.

When Sneha borrows ₹1,400 and repays it
in 3 months — she has a credit history.
Now she can borrow ₹5,000 next time.
Then ₹20,000 for her brother's education.
Then ₹1,00,000 for her own small business.

One contextual credit offer at a medical
store is the first step of a decade-long
financial journey for 190 million Indians
who the system has never seen.

That is the product worth building.

---

## 9. What I Learned

- Invisible users are not bad users —
  they are users the system hasn't
  learned to see yet
- The right data matters more than
  more data — three UPI signals beat
  a CIBIL score for first-time borrowers
- Trust is a design problem — the
  difference between a predatory offer
  and a safe one is four sentences
- Vernacular is not translation —
  it is a completely different design
  philosophy
- The medical store moment taught me
  that context is everything — the same
  product feels completely different
  depending on when and where it appears

---

## 10. Target Companies Building This

| Company | Why relevant |
|---|---|
| PhonePe | Largest UPI volume, Credit on UPI expansion |
| Razorpay | Payment infrastructure, credit products |
| Juspay | UPI checkout and credit integration |
| BharatPe | Built for small merchants and Bharat users |
| Jar / Gullak | Savings and credit for Bharat segment |
| KreditBee | New to credit segment lending |
| Setu by Pine Labs | UPI API infrastructure |

---

## Data Sources

- NPCI Monthly UPI Data March 2026
- RBI Digital Lending Guidelines 2025
- CoinLaw UPI Statistics 2026
- Decentro Indian Fintech Trends 2026
- IBS Intelligence Credit on UPI Report 2025
- Precisa Fintech Startups India 2026

---

*Case study by Mrunal Ghode — Aspiring Product Manager*

*Every insight in this case study was built
from first principles — starting with one
question: why can't Sneha get a loan?*

*📧 Connect: www.linkedin.com/in/mrunal-ghode*
*🔗 Portfolio: github.com/mrunalghode11*
