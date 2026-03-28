# Product Psychology Framework Reference

Full reference for all behavioral science frameworks used in the product-psychology skill.

---

## 1. Fogg Behavior Model (B = MAP)

**Origin**: BJ Fogg, Stanford Persuasive Technology Lab

**Formula**: Behavior = Motivation × Ability × Prompt

All three must occur simultaneously for a behavior to happen. If a target behavior is NOT happening, one of these is below threshold.

### Motivation Levers
- **Pleasure/Pain**: Immediate sensory or emotional response
- **Hope/Fear**: Anticipation of a future outcome
- **Social acceptance/rejection**: What others will think

### Ability Dimensions
- Time: Does the action take too long?
- Money: Does it cost too much?
- Physical effort: Is it physically hard?
- Brain cycles: Does it require too much thinking?
- Social deviance: Does it feel weird or awkward?
- Non-routine: Does it require learning something new?

### Prompt Types
- **Spark**: Motivates and triggers (for low-motivation users) — e.g., "Don't lose your streak!"
- **Facilitator**: Makes it easier and triggers (for low-ability users) — e.g., "One-click checkout"
- **Signal**: Pure trigger for ready users — e.g., a simple notification or reminder

**Design implication**: Identify which element is below threshold. Increasing motivation when ability is the problem wastes effort.

---

## 2. COM-B Model

**Origin**: Michie, van Stralen & West (2011), UCL

**Formula**: Capability + Opportunity + Motivation → Behavior

### Capability
- **Physical capability**: Can the user physically perform the action? (accessibility, motor control)
- **Psychological capability**: Does the user have the knowledge, memory, and decision-making skills?

### Opportunity
- **Physical opportunity**: Is the environment set up to make the action easy? (layout, speed, availability)
- **Social opportunity**: Do social norms and peer behavior support the action?

### Motivation
- **Reflective motivation**: Conscious plans, beliefs, evaluations ("Is this worth doing?")
- **Automatic motivation**: Habits, emotional responses, impulses ("This feels right")

**Design implication**: COM-B is diagnostic first, prescriptive second. Use it to identify what's missing before recommending a solution.

---

## 3. Loss Aversion

**Origin**: Kahneman & Tversky (1979), Prospect Theory

**Core finding**: Losses feel approximately 2× more powerful than equivalent gains.

### Product Applications
- Freemium churn: "You'll lose your saved work" > "Upgrade to save your work"
- Free trial end: "Your Pro features expire in 3 days" > "Upgrade to keep Pro features"
- Inaction framing: "Teams who don't do X fall behind" > "Teams who do X succeed"
- Cancellation flow: Name every benefit the user is giving up

### Caution
Loss aversion works at the point of decision. Don't use it on discovery/awareness content — it creates anxiety where you want curiosity.

---

## 4. Anchoring Effect

**Origin**: Tversky & Kahneman (1974)

**Core finding**: The first number or piece of information presented becomes the reference point for all subsequent judgments.

### Product Applications
- Price anchoring: Show highest tier first, or show original price before discount
- Decoy pricing: A third, inferior option makes the target option look reasonable
- Feature anchoring: Present comprehensive feature list before asking user to choose a plan
- Value anchoring: Show ROI/outcome value before revealing price

### Caution
Anchors must be credible. Inflated "original prices" that users recognize as fake erode trust.

---

## 5. Scarcity & Urgency

**Origins**: Cialdini (1984), Influence

**Core finding**: People assign higher value to things that are rare or time-limited.

### Types
- **Quantity scarcity**: "Only 2 seats left"
- **Time scarcity**: "Offer ends Friday"
- **Access scarcity**: "Invite only" / "Waitlist"
- **Seasonal scarcity**: "Available this month only"

### Product Applications
- E-commerce: Stock counters, low-inventory badges
- SaaS: Limited-time trial extensions, cohort-based onboarding
- Marketplaces: "3 others are viewing this"

### Ethical rule
Scarcity must be real. Fake scarcity (permanently "only 2 left") destroys trust when users discover it. Use countdown timers only when the deadline is genuine.

---

## 6. Social Proof

**Origin**: Cialdini (1984), Influence

**Core finding**: In situations of uncertainty, people look to the behavior of others to determine the correct course of action.

### Types
- **Numerical proof**: User counts, review counts, usage metrics
- **Expert proof**: Industry awards, press mentions, analyst recognition
- **Celebrity/influencer proof**: Known individuals endorsing
- **Peer proof**: People like me are using this (demographic matching)
- **Certification**: Trust badges, security seals, compliance marks

### Specificity rule
Specific proof outperforms vague proof:
- "Many users love us" → weak
- "4.8/5 from 12,400 verified reviews" → strong
- "Used by 94% of Fortune 500 companies" → strong

