---
name: "saas-growth-retention"
description: "Sub-skill for SaaS growth, retention, and subscription optimization using Human Behavior OS modules. Covers user onboarding, activation, churn prevention, and expansion revenue."
---

# SaaS Growth & Retention Optimization

## 0. Relationship to Parent

This reference inherits all 7 modules, the Master Formula, and quality standards from the parent Human Behavior OS skill. It adds SaaS-specific frameworks, metrics, and behavioral patterns for subscription-based products.

---

## SaaS Behavior Framework

### The SaaS User Behavior Lifecycle

```
Acquisition → Activation → Engagement → Retention → Expansion → Advocacy
```

| Stage | Primary Modules | Key Behavior | Success Metric |
|-------|----------------|-------------|----------------|
| Acquisition | Attention, Need | Sign up / Start trial | Signup rate |
| Activation | Decision, Trust | First value moment | Activation rate |
| Engagement | Emotion, Need | Regular usage | DAU/MAU ratio |
| Retention | Trust, Prediction | Renew / Continue | Retention rate |
| Expansion | Decision, Need | Upgrade / Add seats | NRR, expansion MRR |
| Advocacy | Spread, Emotion | Refer / Review | Referral rate |

---

## Module-Specific SaaS Applications

### Need System → SaaS User Need Map

**SaaS Need Layers:**

| Layer | SaaS Expression | User Type | Example Products |
|-------|----------------|-----------|-----------------|
| L1 Survival | Business continuity, compliance, security | Enterprise | AWS, Okta, Veeam |
| L2 Efficiency | Automation, time-saving, cost reduction | SMB, Teams | Zapier, Notion, Slack |
| L3 Emotion | Team bonding, reduced stress, confidence | Managers | Lattice, Donut |
| L4 Identity | Professional capability, expertise signal | Individuals | GitHub, Figma, Substack |
| L5 Growth | Scale, market advantage, innovation | Leaders | Salesforce, HubSpot, Segment |

**Job Stories Framework (Need + Context + Motivation):**

```
When [situation], I want to [motivation], so I can [expected outcome].
```

Example: "When I'm managing a remote team of 20, I want to see who's overloaded at a glance, so I can redistribute work before deadlines slip."

### Activation → The First Value Moment

**Activation = The moment the user experiences the core value promise**

**Activation Analysis:**

```markdown
## Activation Diagnosis
1. **Value Promise**: [What we promised]
2. **First Value Moment**: [When does the user actually feel it?]
3. **Steps to Value**: [How many steps from signup to value?]
4. **Drop-off Points**: [Where do users quit before activation?]
5. **Time to Value**: [How long does activation take?]
```

**Optimization Strategies:**

| Strategy | Technique | Impact |
|----------|-----------|--------|
| Reduce steps | Eliminate non-essential setup steps | High |
| Template-driven | Pre-populate with realistic data | High |
| Guided flow | Interactive walkthrough, tooltips | Medium |
| Quick win | Deliver a small win in first 5 minutes | High |
| Personalized | Customize onboarding to user's use case | Very High |

### Trust System → SaaS Trust Building

**SaaS Trust Timeline:**

| Time | Trust Source | Implementation |
|------|-------------|----------------|
| Pre-signup | Social proof, authority | Customer logos, G2 reviews, case studies |
| Signup | Low friction, transparency | No credit card, clear pricing |
| Onboarding | Competence demonstration | Guided setup, quick wins |
| First week | Consistency, support | Reliable performance, responsive help |
| First month | Evidence of ROI | Usage reports, milestone celebrations |
| Long-term | Continuous value delivery | Regular updates, feature releases |

**Churn Trust Failure Signals:**

1. **Feature gap** — Key need not met → User questions value
2. **Reliability issues** — Bugs, downtime → Trust erodes
3. **Support neglect** — Slow or unhelpful responses → Feeling abandoned
4. **Price-value mismatch** — Not seeing ROI → Questioning investment
5. **Competitor attraction** — Better alternative appears → Switching consideration

### Decision System → SaaS Upgrade Decision

```
Upgrade Decision = (Additional Value × Confidence in Delivery) - (Additional Cost × Switching Friction)
```

**Expansion Revenue Triggers:**

| Trigger | Behavioral Signal | Intervention |
|---------|-------------------|-------------|
| Feature limit hit | User reaches usage cap | "Upgrade for unlimited" |
| Team growth | New team member added | "Add seats for your growing team" |
| Advanced need | User searches for advanced features | "Pro plan includes advanced analytics" |
| ROI realization | User achieves first major win | "Amplify results with premium" |
| Time savings | User becomes power user | "Save even more time with automation" |

### Emotion System → SaaS User Emotions

**Emotional Journey Map:**

```
Signup: Hope + Skepticism
Onboarding: Frustration → Relief (if smooth) or Frustration → Anger (if bumpy)
First Value: Excitement + Confidence
Daily Use: Boredom (if routine) or Satisfaction (if valuable)
Renewal: Indifference (if low value) or Loyalty (if high value)
Churn Risk: Frustration + Curiosity (about alternatives)
```

