---
name: sales-page-architecture
version: 1.0.0
description: "When the user wants to design a specific type of marketing page from scratch — sales page, squeeze page, OTO page, order form page, bridge page, application page, or thank you page. Also use when the user mentions 'sales page,' 'landing page design,' 'squeeze page,' 'OTO page,' 'order form,' 'bridge page,' 'application page,' 'long-form sales page,' 'VSL page,' or 'page wireframe.' Different from page-cro (which audits existing pages) — this skill designs new conversion-specific pages from scratch."
---

# Sales Page Architecture

You are an expert in conversion-focused page design. Your goal is to help users design specific types of marketing pages from scratch with proven structures, wireframes, and section-by-section guidance.

## Before Starting

**Check for product marketing context first:**
If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Page Context
- What type of page do you need? (See page types below)
- What funnel does this page belong to?
- What page comes before this? What comes after?
- What's the ONE action visitors should take?

### 2. Offer Context
- What's being offered on this page?
- What's the price point?
- Who is the target visitor?
- What do they already know when they arrive?

### 3. Traffic Context
- Where is traffic coming from? (Ads, email, organic, referral)
- Is the traffic cold, warm, or hot?
- What message/promise brought them here?

---

## Universal Page Design Rules

1. **No navigation** on funnel pages (squeeze, sales, OTO, order)
2. **One CTA** per page — every element supports that single action
3. **Message match** — headline must reflect what brought them here
4. **Mobile-first** — design for mobile, enhance for desktop
5. **Above-the-fold clarity** — visitor should know what this page is about in 5 seconds
6. **Fast loading** — under 3 seconds or conversions drop dramatically

---

## Page Type: Squeeze Page (Opt-In Page)

**Purpose:** Capture email address in exchange for a lead magnet
**Target conversion rate:** 25-50%

### Short Squeeze Page (Preferred for Paid Traffic)

```
┌──────────────────────────────────────────┐
│            [Headline]                     │
│     What they get + the benefit           │
│                                          │
│     [Subheadline]                        │
│     Expand with specificity              │
│                                          │
│  [Lead Magnet Image/Mockup]              │
│                                          │
│  • Bullet 1: Specific benefit            │
│  • Bullet 2: Specific benefit            │
│  • Bullet 3: Specific benefit            │
│                                          │
│  ┌────────────────────────────┐          │
│  │ Email: __________________ │          │
│  │ [Get Free Access →]       │          │
│  └────────────────────────────┘          │
│                                          │
│  "Join 5,000+ marketers" (social proof)  │
└──────────────────────────────────────────┘
```

### Long Squeeze Page (For Higher-Value Lead Magnets)

Add these sections below the fold:
- What's inside (expanded bullet points)
- Who this is for
- About the author/creator (brief credibility)
- Testimonials from people who've used the resource
- FAQ (2-3 common questions)
- Repeated CTA

---

## Page Type: Long-Form Sales Page

**Purpose:** Sell a product/service through persuasive long-form copy
**Target conversion rate:** 1-5% (cold), 5-15% (warm/hot)

### Section-by-Section Architecture

```
1. PRE-HEAD / EYEBROW
   "[Category] for [Audience]"

2. HEADLINE
   Core promise or transformation

3. SUBHEADLINE
   Expand on headline with specificity

4. HERO SECTION
   Video or product image + Primary CTA

─── Above the fold ────────────────────────

5. PROBLEM SECTION
   Agitate the pain they're experiencing
   "Are you tired of..."
   "You've probably tried..."

6. STORY / EPIPHANY BRIDGE
   Origin story of how you discovered the solution
   Use the 8-step Epiphany Bridge structure

7. SOLUTION REVEAL
   Introduce your product as the answer
   "Introducing [Product Name]"

8. BENEFITS (Not Features)
   3-5 key benefits with supporting details
   Each benefit addresses a specific pain point

9. SOCIAL PROOF BLOCK 1
   Testimonials, case studies, results
   Include specific numbers and outcomes

10. HOW IT WORKS
    3-4 simple steps
    Reduce perceived complexity

11. WHAT'S INCLUDED
    Module-by-module or feature-by-feature breakdown
    Each item with its own value proposition

12. BONUSES
    3-5 bonuses with individual values
    Each addresses a specific objection

13. THE STACK (Value Stack)
    List everything included with values
    Show total value vs. actual price

14. PRICE REVEAL
    Anchor with higher value first
    Present actual price as a fraction of value
    Payment plan option

15. GUARANTEE
    Named guarantee with specific terms
    Risk reversal language

16. CTA BUTTON
    Action-oriented, specific
    "Enroll Now" / "Get Instant Access"

17. SOCIAL PROOF BLOCK 2
    More testimonials, logos, results

18. FAQ
    5-8 common questions and objections

19. FINAL CTA
    Recap the transformation
    Urgency/scarcity reminder
    Final CTA button

20. P.S. SECTION
    Summarize the offer
    Restate guarantee
    Final urgency push
```

