# Feature Roadmap, Module 4 · Your Riverty case

**Team:** Riverty BU Pay & Credit — consumer card

## Strategic anchors
- **Persona:** Lena, a 32-year-old salaried employee in Cologne on a middling income with no real financial cushion, who shops mostly on her phone.
- **Primary metric:** Active Card Usage Rate — the share of approved cardholders who make at least one card transaction within 30 days of approval. Pilot threshold 70%; experiment target 75%.
- **Moment of misery:** In a shop, Riverty is not offered, so she pays by debit and the money leaves her account immediately, before she knows whether she will keep what she bought.
- **Guardrails:** Riverty BNPL share at partner merchants must not drop by more than 2 points among cardholders; on-time repayment rate of at least 98%.

## Scoring
| ID | Feature | Value | Effort | Quadrant | Decision | Rationale |
|---|---|---|---|---|---|---|
| R1 | Pay later anywhere — purchases on the card credit line, repaid after an interest-free period | 5 | 5 | Major Project | **Now** | The core value proposition. It directly solves Lena's biggest pain point — paying before deciding to keep an item — and clearly differentiates the card from debit. It requires significant work across payments, risk and settlement. |
| R2 | Returns net off the balance — refunds automatically matched against what is owed | 5 | 3 | Major Project | **Now** *(moved from Next)* | Without this, R1 does not deliver its promise: a returned item would still be repaid first and refunded later, recreating the debit problem. On card flows refunds arrive linked to the original purchase rather than to a statement, so netting has to be designed explicitly — it does not happen by default. |
| R3 | Pre-filled instant application for existing Riverty users | 4 | 3 | Major Project | **Now** | Lets existing customers apply in minutes using details Riverty already holds, reducing onboarding friction. Must include a CCD2-compliant creditworthiness assessment from day one, since the pilot launches after 20 November 2026. |
| R8 | Instant virtual card and mobile wallet provisioning | 4 | 2 | Quick Win | **Now** | Puts the card in Apple Pay or Google Wallet immediately after approval, so the first purchase does not wait for a physical card. Targets the gap between approval and first use. This is the MVP feature scoped in the PRD. |
| R6 | Partner-merchant rewards | 4 | 2 | Quick Win | **Next** *(moved from Now)* | Supports the merchant-first strategy, but its own rationale says it suits a stage after the core proposition is validated. Design caution: rewarding *card* use at partner merchants would encourage the cannibalisation the guardrail exists to prevent. Rewards should favour Riverty checkout at partners, or card use *outside* the partner base. |
| R7 | Smart reminders before the return window closes and before payment is due | 4 | 2 | Quick Win | **Next** | Helps Lena decide whether to keep or return a purchase, reinforcing "keep it first," and reduces missed payments. Low effort, and directly addresses the payday squeeze. |
| R4 | Automatic repayment on the due date | 3 | 2 | Fill-In | **Later** | Reduces missed payments and reminder fees and improves trust. Kept for later because it changes the product's character towards a standard credit card — which the brief lists as a separate competing idea — and should be a deliberate choice rather than a default. |
| R5 | Anonymised spending insights for merchants | 2 | 5 | Time Sinker | **Cut** | Could strengthen partnerships but gives Lena nothing, and needs significant data engineering and reporting capability. Not suitable for an MVP. |

## Roadmap
### NOW — MVP scope for the friends-and-family pilot
*"Now" is the pilot scope, not a single sprint: R1 alone is a major cross-team project.*
- **R1 Pay later anywhere** — the core proposition.
- **R2 Returns net off the balance** — the mechanism that makes "keep it first" true.
- **R3 Pre-filled instant application** — removes onboarding friction; CCD2-compliant.
- **R8 Instant virtual card and wallet provisioning** — removes the gap between approval and first purchase.

### NEXT — once the core proposition is validated
- **R6 Partner-merchant rewards** — redesigned so it supports rather than cannibalises Riverty checkout.
- **R7 Smart reminders** — return-window and due-date nudges.

### LATER — backlog
- **R4 Automatic repayment** — a deliberate product decision, not a default.

### ✂ Cut List
- **R5 Merchant spending insights** — no user value and high effort.

## Changes from the previous draft
- **R2 moved Next → Now.** R1's promise depends on it; without refund netting the card behaves like debit for anyone who returns an item.
- **R6 moved Now → Next.** Its own rationale said it suits a post-validation stage, and as designed it risked breaching the merchant guardrail.
- **Feature names added** to every ID so the roadmap reads on its own.
- **"Now" clarified** as pilot scope rather than one sprint.