### Placement
Put social proof closest to the point of doubt — at the moment users are deciding whether to trust you.

---

## 7. Reciprocity

**Origin**: Cialdini (1984), Influence

**Core finding**: When we receive something of value, we feel a social obligation to give something back.

### Product Applications
- Value-first onboarding: Do work for the user before asking them to do anything
- Free tools and templates: Give before asking for signup
- Personalization upfront: Show you understand the user's situation before asking for commitment
- Unexpected delight: Small gifts, upgrades, or gestures that weren't promised

### Caution
Reciprocity is most powerful when the gift feels voluntary and personalized. Transactional or obligatory "gifts" don't trigger the same response.

---

## 8. Cognitive Load Theory

**Origin**: Sweller (1988)

**Three types of load**:
- **Intrinsic load**: Complexity inherent to the task
- **Extraneous load**: Complexity created by poor design
- **Germane load**: Mental effort that builds understanding

**Design goal**: Reduce extraneous load. Manage intrinsic load through progressive disclosure.

### Load-reduction techniques
- Chunking: Group related information so it's processed as a unit
- Defaults: Remove decisions by choosing the best option for most users
- Progressive disclosure: Only show what's needed for the current step
- Visual hierarchy: Let layout guide attention so users don't have to decide where to look
- Eliminating redundancy: Remove anything that isn't carrying its weight

---

## 9. Hick's Law

**Origin**: Hick (1952), Hyman (1953)

**Formula**: RT = b × log₂(n + 1) — reaction time increases with the log of the number of options

**Practical rule**: Every time you double the number of choices, you add roughly the same amount of time to the decision.

### Product Applications
- Navigation: Limit top-level nav items to 5–7
- Pricing pages: 3 tiers max; highlight recommended option
- CTAs: One primary CTA per screen; secondary actions should recede visually
- Feature lists: Group and categorize rather than enumerate

### Exception
Hick's Law applies to novel decisions. Experts making familiar decisions aren't significantly slowed by more options.

---

## 10. Peak-End Rule

**Origin**: Kahneman, Frederickson, Schreiber & Redelmeier (1993)

**Core finding**: People remember and evaluate experiences based on the emotional peak and the ending — not the total or average experience.

### Product Applications
- Onboarding: Design a memorable "aha moment" within the first session
- Checkout: The order confirmation page is the end of the purchase experience — make it joyful
- Error recovery: How an error is resolved matters more than the error itself
- Subscription cancellation: The last message a churning user receives shapes their likelihood to return
- Empty states: First-run experiences with no content should be warm and inviting, not blank

---

## 11. Sunk Cost Effect

**Origin**: Arkes & Blumer (1985)

**Core finding**: People continue investing in something because of past investment, not future value.

### Product Applications
- Multi-step forms: Progress bars show what's been invested ("You're 60% done")
- Gamification: Streaks, points, and levels create sunk cost that increases retention
- Onboarding: Early wins that feel like investment
- Trials: "You've set up 4 of 5 integrations — complete your setup" keeps users coming back

### Ethical consideration
Sunk cost can be manipulative if used to keep users in products that no longer serve them. Use it to help users reach genuine value, not to trap them.

---

## 12. Goal Gradient Effect

**Origin**: Hull (1932); replicated in digital contexts by Kivetz, Urminsky & Zheng (2006)

**Core finding**: Motivation and effort increase as people get closer to completing a goal. The closer the finish line, the faster they run.

### Product Applications
- Progress indicators: Show completion percentage — users work harder once past 50%
- Loyalty programs: Accelerate reward earning near the threshold ("Just 2 more purchases for free shipping")
- Onboarding completion: "You're 80% set up" is more motivating than "You've done 4 of 5 steps"
- Gamification: Badges and levels that feel within reach drive more engagement than distant rewards
- Re-engagement: "You're almost there" emails outperform generic "come back" nudges

### Relationship to Sunk Cost
Sunk Cost pulls users back based on what they've *already invested*. Goal Gradient pulls them forward based on *proximity to the finish*. Use both together in multi-step flows.

---

## 13. Zeigarnik Effect

**Origin**: Bluma Zeigarnik (1927)

**Core finding**: People remember incomplete tasks more vividly than completed ones. Unfinished business creates a persistent cognitive tension.

### Product Applications
- Abandoned cart recovery: Users remember what they left behind — recovery emails should reference the specific items
- Progress saves: "You were working on X — pick up where you left off" is more compelling than a generic re-entry prompt
- Onboarding checklists: Partially complete checklists create pull to finish; fully empty or fully complete lists do not
- Notification strategy: Reference the specific unfinished action, not a generic reminder
- Streak preservation: Broken streaks create Zeigarnik tension — a "restore your streak" offer works because the gap feels incomplete

