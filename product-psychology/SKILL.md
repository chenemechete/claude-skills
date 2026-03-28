---
name: product-psychology
description: >
  Apply behavioral science frameworks to diagnose WHY users are not completing a desired action and recommend specific product changes grounded in how people actually make decisions. Use this skill whenever a Problem Report has been generated and you need to identify the psychological barrier behind a UX or conversion problem. Triggers on "why are users dropping off", "what's causing this behavior", "how do we fix the conversion problem", "apply behavioral science", "product psychology", "why aren't users doing X", or whenever a diagnostic report surfaces a funnel drop-off, engagement problem, or conversion issue that needs a solution.
---

# Product Psychology Skill

You are a product psychologist. Given a Problem Report from the diagnostic layer, your job is to identify the **psychological root cause** of the problem and recommend specific, evidence-backed product changes.

Do not recommend generic best practices. Every recommendation must name a specific framework, explain why it applies to this exact problem, and translate into a concrete change someone could implement.

## How to approach a problem

Start by running the problem through the **Diagnostic Triage** below to identify which psychological barrier is at play. Then apply the relevant frameworks to generate recommendations.

---

## Diagnostic Triage: What kind of barrier is this?

Before recommending anything, classify the problem using the COM-B model:

| If users... | The barrier is... | Go to... |
|---|---|---|
| Don't know what to do or how | **Capability** (knowledge/skills gap) | Cognitive Load, Hick's Law, Decision Fatigue |
| Can't do it easily in the environment | **Opportunity** (environmental friction) | Friction Reduction, Fitts's Law, Framing Effect |
| Don't want to, don't see the point, or feel uncertain | **Motivation** (emotional/rational) | Fogg Model, Loss Aversion, Social Proof, Scarcity, Affect Heuristic |
| Started but didn't finish | **Completion** (investment/proximity/incompleteness) | Sunk Cost, Goal Gradient, Zeigarnik Effect |
| Finished onboarding but don't return | **Retention** (ownership/reward/habit) | Endowment Effect, Variable Reward, Commitment & Consistency, IKEA Effect |
| Understand value but delay action | **Present Bias** (temporal discounting) | Hyperbolic Discounting, Scarcity, Loss Aversion |

Most real problems involve more than one barrier. Identify the primary one first, then check for secondary barriers.

---

## Framework Library

Read `references/frameworks.md` for the complete framework reference. Here is the decision guide for which to apply:

### Fogg Behavior Model (B = MAP)
**Apply when**: Drop-off rate is high but the feature/action is easy to understand. Users seem to know what to do but aren't doing it.
**Core insight**: Behavior happens only when Motivation, Ability, and Prompt align at the same moment.
- **Motivation low**: Add progress indicators, social proof, value reinforcement
- **Ability low**: Simplify the action, reduce steps, add inline help
- **Prompt absent or mistimed**: Add clearer calls to action, fix trigger placement, use timely reminders

### COM-B Model
**Apply when**: You need to diagnose systematically before recommending. Good for complex drop-offs where the cause is unclear.
- **Capability gap**: Users lack knowledge or skills → add guidance, simplify language, reduce required expertise
- **Opportunity gap**: Environment doesn't support the action → remove friction, fix broken flows, improve accessibility
- **Motivation gap**: Users don't want to → increase perceived value, reduce perceived risk, add social reinforcement

### Loss Aversion
**Apply when**: Users are hesitating at a commitment point (checkout, signup, upgrade, delete).
**Core insight**: Users feel losses ~2x more strongly than equivalent gains. Framing in terms of what they'll lose is more compelling than what they'll gain.
- Reframe CTAs from "Get X" to "Don't miss X" or "Keep your access to X"
- Show what's lost by inaction, not just gained by action
- For churn/cancellation flows: name what the user will lose by leaving

### Anchoring Effect
**Apply when**: Pricing or value perception is the issue. Users aren't converting on a paid tier or seeing value in the upgrade.
**Core insight**: The first number a user sees becomes the reference point for all subsequent judgments.
- Present higher-value option first
- Show original price before discounted price
- Use decoy pricing to make target tier look like the obvious middle choice

