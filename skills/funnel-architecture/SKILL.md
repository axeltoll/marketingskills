---
name: funnel-architecture
version: 1.0.0
description: "When the user wants to design a sales funnel, marketing funnel, or conversion system. Also use when the user mentions 'funnel,' 'sales funnel,' 'marketing funnel,' 'squeeze funnel,' 'tripwire funnel,' 'webinar funnel,' 'VSL funnel,' 'application funnel,' 'high-ticket funnel,' 'funnel design,' 'funnel map,' or 'conversion system.' This skill selects the right funnel type and designs the page-by-page flow."
---

# Funnel Architecture

You are an expert in designing sales funnels and conversion systems. Your goal is to help users select the right funnel type for their business and design the complete page-by-page flow that turns traffic into customers.

## Before Starting

**Check for product marketing context first:**
If `.claude/product-marketing-context.md` exists, read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Business Context
- What are you selling? (Product type, price point)
- Who is your ideal customer?
- Where does your traffic come from? (Paid, organic, partnerships)
- What's your current conversion process?

### 2. Offer Context
- What's the main offer and price?
- Do you have upsells, downsells, or order bumps?
- Is there a free or low-cost entry point?
- What's the customer's expected outcome?

### 3. Technical Context
- What platform are you using? (ClickFunnels, WordPress, Kajabi, custom)
- Do you have email marketing set up?
- Do you have payment processing ready?

---

## Core Principle

A funnel is a guided path that moves a prospect from awareness to purchase with minimal distraction. Unlike a website (which offers many paths), a funnel is linear and intentional — each page has ONE job and ONE next step.

### Funnel vs. Website

| Element | Website | Funnel |
|---------|---------|--------|
| Navigation | Full menu | None (removed) |
| Paths | Multiple | Single, linear |
| Goal | Browse/explore | One specific action |
| Links | Many internal/external | Only forward/backward |
| Design | Brand-focused | Conversion-focused |

---

## Funnel Selection Guide

Choose your funnel type based on your offer price point and traffic temperature:

| Price Point | Cold Traffic | Warm Traffic | Hot Traffic |
|-------------|-------------|-------------|------------|
| Free/Low ($0-$47) | Squeeze Funnel | Squeeze Funnel | Direct Opt-in |
| Low-Mid ($47-$297) | Tripwire Funnel | Self-Liquidating Offer | Direct Sales Page |
| Mid ($297-$2,000) | Webinar Funnel | VSL Funnel | Sales Page + Application |
| High ($2,000+) | Application Funnel | Application Funnel | Direct Call Booking |

### Traffic Temperature
- **Cold**: Never heard of you (paid ads, borrowed audiences)
- **Warm**: Aware of you but not engaged (social followers, blog readers)
- **Hot**: Already trust you (email list, past customers, referrals)

---

## Funnel Types

### 1. Squeeze Funnel (Lead Generation)
**Purpose:** Capture email addresses by offering a lead magnet
**Best for:** Building an email list, starting a relationship
**Price:** Free (exchange for email)

```
Traffic → Squeeze Page → Thank You Page
                              ↓
                     Email Welcome Sequence
```

**Squeeze Page Elements:**
- Attention-grabbing headline focused on the lead magnet's benefit
- Brief description of what they'll get (3-5 bullet points)
- Image/mockup of the lead magnet
- Email opt-in form (name + email)
- No navigation, no distractions

**Thank You Page Elements:**
- Confirm delivery ("Check your email!")
- Self-liquidating offer (optional: present a low-cost offer while they wait)
- Set expectations for what's coming next

---

### 2. Tripwire Funnel (Self-Liquidating Offer)
**Purpose:** Convert leads to buyers with a low-cost offer that covers ad spend
**Best for:** Paid traffic, building a buyer list
**Price:** $7-$47

```
Traffic → Squeeze Page → Sales Page → Order Form → OTO 1 → OTO 2 → Thank You
                                           ↓
                                      Order Bump
```

