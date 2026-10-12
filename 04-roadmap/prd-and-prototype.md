# PRD & Prototype Sprint (Module 4)

## Pick & scope with MoSCoW
- **The "Now" feature I'm scoping (name + one-line core description):** **R8 — Instant Virtual Mastercard and Mobile Wallet.** Puts the card in Apple Pay or Google Wallet immediately after approval, so Lena can make her first purchase without waiting for a physical card.

- **My finalized Must-Haves (after overriding the AI):**
  1. Instant virtual card generation on approval
  2. Apple Pay and Google Wallet provisioning
  3. Secure customer authentication before provisioning
  4. Card activation confirmation
  5. Real-time card availability — usable for a purchase immediately after provisioning

- **What I demoted from Must → Should/Won't, and why:** **Wallet setup guide (Must → Should).** Helpful for first-time users, but customers can still add the card through the standard Apple Pay or Google Wallet flow. It improves usability but is not essential for completing the first transaction.

### Full MoSCoW
| Priority | Item | Reason |
|---|---|---|
| **Must** | The five items above | Without any one of them, the first purchase cannot happen immediately after approval |
| **Should** | Wallet setup guide | Improves usability; standard wallet flow still works without it |
| **Should** | First-purchase confirmation in the app | Shows Lena where the transaction appears and when it is due — closes the gap the prototype revealed |
| **Could** | Card details viewable in-app for online purchases | Useful for online use, but wallet payment covers the core in-store case |
| **Won't (this MVP)** | Physical card | The point of the feature is to remove the wait for one |
| **Won't (this MVP)** | Additional wallets (e.g. Samsung Pay, wearables) | Apple Pay and Google Wallet cover the target persona |
| **Won't (this MVP)** | Card design customisation | No evidence it affects whether Lena makes a first purchase |
| **Won't (this MVP)** | Cash withdrawal | Adds credit-risk and regulatory complexity with no link to the core proposition |

*The Won't list is deliberate: the brief asks what the first card will intentionally leave out.*

### Dependencies to confirm
- **Wallet tokenisation via Paymentology.** Confirm that Paymentology supports Mastercard token provisioning to Apple Pay and Google Wallet for this programme.
- **Wallet provider agreements.** Issuers typically need their own agreement with Apple and Google before cards can be provisioned. Lead time can be significant and should be checked first, as it can block the feature independently of the build.
- **CCD2 compliance at onboarding.** Approval precedes provisioning, so the creditworthiness assessment and pre-contractual information in R3 must be in place before R8 can be used by any real customer.

## Generate your Simplified PRD
- **One thing my PRD makes explicit that a vague brief would have missed:** It makes explicit that the feature's purpose is to remove the delay between card approval and the first purchase — not "add wallet support" in general. It defines measurable functional requirements, the success metric, and scope boundaries, so the team knows exactly what to build and, equally, what not to build to validate the MVP hypothesis.

## Prompt-to-prototype sprint
- **Where did the prototype reveal a gap in my PRD logic? (what I had to update):** The PRD treated the first purchase as an *event*, not a *story*. Functional requirement FR6 said "immediate payment readiness," and the prototype simulated a purchase — but neither said what happens next. I added a first-purchase story: where the transaction appears in the app, what the notification says, and when the amount falls due. For Lena this matters most, because "keep it first, pay later" only feels real if she can see straight away that nothing has left her account.

- **My prototype, as a link or a screenshot (publish or share from your tool; in Lovable that is Share → Share Preview, in Bolt Publish → Web. No share URL? Screenshot the working flow):** https://lovable.dev/preview/X3jjfIjQe0LOnIAsY2avjKW5ke4iTk4t