---

## Page Type: VSL Page (Video Sales Letter)

**Purpose:** Sell through a persuasive video on a minimal page
**Target conversion rate:** 2-8%

### Page Structure

```
┌──────────────────────────────────────────┐
│                                          │
│  [Curiosity-Driven Headline]             │
│  (Not product-focused — question or      │
│   intrigue that makes them watch)        │
│                                          │
│  ┌────────────────────────────────┐      │
│  │                                │      │
│  │      VIDEO PLAYER              │      │
│  │   (No controls initially)      │      │
│  │                                │      │
│  └────────────────────────────────┘      │
│                                          │
│  [BUY BUTTON - hidden until pitch]       │
│  (Appears at minute 15-20 of video)      │
│                                          │
│  [Minimal text - appears as video        │
│   progresses with key points]            │
│                                          │
└──────────────────────────────────────────┘
```

### VSL Page Best Practices
- No navigation, no distractions
- Buy button appears only when the pitch starts in the video
- Some text can appear below the video as it progresses (matching the content)
- Keep the page design minimal — the video does the selling
- Include urgency elements below the video (countdown, limited spots)
- Add testimonials below the video for those who watch but need more proof

---

## Page Type: Order Form Page

**Purpose:** Collect payment information and complete the purchase
**Target conversion rate:** 50-70% (of those who click "buy")

### Order Form Architecture

```
┌──────────────────────────────────────────┐
│  [Order Summary]                         │
│  Product: [Name]                         │
│  Price: $XXX (or $XX/mo × 3)            │
│                                          │
│  ┌─────────────────────────────────┐     │
│  │ ORDER BUMP                      │     │
│  │ ☐ Add [Bonus Product] - $XX    │     │
│  │ [Brief description]            │     │
│  └─────────────────────────────────┘     │
│                                          │
│  Contact Information                     │
│  Name: _______________                   │
│  Email: ______________                   │
│                                          │
│  Payment Information                     │
│  Card: ____________________              │
│  Exp: ____  CVC: ____                   │
│                                          │
│  ○ Pay in full: $497                     │
│  ○ 3 payments of $197                    │
│                                          │
│  [Complete Order →]                      │
│                                          │
│  🔒 Secure checkout. 60-day guarantee.  │
│  [Security badges / trust symbols]       │
│                                          │
│  Testimonial snippet                     │
└──────────────────────────────────────────┘
```

### Order Form Best Practices
- Recap what they're getting (not just the price)
- Place order bump BEFORE the payment fields
- Include trust symbols and security badges
- Show guarantee near the submit button
- Minimize form fields (name, email, card)
- One or two short testimonials for reassurance
- Payment options (pay in full vs. plan) clearly presented

---

## Page Type: OTO Page (One-Time Offer / Upsell)

**Purpose:** Present an upsell immediately after purchase
**Target conversion rate:** 10-25%

### OTO Page Architecture

```
┌──────────────────────────────────────────┐
│  WAIT! Your order is not yet complete.   │
│                                          │
│  [Congratulations headline]              │
│  "Before you go, I have a special        │
│   one-time offer just for new members"   │
│                                          │
│  [Video or image of the upsell offer]    │
│                                          │
│  Here's what you're getting:             │
│  • [Benefit 1]                           │
│  • [Benefit 2]                           │
│  • [Benefit 3]                           │
│                                          │
│  Regular price: $XXX                     │
│  Your price today: $XX                   │
│  (One-time offer — not available later)  │
│                                          │
│  [YES! Add This To My Order →]           │
│                                          │
│  [No thanks, I'll pass on this offer]    │
│                                          │
└──────────────────────────────────────────┘
```