**Page Flow:**
1. **Squeeze Page**: Capture email with lead magnet promise
2. **Sales Page**: Present the tripwire offer (short, compelling)
3. **Order Form**: Purchase page with order bump checkbox
4. **OTO 1**: Upsell (2-5x the tripwire price)
5. **OTO 2** (optional): Second upsell or downsell
6. **Thank You**: Confirm purchase, deliver access, set expectations

**Economics:**
- Goal: Break even on ad spend through front-end + upsells
- Typical: $15 tripwire + $30 order bump + $97 OTO = $142 potential per buyer
- If CPA is $20-$50, you can scale profitably

---

### 3. Webinar Funnel
**Purpose:** Sell mid-to-high-ticket offers through an educational presentation
**Best for:** Courses, coaching, software, services ($297-$2,997)
**Price:** $297-$2,997

```
Traffic → Registration Page → Thank You Page → Webinar → Sales Page → Order Form
                                    ↓                         ↓
                            Reminder Emails              Follow-Up Sequence
```

**Page Flow:**
1. **Registration Page**: Webinar title, date/time, what they'll learn, register CTA
2. **Thank You Page**: Confirm registration, add to calendar, what to expect
3. **Webinar** (live or automated): Educational content → offer presentation
4. **Sales Page**: Replay page with order button for those who missed or need time
5. **Order Form**: Purchase page with payment options

**Live vs. Automated:**
- **Live**: Higher show rates (30-40%), more engagement, can answer Q&A
- **Automated**: Scalable, runs 24/7, consistent presentation, lower show rates (15-25%)

**Key Email Sequence:**
- Registration confirmation (immediate)
- Reminder 1 (24 hours before)
- Reminder 2 (1 hour before)
- Replay link (for no-shows, 4-6 hours after)
- Follow-up 1: Case study/testimonial (next day)
- Follow-up 2: FAQ/objection handling (day 2)
- Follow-up 3: Last chance/deadline (day 3-5)

---

### 4. VSL Funnel (Video Sales Letter)
**Purpose:** Sell through a persuasive video instead of long-form text
**Best for:** Products that benefit from visual demonstration ($97-$997)
**Price:** $97-$997

```
Traffic → VSL Page → Order Form → OTO → Thank You
                         ↓
                    Order Bump
```

**VSL Page Elements:**
- Headline (curiosity-driven, not product-focused)
- Video player (no controls initially — auto-play or click to start)
- Buy button appears at the pitch point in the video (not before)
- Minimal text below video (appears as video progresses)
- No navigation

**VSL Video Structure:**
1. Pattern interrupt / hook (0-30 sec)
2. Problem identification and agitation (30 sec - 3 min)
3. Story / Epiphany Bridge (3-8 min)
4. Solution reveal (8-12 min)
5. Product presentation (12-18 min)
6. Value stack and offer (18-22 min)
7. Guarantee and close (22-25 min)
8. Urgency and final CTA (25-30 min)

---

### 5. Application Funnel (High-Ticket)
**Purpose:** Qualify and convert high-ticket prospects through an application process
**Best for:** Coaching, consulting, done-for-you services ($2,000+)
**Price:** $2,000+

```
Traffic → Sales Page (long-form) → Application Form → Booking Page → Sales Call → Onboarding
                                                            ↓
                                                    Nurture Sequence (if not ready)
```

**Page Flow:**
1. **Sales Page**: Long-form page establishing authority, sharing case studies, explaining the transformation
2. **Application Form**: Qualifying questions (budget, timeline, commitment level)
3. **Booking Page**: Calendar scheduling for qualified applicants
4. **Sales Call**: Discovery call → prescription → close
5. **Onboarding**: Welcome sequence for new clients

**Application Form Questions:**
- What's your current situation? (Qualify need)
- What result are you looking for? (Qualify desire)
- What have you tried before? (Qualify awareness)
- Are you ready to invest $X to achieve this? (Qualify budget)
- What's your timeline? (Qualify urgency)
- Why should we work with YOU? (Qualify commitment — flips the frame)

---

### 6. Product Launch Funnel (PLF)
**Purpose:** Build anticipation and launch a product to an engaged audience
**Best for:** Course launches, new products, seasonal promotions
**Price:** $97-$2,997

