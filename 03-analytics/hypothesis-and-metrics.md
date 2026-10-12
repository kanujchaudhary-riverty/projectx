# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** Lena, a 32-year-old salaried employee in Cologne on a middling income with no real financial cushion, who shops mostly on her phone.

- **Goal , what this user is ultimately trying to achieve:** To pay only after she has decided to keep the item.

- **Friction / moment of misery , the specific pain blocking their goal:** In a shop, Riverty is not offered, so she pays by debit and the money leaves her account immediately, before she knows whether she will keep what she bought.

- **Current workaround , the external tool or manual process they rely on (M2):** Klarna (app and checkout), which she uses whenever it appears at checkout; PayPal Pay in 3 / Pay in 30 as a fallback; her debit card in physical shops, where no pay-later option exists; and her phone browser, where she may defer the purchase and buy online later instead.

- **Problem Hook , your one-sentence framing of the business crisis (M1):** Riverty's most loyal users carry Klarna and PayPal for everything outside its merchant base — and every month without a card is a month those habits harden around someone else's brand, in the market where the gap is already widest.

- **Value Proposition , the outcome your initiative promised to deliver (M1):** "Keep it first, pay later — anywhere." Lena can use pay-later in stores and beyond partner merchants, with returns netting off her balance before anything is due and one place to see what she owes. Riverty gets a direct, everyday relationship with its users instead of being only a checkout option.

  **Why launch now:** CCD2 (from 20 November 2026) requires a full affordability assessment for every checkout credit purchase, which a card performs once at onboarding instead of on every transaction. Klarna Card grew fivefold in a year and Germany is its largest market. The Mastercard and Paymentology platform is already paid for. And the Amazon Business pilot is absorbing capacity, so the card slips without a committed slot.

## Read your data snapshots
> The course data snapshots were built for the StreamLine and RouteLogic scenarios. For the Riverty case I have used the business-case funnel from the brief instead, and marked the questions that have no Riverty equivalent.

- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** The brief's business case gives a four-step funnel: 5% of existing users convert to a card, 85% are approved, 70% activate, and 5% churn each year. The qualitative pain — wanting pay-later where it is not available — explains why users would *want* the card, but it says nothing about whether they will *activate* it. The 30% of approved users who never activate is where the numbers and the pain diverge: an approved card that sits unused solves nothing. This is why the first experiment targets the step between approval and first purchase.

- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** The business case assumes only 5% annual churn, which I think is optimistic for a card with no proven differentiator — Lena already has Klarna and PayPal on her phone and switching back costs her nothing. The likely risk is not month-0-to-1 churn but non-activation: a user who never makes a first purchase never forms the habit. The pilot therefore measures repeat use in month two, not only first use.

- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** Not applicable to the Riverty case — this snapshot belongs to the StreamLine scenario. The closest Riverty equivalent is the brief's observation that heavy users are the most under-monetised segment, which is the segment Lena represents.

- **Does the low adoption confirm your persona is burdened by tools they don't use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** Not applicable — this snapshot belongs to the RouteLogic scenario. For Riverty, the parallel is that Lena carries several BNPL apps, each with its own due dates, which BaFin's data on users losing track of payments supports.

- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** Not directly applicable. The relevant time gap for Riverty is the one between paying by debit in a shop and receiving a refund after a return — the period in which Lena carries the cost with no cushion.

- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona's friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** Not applicable. The urgency in the Riverty case comes from the competitive data — Klarna Card's growth from 1.3 to 6.5 million active users in a year — rather than from a satisfaction trend.

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** Lena "prefers the money to leave her account only after she has decided to keep the item."

- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:**
  - 36% of BNPL users in Germany have missed a payment deadline in recent months and paid a reminder fee (SCHUFA, April 2025).
  - 14% of BNPL users have lost track of open payments, rising to one in four among users under 30 (BaFin, February 2026).
  - 32% of BNPL users aged 30–45 have paid an instalment late at some point (BaFin, February 2026) — Lena's age band.
  - Riverty's brand preference at e-commerce checkout is around 6% (case brief).

  Together these show two things: users like Lena value control over payment timing, and they are already struggling to manage it across several providers. A single card with returns netting off the balance and clear due dates addresses both.

  *Note: an earlier draft cited "21% of consumers have sufficient reserves" and "47% of users aged 26–39 missed deadlines" from SCHUFA. I could not verify these two figures against the published release, so they are removed until confirmed.*

- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Lena is a 32-year-old salaried employee from Cologne with a middling income and little financial cushion who shops primarily on her phone. She values paying only after she has decided to keep a purchase. In physical stores Riverty is not available, so she pays upfront by debit even when she may return the item. This creates cash-flow pressure she cannot absorb and breaks the consistent "keep it first, pay later" experience she gets online.

- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Let customers pay only for what they decide to keep, even in physical stores where Riverty is not available today.

- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Existing BNPL users make Riverty their everyday payment method. That increases retention through more frequent use, grows revenue through card volume and — mainly — through interest on optional revolving balances, since EU interchange on consumer cards is capped at 0.30%. It reduces churn by building a direct relationship with consumers beyond merchant checkout.

- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** **Active Card Usage Rate** — the share of *approved* cardholders who make at least one card transaction within 30 days of approval.

  *Why approved rather than activated:* measuring from approval captures the users who never activate, which is exactly the step where the business case's 70% assumption is most likely to break.

- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Two guardrails.
  1. **Merchant guardrail:** Riverty BNPL share of cardholders' purchases at Riverty partner merchants must not drop by more than 2 points versus non-cardholders. This catches cannibalisation — a card purchase at a partner merchant earns Riverty only capped interchange, materially less than the merchant fee on a BNPL checkout.
  2. **Credit guardrail:** on-time repayment rate of at least 98% of payments due. Measured per payment due, not per user ever late — so it is consistent with external data showing a third of users have missed at least one payment at some point.

- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** **12 weeks after the friends-and-family launch**, or once 500–1,000 cardholders have been approved, whichever comes first. Twelve weeks is needed because the first repayments only fall due after the interest-free period, so the credit guardrail cannot be read earlier.

  **Minimum thresholds to scale:**
  - Active Card Usage Rate of at least 70% — this directly tests the brief's 70% activation assumption.
  - At least 60% of month-one active users transact again in month two — a signal that a habit is forming.
  - At least 30% of active users make at least one in-store transaction — validating "pay later anywhere" specifically.
  - Both guardrails held.

  **Pivot** if usage is healthy but in-store use is below 30% — the card is being used as an online convenience, which competes with Riverty's own checkout rather than extending it. **Kill** if Active Card Usage Rate stays below 50% after wallet provisioning has been tested, or if the credit guardrail is breached.

  *How these numbers relate:* the 75% target in the experiment plan is the ambition for one-tap wallet provisioning; the 70% here is the minimum the product as a whole must reach to continue.

- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on qualitative evidence that users like Lena want money to leave their account only after deciding to keep an item, and quantitative evidence that 14% of German BNPL users have lost track of payments while Riverty holds only 6% checkout brand preference, we believe that enabling "keep it first, pay later" everywhere for Lena — a 32-year-old salaried employee in Cologne with no financial cushion — will make Riverty part of her everyday spending, as measured by an Active Card Usage Rate of at least 70% within 30 days of approval. We will protect partner-merchant BNPL share and an on-time repayment rate of at least 98%, and make a go/no-go decision 12 weeks after the friends-and-family launch.

## Sources
- SCHUFA, "One in three BNPL users has already missed a payment deadline" (10 April 2025) — https://www.schufa.de/en/newsroom/press-release/schufa-umfrage-jeder-dritte-bnpl-nutzer-hat-schon-eine-bezahlfrist-verpasst/index.jsp
- BaFin, "Buy now, pay later: one in seven people lose track of payments" (February 2026) — https://www.bafin.de/SharedDocs/Veroeffentlichungen/EN/Fachartikel/2026/fa_bj_260202_bnpl_buy_now_pay_later_en.html
- Klarna Card growth: PYMNTS, Klarna Q2 2026 — https://www.pymnts.com/earnings/2026/klarna-card-users-hit-6-5-million-but-stock-plunges-on-lower-outlook/
- EU interchange cap: Regulation (EU) 2015/751 — https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX%3A32015R0751
