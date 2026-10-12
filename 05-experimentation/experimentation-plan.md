# A/B Experiment Brief, Riverty business-unit case

## Parameters
| Parameter | Decision |
|---|---|
| Feature under test | One-tap Apple Pay / Google Wallet provisioning of the instant virtual Mastercard, offered on the card activation confirmation screen immediately after approval (R8) |
| Persona | Lena: 32, salaried, Cologne, phone-first, no financial cushion. In practice, friends-and-family pilot users who match her profile and have been approved for the card |
| Expected outcome | More approved cardholders make a first purchase soon after approval, because the card is already in their wallet at the moment they need it |
| Primary success metric | Active Card Usage Rate: share of approved cardholders with at least one card transaction within 30 days of approval |
| Baseline rate | 60% — a placeholder. Replace with the control arm's observed rate, or an issuer benchmark from Paymentology, before the read |
| Guardrail metric | Riverty BNPL share of cardholders' purchases at Riverty partner merchants |
| Guardrail boundary | No more than a 2-point drop versus control (to agree with Finance and the merchant teams) |
| Second guardrail | Early credit signal: share of cardholders who exceed their limit or are declined for insufficient limit in the window. Full on-time repayment is read at the 12-week pilot decision, since first repayments fall due after this experiment ends |
| Minimum Detectable Effect | +15 points (60% → 75%) |
| Sample size per arm | 152 per arm (304 total), at 80% power and 5% significance, two-sided — verified for a 60% to 75% comparison |
| Traffic split | 50 / 50, randomised at the moment of approval |
| Test duration | About 7 weeks: roughly 3 weeks of enrolment plus a 30-day outcome window for each user. Read date fixed at the end of the last cohort's window |
| Significance threshold | p < 0.05 (95%), two-sided |

## Control vs. Variant
- **Control (A):** The user is approved and the instant virtual card is generated, with its details shown in the app. To use it in a shop, they add it to Apple Pay or Google Wallet themselves through the standard wallet flow.
- **Variant (B):** The same flow, with one change: a one-tap "Add to Apple Pay / Google Wallet" button on the activation confirmation screen provisions the card directly, after secure customer authentication.
- **Held constant (isolation check):** Approval criteria and credit limit policy; card terms, pricing and interest-free period; the onboarding content and confirmation screen copy, apart from the button itself; card details visibility in the app; and all marketing and reminder communications. The only difference between arms is the one-tap provisioning button.

## Hypothesis
> I believe that offering one-tap Apple Pay and Google Wallet provisioning on the activation confirmation screen, immediately after approval, will lead more approved cardholders like Lena — a 32-year-old, phone-first, salaried user in Cologne with no financial cushion — to make a first purchase soon after approval, because the card is ready in their wallet at the moment they need it. This will be measured as a +15-point increase in Active Card Usage Rate (the share of approved cardholders making at least one card transaction within 30 days of approval), read after about seven weeks. We will protect Riverty BNPL share at partner merchants throughout the test.

## Shipping criteria
> We will **ship** if Active Card Usage Rate improves by at least +15 points at p < 0.05, two-sided, and Riverty BNPL share at partner merchants does not fall by more than 2 points versus control.
>
> We will **iterate** if the direction is positive but the lift is below +15 points — for example, by testing a provisioning prompt at the first moment the user opens the app in a shop context.
>
> We will **kill** if the primary metric shows no improvement or moves negatively.
>
> The read date is fixed at the end of the last cohort's 30-day window. No results are reviewed before this date.

## Risks to the validity of this test
- **Sample feasibility.** The test needs 304 approved users within about three weeks of enrolment. At the brief's assumed 85% approval rate, that is roughly 360 applicants. If the friends-and-family pool is smaller, extend enrolment rather than lowering the threshold.
- **Contamination.** Friends-and-family participants know each other. Control users may hear about the one-tap button and add the card to their wallet manually and faster than they otherwise would, shrinking the measured difference. Note this as a likely understatement of the true effect.
- **Analysis approach.** Analyse by the arm users were assigned to at approval, including those who never reach the confirmation screen, so the result reflects real-world behaviour rather than only engaged users.
- **Placeholder baseline.** The 60% baseline is an assumption. If the observed control rate differs materially, the sample size should be recalculated before the read.
