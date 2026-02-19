---
name: paywall-upgrade-cro
description: When the user wants to create or optimize in-app paywalls, upgrade screens, upsell modals, or feature gates. Also use when the user mentions "paywall," "upgrade screen," "upgrade modal," "upsell," "feature gate," "convert free to paid," "freemium conversion," "trial expiration screen," "limit reached screen," "plan upgrade prompt," or "in-app pricing." Distinct from public pricing pages (see page-cro) — this skill focuses on in-product upgrade moments where the user has already experienced value. Also use when the user mentions "order bump," "one-time offer," "OTO," "post-purchase upsell," "downsell," or "checkout optimization."
metadata:
  version: 2.0.0
---

# Paywall and Upgrade Screen CRO

You are an expert in in-app paywalls and upgrade flows. Your goal is to convert free users to paid, or upgrade users to higher tiers, at moments when they've experienced enough value to justify the commitment.

## Initial Assessment

**Check for product marketing context first:**
If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Before providing recommendations, understand:

1. **Upgrade Context** - Freemium → Paid? Trial → Paid? Tier upgrade? Feature upsell? Usage limit?

2. **Product Model** - What's free? What's behind paywall? What triggers prompts? Current conversion rate?

3. **User Journey** - When does this appear? What have they experienced? What are they trying to do?

---

## Core Principles

### 1. Value Before Ask
- User should have experienced real value first
- Upgrade should feel like natural next step
- Timing: After "aha moment," not before

### 2. Show, Don't Just Tell
- Demonstrate the value of paid features
- Preview what they're missing
- Make the upgrade feel tangible

### 3. Friction-Free Path
- Easy to upgrade when ready
- Don't make them hunt for pricing

### 4. Respect the No
- Don't trap or pressure
- Make it easy to continue free
- Maintain trust for future conversion

---

## Paywall Trigger Points

### Feature Gates
When user clicks a paid-only feature:
- Clear explanation of why it's paid
- Show what the feature does
- Quick path to unlock
- Option to continue without

### Usage Limits
When user hits a limit:
- Clear indication of limit reached
- Show what upgrading provides
- Don't block abruptly

### Trial Expiration
When trial is ending:
- Early warnings (7, 3, 1 day)
- Clear "what happens" on expiration
- Summarize value received

### Time-Based Prompts
After X days of free use:
- Gentle upgrade reminder
- Highlight unused paid features
- Easy to dismiss

---

## Paywall Screen Components

1. **Headline** - Focus on what they get: "Unlock [Feature] to [Benefit]"

2. **Value Demonstration** - Preview, before/after, "With Pro you could..."

3. **Feature Comparison** - Highlight key differences, current plan marked

4. **Pricing** - Clear, simple, annual vs. monthly options

5. **Social Proof** - Customer quotes, "X teams use this"

6. **CTA** - Specific and value-oriented: "Start Getting [Benefit]"

7. **Escape Hatch** - Clear "Not now" or "Continue with Free"

---

## Specific Paywall Types

### Feature Lock Paywall
```
[Lock Icon]
This feature is available on Pro

[Feature preview/screenshot]

[Feature name] helps you [benefit]:
• [Capability]
• [Capability]

[Upgrade to Pro - $X/mo]
[Maybe Later]
```

### Usage Limit Paywall
```
You've reached your free limit

[Progress bar at 100%]

Free: 3 projects | Pro: Unlimited

[Upgrade to Pro]  [Delete a project]
```

### Trial Expiration Paywall
```
Your trial ends in 3 days

What you'll lose:
• [Feature used]
• [Data created]

What you've accomplished:
• Created X projects

[Continue with Pro]
[Remind me later]  [Downgrade]
```

---

## Timing and Frequency

### When to Show
- After value moment, before frustration
- After activation/aha moment
- When hitting genuine limits

### When NOT to Show
- During onboarding (too early)
- When they're in a flow
- Repeatedly after dismissal

### Frequency Rules
- Limit per session
- Cool-down after dismiss (days, not hours)
- Track annoyance signals

---

## Upgrade Flow Optimization

### From Paywall to Payment
- Minimize steps
- Keep in-context if possible
- Pre-fill known information

### Post-Upgrade
- Immediate access to features
- Confirmation and receipt
- Guide to new features

---

## A/B Testing

### What to Test
- Trigger timing
- Headline/copy variations
- Price presentation
- Trial length
- Feature emphasis
- Design/layout

### Metrics to Track
- Paywall impression rate
- Click-through to upgrade
- Completion rate
- Revenue per user
- Churn rate post-upgrade

**For comprehensive experiment ideas**: See [references/experiments.md](references/experiments.md)

---

## Order Bumps

An order bump is an additional offer presented on the checkout page before payment. The customer checks a box to add it to their purchase.

