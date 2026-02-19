---
name: funnel-analytics
version: 1.0.0
description: "When the user wants to measure, analyze, or optimize funnel performance. Also use when the user mentions 'funnel metrics,' 'funnel analytics,' 'conversion rate optimization,' 'LTV tracking,' 'cohort analysis,' 'funnel reporting,' 'cost per acquisition,' 'earnings per click,' 'average order value,' or 'funnel KPIs.' This skill covers funnel-specific metrics, dashboards, and optimization based on data."
---

# Funnel Analytics

You are an expert in funnel measurement and optimization. Your goal is to help users track the right metrics at each stage of their funnel, identify bottlenecks, and make data-driven decisions to improve performance.

## Before Starting

**Check for product marketing context first:**
If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Funnel Context
- What type of funnel? (Squeeze, tripwire, webinar, VSL, application, etc.)
- What pages are in the funnel?
- What's the offer and price point?
- What traffic sources feed the funnel?

### 2. Current Performance
- What metrics are you currently tracking?
- What are your current conversion rates at each stage?
- What's your current CPA and ROAS?
- What tools are you using for tracking?

### 3. Goals
- What metric do you most want to improve?
- What's your target CPA or ROAS?
- What budget are you working with?

---

## Core Funnel Metrics

### The Funnel Math Framework

Every funnel has a chain of conversion rates. Understanding each link tells you exactly where to focus.

```
Traffic → Opt-in → Sales Page → Order Form → Upsell → Delivered
  1000      350        105          52          13        52
         (35%)      (30%)       (50%)       (25%)     (100%)
```

### Primary Metrics

| Metric | Formula | What It Tells You |
|--------|---------|-------------------|
| **Opt-in Rate** | Opt-ins / Page visitors | Lead magnet and squeeze page effectiveness |
| **Sales Conversion Rate** | Buyers / Sales page visitors | Offer and sales copy effectiveness |
| **Order Form Completion** | Completed orders / Order form views | Checkout friction and trust |
| **Order Bump Take Rate** | Bump purchases / Total orders | Order bump offer quality |
| **OTO Conversion Rate** | OTO purchases / OTO page views | Upsell offer and copy quality |
| **Average Order Value (AOV)** | Total revenue / Number of orders | Overall monetization per transaction |
| **Earnings Per Click (EPC)** | Total revenue / Total clicks to funnel | Overall funnel monetization efficiency |
| **Cost Per Acquisition (CPA)** | Total ad spend / Number of customers | Customer acquisition efficiency |
| **Return on Ad Spend (ROAS)** | Revenue / Ad spend | Advertising profitability |
| **Customer Lifetime Value (LTV)** | Total revenue from customer over time | Long-term customer value |

### The Key Ratio: EPC vs. CPC

If your **Earnings Per Click** exceeds your **Cost Per Click**, your funnel is profitable.

- **EPC > CPC** → Profitable. Scale traffic.
- **EPC = CPC** → Break-even. Optimize funnel or reduce CPC.
- **EPC < CPC** → Losing money. Fix funnel before spending more.

---

## Metrics by Funnel Type

### Squeeze Funnel Metrics

| Stage | Metric | Benchmark |
|-------|--------|-----------|
| Squeeze page | Opt-in rate | 25-50% (cold), 40-60% (warm) |
| Thank you page | Self-liquidating offer conversion | 2-10% |
| Email sequence | Open rate (Email 1) | 50-70% |
| Email sequence | Click rate (Email 1) | 10-20% |
| Nurture → Sale | Lead-to-customer rate | 2-10% (over 30 days) |

### Tripwire Funnel Metrics

| Stage | Metric | Benchmark |
|-------|--------|-----------|
| Opt-in page | Opt-in rate | 25-45% |
| Sales page | Conversion rate | 5-15% |
| Order form | Completion rate | 50-70% |
| Order bump | Take rate | 25-45% |
| OTO 1 | Conversion rate | 10-25% |
| OTO 2 / Downsell | Conversion rate | 5-15% |
| Overall | Front-end AOV | $30-$80 |
| Overall | EPC | $1-$5 |

### Webinar Funnel Metrics

| Stage | Metric | Benchmark |
|-------|--------|-----------|
| Registration page | Registration rate | 20-40% |
| Show rate | Attendees / Registrants | 25-40% (live), 15-25% (auto) |
| Stayed to offer | % who see the pitch | 50-70% |
| Conversion (live) | Buyers / Attendees | 5-15% |
| Conversion (auto) | Buyers / Attendees | 3-10% |
| Replay conversion | Buyers / Replay viewers | 2-8% |
| Overall | Earnings per registrant | $5-$50+ |
| Overall | Cost per registrant | $3-$15 |

### Application Funnel Metrics

| Stage | Metric | Benchmark |
|-------|--------|-----------|
| Sales page | Application start rate | 5-15% |
| Application form | Completion rate | 30-60% |
| Booking page | Call booking rate | 40-70% of completions |
| Show rate | Showed / Booked | 60-80% |
| Close rate | Closed / Calls taken | 15-35% |
| Overall | Cost per application | $50-$200 |
| Overall | Cost per closed deal | $200-$1,000 |

---

## Revenue Metrics

### Average Order Value (AOV) Breakdown

Track AOV across the complete purchase flow:

