# Pricing Strategy Guide

Use this template when Phase 5 (Revenue & Business Model) needs deeper investigation.

## 1. Pricing Model Decision Tree

```
Is the value delivered repeatedly (weekly/monthly)?
├── YES → Subscription model
│   └── Does usage vary significantly between users?
│       ├── YES → Tiered subscription (usage caps per tier)
│       └── NO → Flat-rate subscription
└── NO → Usage-based or one-time
    └── Do users come back for more?
        ├── YES → Credit/usage-based (pay per use)
        └── NO → One-time purchase (harder to build recurring revenue)
```

## 2. Freemium vs. Free Trial vs. Paid-Only

| Model | Best When | Risk |
|:------|:----------|:-----|
| **Freemium** | Wow moment is instant, sharing drives growth, marginal cost per user is near zero | Free users never convert, support burden |
| **Free trial** (7-14 days) | Product needs time to show value, B2B buyers need to evaluate | Trial expires before they experience value |
| **Paid-only** | Audience is serious (finance, legal, enterprise), problem is urgent | Higher barrier, slower initial growth |
| **Reverse trial** | Best of both — full access for 14 days, then drops to free tier | Complex to implement, confusing if not clear |

**For most Micro SaaS: Freemium with strict limits works best.**
- Free tier proves value quickly
- Limits create natural upgrade pressure
- Low barrier = more word-of-mouth

## 3. Pricing Tier Framework

### The 3+1 Tier Structure

| Tier | Purpose | Pricing Psychology |
|:-----|:--------|:------------------|
| **Free** | Acquisition — get users in the door | Remove all friction, add visible limits |
| **Starter** | Conversion — first dollar from individuals | Price anchor: cheap enough to not need approval ($9-19/mo) |
| **Pro** | Revenue — where most money comes from | 2-3x Starter, unlock the features power users need ($29-49/mo) |
| **Team/Business** | Expansion — multi-seat, higher volume | 2-3x Pro, unlimited usage, priority support ($79-149/mo) |

### Limit Levers (what to restrict on free tier)

Choose 1-2 limits that naturally push users to upgrade:

| Lever | Example | Best For |
|:------|:--------|:---------|
| Volume cap | 5 invoices/week free | Transaction-based tools |
| Feature gate | No batch processing, no API | Power-user features |
| Export limits | Watermarked exports, no CSV | Output-focused tools |
| Storage cap | 100MB free | File/data storage tools |
| Speed/priority | Queue behind paid users | Processing-heavy tools |
| Branding | "Made with [Tool]" watermark | Shareable outputs |

**Golden rule: Free tier must deliver the wow moment. Then limit the scale, not the experience.**

## 4. Price Point Research

### Anchoring Against Alternatives

| Alternative | Cost | Your Price Should Be |
|:-----------|:-----|:--------------------|
| Manual labor (hours x hourly rate) | $/hr x hrs/week | 10-20% of manual cost |
| Hiring someone (freelancer/VA) | $/month | 5-10% of hiring cost |
| Existing tool (competitor pricing) | $/month | 30-70% of competitor |
| Cost of mistakes (errors, fines) | $/incident | Fraction of error cost |

**Example:** If manual invoice entry takes 2 hours/week at $30/hr = $240/mo cost. Your tool at $19/mo = 92% savings. Easy sell.

### Price Sensitivity Testing

Before launching, test with these approaches:
1. **Van Westendorp method** — Ask 4 questions:
   - At what price is this too cheap (seems low quality)?
   - At what price is this a great deal?
   - At what price does it start feeling expensive?
   - At what price is it too expensive to consider?

2. **Simple A/B test** — Show different prices to different landing page visitors

3. **Founding member pricing** — Launch at 50% off "forever" for first 50 users. Tests willingness to pay while building loyalty.

## 5. Revenue Projection Calculator

### Conservative Scenario (Month 6)

| Metric | Value | Notes |
|:-------|:------|:------|
| Monthly visitors | 5,000 | SEO + social + referrals |
| Trial rate | 10% | 500 trials |
| Activation rate | 15% | 75 active users |
| Paid conversion | 40% | 30 paying users |
| Average price | $19/mo | Starter tier |
| **MRR** | **$570** | |

### Moderate Scenario (Month 12)

| Metric | Value | Notes |
|:-------|:------|:------|
| Monthly visitors | 15,000 | Growing SEO + content |
| Trial rate | 15% | 2,250 trials |
| Activation rate | 20% | 450 active users |
| Paid conversion | 50% | 225 paying users |
| Average price | $25/mo | Mix of tiers |
| **MRR** | **$5,625** | |

### Optimistic Scenario (Month 18)

| Metric | Value | Notes |
|:-------|:------|:------|
| Monthly visitors | 30,000 | SEO compounding + affiliates |
| Trial rate | 15% | 4,500 trials |
| Activation rate | 25% | 1,125 active users |
| Paid conversion | 50% | 562 paying users |
| Average price | $30/mo | Tier mix shifting up |
| **MRR** | **$16,860** | |

## 6. Churn Reduction Playbook

Monthly churn target: < 5% for Micro SaaS

| Churn Cause | Detection Signal | Fix |
|:-----------|:----------------|:----|
| No ongoing value | Users log in once, never return | Add recurring use case, email reminders |
| Found alternative | Sudden drop after competitor launch | Differentiate harder, lock in with data |
| Too expensive | Cancellation reason = price | Add cheaper tier, show ROI in-app |
| Missing feature | Feature requests before cancellation | Ship top-requested features fast |
| Poor experience | Support tickets before cancellation | Fix UX pain points, faster support |

**Churn prevention > churn recovery.** Small weekly improvements + fast support = your edge over big SaaS.

## 7. Monetization Timeline

| Week | Action |
|:-----|:-------|
| Week 1 | Launch with freemium. Starter tier only ($19/mo). |
| Week 2-4 | Collect feedback from free users. Watch what hits limits. |
| Month 2 | Add Pro tier ($49/mo) based on what power users request. |
| Month 3 | Add Team tier ($99/mo) if multi-user demand appears. |
| Month 4+ | Optimize pricing based on conversion data. Test annual plans (2 months free). |

**Rule: Start simple. Add tiers based on real demand, not assumptions.**