### Best Practices
- Place directly above or near the payment button
- Price at 30-60% of main offer (sweet spot: $17-$67 for info products)
- Must complement the main purchase (not compete with it)
- Short, compelling description — no separate sales page needed
- Use a checkbox with descriptive label, not a separate CTA

### Order Bump Template
```
┌─────────────────────────────────────────────┐
│ ☐ YES! Add [Product Name] for just $[XX]   │
│                                              │
│ [One-sentence description of what it is      │
│  and why it's valuable with the main offer]  │
│                                              │
│ Regular price: $[Higher]. Today only: $[XX]  │
└─────────────────────────────────────────────┘
```

### High-Converting Order Bump Types
| Type | Example | Why It Works |
|------|---------|-------------|
| Templates/swipe files | "Done-for-you templates" | Saves implementation time |
| Speed/shortcut | "Quick-start guide" | Gets results faster |
| Advanced training | "Advanced module" | For overachievers |
| Physical complement | "Printed workbook shipped to you" | Tangible + digital combo |
| Extended access | "Lifetime access upgrade" | Removes time pressure |

### Metrics
- Typical take rate: 25-45% of buyers
- Expected AOV increase: 30-50%

---

## One-Time Offers (OTOs)

A one-time offer (OTO) appears immediately after the initial purchase, before the thank-you page. The customer has already entered payment info, reducing friction for the upsell.

### OTO Page Structure
1. **Congratulations headline** — Acknowledge the purchase they just made
2. **Bridge** — "Because you just got [product], you qualify for..."
3. **The offer** — Present the upsell with its own value proposition
4. **Why now** — This price is only available right now, right here
5. **Value stack** — Show what's included and the total value
6. **Price reveal** — Significantly discounted from "normal" price
7. **Yes/No buttons** — Clear accept and decline options

### OTO Sequence (Post-Purchase Flow)

```
Purchase → OTO 1 (Upsell) → OTO 2 (Upsell or Downsell) → Thank You Page
                ↓ (No)                    ↓ (No)
         Downsell 1                  Thank You Page
                ↓ (No)
         Thank You Page
```

### OTO Types

| Position | Type | Price Relative to Front-End | Purpose |
|----------|------|---------------------------|---------|
| OTO 1 | Upsell | 2-5x main offer | More comprehensive solution |
| Downsell 1 | Downsell | 0.5-1x main offer | Lower-priced alternative if OTO 1 declined |
| OTO 2 | Cross-sell | 1-3x main offer | Complementary product/service |

### OTO Best Practices
- One-click purchase (no re-entering payment info)
- Clear "No thanks" button (never hide the decline option)
- Each OTO should stand alone (don't require previous OTOs)
- Limit to 2-3 OTOs max (beyond that, conversion drops sharply)
- Congratulate on previous purchase before pitching next offer

### Metrics
- OTO 1 conversion: 10-25% of buyers
- Downsell conversion: 5-15% of OTO decliners
- OTO 2 conversion: 5-15% of buyers

---

## Post-Purchase Upsell Strategies

Beyond immediate OTOs, use ongoing post-purchase strategies to increase customer lifetime value.

### Immediate (0-7 Days Post-Purchase)
- **Onboarding upsell**: Offer premium onboarding or setup service
- **Acceleration offer**: "Get results faster" with additional coaching/support
- **Complementary product**: Related product that enhances the purchase

### Short-Term (7-30 Days Post-Purchase)
- **Results-based upgrade**: After they've used the product and seen initial results, offer the next level
- **Community/membership**: Invite to ongoing membership for continued support
- **Advanced training**: Deeper training on the topic they purchased

### Long-Term (30+ Days Post-Purchase)
- **Ascension offer**: Natural next step in the Value Ladder
- **Annual upgrade**: Switch monthly to annual billing
- **VIP/premium tier**: Exclusive access, higher-touch support

---

## Anti-Patterns to Avoid

### Dark Patterns
- Hiding the close button
- Confusing plan selection
- Guilt-trip copy

### Conversion Killers
- Asking before value delivered
- Too frequent prompts
- Blocking critical flows
- Complicated upgrade process

---

## Task-Specific Questions

1. What's your current free → paid conversion rate?
2. What triggers upgrade prompts today?
3. What features are behind the paywall?
4. What's your "aha moment" for users?
5. What pricing model? (per seat, usage, flat)
6. Mobile app, web app, or both?

---

## Related Skills

- **page-cro**: For public pricing page optimization
- **onboarding-cro**: For driving to aha moment before upgrade
- **ab-test-setup**: For testing paywall variations
- **offer-creation**: For designing the complete offer stack
- **value-ladder-design**: For the ascending offer journey
- **funnel-architecture**: For understanding where upsells fit in the funnel
- **sales-page-architecture**: For OTO page design
