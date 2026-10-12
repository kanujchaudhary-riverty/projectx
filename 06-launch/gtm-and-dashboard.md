# GTM Strategy & Success Dashboard

> **Module 6 · ★ Deliverable 6.** Repo file `06-launch/gtm-and-dashboard.md` — part of your submission.
> It becomes the **GTM Strategy & Success Dashboard** slide of your Module 6 final deck.

## Go-to-market summary

**Strategy: a deliberately small, closed launch to existing Riverty users in Germany, designed to learn rather than to scale.** The friends-and-family MVP is not a marketing launch. Its job is to test the riskiest assumptions in the business case — activation, repeat use and in-store adoption — before Riverty spends anything on acquisition.

**Who we launch to.** Existing Riverty BNPL users who match Lena's profile: frequent users, phone-first, already repaying on time. We start with Riverty's own users rather than new customers because the relationship already exists, the application can be pre-filled, and Riverty's 6% brand preference means cold acquisition would be expensive and uninformative.

**Launch size and phasing.**
| Phase | Who | Size | Purpose |
|---|---|---|---|
| 0 · Internal alpha | Riverty employees | Small group | Test the end-to-end flow — application, card, wallet, purchase, return, repayment — before any customer sees it |
| 1 · Friends and family | Employees' invited contacts matching the persona | ~360 applicants → ~304 approved | Run the one-tap wallet experiment at the required sample size |
| 2 · Partner store pilot | Shoppers at one retail partner, a few Cologne stores, against comparable control stores | A few stores | Test real in-store demand, with the partner as the distribution channel for the card |
| 3 · Heavy-user invite | Selected frequent Riverty users, invited in-app | Up to 500–1,000 approved cardholders | Reach the pilot decision sample and test behaviour outside Riverty's own network |

**Channels.**
- **In-app invitation in the Riverty app** — the primary channel. It reaches users at the moment they are already managing a Riverty purchase, and allows a pre-filled application.
- **Personal invitation links** for the friends-and-family phase.
- **Email** to selected heavy users in phase 2, as a reminder rather than the main channel.
- **No paid media** at this stage. Paid acquisition would add cost and noise before we know whether the card retains users.

**Message.** *"Keep it first, pay later — anywhere."* Lead with the in-store moment — tap in any shop, nothing leaves your account until it's due, and returns reduce what you owe. Not with rewards or design, which the MVP deliberately leaves out.

**Merchant communication.** Before phase 2, brief Riverty's key partner merchants that the card extends Riverty beyond their checkout rather than competing with it, and that Riverty is monitoring BNPL share at partner merchants as a launch guardrail. This protects the merchant-first strategy and avoids partners hearing about the card from their customers first.

**Launch gates — nothing goes to customers until all are met.**
- CCD2-compliant creditworthiness assessment and pre-contractual information in place, since the launch falls after 20 November 2026
- Legal confirmation of the CCD2 premise behind the proposition: that card drawdowns do not each require a fresh assessment
- Apple Pay and Google Wallet issuer agreements signed and provisioning confirmed with Paymentology
- Refund netting working end to end, since "keep it first" depends on it
- A committed engineering and operations slot once the Amazon Business pilot is stable

**Decision point.** 12 weeks after the friends-and-family launch, or once 500–1,000 cardholders are approved: **scale** to a broader in-app rollout, **pivot** the proposition, or **stop**, against the thresholds below.

## In-store partner pilot

**The idea: partner for distribution, not acceptance.** If a partner's job were to accept Riverty pay-later at its tills, no card would be needed — and every merchant would need its own integration. Instead, the partner's job is to put the card in Lena's hand inside the store. She scans a QR code on the shelf or at the till, applies on her own phone with one CCD2 assessment, gets the card in her phone wallet within minutes, and taps to pay — at that till and everywhere after. This gives the 30% in-store target something that actually drives it, and brings Riverty's merchant-first strategy into the launch instead of bypassing it.