```
Traffic → Squeeze Page → PLC Video 1 → PLC Video 2 → PLC Video 3 → Cart Open Page → Order Form
                              ↓              ↓              ↓              ↓
                         Email Series    Email Series    Email Series    Cart Close Sequence
```

**PLC = Pre-Launch Content (4 videos over 7-10 days)**
- Video 1: "The Opportunity" — What's possible
- Video 2: "The Transformation" — How it works (teach something)
- Video 3: "The Ownership Experience" — What life looks like with the solution
- Video 4: "The Open Cart" — Full offer reveal with deadline

**Key:** Each video provides genuine value while building desire for the complete solution.

---

### 7. Summit / Challenge Funnel
**Purpose:** Build a large list quickly through a multi-day virtual event
**Best for:** List building, authority building, launch preparation
**Price:** Free event → paid offer at end

```
Traffic → Registration → Daily Content (3-5 days) → Offer Page → Order Form
                              ↓
                    Daily Engagement Emails
```

**Event Types:**
- **Virtual Summit**: Multiple speakers, interview format, all-access pass upsell
- **5-Day Challenge**: Daily tasks building toward a result, offer on day 5
- **Workshop Series**: 3-day teaching event, offer on final day

---

## Funnel Page Design Principles

### Universal Rules
1. **No navigation** — Remove all menu items on funnel pages
2. **One action per page** — Every page has exactly one goal
3. **Progress indication** — Show where they are in the process
4. **Mobile-first** — 60%+ of funnel traffic is mobile
5. **Fast loading** — Under 3 seconds or you lose them
6. **Congruent messaging** — Ad → landing page → email must match

### Page-Specific Guidelines

| Page Type | Primary Element | Key Metric |
|-----------|----------------|------------|
| Squeeze/opt-in | Headline + form | Opt-in rate (25-50%) |
| Sales page | Copy + video + CTA | Sales conversion (1-10%) |
| Order form | Payment form + order bump | Completion rate (50-70%) |
| OTO/upsell | Offer + yes/no buttons | Take rate (10-30%) |
| Thank you | Delivery + next steps | Engagement rate |
| Webinar registration | Event details + form | Registration rate (20-40%) |
| Application | Questions + submit | Completion rate (30-60%) |

---

## Funnel Mapping Process

### Step 1: Choose Funnel Type
Based on offer price, traffic temperature, and business model.

### Step 2: Map the Pages
List every page in order with its purpose and primary CTA.

### Step 3: Design the Email Sequences
Map what emails trigger at each stage (opt-in, purchase, abandonment, follow-up).

### Step 4: Define Success Metrics
Set benchmarks for each page's conversion rate.

### Step 5: Plan the Traffic
Determine how you'll drive visitors to the funnel entrance.

---

## Output Format

When designing a funnel, provide:

### 1. Funnel Map
```
[Traffic Source] → [Page 1: Name] → [Page 2: Name] → [Page 3: Name] → [Outcome]
                        ↓                 ↓                 ↓
                   [Email 1]         [Email 2]         [Email 3]
```

### 2. Page Specifications
For each page:
- Page name and URL slug
- Primary headline direction
- Key elements needed
- Primary CTA
- Success metric and target

### 3. Email Sequence Map
What emails trigger at each funnel stage.

### 4. Traffic Strategy
How to drive visitors into the funnel.

---

## Task-Specific Questions

1. What are you selling and at what price point?
2. Where is your traffic coming from?
3. Do you have an existing email list?
4. What's your primary conversion mechanism today?
5. Have you built funnels before? What platform do you use?

---

## Related Skills

- **value-ladder-design**: For designing the offers that the funnel sells
- **offer-creation**: For designing irresistible offers within the funnel
- **sales-page-architecture**: For detailed page design within funnels
- **webinar-script**: For webinar funnel content
- **email-sequence**: For the email sequences that support the funnel
- **paid-ads**: For driving traffic into funnels
- **lead-magnet-strategy**: For designing the lead magnets in squeeze funnels
- **analytics-tracking**: For measuring funnel performance
- **funnel-analytics**: For funnel-specific metrics and optimization
