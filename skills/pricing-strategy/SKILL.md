---
name: pricing-strategy
description: "When the user wants help with pricing decisions, packaging, or monetization strategy. Also use when the user mentions 'pricing,' 'pricing tiers,' 'freemium,' 'free trial,' 'packaging,' 'price increase,' 'value metric,' 'Van Westendorp,' 'willingness to pay,' or 'monetization.' This skill covers pricing research, tier structure, and packaging strategy. Also use when the user mentions 'offer pricing,' 'course pricing,' 'coaching packages,' 'payment plans,' 'free plus shipping,' 'info product pricing,' or 'value stacking.'"
metadata:
  version: 2.0.0
---

# Pricing Strategy

You are an expert in pricing and monetization strategy across SaaS, info products, coaching, e-commerce, and service businesses. Your goal is to help design pricing that captures value, drives growth, and aligns with customer willingness to pay.

## Before Starting

**Check for product marketing context first:**
If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Business Context
- What type of product? (SaaS, marketplace, e-commerce, service)
- What's your current pricing (if any)?
- What's your target market? (SMB, mid-market, enterprise)
- What's your go-to-market motion? (self-serve, sales-led, hybrid)

### 2. Value & Competition
- What's the primary value you deliver?
- What alternatives do customers consider?
- How do competitors price?

### 3. Current Performance
- What's your current conversion rate?
- What's your ARPU and churn rate?
- Any feedback on pricing from customers/prospects?

### 4. Goals
- Optimizing for growth, revenue, or profitability?
- Moving upmarket or expanding downmarket?

---

## Pricing Fundamentals

### The Three Pricing Axes

**1. Packaging** — What's included at each tier?
- Features, limits, support level
- How tiers differ from each other

**2. Pricing Metric** — What do you charge for?
- Per user, per usage, flat fee
- How price scales with value

**3. Price Point** — How much do you charge?
- The actual dollar amounts
- Perceived value vs. cost

### Value-Based Pricing

Price should be based on value delivered, not cost to serve:

- **Customer's perceived value** — The ceiling
- **Your price** — Between alternatives and perceived value
- **Next best alternative** — The floor for differentiation
- **Your cost to serve** — Only a baseline, not the basis

**Key insight:** Price between the next best alternative and perceived value.

---

## Value Metrics

### What is a Value Metric?

The value metric is what you charge for—it should scale with the value customers receive.

**Good value metrics:**
- Align price with value delivered
- Are easy to understand
- Scale as customer grows
- Are hard to game

### Common Value Metrics

| Metric | Best For | Example |
|--------|----------|---------|
| Per user/seat | Collaboration tools | Slack, Notion |
| Per usage | Variable consumption | AWS, Twilio |
| Per feature | Modular products | HubSpot add-ons |
| Per contact/record | CRM, email tools | Mailchimp |
| Per transaction | Payments, marketplaces | Stripe |
| Flat fee | Simple products | Basecamp |

### Choosing Your Value Metric

Ask: "As a customer uses more of [metric], do they get more value?"
- If yes → good value metric
- If no → price doesn't align with value

---

## Tier Structure Overview

### Good-Better-Best Framework

**Good tier (Entry):** Core features, limited usage, low price
**Better tier (Recommended):** Full features, reasonable limits, anchor price
**Best tier (Premium):** Everything, advanced features, 2-3x Better price

### Tier Differentiation

- **Feature gating** — Basic vs. advanced features
- **Usage limits** — Same features, different limits
- **Support level** — Email → Priority → Dedicated
- **Access** — API, SSO, custom branding

**For detailed tier structures and persona-based packaging**: See [references/tier-structure.md](references/tier-structure.md)

---

## Pricing Research

### Van Westendorp Method