**Candidate partners in Germany.**
| Retailer | Fit | Why |
|---|---|---|
| **TK Maxx** | **Best fit** | 190 stores in Germany, including central Cologne. A store-led treasure hunt with impulse finds and frequent returns — exactly where "keep it first" matters most. In-store volume is new for Riverty, so there is nothing to cannibalise. To verify: any existing card or pay-later arrangement. |
| **IKEA** | Proof of model, not a partner | Already runs the IKEA Family credit card with its partner bank Ikano, including conversion of purchases from €99 into 0% financing, and customers can apply by smartphone in any store. This proves retailer-anchored cards with in-store sign-up work in Germany — but IKEA has no gap for Riverty to fill, and Klarna already covers invoice online. |
| **Lidl** | Weak fit | Runs its own payments: Lidl Pay inside Lidl Plus, processed by Schwarz Payment Solutions. Small grocery baskets, and pay-later on groceries is a responsible-lending and reputational risk under CCD2. Possible later for non-food promotions only. |

**A competitor has already moved.** In July 2026 Lululemon rolled out Klarna in-store across Germany via Adyen: shoppers scan a QR code at checkout and pay in the Klarna app, with no application form or separate card. It proves the demand is real — but it requires an integration for every merchant. Riverty's card needs none, so the partner becomes a launch channel rather than a technical dependency.

**Why a partner would say yes.** In-store pay-later on terminals it already has, at card acceptance cost rather than a BNPL fee, plus a merchant-funded launch incentive that stays in-store only.

**Watch.** If store staff actively promote credit applications, the retailer may take on regulated credit-intermediary obligations — self-service QR reduces this, but Legal must confirm. A partnership takes months to agree, so it follows the friends-and-family phase rather than blocking it.

**Sources:** TK Maxx Germany press centre (190 stores) — https://mediacentre.tkmaxx.de/pressrelease/details/25311 · IKEA Family Kreditkarte — https://www.ikea.com/de/de/customer-service/services/finance-options/ikea-family-kreditkarte-pub3c691320/ · IKEA payment methods — https://www.ikea.com/de/de/customer-service/knowledge/articles/1c14c16b-be77-47b7-90f2-4cc2410803f1.html · Lidl Plus terms (Lidl Pay) — https://www.lidl.de/c/lidl-plus-teilnahmebedingungen/s10005289 · Lululemon × Klarna in-store, FashionNetwork, July 2026 — https://us.fashionnetwork.com/news/Lululemon-rolls-out-klarna-as-a-new-in-store-payment-option-across-germany-and-the-uk,1855326.html

## Success dashboard

| KPI | Baseline | Target | Measurement window |
|---|---|---|---|
| **Active Card Usage Rate** — share of approved cardholders with at least one card transaction | 60% (placeholder; replace with the observed control rate) | ≥70% to scale the pilot; 75% for the one-tap wallet variant | 30 days from approval |
| **Repeat use** — share of month-one active users who transact again in month two | No baseline — new product | ≥60% | Month two after approval |
| **In-store adoption** — share of active users with at least one in-store transaction | 0% — Riverty has no in-store presence today | ≥30% | 12-week pilot |
| **Approval rate** — share of applicants approved | 85% (business case assumption) | Validate the assumption; flag if below 75% | Enrolment period |
| **Partner pilot: in-store sign-ups** — card applications per partner store per week | No baseline — new channel | To set with the partner | Partner pilot |
| **Partner pilot: spend outside the partner** — share of card spend at other merchants | No baseline | Rising over the pilot; a low share means we built a store card | Partner pilot |
| **Guardrail: partner-merchant BNPL share** — Riverty BNPL share of cardholders' purchases at partner merchants | Current share among the same users before card issuance | No more than a 2-point drop | 12-week pilot |
| **Guardrail: on-time repayment** — share of payments due paid on time | Riverty's current BNPL on-time rate | ≥98% | 12-week pilot, from first repayment due |

**How to read the dashboard.** The first three KPIs tell us whether Lena adopts the card, keeps using it, and uses it for the reason it exists — in shops. The two guardrails tell us whether that adoption is costing Riverty its merchant relationships or its credit quality. Strong usage with a breached guardrail is a stop signal, not a success.