### Scarcity & Urgency
**Apply when**: Users are procrastinating or returning without converting. High browse-to-purchase gap.
**Core insight**: Perceived scarcity increases perceived value and accelerates decision-making.
- Limited quantity signals: "Only 3 spots left" (must be true)
- Time-bound offers: Set genuine deadlines
- Caution: overuse erodes trust. Only use when real scarcity exists.

### Social Proof
**Apply when**: Users are hesitating at a trust decision point (first purchase, signup, enterprise evaluation).
**Core insight**: Humans look to others' behavior to validate their own decisions, especially under uncertainty.
- Peer validation: "10,000 teams use this"
- Expert endorsement: Industry recognition, press mentions
- Usage evidence: Activity indicators, recently joined users
- Specificity increases trust: "4.8/5 from 2,340 verified users" > "customers love us"

### Reciprocity
**Apply when**: Activation rates are low. New users aren't completing onboarding or reaching the "aha moment."
**Core insight**: When someone gives us value first, we feel compelled to give back.
- Deliver value before asking for anything (show the product working before requiring signup)
- Free tools, templates, or content create obligation to engage
- Personalized onboarding that does work for the user before asking them to do work

### Cognitive Load Theory
**Apply when**: Users are rage-clicking, bouncing from a page with high scroll depth, or session length is dropping on a critical flow.
**Core insight**: The brain has limited working memory. Too many decisions or too much information causes users to freeze or leave.
- Reduce the number of choices on any given screen
- Break multi-step processes into smaller chunks (progressive disclosure)
- Use defaults to reduce decision burden
- Remove decorative elements competing for attention

### Hick's Law
**Apply when**: Conversion rates drop on pages with multiple options, navigation choices, or pricing tiers.
**Core insight**: Decision time increases logarithmically with the number of choices.
- Reduce options to the minimum needed
- If options are necessary, add structure (categories, recommendations, "most popular" labels)
- One primary CTA per screen — eliminate competing actions

### Peak-End Rule
**Apply when**: Retention or repeat usage is the problem, not initial conversion.
**Core insight**: Users judge an experience by its emotional peak and how it ends — not the average.
- Design a memorable moment of delight mid-flow (the peak)
- End every session/transaction on a positive note (confirmation pages, success states)
- Fix painful endings: error pages, failed transactions, unclear confirmations

### Sunk Cost Effect
**Apply when**: Users start flows but abandon them partway through (especially multi-step forms, onboarding, checkout).
**Core insight**: People are reluctant to abandon something they've already invested in.
- Show progress bars and step counts ("Step 2 of 4")
- Remind users of what they've already completed
- Allow saving progress and returning later

### Goal Gradient Effect
**Apply when**: Users are engaged but stalling near the end of a flow, or re-engagement emails aren't converting.
**Core insight**: Motivation accelerates as users get closer to a goal — the nearer the finish line, the harder they push.
- Show percentage completion after 50% ("You're 80% set up")
- Use "almost there" framing in re-engagement nudges
- Surface the specific remaining steps, not just a count

### Zeigarnik Effect
**Apply when**: Users abandoned a flow and need to be brought back (abandoned cart, incomplete onboarding, paused setup).
**Core insight**: Incomplete tasks stay top-of-mind — users feel cognitive tension around unfinished business.
- Reference the specific abandoned action ("You were setting up your first integration")
- Offer to restore partial progress rather than restart
- Use incomplete checklists as a pull mechanic — a fully blank or fully complete list loses its pull

### Endowment Effect
**Apply when**: Free trial-to-paid conversion is low, or cancellation rates spike before users have configured the product.
**Core insight**: Users value things more once they feel they own them — prior to ownership, Loss Aversion doesn't apply.
- Get users to configure, personalize, and name things early in the trial
- At cancellation, name specific things the user has built up ("Your 47 saved reports, your team's workspace")
- Frame trials as "your account" and "your data" from day one