### OTO Best Practices
- One-click purchase (no re-entering payment info)
- Clear "No thanks" link (never hide the decline)
- Acknowledge the purchase they just made before pitching
- Create genuine connection to the previous purchase
- Maximum 2-3 OTOs before the thank you page

---

## Page Type: Bridge Page

**Purpose:** Warm up cold traffic before sending to the main offer page
**Target conversion rate:** 40-60% (click-through to next page)

### Bridge Page Architecture

```
┌──────────────────────────────────────────┐
│  [Headline: "Before you see [product],   │
│   watch this quick video..."]            │
│                                          │
│  [Short Video - 2-5 minutes]             │
│  • Personal introduction                 │
│  • Why you created this                  │
│  • What they're about to see             │
│  • Why it matters for them               │
│                                          │
│  [Continue to [Next Page] →]             │
│                                          │
└──────────────────────────────────────────┘
```

### When to Use a Bridge Page
- Between an ad and a sales page (especially for cold traffic)
- Between an affiliate promotion and your offer
- When the sales page needs pre-framing or context
- When you need to establish credibility before the pitch

---

## Page Type: Application Page

**Purpose:** Qualify prospects for high-ticket offers
**Target conversion rate:** 30-50% (of those who start the application)

### Application Page Architecture

```
┌──────────────────────────────────────────┐
│  [Headline: Apply for [Program Name]]    │
│  [Subhead: We only work with X people    │
│   per quarter. See if you qualify.]      │
│                                          │
│  [Brief description of what they're      │
│   applying for and the transformation]   │
│                                          │
│  APPLICATION FORM:                       │
│  1. Name + Email + Phone                 │
│  2. What's your current situation?       │
│  3. What result are you looking for?     │
│  4. What have you tried before?          │
│  5. Why do you want this now?            │
│  6. Are you ready to invest $X-$X?       │
│  7. Anything else we should know?        │
│                                          │
│  [Submit Application →]                  │
│                                          │
│  "Applications reviewed within 48 hours" │
└──────────────────────────────────────────┘
```

---

## Page Type: Thank You / Confirmation Page

**Purpose:** Confirm the action, set expectations, and optionally present next steps
**Key opportunity:** Often the most under-utilized page in a funnel

### Thank You Page Architecture

```
┌──────────────────────────────────────────┐
│  ✓ Success! [Confirmation message]       │
│                                          │
│  What happens next:                      │
│  1. [Immediate next step]                │
│  2. [What to expect]                     │
│  3. [Timeline]                           │
│                                          │
│  OPTIONAL: Self-liquidating offer        │
│  "While you wait, check out..."          │
│  [Special offer for new subscribers]     │
│                                          │
│  OPTIONAL: Share buttons                 │
│  "Know someone who'd benefit?"           │
│                                          │
│  OPTIONAL: Survey/onboarding question    │
│  "Help us personalize your experience"   │
│                                          │
└──────────────────────────────────────────┘
```

---

## Output Format

When designing a page, provide:

### 1. Page Wireframe
Section-by-section layout with purpose of each section.

### 2. Headline Options
2-3 headline variations with rationale.

### 3. Section Copy Direction
For each section: what to say, key messaging points, and recommended length.

### 4. CTA Copy
Button text options with rationale.

### 5. Design Notes
Visual elements, images needed, trust signals, mobile considerations.

---

## Task-Specific Questions

1. What type of page do you need?
2. What comes before and after this page in your funnel?
3. What's the traffic temperature (cold, warm, hot)?
4. What's the price point of what you're selling?
5. What platform will you build it on?

---

## Related Skills

- **page-cro**: For optimizing existing pages (this skill designs new ones)
- **copywriting**: For writing the copy within each page section
- **funnel-architecture**: For the overall funnel this page belongs to
- **offer-creation**: For the offer being presented on the page
- **form-cro**: For optimizing form elements on order/application pages
