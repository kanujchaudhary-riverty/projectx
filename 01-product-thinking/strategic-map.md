# Strategic Discovery Map (Module 1)

> Note: this module's exercise was completed on the course's sample app (a hydration tracker). The reflections on method below are my original answers. The final section applies the same lessons to the Riverty card case.

## Responses
- **Write one feature from the map that, if an engineer asked "why is this a priority for our 12-week roadmap?", you honestly could not give a strategic answer for.:** Smart bottles. If an engineer asked why it is on a 12-week roadmap, my honest answer would be that it was on the map — and that is not a strategy.

  I would rather answer based on customer need and business goal:

  *Customer need:* Do users say forgetting to log is why they quit? If so, auto-logging addresses the real drop-off point. What share of current or target users already own a connected bottle, or would buy one? Is manual logging the top friction in onboarding and day-7 data?

  *Business goal:* If the goal is retention or engagement, smart bottles only matter if they lift it for a meaningful segment.

- **Write one feature that looks "correct" for the app but has zero strategic weight, you have no idea if it helps the company make money or whether a single user actually asked for it.:** A hydration score. A single 0–100 score looks like a natural part of the Insights branch. It sounds smart, makes the dashboard look polished, and any PM would nod at it in a feature review. But there is no evidence anyone asked for it — users want to know whether they hit their goal, and the progress ring already answers that — and there is no link to revenue, retention or conversion.

- **Compare V3 to your Step 1 baseline. What changed, and is the output objectively better, did the AI get smarter, or did your added PM knowledge (JTBD, effort/impact, retention) force it to be useful?:** 
  - *Structure.* The baseline grouped features by type: logging, goals, reminders, insights, devices, engagement. V3 groups by decision: why users care, what is broken, what to build first, how to earn money, and what will make them leave.
  - *Ranking.* Baseline leaves were all equal. V3 marks one-tap logging and adaptive reminders as quick wins and calls the wearable auto-log a big bet that needs proof. The hydration score and smart bottles no longer get a slot by default.
  - *Tensions.* The baseline had none. V3 surfaces three: wearable bet versus quick wins, paywall versus habit growth, and nudging versus annoying users.
  - *User grounding.* Every branch ties back to the target user, so every feature traces back to a problem.

  The AI did not get smarter. My added PM framing forced it to be useful.

- **Key takeaway: how does this prove the PM's role is to think while the AI's role is to execute?:** The first prompt said, in effect, "make a mind map," and the model delivered a tidy, generic one. The third prompt told it who the user is, which lens to use for each branch, and to flag disagreements. Everything that made V3 better was a judgement call made before the model wrote anything.

  The model organises, sorts and formats quickly, but it does not know which problem matters, which trade-off the company should take, or whether a ranking is right. It can point to a paywall dilemma, but the PM has to resolve it using the company's goals and its users.

## Applied to the Riverty card case
- **A feature I could not justify on a 12-week roadmap:** Merchant spending insights (R5). It sounds merchant-friendly, which fits Riverty's merchant-first strategy, but it gives Lena nothing, requires significant data engineering, and no merchant has asked for it. It is cut from the roadmap for that reason.
- **A feature that looks correct but has zero strategic weight:** A customisable card design. Every card launch seems to have one, it demos well, and it would generate enthusiasm in a friends-and-family pilot. But nothing in the brief suggests card design drives Lena's choice of payment method, and it moves none of the metrics that decide the pilot.
- **The same lesson, applied:** The AI could generate a long list of card features in seconds. The strategic work was deciding that the card's value lives in the timing of when money leaves Lena's account, and that most features which do not affect that timing can wait.