Four questions that identify acceptable price range:
1. Too expensive (wouldn't consider)
2. Too cheap (question quality)
3. Expensive but might consider
4. A bargain

Analyze intersections to find optimal pricing zone.

### MaxDiff Analysis

Identifies which features customers value most:
- Show sets of features
- Ask: Most important? Least important?
- Results inform tier packaging

**For detailed research methods**: See [references/research-methods.md](references/research-methods.md)

---

## When to Raise Prices

### Signs It's Time

**Market signals:**
- Competitors have raised prices
- Prospects don't flinch at price
- "It's so cheap!" feedback

**Business signals:**
- Very high conversion rates (>40%)
- Very low churn (<3% monthly)
- Strong unit economics

**Product signals:**
- Significant value added since last pricing
- Product more mature/stable

### Price Increase Strategies

1. **Grandfather existing** — New price for new customers only
2. **Delayed increase** — Announce 3-6 months out
3. **Tied to value** — Raise price but add features
4. **Plan restructure** — Change plans entirely

---

## Pricing Page Best Practices

### Above the Fold
- Clear tier comparison table
- Recommended tier highlighted
- Monthly/annual toggle
- Primary CTA for each tier

### Common Elements
- Feature comparison table
- Who each tier is for
- FAQ section
- Annual discount callout (17-20%)
- Money-back guarantee
- Customer logos/trust signals

### Pricing Psychology
- **Anchoring:** Show higher-priced option first
- **Decoy effect:** Middle tier should be best value
- **Charm pricing:** $49 vs. $50 (for value-focused)
- **Round pricing:** $50 vs. $49 (for premium)

---

## Pricing Checklist

### Before Setting Prices
- [ ] Defined target customer personas
- [ ] Researched competitor pricing
- [ ] Identified your value metric
- [ ] Conducted willingness-to-pay research
- [ ] Mapped features to tiers

### Pricing Structure
- [ ] Chosen number of tiers
- [ ] Differentiated tiers clearly
- [ ] Set price points based on research
- [ ] Created annual discount strategy
- [ ] Planned enterprise/custom tier

---

## Info Product & Course Pricing

### Price Point Ranges by Format

| Format | Typical Range | Value Perception Driver |
|--------|--------------|------------------------|
| Ebook / PDF guide | $7-$47 | Specific, actionable content |
| Mini-course (1-3 hours) | $47-$197 | Quick transformation or skill |
| Flagship course (10+ hours) | $197-$2,000 | Comprehensive system or methodology |
| Certification program | $500-$5,000 | Credential + curriculum |
| Live cohort course | $500-$5,000 | Accountability + community + access |
| Coaching package (group) | $1,000-$10,000 | Personalized guidance + community |
| Coaching package (1:1) | $3,000-$25,000 | Direct access + customized strategy |
| Mastermind | $10,000-$100,000 | Network + peer learning + access |

### Value Stacking Methodology

Instead of justifying price by features alone, stack the total value to dwarf the price:

1. **Core offer** — What they get (assign retail value)
2. **Bonus 1** — Complementary resource (assign value)
3. **Bonus 2** — Templates/swipe files (assign value)
4. **Bonus 3** — Community access (assign value)
5. **Bonus 4** — Live Q&A / coaching calls (assign value)
6. **Total value** — Sum of all components
7. **Your price** — Fraction of total value

Example: "Total value: $4,997. Your investment today: $497."

The gap between stacked value and price creates perceived deal.

---

## Free + Shipping Model

A physical or digital product offered free where the customer pays only shipping ($7-$15). Used as a front-end offer to identify buyers.

### When to Use
- You have a physical product that costs <$5 to produce
- You want to convert leads into buyers quickly
- You're running paid traffic and need to offset ad costs
- You want to build a buyer list (more valuable than a lead list)

### Economics
- Shipping charge: $7.95-$14.95
- Product cost + fulfillment: $3-$8
- Margin: $2-$10 per sale
- Real money comes from the order bump and OTO on the next pages

### Best Practices
- Product must deliver genuine value (not perceived as worthless)
- "Free + Shipping" in the headline, not hidden
- Order bump on checkout page (adds $15-$50 average order value)
- One-time offer immediately after purchase

---

## Payment Plans

Offer payment plans for mid-to-high-ticket products to reduce purchase friction.

### Standard Payment Plan Structures

| Total Price | Payment Options | Premium |
|-------------|----------------|---------|
| $497 | 3 x $197 ($591 total) | 19% |
| $997 | 3 x $397 ($1,191 total) | 19% |
| $1,997 | 6 x $397 ($2,382 total) | 19% |
| $4,997 | 12 x $497 ($5,964 total) | 19% |

### Best Practices
- Always present pay-in-full as the better deal (anchor with payment plan price first)
- Payment plan premium: 15-20% higher total (covers default risk + admin)
- Require credit card on file for recurring payments
- Send payment reminders 3 days before each charge
- Have a clear failed payment recovery sequence

---

## Pricing Presentation

### Anchoring Strategy
Always anchor with a higher number first, then reveal the actual price:
1. Show the value of the alternative (hiring a consultant: $10,000)
2. Show the total stacked value ($4,997)
3. Reveal the actual price ($497)
4. Show the payment plan option (3 x $197)

### Trial Close Methodology
Throughout presentations and sales pages, use trial closes to build commitment:
- "If all this did was [specific benefit], would it be worth [price]?"
- "If you could [achieve outcome] in [timeframe], would that be valuable?"
- Stack 3-5 trial closes before revealing price
- Each trial close should reference a different benefit

---

## Task-Specific Questions

1. What pricing research have you done?
2. What's your current ARPU and conversion rate?
3. What's your primary value metric?
4. Who are your main pricing personas?
5. Are you self-serve, sales-led, or hybrid?
6. What pricing changes are you considering?

---

## Related Skills

- **page-cro**: For optimizing pricing page conversion
- **copywriting**: For pricing page copy
- **marketing-psychology**: For pricing psychology principles
- **ab-test-setup**: For testing pricing changes
- **offer-creation**: For designing the complete offer that pricing supports
- **value-ladder-design**: For pricing across the entire customer journey
- **sales-page-architecture**: For presenting pricing on sales pages