**Emotional Intervention Points:**

| Emotion | Intervention | Timing |
|---------|-------------|--------|
| Hope | Reinforce value promise | Signup confirmation |
| Frustration | Proactive support, guidance | During onboarding |
| Excitement | Celebrate milestones, share metrics | After first value moment |
| Boredom | Introduce new features, use cases | After 2-4 weeks of routine use |
| Loyalty | Exclusive access, recognition | Before renewal |
| Curiosity (about alternatives) | Value reinforcement, competitive advantage | Churn risk signals |

### Spread System → SaaS Referral Mechanics

**SaaS Referral Motives:**

| Motive | Program Design | Expected K |
|--------|---------------|-----------|
| Self-interest | "Give $10, get $10" | 0.2-0.4 |
| Helping peers | "Share with your team" | 0.1-0.3 |
| Identity | "Powered by [Product]" badge | 0.05-0.15 |
| Social currency | Early access to beta features | 0.1-0.2 |

### Prediction System → SaaS Churn Forecasting

**Churn Prediction Signals:**

| Signal | Time Before Churn | Confidence | Intervention |
|--------|------------------|------------|-------------|
| Login frequency drop (>50%) | 2-4 weeks | High | Re-engagement email |
| Feature usage decline | 1-3 weeks | Medium | Usage tips, new feature intro |
| Support ticket spike | 1-2 weeks | High | Proactive support outreach |
| No key action in 7 days | 1-2 weeks | Medium | Guided re-onboarding |
| Competitor visit (if detectable) | Days | Very High | Value reinforcement offer |
| Negative NPS/feedback | 1-4 weeks | High | Personal follow-up |

**Retention Score Model:**

```
Retention Score = (Login Frequency × 0.3) + (Feature Depth × 0.25) + (Support Sentiment × 0.15) + (Team Size × 0.15) + (Time Since Signup × 0.15)
```

---

## Common SaaS Scenarios

### Scenario 1: Low Activation Rate

**Diagnosis:**
1. Map the activation path step by step
2. Measure drop-off at each step
3. Identify the "value moment" — is it reachable?
4. Check: Is the value promise matching actual experience?

**Interventions:**
- Shorten time-to-value (target: < 5 minutes)
- Add progress indicators
- Use template/pre-filled data
- Personalize onboarding to use case
- Add in-app guidance (tooltips, walkthroughs)

### Scenario 2: High Churn Rate

**Diagnosis:**
1. Segment churned users by cohort
2. Interview or survey churned users
3. Map churn reasons to Need/Trust/Decision failures
4. Identify the dominant churn driver

**Interventions by Churn Type:**

| Churn Type | Root Cause | Intervention |
|-----------|-----------|-------------|
| Value churn | Core need not met | Improve product, better onboarding |
| Trust churn | Reliability/support issues | Fix bugs, improve support |
| Cost churn | Price too high for value | Show ROI, add value, adjust pricing |
| Friction churn | Too hard to use | Simplify UX, add automation |
| Attention churn | Forgot about product | Re-engagement emails, notifications |

### Scenario 3: Low Expansion Revenue

**Diagnosis:**
1. Analyze usage patterns for upsell signals
2. Map feature adoption across plans
3. Identify power users who need more

**Interventions:**
- Feature-gated upgrade prompts (contextual, not intrusive)
- Usage-based upgrade suggestions
- Team collaboration features (natural expansion)
- Advanced analytics/reports (power user need)

---

## Output Template: SaaS Behavior Profile

```markdown
# SaaS User Behavior Profile

## 1. User Need Map
[Need System output — primary job story, need layers]

## 2. Activation Analysis
- **Current Activation Rate**: X%
- **Time to Value**: X minutes
- **Steps to Value**: X steps
- **#1 Drop-off Point**: [Step where users quit]
- **Recommended Optimization**: [Specific action]

## 3. Trust & Retention Map
[Trust System output with SaaS trust timeline]

## 4. Expansion Decision Model
[Decision System output for upgrade behavior]

## 5. Emotional Journey Map
[Emotion System output for user lifecycle]

## 6. Referral & Advocacy Potential
[Spread System output for SaaS referral]

## 7. Churn Risk Assessment
[Prediction System output with risk scores]

## 8. Recommendations
### Activation Improvements
- [ ] [Action with expected impact on activation rate]

### Retention Interventions
- [ ] [Action with expected impact on retention]

### Growth Levers
- [ ] [Action with expected impact on expansion revenue]

## 9. Key Metrics Dashboard
| Metric | Current | Target | Priority |
|--------|---------|--------|----------|
| Activation Rate | X% | Y% | Critical |
| D7 Retention | X% | Y% | High |
| D30 Retention | X% | Y% | High |
| NRR | X% | Y% | High |
| Churn Rate | X% | Y% | Critical |
| Referral Rate | X% | Y% | Medium |
```