### Relationship to Sunk Cost & Goal Gradient
Sunk Cost = past investment. Goal Gradient = proximity to finish. Zeigarnik = the discomfort of *incompleteness itself*. All three are distinct mechanisms that can stack.

---

## 14. Endowment Effect

**Origin**: Thaler (1980); Kahneman, Knetsch & Thaler (1990)

**Core finding**: People ascribe more value to things simply because they own or feel they possess them. The mere sense of ownership increases perceived worth.

### Product Applications
- Free trials: Users who have "used" a product feel they own it — removing access feels like a loss, not just a missed gain
- Personalized workspaces: Dashboards, folders, and settings users have configured feel like "theirs," increasing churn cost
- Data portability framing: "Your data, your history, your contacts" frames the product as something the user owns
- Cancellation flows: Name the specific things the user has built up ("Your 47 saved items, your custom reports, your team's history")
- Onboarding investment: The more users configure and personalize early, the higher the perceived ownership — and retention

### Relationship to Loss Aversion
Loss Aversion is about *potential* future losses. The Endowment Effect is about *current* possession feeling. A user who hasn't tried the product yet can experience Loss Aversion but not Endowment Effect. Both activate powerfully together once a trial is underway.

---

## 15. Framing Effect

**Origin**: Kahneman & Tversky (1981)

**Core finding**: The same information, presented in different ways, leads to systematically different decisions. People don't evaluate options in absolute terms — they evaluate them relative to how they're presented.

### Framing types

**Gain vs. Loss framing**
- "Save 20%" vs. "Don't lose 20%" — loss frame typically more persuasive (see Loss Aversion)
- "97% uptime" vs. "Less than 1% downtime" — equivalent, but the first feels positive and the second emphasizes failure

**Attribute framing**
- "95% fat-free" vs. "Contains 5% fat" — identical, but first is perceived as healthier
- "99% of users succeed" vs. "1 in 100 users fail" — same data, opposite emotional weight

**Risky choice framing**
- Certain gain: "Get $50 for free" vs. Risky gain: "50% chance of getting $100" — most users prefer certain gain
- Certain loss: "Pay $50" vs. Risky loss: "50% chance of paying $100" — most users prefer the risky option to avoid the certain loss

### Product Applications
- Pricing: Frame cost as daily cost ("Less than a coffee a day") vs. annual total
- Features: Frame the *outcome* not the *mechanism* — "Ship faster" not "CI/CD pipeline"
- Onboarding: Frame required steps as gaining capability, not completing admin tasks
- Error messages: Frame recovery as gain ("Let's get you back on track") not loss ("Your session expired")
- Risk disclosure: Frame security features as protection gained, not threats avoided

---

## 16. Hyperbolic Discounting (Present Bias)

**Origin**: Ainslie (1975); Laibson (1997)

**Core finding**: People discount future rewards at a much higher rate than rational models predict — and disproportionately favor immediate rewards over future ones, even when the future reward is much larger.

### The discount curve
Rational discounting is exponential and consistent. Hyperbolic discounting is steeper for near-term delays:
- "£100 today vs. £110 tomorrow" — most choose £100 today
- "£100 in 30 days vs. £110 in 31 days" — most choose £110 in 31 days
The preference reverses when the immediate option is removed. Present Bias is what makes users say "I'll set that up later" — and then never do.

### Product Applications
- Onboarding activation: Offer an immediate reward (insight, template, result) before asking users to do work
- Trial conversion: Emphasize what they lose *right now* if they don't upgrade, not long-term ROI
- Feature adoption: Make the first-use reward immediate — don't front-load setup before showing value
- Subscription: Monthly framing with immediate cancellation rights lowers commitment barrier vs. annual
- Habit formation: Build in immediate feedback loops (daily check-ins, instant summaries) rather than promising future outcomes

### Caution
Features that rely purely on future value (e.g., analytics that "pay off over time") will consistently underperform features with immediate feedback. Either front-load the reward or simulate it.

---

## 17. IKEA Effect

**Origin**: Norton, Mochon & Ariely (2012)

**Core finding**: People place disproportionately high value on things they have partially created or assembled themselves, regardless of the quality of the output.

### Product Applications
- Onboarding personalization: Let users configure their workspace, choose preferences, and make small decisions early — they'll value the product more
- Templates and customization: Giving users a starting point they then modify creates more ownership than a fully built solution
- Collaborative setup: Wizards that ask for input ("Tell us about your goals") feel like co-creation, not interrogation
- User-generated content: Products where users create content (playlists, boards, workflows) have higher retention because of perceived co-authorship
- Interactive onboarding: Replace passive walkthroughs with user-driven exploration — "click here to try it" beats "watch this"