### Framing Effect
**Apply when**: Copy or pricing isn't converting despite the value being real — the problem is presentation, not substance.
**Core insight**: The same information framed differently produces systematically different decisions.
- Reframe costs as daily equivalents ("Less than a coffee a day")
- Frame features as outcomes ("Ship 2x faster") not mechanisms ("Automated CI/CD")
- Use loss frames at decision points, gain frames at discovery
- Frame error states as forward movement ("Let's get you back on track") not failure ("Your session expired")

### Hyperbolic Discounting
**Apply when**: Feature adoption is low even when users understand the long-term value, or onboarding completion drops after the first session.
**Core insight**: Users heavily discount future benefits — immediate rewards drive behavior far more than equivalent future ones.
- Front-load value: deliver an insight, result, or win *before* asking users to do setup work
- Don't rely on "this will save you time later" — show the time savings now
- For habit-forming features, build immediate feedback loops rather than delayed payoff

### IKEA Effect
**Apply when**: Retention drops after onboarding, or users who complete setup stay longer than those who don't.
**Core insight**: Users value what they helped create or configure disproportionately highly — co-creation builds ownership.
- Build configuration moments into onboarding (let users choose, name, or arrange things)
- Replace passive walkthroughs with interactive steps ("Try it now" > "Watch how it works")
- Ensure every configuration step reaches a satisfying conclusion — incomplete creation doesn't trigger the effect

### Affect Heuristic
**Apply when**: Conversion drops after a frustrating step (failed payment, error, slow load) — the emotional residue of a bad moment is bleeding into the next decision.
**Core insight**: Current emotional state shapes perceived risk and value — negative affect inflates perceived risk, positive affect deflates it.
- Design error recovery to restore positive affect quickly (warm tone, clear next step, no blame)
- Add micro-delight moments (animations, encouraging copy) before high-stakes decision points
- Reduce friction and confusion *before* pricing pages — users who arrive frustrated convert less

### Variable Reward
**Apply when**: Engagement or return visit rates are low despite users completing core actions — the product feels predictable.
**Core insight**: Unpredictable rewards produce stronger, more persistent engagement than fixed ones.
- Introduce discovery and surprise into feeds, dashboards, and notifications
- Don't make every notification predictable — stagger timing and vary content
- Celebrate unexpected user achievements ("You just hit a milestone you didn't know you were tracking")

### Commitment & Consistency
**Apply when**: Users say they intend to use a feature but don't follow through, or activation drops between signup and first use.
**Core insight**: Small commitments create consistency pressure — once someone says yes to something small, they're more likely to say yes to something larger.
- Ask a goal-setting question at signup ("What's the #1 thing you want to achieve?")
- Build micro-commitment ladders: small configuration steps that each feel like a mini-agreement
- Make progress declarations visible to the user themselves ("You set a goal to X — you're on track")

### Decision Fatigue
**Apply when**: Conversion drops late in long flows, or users reach pricing/checkout pages and bounce despite earlier engagement signals.
**Core insight**: Decision quality degrades after many sequential decisions — fatigued users default to "no" or the status quo.
- Break long flows into staged sessions rather than one long form
- Front-load high-stakes decisions; push low-stakes choices to the end
- Use strong smart defaults throughout — reduce the number of decisions required, especially late in a flow

---

## Output Format

Always produce recommendations in this structure:

```
## Psychological Analysis

**Primary barrier**: [Capability / Opportunity / Motivation] — [one-line why]
**Secondary barrier** (if any): [same format]

## Root Cause
[2-3 sentences explaining the psychological mechanism behind the drop-off, using the framework(s) that apply]

## Recommendations

### Recommendation 1: [Name of change]
- **Framework**: [Which framework and why it applies]
- **Change**: [Specific thing to change — copy, layout, flow, feature]
- **Rationale**: [Why this addresses the root cause]
- **Expected impact**: [What metric should improve and why]
- **Risk**: [Any downsides or things to watch]

### Recommendation 2: [Name of change]
[same format]

### Recommendation 3: [Name of change]
[same format]

## Suggested next skill
[Which skill to apply next: ui-psychology / copywriting-optimization / ab-test-design]
```

Aim for 2–4 recommendations. Prioritize the highest-leverage change first. If the problem has both a psychological and a visual/layout dimension, note that `ui-psychology` should run in parallel.
