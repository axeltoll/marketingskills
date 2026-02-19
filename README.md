# Marketing Skills for Claude Code

A collection of AI agent skills focused on marketing tasks — from funnel architecture and offer design to conversion optimization, copywriting, SEO, and growth engineering. Built for marketers, founders, and entrepreneurs who want Claude Code (or similar AI coding assistants) to help build complete marketing systems.

Originally built by [Corey Haines](https://corey.co?ref=marketingskills). Need hands-on help? Check out [Conversion Factory](https://conversionfactory.co?ref=marketingskills) — Corey's agency for conversion optimization, landing pages, and growth strategy. Want to learn more about marketing? Subscribe to [Swipe Files](https://swipefiles.com?ref=marketingskills).

New to the terminal and coding agents? Check out the companion guide [Coding for Marketers](https://codingformarketers.com?ref=marketingskills).

**Funnel Profits AI Engine extension by [axeltoll](https://github.com/axeltoll)** — Added 12 new skills and enhanced 10 existing skills with funnel architecture, story-based selling, offer design, and multi-business-model support. See [What's New](#whats-new-funnel-profits-ai-engine-by-axeltoll) below.

**Contributions welcome!** Found a way to improve a skill or have a new one to add? [Open a PR](#contributing).

## What are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you add these to your project, Claude Code can recognize when you're working on a marketing task and apply the right frameworks and best practices.

## Available Skills

Legend: **NEW** = Created by axeltoll | **ENHANCED** = Original by Corey Haines, enhanced by axeltoll | *No tag* = Original by Corey Haines (unchanged)

<!-- SKILLS:START -->
| Skill | Description | Author |
|-------|-------------|--------|
| [ab-test-setup](skills/ab-test-setup/) | A/B test and experiment design | Corey Haines |
| [analytics-tracking](skills/analytics-tracking/) | Event tracking and measurement setup | Corey Haines |
| [cold-email](skills/cold-email/) | B2B cold outreach emails and follow-up sequences | Jiliac |
| [competitor-alternatives](skills/competitor-alternatives/) | Competitor comparison and alternative pages | Corey Haines |
| [content-strategy](skills/content-strategy/) | Content planning, pillars, and funnel alignment | **ENHANCED** |
| [copy-editing](skills/copy-editing/) | Edit and polish existing marketing copy | Corey Haines |
| [copywriting](skills/copywriting/) | Marketing copy with story-based selling frameworks | **ENHANCED** |
| [dream-100-partnerships](skills/dream-100-partnerships/) | Influencer, JV, and strategic partnership strategy | **NEW** |
| [email-sequence](skills/email-sequence/) | Email sequences, Soap Opera/Seinfeld, behavioral segmentation | **ENHANCED** |
| [expert-positioning](skills/expert-positioning/) | Personal brand, Attractive Character, authority building | **NEW** |
| [form-cro](skills/form-cro/) | Lead capture and contact form optimization | Corey Haines |
| [free-tool-strategy](skills/free-tool-strategy/) | Free tools for marketing and lead generation | Corey Haines |
| [funnel-analytics](skills/funnel-analytics/) | Funnel metrics, dashboards, and bottleneck analysis | **NEW** |
| [funnel-architecture](skills/funnel-architecture/) | Sales funnel design — squeeze, tripwire, webinar, VSL, application | **NEW** |
| [launch-strategy](skills/launch-strategy/) | Product launches with PLF and content launch frameworks | **ENHANCED** |
| [lead-magnet-strategy](skills/lead-magnet-strategy/) | Lead magnet design, creation, and optimization | **NEW** |
| [marketing-ideas](skills/marketing-ideas/) | 140+ marketing ideas and inspiration | Corey Haines |
| [marketing-psychology](skills/marketing-psychology/) | 70+ mental models, Big Domino, trial closes | **ENHANCED** |
| [membership-continuity](skills/membership-continuity/) | Membership programs, retention, and recurring revenue | **NEW** |
| [offer-creation](skills/offer-creation/) | Irresistible offer design — value stacking, guarantees, urgency | **NEW** |
| [onboarding-cro](skills/onboarding-cro/) | Post-signup activation and time-to-value | Corey Haines |
| [page-cro](skills/page-cro/) | Marketing page conversion optimization | Corey Haines |
| [paid-ads](skills/paid-ads/) | Paid campaigns with funnel-specific ad strategies | **ENHANCED** |
| [paywall-upgrade-cro](skills/paywall-upgrade-cro/) | In-app upgrades, order bumps, OTOs, upsell flows | **ENHANCED** |
| [popup-cro](skills/popup-cro/) | Popup and modal optimization | Corey Haines |
| [pricing-strategy](skills/pricing-strategy/) | Pricing across SaaS, info products, coaching, and e-commerce | **ENHANCED** |
| [product-marketing-context](skills/product-marketing-context/) | Positioning foundation with Value Ladder and Attractive Character | **ENHANCED** |
| [programmatic-seo](skills/programmatic-seo/) | SEO-driven pages at scale | Corey Haines |
| [referral-program](skills/referral-program/) | Referral and affiliate programs | Corey Haines |
| [sales-page-architecture](skills/sales-page-architecture/) | Page design — sales, squeeze, OTO, order form, application | **NEW** |
| [schema-markup](skills/schema-markup/) | Structured data and schema markup | Corey Haines |
| [seo-audit](skills/seo-audit/) | Technical and on-page SEO audit | Corey Haines |
| [signup-flow-cro](skills/signup-flow-cro/) | Registration and trial activation flow optimization | Corey Haines |
| [social-content](skills/social-content/) | Social content with Hook/Story/Offer framework | **ENHANCED** |
| [story-based-selling](skills/story-based-selling/) | Narrative persuasion, false belief architecture, Three Secrets | **NEW** |
| [value-ladder-design](skills/value-ladder-design/) | Customer ascension model from free to premium | **NEW** |
| [video-sales-content](skills/video-sales-content/) | VSL scripts, video ads, demos, and video funnels | **NEW** |
| [webinar-script](skills/webinar-script/) | Perfect Webinar framework and presentation scripting | **NEW** |
<!-- SKILLS:END -->

## Installation

### Option 1: CLI Install (Recommended)

Use [npx skills](https://github.com/vercel-labs/skills) to install skills directly:

```bash
# Install all skills
npx skills add coreyhaines31/marketingskills

# Install specific skills
npx skills add coreyhaines31/marketingskills --skill page-cro copywriting

# List available skills
npx skills add coreyhaines31/marketingskills --list
```

This automatically installs to your `.claude/skills/` directory.

### Option 2: Claude Code Plugin

Install via Claude Code's built-in plugin system:

```bash
# Add the marketplace
/plugin marketplace add coreyhaines31/marketingskills

# Install all marketing skills
/plugin install marketing-skills
```

### Option 3: Clone and Copy

Clone the entire repo and copy the skills folder:

```bash
git clone https://github.com/coreyhaines31/marketingskills.git
cp -r marketingskills/skills/* .claude/skills/
```

### Option 4: Git Submodule

Add as a submodule for easy updates:

```bash
git submodule add https://github.com/coreyhaines31/marketingskills.git .claude/marketingskills
```

Then reference skills from `.claude/marketingskills/skills/`.

### Option 5: Fork and Customize

1. Fork this repository
2. Customize skills for your specific needs
3. Clone your fork into your projects

### Option 6: SkillKit (Multi-Agent)

Use [SkillKit](https://github.com/rohitg00/skillkit) to install skills across multiple AI agents (Claude Code, Cursor, Copilot, etc.):

```bash
# Install all skills
npx skillkit install coreyhaines31/marketingskills

# Install specific skills
npx skillkit install coreyhaines31/marketingskills --skill page-cro copywriting

# List available skills
npx skillkit install coreyhaines31/marketingskills --list
```

## Usage

Once installed, just ask Claude Code to help with marketing tasks:

```
"Help me optimize this landing page for conversions"
→ Uses page-cro skill

"Write homepage copy for my SaaS"
→ Uses copywriting skill

"Set up GA4 tracking for signups"
→ Uses analytics-tracking skill

"Create a 5-email welcome sequence"
→ Uses email-sequence skill
```

You can also invoke skills directly:

```
/page-cro
/email-sequence
/seo-audit
```

## What's New: Funnel Profits AI Engine by axeltoll

*Date: February 17, 2026*

This fork extends Corey Haines' original 25 marketing skills with **12 brand-new skills** and **10 enhanced skills** (v1.0.0 → v2.0.0), adding the strategic and architectural layers needed to build complete funnel-based marketing systems. Based on Russell Brunson's Secrets Trilogy, Alex Hormozi's offer frameworks, and industry best practices.

### 12 New Skills (Created by axeltoll)

| Skill | What It Covers |
|-------|---------------|
| `value-ladder-design` | Customer ascension model — free → front-end → core → premium → continuity |
| `funnel-architecture` | 7 funnel types: squeeze, tripwire, webinar, VSL, application, PLF, summit |
| `offer-creation` | Irresistible offer design — Grand Slam Offer framework, value stacking, Stack Slide, guarantees, urgency/scarcity |
| `expert-positioning` | Attractive Character framework (4 identity types), authority building, movement building, proprietary frameworks |
| `sales-page-architecture` | Page wireframes for 7 page types: long-form sales, squeeze, VSL, OTO, order form, bridge, application |
| `webinar-script` | Perfect Webinar framework — 3-act structure, Three Secrets, Stack Slide close, slide templates |
| `video-sales-content` | VSL scripting, video ad scripts by platform, demo video structure, testimonial guidelines |
| `lead-magnet-strategy` | Lead magnet types (4 tiers), naming formulas, opt-in page optimization, delivery sequences |
| `dream-100-partnerships` | Systematic Dream 100 methodology — identification, relationship building, outreach templates, JV/affiliate programs |
| `funnel-analytics` | Funnel metrics by type, EPC vs CPC, bottleneck identification, dashboard design, testing framework |
| `membership-continuity` | 5 membership models, retention strategy, churn reduction tactics, cancellation save flows, community engagement |

### 10 Enhanced Skills (Original by Corey Haines, enhanced by axeltoll)

| Skill | What Was Added |
|-------|---------------|
| `product-marketing-context` | Value Ladder mapping, Origin Story (Epiphany Bridge), Attractive Character profile, Big Domino Statement, Dream 100 Targets |
| `copywriting` | Hook/Story/Offer framework, Epiphany Bridge script, New Opportunity vs Improvement positioning, Story Types Library, Big Domino |
| `email-sequence` | Soap Opera Sequence (5-email story-driven welcome), Seinfeld Daily Broadcast, Behavioral Email Segmentation, Ascension Sequences |
| `social-content` | Hook/Story/Offer System with platform-specific templates (LinkedIn, Twitter/X, Instagram, TikTok) |
| `pricing-strategy` | Info product/course pricing, free+shipping model, payment plan structures, value stacking methodology, trial close pricing presentation |
| `marketing-psychology` | Big Domino concept, New Opportunity vs Improvement, Trial Closes, 3 Secrets Framework, Stack Slide closing technique |
| `paid-ads` | Funnel-specific ad strategies: lead magnet ads, webinar registration ads, tripwire ads, high-ticket application ads, funnel-aware retargeting |
| `launch-strategy` | Product Launch Formula (PLF) — 4-video pre-launch sequence, content-based launch framework |
| `paywall-upgrade-cro` | Order bumps (design + metrics), One-Time Offers (OTO page structure + sequencing), post-purchase upsell strategies |
| `content-strategy` | Dream 100 content strategy, content funnel alignment (awareness → advocacy), content repurposing for funnels |

### 15 Unchanged Skills (Original by Corey Haines)

`ab-test-setup`, `analytics-tracking`, `competitor-alternatives`, `copy-editing`, `form-cro`, `free-tool-strategy`, `marketing-ideas`, `onboarding-cro`, `page-cro`, `popup-cro`, `programmatic-seo`, `referral-program`, `schema-markup`, `seo-audit`, `signup-flow-cro`

---

## Skill Categories

### Funnel Architecture & Strategy
- `value-ladder-design` - Customer ascension from free to premium
- `funnel-architecture` - Sales funnel types, selection, and design
- `offer-creation` - Irresistible offer building (value stacking, guarantees)
- `expert-positioning` - Personal brand and Attractive Character framework
- `lead-magnet-strategy` - Lead magnet design, creation, and optimization

### Content & Copy
- `copywriting` - Marketing copy with Epiphany Bridge and HSO frameworks
- `copy-editing` - Edit and polish existing copy
- `email-sequence` - Email sequences with Soap Opera/Seinfeld and behavioral segmentation
- `social-content` - Social content with Hook/Story/Offer system
- `sales-page-architecture` - Page-type-specific design (sales, squeeze, OTO, application)
- `content-strategy` - Content planning with Dream 100 and funnel alignment

### Conversion Optimization
- `page-cro` - Any marketing page
- `signup-flow-cro` - Registration flows
- `onboarding-cro` - Post-signup activation
- `form-cro` - Lead capture forms
- `popup-cro` - Modals and overlays
- `paywall-upgrade-cro` - In-app upgrades, order bumps, OTOs

### Video & Presentations
- `webinar-script` - Perfect Webinar framework and presentation scripting
- `video-sales-content` - VSL scripts, video ads, demos, and video funnels

### Outreach
- `cold-email` - B2B cold outreach emails and sequences

### SEO & Discovery
- `seo-audit` - Technical and on-page SEO
- `programmatic-seo` - Scaled page generation
- `competitor-alternatives` - Comparison and alternative pages
- `schema-markup` - Structured data

### Traffic & Growth
- `paid-ads` - Paid campaigns with funnel-specific ad strategies
- `dream-100-partnerships` - Influencer, JV, and strategic partnership strategy
- `launch-strategy` - Product launches with PLF and content launch frameworks
- `referral-program` - Referral and affiliate programs

### Measurement & Testing
- `analytics-tracking` - Event tracking setup
- `ab-test-setup` - Experiment design
- `funnel-analytics` - Funnel-specific metrics and bottleneck analysis

### Strategy & Monetization
- `marketing-ideas` - 140+ marketing ideas
- `marketing-psychology` - 70+ mental models and persuasion frameworks
- `pricing-strategy` - Pricing across SaaS, info products, coaching, and e-commerce
- `membership-continuity` - Membership programs and recurring revenue
- `free-tool-strategy` - Marketing tools and calculators

### Foundation
- `product-marketing-context` - Positioning with Value Ladder and Attractive Character

## Contributing

Found a way to improve a skill? Have a new skill to suggest? PRs and issues welcome!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on adding or improving skills.

## License

[MIT](LICENSE) - Use these however you want.