### Design implication
The IKEA Effect is fragile: it requires that users *complete* the creative act. Partially built things that users abandoned don't generate the effect. Design so that every configuration step reaches a satisfying conclusion.

---

## 18. Affect Heuristic

**Origin**: Slovic, Finucane, Peters & MacGregor (2002)

**Core finding**: People's current emotional state shapes their judgments of risk, benefit, and value. When feeling positive, users perceive higher benefit and lower risk. When feeling negative, they perceive lower benefit and higher risk.

### Product Applications
- Error recovery: The tone and design of error states directly affects conversion *after* the error — a warm, confident error message restores positive affect and keeps users moving
- Loading states: Dead time during loading (no feedback, no progress) creates negative affect that taints the subsequent experience
- Onboarding delight: Small moments of unexpected delight (animations, encouraging copy, progress celebrations) prime users for higher perceived value
- Pricing pages: Users in a frustrated or confused state will perceive higher risk from paying — reduce friction *before* the pricing page
- Trust signals: Visual warmth, friendly copy, and human photography raise positive affect before a commitment decision

### Relationship to Peak-End Rule
Peak-End Rule determines what users *remember* about an experience. Affect Heuristic determines what they *decide* moment-to-moment. Both matter: positive affect at decision points drives conversion; positive peaks and endings drive memory and return.

---

## 19. Variable Reward

**Origin**: Skinner (1938); applied to digital products by Eyal (2014) in Hooked

**Core finding**: Rewards that arrive unpredictably produce stronger and more persistent behavior than fixed, predictable rewards. The uncertainty itself is motivating.

### Types of variable reward
- **Variable reward of the tribe**: Social validation that varies (likes, comments, reactions) — quantity and quality are unpredictable
- **Variable reward of the hunt**: Search results, feeds, and discovery where content value varies — users scroll because the next item *might* be great
- **Variable reward of the self**: Task completion and personal mastery where the sense of accomplishment varies with challenge

### Product Applications
- Notification timing: Don't batch all notifications — staggered, unpredictable delivery increases open rates
- Feed and discovery: Algorithmic ranking should surface unexpectedly relevant content, not just chronological or perfectly predicted content
- Gamification: Loot boxes, random unlocks, and surprise rewards outperform predictable reward schedules
- Onboarding: Occasional delighters ("You discovered X!") create variable reward of self
- Email subject lines: Curiosity-gap subjects create variable reward of the hunt

### Ethical consideration
Variable reward is one of the most powerful engagement mechanics and one of the most abused. It can create compulsive use patterns. Use it to surface genuine value, not to manufacture engagement through uncertainty alone.

---

## 20. Commitment & Consistency

**Origin**: Cialdini (1984), Influence; Festinger (1957), Cognitive Dissonance

**Core finding**: Once people make a commitment — especially publicly or in writing — they feel internal and external pressure to behave consistently with it. Small commitments prime larger ones.

### The ladder of commitment
Small ask → Medium ask → Large ask. Each agreement makes the next one more likely because users want to stay consistent with their self-image as "someone who said yes."

### Product Applications
- Onboarding micro-commitments: "What's your #1 goal?" at signup primes users to act in service of that stated goal
- Progress declarations: "I want to [learn Spanish / lose 10kg / ship faster]" creates consistency pressure to follow through
- Social commitment: Sharing a goal publicly (within the product or externally) dramatically increases follow-through
- Opt-in flows: Small yes (accepting cookies, allowing notifications) lowers threshold for the next ask
- Trials: Users who configure their account feel committed to the outcome — don't let trials start blank

### Relationship to Sunk Cost
Sunk Cost is about past *investment*. Commitment & Consistency is about past *statements*. Both create psychological lock-in, but through different mechanisms: investment vs. identity.

---

## 21. Decision Fatigue

**Origin**: Baumeister et al. (1998); Danziger, Levav & Avnaim-Pesso (2011)

**Core finding**: The quality of decisions deteriorates after a long sequence of decision-making. Fatigued decision-makers default to the easiest available option — which is often "no" or the status quo.

### Product Applications
- Form design: Don't stack too many decisions in a single form session — break into stages, use progressive disclosure
- Onboarding sequencing: Front-load decisions that require genuine thought; put low-stakes decisions at the end
- Pricing pages visited late in the session: If users reach pricing after extensive browsing, conversion will be lower — reduce decision load earlier in the funnel
- Default states: When decision fatigue is likely, strong defaults with an opt-out perform better than opt-in choices
- Navigation depth: Deep navigation requiring many sequential choices before reaching a destination creates compounding fatigue

### Relationship to Cognitive Load
Cognitive Load is about *complexity within a moment*. Decision Fatigue is about *depletion across time*. A simple decision repeated many times causes Decision Fatigue; a single complex decision causes Cognitive Load. Both result in avoidance or poor choices, but require different fixes.
