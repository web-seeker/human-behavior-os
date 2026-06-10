---
name: "ecommerce-conversion"
description: "Sub-skill for e-commerce conversion optimization using Human Behavior OS modules. Covers purchase behavior, cart abandonment, pricing psychology, and checkout optimization."
---

# E-Commerce Conversion Optimization

## 0. Relationship to Parent

This reference inherits all 7 modules, the Master Formula, and quality standards from the parent Human Behavior OS skill. It adds e-commerce-specific frameworks, metrics, and intervention patterns.

---

## E-Commerce Behavior Framework

### The E-Commerce Decision Journey

```
Awareness → Interest → Search → Compare → Decide → Purchase → Post-Purchase
```

Each stage maps to specific modules:

| Stage | Primary Modules | Key Question |
|-------|----------------|-------------|
| Awareness | Attention, Need | How do they find us? |
| Interest | Attention, Emotion | Why do they stay? |
| Search | Need, Trust | What are they looking for? |
| Compare | Decision, Trust | Why choose us? |
| Decide | Decision, Emotion | Why buy now? |
| Purchase | Decision, Trust | Why complete the transaction? |
| Post-Purchase | Spread, Prediction | Will they return? Refer? |

---

## Module-Specific E-Commerce Applications

### Need System → Purchase Motivation Map

**E-Commerce Need Layers:**

| Layer | E-Commerce Expression | Common Products |
|-------|----------------------|-----------------|
| L1 Survival | Essential goods, emergency supplies | Food, medicine, repairs |
| L2 Efficiency | Time-saving, cost-saving solutions | Tools, services, bundles |
| L3 Emotion | Mood-enhancing, gift-giving | Fashion, entertainment, gifts |
| L4 Identity | Status symbols, taste signals | Luxury, niche, artisanal |
| L5 Growth | Self-improvement tools | Courses, books, equipment |

**Analysis Template:**

```markdown
## Purchase Motivation Map
- **Product Category Need Layer**: [L1-L5]
- **Buyer's Primary Need**: [Specific need within layer]
- **Purchase Trigger Event**: [What event precipitates the need]
- **Urgency Level**: [1-10] — [Why]
- **Comparison Set**: [What else they're considering]
```

### Trust System → E-Commerce Trust Stack

**Trust Signals by Purchase Stage:**

| Stage | Trust Signals | Implementation |
|-------|--------------|----------------|
| Landing | Reviews, ratings, media mentions | Star ratings, "As seen in", user count |
| Product Page | Detailed photos, specs, Q&A | 360° images, size guides, FAQ |
| Checkout | Security badges, payment options | SSL, trusted payment logos |
| Post-Purchase | Easy returns, responsive support | Return policy, live chat |

**Cart Abandonment Trust Analysis:**

Common trust failures that cause abandonment:
1. **Price surprise** — Hidden fees at checkout
2. **Security concern** — Unfamiliar payment process
3. **Return anxiety** — Unclear return policy
4. **Delivery uncertainty** — No clear shipping info
5. **Product doubt** — Not enough information to decide

### Decision System → Purchase Decision Equation

```
Buy Decision = (Product Value + Urgency + Trust) - (Price + Risk + Effort + Delay)
```

**Pricing Psychology Interventions:**

| Technique | Mechanism | Best For |
|----------|-----------|----------|
| Anchoring | Show high price first, then discount | Premium products |
| Decoy effect | Add a third option to make target look best | Plan comparisons |
| Bundle pricing | Package items to obscure individual prices | Multi-product |
| Pay-over-time | Reduce perceived upfront cost | High-ticket items |
| Flash urgency | Time-limited offer | Impulse purchases |
| Social proof pricing | "X people bought today" | Popular products |

### Emotion System → Purchase Emotions

**Pre-Purchase Emotional Sequence:**

```
Desire (want the outcome) → Anxiety (fear of wrong choice) → Excitement (anticipation) → Satisfaction (post-purchase)
```