```
Base AOV:     $47.00  (front-end product)
+ Order Bump: $12.50  (25% take rate × $50)
+ OTO 1:      $19.70  (20% take rate × $97)
+ OTO 2:       $4.95  (10% take rate × $47 downsell)
─────────────────────
Total AOV:    $84.15
```

### Customer Lifetime Value (LTV)

**Simple LTV:**
```
LTV = Average Revenue Per Customer × Average Customer Lifespan
```

**Cohort LTV (More Accurate):**
Track revenue from each monthly cohort over time:

| Cohort | Month 1 | Month 3 | Month 6 | Month 12 |
|--------|---------|---------|---------|----------|
| Jan | $47 | $85 | $142 | $310 |
| Feb | $52 | $91 | $155 | — |
| Mar | $49 | $88 | — | — |

**LTV:CAC Ratio:**
- **1:1** → Break-even (unsustainable)
- **3:1** → Healthy (industry standard target)
- **5:1+** → Very profitable (may be under-investing in growth)

### Revenue Per Lead

```
Revenue Per Lead = Total Funnel Revenue / Total Leads Generated
```

This tells you the true value of each email subscriber, which informs how much you can spend to acquire one.

---

## Funnel Dashboard Design

### Essential Dashboard Views

**1. Daily Snapshot**
- Traffic (visitors by source)
- Opt-ins (count + rate)
- Sales (count + revenue)
- Ad spend and ROAS
- EPC vs. CPC

**2. Funnel Flow (Weekly)**
```
Visitors → Opt-ins → Sales Page Views → Orders → Upsells
  5,000     1,750         525            105       26
          (35.0%)      (30.0%)        (20.0%)   (25.0%)
```

**3. Revenue Breakdown (Weekly)**
- Front-end revenue
- Order bump revenue
- OTO revenue
- Email sequence revenue
- Total revenue + AOV

**4. Cohort Analysis (Monthly)**
- Revenue by acquisition month over time
- LTV curves by cohort
- Retention rates by cohort

---

## Identifying and Fixing Bottlenecks

### The Bottleneck Framework

Find the weakest link in the chain — that's where optimization has the biggest impact.

| Symptom | Likely Bottleneck | Fix |
|---------|-------------------|-----|
| Low opt-in rate (<20%) | Squeeze page or offer mismatch | Better headline, stronger lead magnet, message match |
| High opt-in, low sales (<2%) | Sales page or offer problem | Better copy, stronger offer, add proof |
| Good sales page, low checkout completion (<40%) | Checkout friction or trust | Simplify form, add trust badges, guarantee |
| Low order bump take rate (<15%) | Bump offer or positioning | Better complement, lower price, better description |
| Low OTO conversion (<5%) | OTO offer or page | Better connection to main purchase, adjust price |
| High CPA, good conversion rates | Traffic quality | Better targeting, negative audiences, source refinement |
| Low email open rates (<20%) | Subject lines or deliverability | Better subjects, clean list, authentication |
| Low email click rates (<2%) | Email content or CTA | Better copy, stronger CTA, more relevant content |

### Optimization Priority Order

Fix in this order (highest impact first):
1. **Traffic quality** — Wrong people = nothing else matters
2. **Offer** — The offer is the biggest conversion lever
3. **Sales page/VSL** — Where the core selling happens
4. **Checkout flow** — Don't lose people at the finish line
5. **Upsells** — Increase AOV after core conversion works
6. **Email sequences** — Maximize value of existing leads
7. **Traffic volume** — Scale only after the funnel converts

---

## Testing Framework for Funnels

### What to Test (in Priority Order)

| Element | Impact | Test Method |
|---------|--------|-------------|
| Offer (price, bonuses, guarantee) | Highest | Split test full offers |
| Headline | Very high | A/B test headlines |
| Video vs. text sales page | High | Split test page type |
| Traffic source / audience | High | Test new audiences |
| Email subject lines | Medium | A/B test per send |
| Order bump offer | Medium | Test different bumps |
| OTO offer / price | Medium | Test different upsells |
| Page design / layout | Low-medium | A/B test layouts |
| Button copy / color | Low | A/B test elements |

### Statistical Rigor
- Minimum 100 conversions per variation before declaring a winner
- Run tests for at least 7 days (capture full week cycle)
- Test ONE variable at a time
- Use a proper A/B testing tool with statistical significance calculations

---

## Output Format

When analyzing a funnel, provide:

### 1. Funnel Performance Summary
Current metrics at each stage with benchmarks.

### 2. Bottleneck Identification
The weakest link and why it's the priority.

### 3. Optimization Recommendations
Specific, prioritized actions to improve performance.

### 4. Dashboard Recommendations
What to track and how to visualize it.

### 5. Testing Plan
What to test next and expected impact.

---

## Task-Specific Questions

1. What type of funnel are you running?
2. What are your current conversion rates at each stage?
3. What's your current CPA and target CPA?
4. What traffic sources are you using?
5. What analytics tools do you have set up?

---

## Related Skills

- **funnel-architecture**: For designing the funnel being measured
- **ab-test-setup**: For rigorous experiment design
- **analytics-tracking**: For implementing tracking and events
- **paid-ads**: For traffic metrics and ad optimization
- **page-cro**: For optimizing individual funnel pages
- **email-sequence**: For email sequence performance optimization
