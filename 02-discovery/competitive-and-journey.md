# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Lena, a 32-year-old salaried employee in Cologne on a middling income with no real financial cushion, who shops mostly on her phone and uses BNPL on most non-trivial purchases.

- **Goal, what is this user ultimately trying to achieve?:** To pay only after she has decided to keep the item.

- **Friction, the main barrier (moment of misery) stopping them from succeeding:** In a shop, Riverty is not offered, so she pays by debit and the money leaves her account immediately, before she knows whether she will keep what she bought.

- **External tools, the outside platforms or tools the user is forced to use:**
  - **Klarna (app and checkout):** the brief says she has it installed and uses it whenever it appears at checkout. The most strongly supported alternative.
  - **PayPal (Pay in 3 / Pay in 30):** also installed, and used as a fallback BNPL option. Also supported by the brief.
  - **Her debit card:** the likely forced choice in a shop, where Riverty is not offered. The brief implies this but does not state it.
  - **Her phone browser and online shops:** where she would buy later if she skips the in-store purchase.

- **The process, the 3 to 5 manual steps the user takes to get the job done:**
  1. Find the item in the shop and realise Riverty is not offered there.
  2. Pay by debit, so the money leaves her account straight away, before she has decided to keep it.
  3. Take it home and decide whether she wants to keep it.
  4. Return it if she does not, going back to the shop or posting it.
  5. Wait for the refund to reach her account, carrying the gap in the meantime with no cushion.

- **Core frustration, the exact moment the process feels most "broken":** The moment she pays by debit in the shop. The money leaves her account before she has decided to keep the item. That reverses the one thing she wants from pay-later, and she has no cushion to absorb it if she changes her mind.

- **The evidence, a specific quote or behavior from the research that proves this:** Her stated preference: she "prefers the money to leave her account only after she has decided to keep the item." This proves the want, and it is exactly what breaks at step 2.

- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** `journey-map.html` (committed alongside this file).

## Competitive landscape

| Alternative | What it offers Lena | Why it matters | The gap Riverty can use |
|---|---|---|---|
| **Klarna Card** | Card that draws from the customer's own funds for everyday spending, with the option to spread the cost of a specific purchase | The direct benchmark. 6.5 million active users across 16 countries, up from 1.3 million a year earlier. Germany is Klarna's largest market by volume | Primarily a debit proposition with optional instalments on chosen purchases — not a pay-later-by-default credit line |
| **PayPal** | Pay in 3 and Pay in 30 in Germany | The payment brand most Riverty users already carry; around 20% of German online transactions in one receipt-panel study | Online-first; no single pay-later-anywhere card proposition in the brief |
| **Instalment card banks** (Santander Zero, Advanzia, TF Bank) | Traditional credit cards with instalment or revolving credit | Already hold the interest-income pool the card business case depends on | Credit-card experience rather than BNPL-native; no relationship with Lena's BNPL behaviour |
| **Scalapay** (Italy) | Virtual Mastercard carrying online BNPL into physical stores | Proof that BNPL-into-stores via a virtual card works | Not active in Germany as a card proposition per the brief |
| **FLOA and Alma** (France) | Instalments paired with their own card issuance | Proof the BNPL-plus-card model works in France | Relevant to a later French expansion rather than the German MVP |
| **Doing nothing different** | Whatever BNPL appears at checkout, or her existing debit card | The most common alternative of all | This is the real competitor: Lena's indifference, not any one brand |

**What the data says about Germany specifically.** Klarna's share of German online payment transactions tripled from 4.5% in H1 2024 to 14.0% in H2 2025, before easing to 11.7% in early 2026 (email-receipt panel, n = 6,953). In its Q2 2026 results, Klarna cut its full-year volume outlook, attributing it largely to weakening discretionary spending in Germany. So the German market is both where Klarna is strongest and where it is currently softest.

**The honest constraint.** Klarna's brand awareness in Germany is 87%. Riverty's brand preference at checkout is around 6%. Riverty cannot win this on brand, and the proposition does not try to. It aims at Riverty's existing users, where the relationship already exists, and competes on the timing of when money leaves Lena's account rather than on awareness.

**Which competitors truly matter for the MVP:** Klarna Card and doing nothing. Klarna sets the bar Lena will compare against; doing nothing is what she will actually choose unless the card gives her a clear reason to switch. PayPal is a fallback behaviour rather than a direct card competitor. The instalment banks matter to the business case, not to Lena's decision.

## Sources
- Klarna Card active users and German outlook: PYMNTS, Klarna Q2 2026 — https://www.pymnts.com/earnings/2026/klarna-card-users-hit-6-5-million-but-stock-plunges-on-lower-outlook/
- Klarna Card product description: Klarna investor news, 19 March 2026 — https://investors.klarna.com/News--Events/news/news-details/2026/Klarna-Card-reaches-5-million-active-customers/default.aspx
- Klarna German online payment share: General Evidence receipt panel — https://www.generalevidence.com/en/insights/consumption/online-shopping/klarna-payment-share-germany-online-2024-2026
- Klarna brand awareness Germany: Analyzify Klarna statistics (2024 data; treat as indicative) — https://analyzify.com/statsup/klarna
- Competitor list and Riverty brand preference: Riverty case study brief