**Emotional Intervention Points:**

| Emotion | Intervention | Where |
|---------|-------------|-------|
| Desire | Benefit-focused imagery, lifestyle copy | Product page hero |
| Anxiety | Money-back guarantee, reviews, comparisons | Below fold |
| Excitement | Countdown, limited stock, fast delivery promise | Near CTA |
| Satisfaction | Order confirmation, unboxing preview | Thank you page |

### Spread System → E-Commerce Viral Mechanics

**E-Commerce Sharing Triggers:**

| Trigger | Implementation | Expected K |
|---------|---------------|-----------|
| Deal sharing | "Share for $10 off" referral | 0.3-0.5 |
| Unboxing experience | Beautiful packaging, Instagram-worthy | 0.1-0.3 |
| Status purchase | "Just bought" social notification | 0.05-0.15 |
| Gift purchase | Gift wrapping + personal message | 0.1-0.2 |
| Review incentive | Discount on next purchase for review | 0.2-0.4 |

### Prediction System → E-Commerce Behavior Forecasting

**Key Predictive Signals:**

| Signal | Predicts | Lead Time | Intervention |
|--------|----------|-----------|-------------|
| Cart value > average | High intent | Immediate | Offer upsell |
| 2+ visits to same product | Consideration | 1-3 days | Retarget with social proof |
| Price comparison tool used | Decision phase | Hours | Price match or value add |
| Abandoned cart | Intent but friction | Minutes | Recovery email sequence |
| Repeat purchase pattern | Loyalty forming | Weeks | Subscription offer |

---

## Common E-Commerce Scenarios

### Scenario 1: Cart Abandonment

**Quick Diagnosis:**
1. Check abandonment rate by step (cart → checkout → payment)
2. Identify the highest-dropoff step
3. Map to trust/decision/emotion failure

**Intervention Framework:**
- **Cart page**: Add trust signals, save for later, wishlist
- **Checkout**: Reduce fields, guest checkout, progress indicator
- **Payment**: Multiple options, security badges, price transparency
- **Post-abandonment**: Email sequence (1hr → 24hr → 72hr)

### Scenario 2: Low Conversion Rate

**Diagnosis Checklist:**
- [ ] Is the value proposition clear in 5 seconds?
- [ ] Are trust signals visible above the fold?
- [ ] Is the CTA prominent and action-oriented?
- [ ] Is the price justified relative to perceived value?
- [ ] Is the path from interest to purchase ≤ 3 clicks?

### Scenario 3: Low Average Order Value

**AOV Optimization:**
- Cross-sell: "Frequently bought together"
- Upsell: "Upgrade to premium"
- Bundle: "Complete the set"
- Threshold: "Free shipping on $50+"
- anchoring: Show per-unit price for bulk

---

## Output Template: E-Commerce Behavior Profile

```markdown
# E-Commerce Behavior Profile

## 1. Purchase Motivation Map
[Need System output]

## 2. Trust Stack Analysis
[Trust System output with e-commerce signals]

## 3. Conversion Funnel Diagnosis
[Decision System output mapped to funnel stages]

## 4. Emotional Journey Map
[Emotion System output for purchase sequence]

## 5. Viral Potential Assessment
[Spread System output for e-commerce]

## 6. Purchase Prediction Model
[Prediction System output for buying behavior]

## 7. Optimization Recommendations
### Quick Wins (This Week)
- [ ] [Specific action with expected impact]

### Medium-Term (This Month)
- [ ] [Specific action with expected impact]

### Strategic (This Quarter)
- [ ] [Specific action with expected impact]

## 8. Key Metrics
| Metric | Current | Target | Priority |
|--------|---------|--------|----------|
| Conversion Rate | X% | Y% | High |
| AOV | $X | $Y | Medium |
| Cart Abandonment | X% | Y% | High |
| Repeat Purchase Rate | X% | Y% | Medium |
| Referral Rate | X% | Y% | Low |
```
