# NUBUILDCo -- Meta Ads Creative Strategy

**Prepared by:** ZippyScale Performance Marketing
**Client:** NUBUILDCo (New Build)
**Founder:** VijayKrishna Guttikonda
**Date:** February 6, 2026
**Version:** 1.0
**Classification:** Internal -- ZippyScale Team Only

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [Campaign Architecture](#2-campaign-architecture)
3. [Creative Themes](#3-creative-themes)
4. [Static Ad Matrix](#4-static-ad-matrix)
5. [Carousel Concepts](#5-carousel-concepts)
6. [Video Ad Concepts](#6-video-ad-concepts)
7. [Hook Testing Matrix](#7-hook-testing-matrix)
8. [Testing Framework and Weekly Plan](#8-testing-framework-and-weekly-plan)
9. [File Naming Convention](#9-file-naming-convention)
10. [Production Timeline](#10-production-timeline)

---

## 1. Executive Summary

### The Business

NUBUILDCo is a premium end-to-end construction, interiors, and design consultation firm based in Banjara Hills, Hyderabad. Led by VijayKrishna Guttikonda (6+ years experience, Rs.25Cr+ delivered), the firm handles everything from architecture through construction through interiors through handover -- eliminating the multi-vendor chaos that plagues high-value homebuilders in Hyderabad.

**Sweet spot:** Rs.50L -- Rs.5Cr projects | Rs.2,200 -- Rs.10,000/sq.ft.
**Minimum project:** Rs.30L
**Landing page:** https://nubuildco.netlify.app

### Campaign Objective

Generate 15-17 qualified leads over 4 weeks from affluent Hyderabad West homeowners/builders, resulting in 8-10 consultations and 2 closures. One closure at the sweet-spot range pays for the entire campaign many times over.

### Budget Summary

| Line Item | Amount | % of Total |
|---|---|---|
| Lead Generation (Campaigns 1 + 2) | Rs.85,000 | 85% |
| Retargeting (Campaign 3) | Rs.10,000 | 10% |
| Buffer / Testing | Rs.5,000 | 5% |
| **Total** | **Rs.1,00,000** | **100%** |

### Target KPIs

| Metric | Target | Notes |
|---|---|---|
| CTR (Link Click-Through Rate) | 1.5% -- 2.5% | Above 2% = strong creative-audience fit |
| CPL (Cost Per Lead) | Rs.600 -- Rs.700 | Blended across all campaigns |
| Total Leads | 15 -- 17 | Over 4-week flight |
| Consultations Booked | 8 -- 10 | ~60% lead-to-consultation rate |
| Closures | 2 | ~20-25% consultation-to-close rate |
| Frequency Cap | < 3.0 | Per ad set, per week |
| Relevance Score | > 7 | Monitor in Ads Manager |

### Target Audience Profile

| Attribute | Detail |
|---|---|
| **Demographics** | Age 35-55, Male + Female (joint decision), HHI Rs.2Cr+ |
| **Professions** | Business owners, CXOs, Doctors, Lawyers, CAs, IT professionals (L7+), NRIs |
| **Geography** | Hyderabad West: Banjara Hills, Jubilee Hills, Gachibowli, Kondapur, Madhapur, Financial District, Nanakramguda, Manikonda |
| **Decision Dynamic** | Joint (husband + wife). Both must be reached. |
| **Purchase Triggers** | New plot purchase, old home renovation, investment property build |
| **Pain Points** | (1) Budget overruns (2) Contractor chaos / multi-vendor nightmare (3) Timeline delays |
| **Red Flag Leads** | Budget below Rs.30L, "just planning / no timeline," price-shopping only |

### Offers (Funnel Stages)

| Offer | Funnel Stage | Intent Level | Price | Purpose |
|---|---|---|---|---|
| Offer 1: Rs.4,999 Design Consultation | Bottom-of-Funnel | HIGH | Rs.4,999 (paid) | Qualifies serious buyers. Payment = commitment filter. |
| Offer 2: Free 2026 Hyderabad Home Building Cost Guide | Top-of-Funnel | MEDIUM | Free (lead magnet) | Captures planning-stage leads. Nurture into consultation. |
| Offer 3: Free 15-Min Strategy Call | Mid-Funnel | MEDIUM-HIGH | Free | Lower friction than paid consult. Captures ready-but-hesitant. |

---

## 2. Campaign Architecture

### Meta Ads Manager Structure

```
Account: NUBUILDCo
|
+-- Campaign 1: [LEAD-GEN] Rs.4,999 Design Consultation
|   +-- Ad Set 1A: Interest - Interior Design + Home Decor
|   +-- Ad Set 1B: Interest - Business Owners + Entrepreneurs
|   +-- Ad Set 1C: Interest - Luxury Real Estate + Property Investment
|
+-- Campaign 2: [LEAD-GEN] Free Cost Guide Download
|   +-- Ad Set 2A: Interest - Home Improvement + Renovation
|   +-- Ad Set 2B: Interest - Architecture + Design
|   +-- Ad Set 2C: Interest - High Income Professionals (Doctors, CAs, Lawyers)
|
+-- Campaign 3: [RETARGETING] Website Visitors + Engagers (Week 2+)
|   +-- Ad Set 3A: Website Visitors (last 30 days)
|   +-- Ad Set 3B: FB/IG Engagers (last 30 days)
|   +-- Ad Set 3C: Video Viewers 50%+ (when available)
```

### Campaign 1: Lead Gen -- Rs.4,999 Design Consultation

**Objective:** Leads (Instant Form or Website Conversions)
**Optimization Event:** Lead
**Bid Strategy:** Lowest cost (auto-bid)
**Budget:** Rs.45,000 total (Rs.1,500/day for 30 days)
**Placement:** Automatic (Facebook Feed, Instagram Feed, Instagram Stories, Facebook Stories, Reels)
**Attribution Window:** 7-day click, 1-day view

| Ad Set | Targeting | Daily Budget | Audience Size (est.) |
|---|---|---|---|
| 1A: Interior Design | Interests: Interior design, home decor, Architectural Digest, Houzz, home furnishing. Geo: Hyderabad West. Age: 35-55. | Rs.500/day | 120K-250K |
| 1B: Business Owners | Interests: Entrepreneurship, business owner, small business, startup company. Behaviors: Business page admins. Geo: Hyderabad West. Age: 35-55. | Rs.500/day | 80K-180K |
| 1C: Luxury Real Estate | Interests: Luxury real estate, property investment, real estate investing, NoBroker, 99acres, MagicBricks. Geo: Hyderabad West. Age: 35-55. | Rs.500/day | 100K-200K |

**Exclusions across all ad sets:**
- Custom audience: Existing leads (upload list)
- Age below 35, above 55
- Location outside Hyderabad metro

### Campaign 2: Lead Gen -- Free Cost Guide

**Objective:** Leads (Instant Form)
**Optimization Event:** Lead
**Bid Strategy:** Lowest cost
**Budget:** Rs.40,000 total (Rs.1,350/day for 30 days)
**Placement:** Automatic
**Attribution Window:** 7-day click, 1-day view

| Ad Set | Targeting | Daily Budget | Audience Size (est.) |
|---|---|---|---|
| 2A: Home Improvement | Interests: Home improvement, renovation, home remodeling, DIY home. Geo: Hyderabad West. Age: 35-55. | Rs.450/day | 150K-300K |
| 2B: Architecture | Interests: Architecture, modern architecture, residential architecture, interior architecture, civil engineering. Geo: Hyderabad West. Age: 35-55. | Rs.450/day | 80K-160K |
| 2C: High Income Professionals | Interests: Medical profession, chartered accountant, legal profession, IT industry. Job titles: Doctor, CA, Advocate, Software Engineer (L7+). Geo: Hyderabad West. Age: 35-55. | Rs.450/day | 100K-220K |

### Campaign 3: Retargeting (Launches Week 2)

**Objective:** Leads (Instant Form or Website Conversions)
**Optimization Event:** Lead
**Bid Strategy:** Lowest cost
**Budget:** Rs.10,000 total (Rs.500/day for 20 days, starting Week 2)
**Placement:** Automatic
**Attribution Window:** 7-day click, 1-day view

| Ad Set | Audience Source | Daily Budget | Notes |
|---|---|---|---|
| 3A: Website Visitors | Facebook Pixel -- All page visitors, last 30 days. Exclude: Already submitted form. | Rs.200/day | Warm audience. Serve Offer 1 (Consultation). |
| 3B: Engagers | People who engaged with FB/IG page or ads in last 30 days. | Rs.200/day | Serve Offer 1 with testimonial/authority hooks. |
| 3C: Video Viewers | People who watched 50%+ of any video ad. | Rs.100/day | Activate once video assets are live. Serve Offer 1. |

**Retargeting Creative Strategy:**
- Heavier push on Offer 1 (paid consultation) since these audiences have already shown interest
- Use objection-handling copy: "Still thinking about your dream home?"
- Use social proof: "Rs.25Cr+ in projects delivered"
- Use urgency: "2026 construction costs are rising -- lock in your design consultation now"

### Budget Flow Summary

| Week | Campaign 1 | Campaign 2 | Campaign 3 | Daily Total | Weekly Total |
|---|---|---|---|---|---|
| Week 1 (Days 1-7) | Rs.1,500/day | Rs.1,350/day | -- | Rs.2,850/day | Rs.19,950 |
| Week 2 (Days 8-14) | Rs.1,500/day | Rs.1,350/day | Rs.500/day | Rs.3,350/day | Rs.23,450 |
| Week 3 (Days 15-21) | Rs.1,500/day | Rs.1,350/day | Rs.500/day | Rs.3,350/day | Rs.23,450 |
| Week 4 (Days 22-30) | Rs.1,500/day | Rs.1,350/day | Rs.500/day | Rs.3,350/day | Rs.30,150 |
| **Total** | **Rs.45,000** | **Rs.40,500** | **Rs.10,000** | -- | **Rs.95,550** |
| Buffer | -- | -- | -- | -- | Rs.4,450 |

*Note: Budget will shift dynamically based on Week 1 performance. Winning ad sets get budget increases; underperformers get paused. The Rs.4,450 buffer covers ad set rebalancing and creative testing.*

---

## 3. Creative Themes

### Theme 1: Transformation Story

**Core Message:** "From empty plot to dream home -- this is what NUBUILDCo delivers."
**Emotional Lever:** Aspiration, pride of ownership, "imagine living here"
**Visual Direction:** Before/after, hero interior shots, dramatic reveals

| Element | Copy |
|---|---|
| **Hook (Primary Text, Line 1)** | "This was an empty plot 8 months ago." |
| **Body** | "Today, it's a home that stops people in their tracks. NUBUILDCo handled everything -- architecture, construction, interiors, handover. One team. Zero chaos. This is what end-to-end looks like." |
| **Headline** | Your Dream Home, Designed and Delivered |
| **Description** | Premium construction and interiors in Hyderabad. Rs.2,200/sq.ft. onwards. |
| **CTA Button** | Learn More / Book Now |

### Theme 2: End-to-End Promise

**Core Message:** "Why hire 5 vendors when one team does it all?"
**Emotional Lever:** Relief, simplicity, control
**Visual Direction:** Process-oriented, split panels showing all 4 stages, timeline visuals

| Element | Copy |
|---|---|
| **Hook (Primary Text, Line 1)** | "Hiring a contractor, then a designer, then an interior firm, then a project manager..." |
| **Body** | "Sound exhausting? It is. That's exactly why NUBUILDCo exists. We handle architecture, construction, interiors, and handover -- under one roof, with one team, at one price. No vendor juggling. No finger-pointing. No surprises." |
| **Headline** | One Team. Start to Finish. |
| **Description** | Architecture + Construction + Interiors + Handover. All NUBUILDCo. |
| **CTA Button** | Book Now / Learn More |

### Theme 3: Fear Resolution

**Core Message:** "We solve the 3 nightmares of home-building: budget overruns, contractor chaos, and delays."
**Emotional Lever:** Fear of loss, anxiety relief, "finally someone gets it"
**Visual Direction:** Dark/moody backgrounds with bold text overlays, contrast with luxury result

| Element | Copy |
|---|---|
| **Hook (Primary Text, Line 1)** | "Quoted Rs.50 lakhs. Final bill: Rs.80 lakhs. Sound familiar?" |
| **Body** | "Budget overruns. Endless delays. Five different contractors pointing fingers at each other. We've heard this story a hundred times -- because it happens to almost every homeowner in Hyderabad. NUBUILDCo was built to end this. Fixed pricing. Fixed timelines. One accountable team. Rs.25Cr+ delivered with zero budget surprises." |
| **Headline** | No Overruns. No Delays. No Chaos. |
| **Description** | Premium construction + interiors in Hyderabad. Fixed pricing guaranteed. |
| **CTA Button** | Book Now |

### Theme 4: Premium Lifestyle

**Core Message:** "You've earned this. Build a home that matches your ambition."
**Emotional Lever:** Status, aspiration, self-reward, "you deserve this"
**Visual Direction:** Hero shots of luxurious interiors, warm lighting, cinematic feel

| Element | Copy |
|---|---|
| **Hook (Primary Text, Line 1)** | "You didn't work this hard to live in an average home." |
| **Body** | "Double-height atriums. Italian marble floors. Bespoke interiors that feel like a 5-star hotel -- but it's your home. NUBUILDCo designs and builds premium residences for Hyderabad's most discerning families. Starting at Rs.2,200/sq.ft. with end-to-end execution." |
| **Headline** | Luxury Homes for Those Who've Earned It |
| **Description** | Premium construction + interiors by NUBUILDCo. Banjara Hills, Hyderabad. |
| **CTA Button** | Learn More |

### Theme 5: Educational (Cost Guide)

**Core Message:** "Know the real cost of building in Hyderabad before you start."
**Emotional Lever:** Information asymmetry, "insider knowledge," empowerment
**Visual Direction:** Clean, data-driven, guide/PDF mockup, informational graphics

| Element | Copy |
|---|---|
| **Hook (Primary Text, Line 1)** | "How much does it actually cost to build a home in Hyderabad in 2026?" |
| **Body** | "Most people have no idea -- and that's how contractors take advantage. We've put together a free 2026 cost guide covering: per sq.ft. rates for Banjara Hills, Jubilee Hills, Gachibowli & more. Material cost breakdowns. Interior budgets by room. Realistic timelines. Download it free. No commitment." |
| **Headline** | Free: 2026 Hyderabad Home Building Cost Guide |
| **Description** | Real numbers. No fluff. Know before you build. |
| **CTA Button** | Download |

---

## 4. Static Ad Matrix

### 12 Static Ad Creatives

All ads are produced in two sizes:
- **1080 x 1080** (Square -- Facebook Feed, Instagram Feed)
- **1080 x 1350** (Portrait -- Instagram Feed, Stories)

**Color System (from brand guidelines):**
- Primary Brown: #81350B
- Dark Brown: #5C2608
- Gold Accent: #C49A6C
- Cream Background: #FAF6F1
- Dark Background: #151110
- White: #FFFFFF

**Typography (from brand guidelines):**
- Display/Headlines: Cormorant Garamond (Serif)
- Body/Subtext: Inter (Sans-serif)

---

#### OFFER 1: Rs.4,999 Design Consultation (3 Primary Statics)

##### Ad S01 -- "Transformation: Atrium Reveal"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S01-TRANSFORM-CONSULT-ATRIUM |
| **Theme** | Theme 1: Transformation Story |
| **Hook Style** | Transformation ("This was an empty plot...") |
| **Photo** | P1291276.jpg -- Double-height atrium with chandelier (HERO) |
| **Headline on Image** | "This Was an Empty Plot 8 Months Ago." |
| **Subtext on Image** | NUBUILDCo -- Architecture. Construction. Interiors. Handover. |
| **CTA on Image** | "Book Your Rs.4,999 Design Consultation" (button-style overlay, bottom) |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Dark gradient overlay bottom 40%. White text on gradient. Gold accent on CTA button (#C49A6C). NUBUILDCo logo (white) top-left corner. |
| **Primary Text** | "This was an empty plot 8 months ago. Today, it's a home that stops people in their tracks. NUBUILDCo handled everything -- architecture, construction, interiors, handover. One team. Zero chaos. Book a Rs.4,999 design consultation and see what we'd create for your plot." |
| **Headline** | Your Dream Home, Designed and Delivered |
| **CTA Button** | Book Now |

##### Ad S02 -- "End-to-End: Grand Foyer"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S02-E2E-CONSULT-FOYER |
| **Theme** | Theme 2: End-to-End Promise |
| **Hook Style** | Question ("Why hire 5 vendors?") |
| **Photo** | P1291319.jpg -- Grand foyer with wood doors |
| **Headline on Image** | "Why Hire 5 Vendors When One Team Does It All?" |
| **Subtext on Image** | Design / Construction / Interiors / Handover |
| **CTA on Image** | "Rs.4,999 Design Consultation -- Book Now" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Semi-transparent brown bar (#81350B at 85% opacity) across bottom third. White text. Logo top-left. Four small icons (pencil, hammer, sofa, key) in a row above CTA. |
| **Primary Text** | "Hiring a contractor, then a designer, then an interior firm, then a project manager... Sound exhausting? That's exactly why NUBUILDCo exists. One team. One price. One commitment. Book a Rs.4,999 design consultation -- we'll show you exactly how we'd bring your vision to life." |
| **Headline** | One Team. Start to Finish. |
| **CTA Button** | Book Now |

##### Ad S03 -- "Fear Resolution: No Overruns"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S03-FEAR-CONSULT-DINING |
| **Theme** | Theme 3: Fear Resolution |
| **Hook Style** | Fear ("Quoted Rs.50L. Final bill: Rs.80L.") |
| **Photo** | P1291461.jpg -- Elegant dining room, green chairs |
| **Headline on Image** | "Quoted Rs.50 Lakhs. Final Bill: Rs.80 Lakhs." (top, in red/warning style) followed by "Not With Us." (large, white, below) |
| **Subtext on Image** | Fixed Pricing. Fixed Timeline. Zero Surprises. |
| **CTA on Image** | "Get Your Fixed-Price Design Consultation -- Rs.4,999" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo with heavy dark overlay (70% black). Warning text in a muted red/coral (#C33E3E). "Not With Us." in large white Cormorant Garamond. CTA bar at bottom in brand brown (#81350B). Logo top-left (white). |
| **Primary Text** | "Quoted Rs.50 lakhs. Final bill: Rs.80 lakhs. Sound familiar? Budget overruns. Endless delays. Five different contractors pointing fingers. NUBUILDCo was built to end this nightmare. Fixed pricing. Fixed timelines. One accountable team. Rs.25Cr+ delivered with zero budget surprises. Book your Rs.4,999 design consultation today." |
| **Headline** | No Overruns. No Delays. No Chaos. |
| **CTA Button** | Book Now |

---

#### OFFER 2: Free Cost Guide (3 Primary Statics)

##### Ad S04 -- "Cost Guide: Educational"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S04-EDU-GUIDE-EXTERIOR |
| **Theme** | Theme 5: Educational |
| **Hook Style** | Question ("How much does it actually cost?") |
| **Photo** | P1291697.jpg -- Modern exterior architecture |
| **Headline on Image** | "How Much Does It Cost to Build a Home in Hyderabad in 2026?" |
| **Subtext on Image** | Free Cost Guide -- Real Numbers, No Fluff |
| **CTA on Image** | "Download Free Guide" (with a down-arrow icon) |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Split design: Photo on left 60%, cream (#FAF6F1) panel on right 40% with text. Brown (#81350B) headline text. A small mockup of a PDF/guide cover overlaid at the intersection. Logo at top of cream panel. |
| **Primary Text** | "How much does it actually cost to build a home in Hyderabad in 2026? Most people have no idea -- and that's how contractors take advantage. Download our free 2026 cost guide: per sq.ft. rates by locality, material costs, interior budgets, realistic timelines. No commitment required." |
| **Headline** | Free: 2026 Hyderabad Home Building Cost Guide |
| **CTA Button** | Download |

##### Ad S05 -- "Cost Guide: Data Points"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S05-EDU-GUIDE-STAIRCASE |
| **Theme** | Theme 5: Educational |
| **Hook Style** | Authority ("6+ years, Rs.25Cr+ delivered") |
| **Photo** | P1291491.jpg -- Lit staircase with stone wall |
| **Headline on Image** | "Rs.2,200 to Rs.10,000 Per Sq. Ft." (large) followed by "What Does Your Budget Actually Get You?" |
| **Subtext on Image** | 2026 Cost Guide -- Free Download |
| **CTA on Image** | "Get the Free Guide" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Dark gradient from bottom. Large price range in gold (#C49A6C). Supporting text in white. CTA button in white with brown text. Logo top-left (white). |
| **Primary Text** | "Rs.2,200 per sq.ft. or Rs.10,000? The difference is massive -- and most homeowners don't understand what drives the cost until it's too late. We put together a free guide breaking down every cost factor for building in Hyderabad in 2026. Per sq.ft. rates. Material tiers. Interior budgets. Timeline expectations. Download it before you sign your next contractor quote." |
| **Headline** | Know the Real Numbers Before You Build |
| **CTA Button** | Download |

##### Ad S06 -- "Cost Guide: Lifestyle + Education"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S06-LIFESTYLE-GUIDE-LIVING |
| **Theme** | Theme 4: Premium Lifestyle + Theme 5: Educational (hybrid) |
| **Hook Style** | Transformation ("Planning to build in 2026?") |
| **Photo** | P1291304.jpg -- Modern living room with marble |
| **Headline on Image** | "Planning to Build in 2026?" (top) followed by "Start With the Right Numbers." (center, large) |
| **Subtext on Image** | Hyderabad Home Building Cost Guide -- Free |
| **CTA on Image** | "Download Now -- It's Free" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Light warm overlay (cream tint at 20%). Text in dark brown (#3D3229). Accent line in gold above CTA. Logo bottom-right (brown). Clean, editorial feel. |
| **Primary Text** | "Planning to build a home in Hyderabad in 2026? Before you talk to a single contractor, know what things actually cost. Our free cost guide covers everything: construction rates across Banjara Hills, Jubilee Hills, Gachibowli, Kondapur. Material breakdowns. Interior budgets. And realistic timelines. No signup required. Just download and plan smarter." |
| **Headline** | Free 2026 Hyderabad Cost Guide |
| **CTA Button** | Download |

---

#### OFFER 1 -- ALTERNATE HOOKS (3 Statics)

##### Ad S07 -- "Authority: Rs.25Cr Delivered"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S07-AUTHORITY-CONSULT-LATTICE |
| **Theme** | Theme 4: Premium Lifestyle |
| **Hook Style** | Authority |
| **Photo** | P1291385.jpg -- Lattice wall with chandelier, symmetrical |
| **Headline on Image** | "Rs.25 Crore+ in Homes Delivered." (large, centered) followed by "Yours Could Be Next." |
| **Subtext on Image** | NUBUILDCo -- 6+ Years of Premium Construction |
| **CTA on Image** | "Book Rs.4,999 Design Consultation" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Minimal overlay -- just enough for text legibility (30% dark gradient from bottom and top). Gold (#C49A6C) for the Rs.25 Crore figure. White for remaining text. Logo top-center (white). Symmetrical composition matching the symmetrical photo. |
| **Primary Text** | "Rs.25 Crore+ in homes designed, built, and delivered. 6+ years of end-to-end construction and interiors in Hyderabad. From Banjara Hills villas to Gachibowli residences -- NUBUILDCo has built homes for some of the city's most discerning families. Book your Rs.4,999 design consultation. We'll show you what your dream home actually looks like -- with real plans, real timelines, and a fixed price." |
| **Headline** | Premium Construction by NUBUILDCo |
| **CTA Button** | Book Now |

##### Ad S08 -- "Offer-Led: Rs.4,999 Value Stack"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S08-OFFER-CONSULT-HERRING |
| **Theme** | Theme 2: End-to-End Promise |
| **Hook Style** | Offer-Led |
| **Photo** | P1291550.jpg -- Herringbone floor landing |
| **Headline on Image** | "Rs.4,999 Design Consultation" (large, prominent) |
| **Subtext on Image** | Includes: Site Visit + 3D Renders + Material Selection + Fixed-Price Quote |
| **CTA on Image** | "Book Your Consultation" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Photo takes top 55% of frame. Bottom 45% is solid brand brown (#81350B). Price in large gold (#C49A6C) text against the brown. Bullet points of inclusions in white Inter font. Logo bottom-right (white). Clean, premium, catalog feel. |
| **Primary Text** | "For Rs.4,999, here's what you get: A dedicated site visit by our lead architect. Custom 3D renders of your dream home. Material selection guidance. A fixed-price construction quote -- no hidden costs. This isn't a sales pitch disguised as a consultation. It's a working session with a team that's delivered Rs.25Cr+ in premium homes. Limited slots available each month." |
| **Headline** | Get Your Custom Design Consultation |
| **CTA Button** | Book Now |

##### Ad S09 -- "Question: Tired of Contractor Drama?"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S09-QUESTION-CONSULT-SHOP |
| **Theme** | Theme 3: Fear Resolution |
| **Hook Style** | Question |
| **Photo** | P1291734.jpg -- Commercial shop interior (arched niches) |
| **Headline on Image** | "Tired of Contractor Drama?" (top, large) followed by "There's a Better Way to Build." |
| **Subtext on Image** | One Team. Fixed Price. On-Time Delivery. |
| **CTA on Image** | "Book Your Rs.4,999 Consultation" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Dark overlay upper portion for headline contrast. Lower third has a frosted glass / blur effect bar with subtext and CTA. White and gold text. Logo top-right (white). |
| **Primary Text** | "Tired of contractor drama? Tired of budgets that balloon, timelines that slip, and vendors who disappear mid-project? NUBUILDCo is the opposite of all that. One team handles architecture, construction, interiors, and handover. One fixed price. One timeline you can actually count on. See the difference for yourself -- book a Rs.4,999 design consultation." |
| **Headline** | Build Without the Chaos |
| **CTA Button** | Book Now |

---

#### OFFER 2 -- ALTERNATE HOOKS (3 Statics)

##### Ad S10 -- "Fear-Led: Contractor Markup"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S10-FEAR-GUIDE-ATRIUM |
| **Theme** | Theme 3: Fear Resolution + Theme 5: Educational |
| **Hook Style** | Fear |
| **Photo** | P1291276.jpg -- Double-height atrium with chandelier (HERO) |
| **Headline on Image** | "Your Contractor's Quote Is Probably 30% Too High." |
| **Subtext on Image** | Know the real numbers. Download our free cost guide. |
| **CTA on Image** | "Download Free Guide" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo with heavy dark overlay (75%). Bold white headline text. Red accent (#C33E3E) on "30% Too High." Gold subtext. CTA button: white background, brown text. Logo top-left (white). |
| **Primary Text** | "Your contractor's quote is probably 30% too high. How do we know? Because we've seen hundreds of Hyderabad homeowners overpay for construction and interiors -- simply because they didn't know the real market rates. Our free 2026 Cost Guide gives you the numbers: what construction actually costs per sq.ft. in Banjara Hills, Jubilee Hills, Gachibowli. What materials cost at different quality tiers. What to budget for interiors. Download it. Then compare it to your contractor's quote." |
| **Headline** | Stop Overpaying for Your Home |
| **CTA Button** | Download |

##### Ad S11 -- "Transformation-Led: Build Smart"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S11-TRANSFORM-GUIDE-DINING |
| **Theme** | Theme 1: Transformation + Theme 5: Educational |
| **Hook Style** | Transformation |
| **Photo** | P1291461.jpg -- Elegant dining room, green chairs |
| **Headline on Image** | "Homes Like This Start With a Plan." (top) followed by "Get Yours Free." (center, large) |
| **Subtext on Image** | 2026 Hyderabad Home Building Cost Guide |
| **CTA on Image** | "Free Download" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Full-bleed photo. Light gradient overlay from top (warm cream tint) for headline legibility. "Get Yours Free" in brand brown (#81350B), large. Lower portion clean with small gold accent divider. Logo top-left (brown). Elegant, editorial design. |
| **Primary Text** | "This dining room didn't happen by accident. It started with the right plan, the right budget, and the right team. If you're planning to build in 2026, start with the right numbers. Our free cost guide breaks down per-sq.ft. rates, material costs, interior budgets, and timelines for homes in Hyderabad. Download it now -- it takes 10 seconds." |
| **Headline** | Plan Your Dream Home With Real Numbers |
| **CTA Button** | Download |

##### Ad S12 -- "Offer-Led: Free Resource"

| Field | Specification |
|---|---|
| **Ad Name** | NB-S12-OFFER-GUIDE-FOYER |
| **Theme** | Theme 5: Educational |
| **Hook Style** | Offer-Led |
| **Photo** | P1291319.jpg -- Grand foyer with wood doors |
| **Headline on Image** | "FREE" (very large, bold) followed by "2026 Hyderabad Home Building Cost Guide" |
| **Subtext on Image** | Per Sq.Ft. Rates / Material Costs / Interior Budgets / Timelines |
| **CTA on Image** | "Download Now -- No Signup Required" |
| **Sizes** | 1080x1080 + 1080x1350 |
| **Color Treatment** | Photo with warm brown overlay (60% opacity, brand brown #81350B). "FREE" in massive white Cormorant Garamond, centered. Supporting text in cream (#FAF6F1). Bullet points separated by gold dots. CTA bar at bottom: cream background, brown text. Logo top-center (white). |
| **Primary Text** | "We just published the most comprehensive home building cost guide for Hyderabad in 2026. Inside: Construction cost per sq.ft. -- by locality and quality tier. Material costs -- steel, cement, marble, wood, and more. Interior budgets -- room by room breakdown. Timeline expectations -- realistic, not optimistic. It's completely free. No signup form. No spam. Just real numbers from a team that's delivered Rs.25Cr+ in Hyderabad homes." |
| **Headline** | Free 2026 Cost Guide -- Download Now |
| **CTA Button** | Download |

---

### Static Ad Matrix -- Quick Reference Table

| Ad ID | Name | Theme | Hook | Offer | Photo | Headline on Image |
|---|---|---|---|---|---|---|
| S01 | Atrium Reveal | Transformation | Transformation | Consultation | P1291276.jpg | "This Was an Empty Plot 8 Months Ago." |
| S02 | Grand Foyer | End-to-End | Question | Consultation | P1291319.jpg | "Why Hire 5 Vendors When One Team Does It All?" |
| S03 | Fear Dining | Fear Resolution | Fear | Consultation | P1291461.jpg | "Quoted Rs.50 Lakhs. Final Bill: Rs.80 Lakhs." |
| S04 | Edu Exterior | Educational | Question | Cost Guide | P1291697.jpg | "How Much Does It Cost to Build...?" |
| S05 | Data Staircase | Educational | Authority | Cost Guide | P1291491.jpg | "Rs.2,200 to Rs.10,000 Per Sq. Ft." |
| S06 | Lifestyle Living | Lifestyle + Edu | Transformation | Cost Guide | P1291304.jpg | "Planning to Build in 2026?" |
| S07 | Authority Lattice | Premium Lifestyle | Authority | Consultation | P1291385.jpg | "Rs.25 Crore+ in Homes Delivered." |
| S08 | Offer Herringbone | End-to-End | Offer-Led | Consultation | P1291550.jpg | "Rs.4,999 Design Consultation" |
| S09 | Question Shop | Fear Resolution | Question | Consultation | P1291734.jpg | "Tired of Contractor Drama?" |
| S10 | Fear Atrium | Fear + Edu | Fear | Cost Guide | P1291276.jpg | "Your Contractor's Quote Is Probably 30% Too High." |
| S11 | Transform Dining | Transform + Edu | Transformation | Cost Guide | P1291461.jpg | "Homes Like This Start With a Plan." |
| S12 | Offer Foyer | Educational | Offer-Led | Cost Guide | P1291319.jpg | "FREE -- 2026 Cost Guide" |

---

## 5. Carousel Concepts

### Carousel C01: Before/After Transformation

**Title:** The NUBUILDCo Transformation
**Number of Cards:** 5
**Primary Text:** "From an empty plot to a home that takes your breath away. Swipe to see a real NUBUILDCo project -- designed, built, and delivered end-to-end by one team."
**Headline:** See the Full Transformation
**Description:** Premium Construction + Interiors in Hyderabad
**CTA Button:** Book Now

| Card | Image | Text Overlay |
|---|---|---|
| Card 1 (Cover) | P1291697.jpg (Exterior) | "From This..." -- Exterior shell / architectural view |
| Card 2 | P1291319.jpg (Grand Foyer) | "To This." -- Completed grand foyer with bespoke wood doors |
| Card 3 | P1291276.jpg (Atrium) | "Double-Height Atrium -- Designed + Built by NUBUILDCo" |
| Card 4 | P1291461.jpg (Dining) | "Every Detail, Curated." -- Bespoke dining with designer furniture |
| Card 5 (CTA Card) | P1291385.jpg (Lattice) with text overlay | "Ready to Build Your Legacy? Book a Rs.4,999 Design Consultation" |

**Notes for designer:** Each card should have a consistent gold bottom bar with the NUBUILDCo logo on the left and the card number ("1 of 5") on the right. Transition from darker/raw images on Card 1 to warm, luxurious tones on Cards 3-5.

---

### Carousel C02: "Why Hire 5 Vendors?" Process Carousel

**Title:** The End-to-End Advantage
**Number of Cards:** 6
**Primary Text:** "Most homeowners hire 5 different vendors -- and spend months coordinating between them. Here's how NUBUILDCo does it differently. One team. Four stages. Zero chaos."
**Headline:** One Team. Start to Finish.
**Description:** Architecture + Construction + Interiors + Handover
**CTA Button:** Learn More

| Card | Image | Text Overlay |
|---|---|---|
| Card 1 (Cover) | Branded graphic: dark background (#151110) | "Why Hire 5 Vendors When 1 Does It All?" -- Large text with NUBUILDCo logo |
| Card 2 | Icon-based graphic, step 01 | **Stage 1: Design Consultation** -- "We listen to your vision and create architectural plans + 3D renders before a single brick is laid." |
| Card 3 | P1291697.jpg (Exterior) | **Stage 2: Construction** -- "In-house team. Premium materials. Milestone tracking. Your home rises on schedule." |
| Card 4 | P1291304.jpg (Living Room) | **Stage 3: Interior Design** -- "Furniture, lighting, finishes, fixtures -- functional, beautiful, uniquely yours." |
| Card 5 | P1291550.jpg (Herringbone) | **Stage 4: Handover** -- "Walk into a fully finished home. Final inspections done. Ready to move in." |
| Card 6 (CTA Card) | Branded graphic: brand brown (#81350B) background | "Ready for the End-to-End Experience? Book your Rs.4,999 Design Consultation. 6+ years. Rs.25Cr+ delivered." |

**Notes for designer:** Cards 2-5 should have a numbered step indicator ("01 / 04") in gold. Consistent bottom bar across all cards. Cards 2 and 6 are graphics-only (no photos); Cards 3-5 are photo-based with text overlay.

---

### Carousel C03: "How Much Does It Cost?" Educational Carousel

**Title:** The Real Cost of Building in Hyderabad (2026)
**Number of Cards:** 5
**Primary Text:** "Thinking about building a home in Hyderabad? Here's what it actually costs in 2026 -- per sq.ft. rates, material breakdowns, and interior budgets. No guesswork. (Full guide available for free download.)"
**Headline:** 2026 Hyderabad Home Building Costs
**Description:** Free Cost Guide Available
**CTA Button:** Download

| Card | Image | Text Overlay |
|---|---|---|
| Card 1 (Cover) | Branded graphic: cream (#FAF6F1) background | "How Much Does It Really Cost to Build a Home in Hyderabad?" -- NUBUILDCo logo + "2026 Cost Guide" badge |
| Card 2 | Branded infographic | **Construction Cost:** "Rs.2,200 -- Rs.10,000 per sq.ft." with breakdown: Standard (Rs.2,200-3,500), Premium (Rs.3,500-6,000), Ultra-Luxury (Rs.6,000-10,000) |
| Card 3 | Branded infographic | **Material Costs:** Quick snapshot of steel, cement, marble, wood, electricals with 2026 price ranges |
| Card 4 | Branded infographic | **Interior Budgets:** Room-by-room budget ranges -- Living Room, Kitchen, Master Bedroom, Bathroom |
| Card 5 (CTA Card) | P1291276.jpg (Atrium) with overlay | "Want the Complete Breakdown? Download the Free 2026 Hyderabad Home Building Cost Guide." CTA: "Download Free Guide" |

**Notes for designer:** Cards 1-4 should feel like pages from a premium PDF guide -- clean, data-forward, cream/brown/gold palette. Use Inter for data points and Cormorant Garamond for headers. Card 5 transitions back to an aspirational photo.

---

### Carousel C04: Portfolio Showcase

**Title:** Our Work Speaks for Itself
**Number of Cards:** 7
**Primary Text:** "Every home we build is a reflection of its owner -- and a testament to what end-to-end execution looks like. Swipe through a selection of NUBUILDCo projects across Hyderabad."
**Headline:** Crafted With Precision
**Description:** Rs.25Cr+ in Premium Homes Delivered
**CTA Button:** Book Now

| Card | Image | Text Overlay |
|---|---|---|
| Card 1 | P1291276.jpg (HERO Atrium) | "Double-Height Atrium" -- Residential, Hyderabad |
| Card 2 | P1291385.jpg (Lattice) | "Lattice Feature Wall" -- Bespoke Woodwork |
| Card 3 | P1291304.jpg (Living Room) | "Modern Living" -- Italian Marble + Designer Furniture |
| Card 4 | P1291461.jpg (Dining) | "Bespoke Dining" -- Custom Interiors |
| Card 5 | P1291491.jpg (Staircase) | "Sculptural Staircase" -- Stone + Lighting |
| Card 6 | P1291550.jpg (Herringbone) | "Herringbone Detailing" -- Floor-to-Ceiling Precision |
| Card 7 (CTA) | Branded: Dark background with gold text | "Your Home Could Look Like This. Book a Rs.4,999 Design Consultation with NUBUILDCo. Banjara Hills, Hyderabad." |

**Notes for designer:** Minimal text on cards 1-6 -- let the photos do the talking. Small label at bottom of each card with project type. Consistent gold accent line. Card 7 is a branded graphic CTA.

---

### Carousel C05: Objection Handling

**Title:** "But What If..."
**Number of Cards:** 6
**Primary Text:** "We've heard every concern. Here's how we've addressed them all -- before you even need to ask."
**Headline:** Every Concern, Already Addressed
**Description:** NUBUILDCo -- Build Without the Worry
**CTA Button:** Book Now

| Card | Image | Text Overlay |
|---|---|---|
| Card 1 (Cover) | Branded: Dark background | "Still Thinking About It? Let's Address Your Concerns." |
| Card 2 | Branded graphic | **"What if the budget goes over?"** -- "We provide a fixed-price quote before construction begins. The price you agree on is the price you pay. Period." |
| Card 3 | Branded graphic | **"What if there are delays?"** -- "We work with milestone-based timelines and weekly progress updates. 6+ years and Rs.25Cr+ delivered on schedule." |
| Card 4 | Branded graphic | **"What if the quality isn't what I expected?"** -- "Premium materials only. Regular quality inspections. And you approve every material and design choice before we proceed." |
| Card 5 | Branded graphic | **"What if I need to change something mid-project?"** -- "We build flexibility into our process. Design revisions are part of the consultation phase -- not an afterthought." |
| Card 6 (CTA) | P1291276.jpg (Atrium) with overlay | "No More 'What Ifs.' Just Results. Book Your Rs.4,999 Design Consultation." |

**Notes for designer:** Cards 2-5 use a consistent layout: objection in large italic Cormorant Garamond (gold), answer in clean Inter (white) on dark background (#151110). Small checkmark icon before each answer. Card 6 returns to photo with CTA overlay.

---

## 6. Video Ad Concepts

*Note: These concepts are ready for production once video assets (site footage, founder interview, project walkthroughs) become available. Storyboards are provided for planning.*

### Video V01: 15-Second Transformation Reel

**Title:** "From Plot to Palace"
**Format:** 9:16 Vertical (Instagram Reels, Facebook Reels, Stories)
**Duration:** 15 seconds
**Audio:** Trending ambient/cinematic audio or subtle orchestral

| Timestamp | Visual | Text Overlay |
|---|---|---|
| 0-2s | Quick cuts: empty plot / construction site (raw, unfinished) | "This was an empty plot." |
| 2-5s | Transition effect (blur/wipe) to completed exterior (P1291697 style) | "8 months later..." |
| 5-8s | Slow cinematic pan through atrium (P1291276 style) | No text -- let the visual speak |
| 8-11s | Quick cuts: dining (P1291461), staircase (P1291491), living room (P1291304) | "NUBUILDCo -- End-to-End" |
| 11-15s | Logo reveal on dark background + CTA | "Book your Rs.4,999 Design Consultation" + website URL |

**Primary Text:** "This was an empty plot 8 months ago. One team. One vision. One incredible home. NUBUILDCo -- Architecture. Construction. Interiors. Handover."
**CTA Button:** Book Now

---

### Video V02: 30-Second "How We Work" Explainer

**Title:** "The NUBUILDCo Way"
**Format:** 1:1 (Feed) + 9:16 (Stories/Reels)
**Duration:** 30 seconds
**Audio:** Clean, modern background music. Optional: founder voiceover.

| Timestamp | Visual | Text/VO |
|---|---|---|
| 0-3s | Hook shot: Close-up of luxury detail (chandelier / marble) | "Building a home shouldn't be a nightmare." |
| 3-8s | Split screen: LEFT = chaos (multiple vendors, phone calls, paperwork), RIGHT = calm (NUBUILDCo team at work) | "Most people hire 5 different vendors. We think you need just one." |
| 8-13s | Step 1: Design -- 3D render reveal, architect sketching | "Step 1: We design your vision in 3D." |
| 13-18s | Step 2-3: Construction + Interiors -- time-lapse of build, interior install | "Step 2: We build it. Step 3: We finish every detail." |
| 18-23s | Step 4: Handover -- keys being handed over, family walking into finished home | "Step 4: We hand you the keys." |
| 23-27s | Portfolio montage: 3-4 quick shots of completed projects | "Rs.25 Crore+ delivered. 6+ years. Hyderabad's premium builder." |
| 27-30s | Logo + CTA on dark background | "Book your Rs.4,999 Design Consultation. nubuildco.netlify.app" |

**Primary Text:** "Why hire 5 vendors when one team does it all? NUBUILDCo handles architecture, construction, interiors, and handover. One team. Fixed price. No chaos."
**CTA Button:** Book Now

---

### Video V03: 60-Second Portfolio Walkthrough

**Title:** "Walk Through a NUBUILDCo Home"
**Format:** 9:16 (Primary) + 1:1 (Secondary)
**Duration:** 60 seconds
**Audio:** Ambient cinematic track. Optional founder narration.

| Timestamp | Visual | Text/VO |
|---|---|---|
| 0-5s | Exterior approach -- camera walks toward front door | "What does a NUBUILDCo home look like from the inside?" |
| 5-15s | Grand foyer (P1291319 style) -- slow pan, details of wood doors | "Every element is custom. Every detail, intentional." |
| 15-25s | Living room (P1291304 style) -- wide shot, then close-up of marble, furniture | "Italian marble. Bespoke furniture. Designed for how you actually live." |
| 25-35s | Dining room (P1291461 style) + staircase (P1291491 style) | "From the dining room to the staircase -- every space tells a story." |
| 35-45s | Atrium (P1291276 style) -- dramatic upward pan to chandelier | "And then there's this. A double-height atrium with a custom chandelier." |
| 45-50s | Herringbone detail (P1291550 style) + lattice wall (P1291385 style) | "This is what Rs.25Cr+ of delivered projects looks like." |
| 50-55s | Founder piece-to-camera (when available) | "I'm VijayKrishna, founder of NUBUILDCo. Let's build something extraordinary." |
| 55-60s | Logo + CTA | "Book your Rs.4,999 Design Consultation. Link in bio." |

**Primary Text:** "Take a walk through one of our completed homes. Every surface, every fixture, every detail -- designed and delivered by one team. This is the NUBUILDCo standard."
**CTA Button:** Book Now

---

## 7. Hook Testing Matrix

### All Hook x Offer Combinations (15 Total)

Priority is rated P1 (highest) through P3 (lowest) based on expected performance for this audience and budget.

| # | Hook Type | Offer | Example Hook Line | Priority | Launch Week | Rationale |
|---|---|---|---|---|---|---|
| H01 | **Fear** | Consultation | "Quoted Rs.50L. Final bill: Rs.80L." | **P1** | Week 1 | Pain is the strongest motivator for high-ticket. Directly addresses #1 pain point. |
| H02 | **Transformation** | Consultation | "This was an empty plot 8 months ago." | **P1** | Week 1 | Aspiration + proof. Shows tangible outcome. |
| H03 | **Question** | Cost Guide | "How much does it actually cost to build in Hyderabad?" | **P1** | Week 1 | Curiosity-driven. Perfect for TOF lead magnet. |
| H04 | **Offer** | Cost Guide | "FREE: 2026 Hyderabad Home Building Cost Guide" | **P1** | Week 1 | Direct offer. Low friction for cold audiences. |
| H05 | **Question** | Consultation | "Why hire 5 vendors when one team does it all?" | **P1** | Week 1 | Challenges status quo. Strong for business owners. |
| H06 | **Authority** | Consultation | "Rs.25 Crore+ in homes delivered." | **P2** | Week 1 | Social proof. Strong for NRI and CXO audiences. |
| H07 | **Fear** | Cost Guide | "Your contractor's quote is probably 30% too high." | **P2** | Week 1 | Fear + education combo. Drives guide downloads. |
| H08 | **Transformation** | Cost Guide | "Homes like this start with a plan." | **P2** | Week 2 | Aspirational entry to educational offer. |
| H09 | **Offer** | Consultation | "Rs.4,999 Design Consultation: Site Visit + 3D Renders + Fixed Quote" | **P2** | Week 2 | Value-stack approach. Works for analytical buyers. |
| H10 | **Question** | Strategy Call | "Is your contractor giving you the full picture?" | **P2** | Week 2 | Retargeting hook. Seeds doubt, offers resolution. |
| H11 | **Fear** | Strategy Call | "3 mistakes that cost Hyderabad homeowners lakhs." | **P2** | Week 2 | Fear + education. Retargeting only. |
| H12 | **Authority** | Cost Guide | "From the team behind Rs.25Cr+ in homes -- a free cost guide." | **P3** | Week 2 | Authority + free offer. Lower urgency. |
| H13 | **Transformation** | Strategy Call | "We turned this plot into a Rs.2Cr home in 10 months." | **P3** | Week 3 | Specific case study hook. Needs strong visual. |
| H14 | **Authority** | Strategy Call | "6+ years. Rs.25Cr+ delivered. Let's talk about your project." | **P3** | Week 3 | Direct. Best for warm/retargeted audiences. |
| H15 | **Offer** | Strategy Call | "Free 15-Minute Strategy Call -- Limited Slots This Week" | **P3** | Week 3 | Urgency + free offer. Retargeting only. |

### Hook Distribution by Offer

| Offer | Fear | Question | Transformation | Authority | Offer-Led | Total |
|---|---|---|---|---|---|---|
| Consultation (Rs.4,999) | H01 | H05 | H02 | H06 | H09 | 5 |
| Cost Guide (Free) | H07 | H03 | H08 | H12 | H04 | 5 |
| Strategy Call (Free) | H11 | H10 | H13 | H14 | H15 | 5 |
| **Total** | **3** | **3** | **3** | **3** | **3** | **15** |

### Week 1 Launch Priority

Launch with hooks H01 through H07 (7 hooks) in Week 1. These map to static ads S01-S07 and S10. The remaining hooks (H08-H15) launch in Weeks 2-3 based on Week 1 learnings.

---

## 8. Testing Framework and Weekly Plan

### Decision Criteria

| Metric | Action | Threshold |
|---|---|---|
| **CTR < 1.0%** after 1,000 impressions | KILL the ad | Creative is not resonating. Replace. |
| **CTR 1.0% - 1.5%** after 2,000 impressions | WATCH for 48 more hours | Borderline. May improve with delivery optimization. |
| **CTR > 1.5%** | KEEP running | Strong creative signal. |
| **CTR > 2.5%** | SCALE -- increase budget 20-30% | Winner. Double down. |
| **CPL > Rs.900** after 5+ leads | KILL the ad set | Too expensive. Audience or creative issue. |
| **CPL Rs.700 - Rs.900** after 5+ leads | OPTIMIZE | Adjust audience, try new creative in the ad set. |
| **CPL < Rs.700** | SCALE | Increase daily budget by 20% every 48 hours. |
| **CPL < Rs.500** | AGGRESSIVE SCALE | Increase budget 30-50%. This is a winner. |
| **Frequency > 3.0** per week | ROTATE creative | Audience fatigue. Swap in new ads. |
| **Frequency > 4.5** per week | PAUSE ad set | Audience exhausted. Expand or replace targeting. |
| **Lead Quality: <30% answering calls** | REVIEW form / audience | Too many low-intent leads. Tighten qualifying questions. |
| **Relevance Score < 5** | KILL | Poor audience-creative fit. |

### Week-by-Week Execution Plan

---

#### WEEK 1: Launch and Learn (Days 1-7)

**Objective:** Establish baseline performance. Identify winning creatives and audiences.
**Daily Budget:** Rs.2,850/day (Campaign 1: Rs.1,500 + Campaign 2: Rs.1,350)
**Total Spend:** ~Rs.19,950

**Day 1-2: Launch**
- Launch Campaign 1 (Consultation) with 4-5 static ads:
  - S01 (Transformation/Atrium), S02 (E2E/Foyer), S03 (Fear/Dining) -- across all 3 ad sets
  - S07 (Authority/Lattice), S08 (Offer/Herringbone) -- in top 2 ad sets
- Launch Campaign 2 (Cost Guide) with 3-4 static ads:
  - S04 (Edu/Exterior), S05 (Data/Staircase), S06 (Lifestyle/Living) -- across all 3 ad sets
  - S10 (Fear/Atrium) -- in top 2 ad sets
- Total active ads: 8-10
- Verify pixel fires correctly on landing page
- Verify Instant Form submissions are flowing to CRM/WhatsApp

**Day 3: First Check**
- Review impressions and CTR for all ads
- Check for any ad set delivery issues (too few impressions = audience too small)
- No changes yet -- let Meta's algorithm optimize

**Day 4-5: First Optimization**
- Evaluate CTR at 1,000+ impressions per ad
- KILL any ad with CTR < 1.0% after 1,500+ impressions
- Identify top 2-3 ads by CTR and engagement
- Check CPL trend (too early for definitive CPL data, but watch direction)
- Ensure ad review has not flagged any ads

**Day 6-7: Week 1 Close**
- Full performance review: CTR, CPL, leads generated, lead quality
- Call all leads within 2 hours of submission -- track answer rates and qualification
- Decision: Which ad sets to keep, which to pause
- Prepare Week 2 creative refresh based on winning themes/hooks

**Week 1 Expected Results:**
- Impressions: 40,000-60,000
- Clicks: 600-1,200
- Leads: 4-6
- CPL: Rs.700-1,000 (higher in early learning phase)

---

#### WEEK 2: Iterate and Retarget (Days 8-14)

**Objective:** Double down on winners. Launch retargeting. Test new hooks.
**Daily Budget:** Rs.3,350/day (Campaign 1: Rs.1,500 + Campaign 2: Rs.1,350 + Campaign 3: Rs.500)
**Total Spend:** ~Rs.23,450

**Day 8-9: Implement Week 1 Learnings**
- Increase budget on winning ad sets by 20%
- Pause underperforming ad sets (CPL > Rs.900, CTR < 1.0%)
- Launch 2-3 new creatives using alternate hooks:
  - If Fear hooks won: Test S09 (Question/Shop) and S11 (Transformation/Dining)
  - If Education hooks won: Test S12 (Offer/Foyer) and Carousel C03 (Cost breakdown)
  - If Transformation hooks won: Test Carousel C01 (Before/After) and C04 (Portfolio)

**Day 10: Launch Retargeting (Campaign 3)**
- Ad Set 3A: Website visitors (should have 500+ by now)
- Ad Set 3B: FB/IG engagers
- Use high-intent Offer 1 (Consultation) creatives for retargeting
- Use objection-handling copy (Carousel C05 if produced)

**Day 11-12: Monitor + Optimize**
- Check retargeting CPL (should be lower than prospecting -- target Rs.400-500)
- Check frequency across all active ad sets
- Rotate any creative with frequency > 3.0

**Day 13-14: Week 2 Close**
- Full performance review
- Calculate blended CPL across all campaigns
- Assess lead quality: How many leads answered calls? How many booked consultations?
- Prepare Week 3 plan

**Week 2 Expected Results:**
- Leads: 5-6 (cumulative: 9-12)
- CPL: Rs.600-800 (improving as winners scale)
- Consultations booked from Week 1 leads: 3-4

---

#### WEEK 3: Scale Winners (Days 15-21)

**Objective:** Scale winning combinations aggressively. Launch lookalikes. Refresh creatives.
**Daily Budget:** Rs.3,350/day (with dynamic rebalancing toward winners)
**Total Spend:** ~Rs.23,450

**Key Actions:**
- Create Lookalike Audiences:
  - 1% LAL of leads generated (need 50+ leads ideally, but can try with 30+)
  - 1% LAL of website visitors
  - Layer with geo (Hyderabad West) and age (35-55)
- Scale winning ad sets to Rs.700-1,000/day
- Pause all ad sets with CPL > Rs.800 that haven't improved
- Launch 2-3 fresh creatives to combat fatigue:
  - Carousel C02 (Process) or C04 (Portfolio)
  - New static using winning hook style with different photo
- If video assets available: Launch V01 (15-sec Reel)

**Week 3 Expected Results:**
- Leads: 4-5 (cumulative: 13-17)
- CPL: Rs.550-700 (optimized)
- Consultations booked from Week 1-2 leads: 5-7 (cumulative)

---

#### WEEK 4: Optimize and Close (Days 22-30)

**Objective:** Maximize remaining budget on proven performers. Close the month strong.
**Daily Budget:** Rs.3,350/day
**Total Spend:** ~Rs.30,150

**Key Actions:**
- Allocate 70%+ of budget to top 2-3 ad sets
- Kill everything with CPL > Rs.750
- Push retargeting harder (increase to Rs.300-400/day if audience size supports)
- Launch final creative refresh:
  - Urgency-based hooks: "Only 3 consultation slots left this month"
  - Testimonial-style if any client quotes are available
- If video V01 performed well, launch V02 (30-sec explainer)
- Begin planning Month 2 strategy based on full-month data

**Week 4 Expected Results:**
- Leads: 3-4 (cumulative: 15-17+)
- CPL: Rs.500-650 (fully optimized)
- Total consultations: 8-10
- Expected closures: 2 (at Rs.50L-5Cr project value)

---

### Monthly Performance Dashboard Template

| Metric | Target | Week 1 | Week 2 | Week 3 | Week 4 | Total |
|---|---|---|---|---|---|---|
| Spend | Rs.1,00,000 | | | | | |
| Impressions | -- | | | | | |
| Clicks | -- | | | | | |
| CTR | 1.5-2.5% | | | | | |
| Leads | 15-17 | | | | | |
| CPL | Rs.600-700 | | | | | |
| Consultations | 8-10 | | | | | |
| Closures | 2 | | | | | |
| ROAS | >10x | | | | | |

---

## 9. File Naming Convention

### Naming Structure

All deliverables follow this pattern:

```
NB-[TYPE][NUMBER]-[THEME]-[OFFER]-[PHOTO/VARIANT]-[SIZE].[EXT]
```

### Component Key

| Code | Meaning |
|---|---|
| **NB** | NUBUILDCo (client prefix) |
| **S** | Static ad |
| **C** | Carousel ad (set) |
| **CC** | Carousel card (individual) |
| **V** | Video ad |
| **R** | Retargeting variant |

| Theme Code | Theme |
|---|---|
| TRANSFORM | Transformation Story |
| E2E | End-to-End Promise |
| FEAR | Fear Resolution |
| LIFESTYLE | Premium Lifestyle |
| EDU | Educational |
| AUTHORITY | Authority/Social Proof |
| OFFER | Offer-Led |
| QUESTION | Question Hook |
| OBJECTION | Objection Handling |

| Offer Code | Offer |
|---|---|
| CONSULT | Rs.4,999 Design Consultation |
| GUIDE | Free Cost Guide |
| CALL | Free Strategy Call |

| Size Code | Dimensions |
|---|---|
| SQ | 1080 x 1080 (Square) |
| PT | 1080 x 1350 (Portrait) |
| ST | 1080 x 1920 (Stories) |
| VT | 1080 x 1920 (Vertical Video) |
| HD | 1920 x 1080 (Horizontal Video) |

### Examples

```
NB-S01-TRANSFORM-CONSULT-ATRIUM-SQ.png       -- Static 01, square
NB-S01-TRANSFORM-CONSULT-ATRIUM-PT.png       -- Static 01, portrait
NB-C01-TRANSFORM-CONSULT-CARD1-SQ.png        -- Carousel 01, Card 1
NB-C01-TRANSFORM-CONSULT-CARD5CTA-SQ.png     -- Carousel 01, Card 5 (CTA)
NB-V01-TRANSFORM-CONSULT-15SEC-VT.mp4        -- Video 01, vertical
NB-R-S01-FEAR-CONSULT-ATRIUM-SQ.png          -- Retargeting variant of S01
```

### Folder Structure

```
/ads/
  /strategy/
    NUBUILDCo_Creative_Strategy.md    <-- This document
  /copy/
    NB-ad-copy-all.md                 <-- All primary text + headlines
  /mockups/
    /statics/
      NB-S01-TRANSFORM-CONSULT-ATRIUM-SQ.png
      NB-S01-TRANSFORM-CONSULT-ATRIUM-PT.png
      ...
    /carousels/
      /C01-transformation/
        NB-C01-TRANSFORM-CONSULT-CARD1-SQ.png
        NB-C01-TRANSFORM-CONSULT-CARD2-SQ.png
        ...
      /C02-process/
        ...
    /videos/
      /V01-transformation-reel/
        NB-V01-TRANSFORM-CONSULT-15SEC-VT.mp4
        NB-V01-storyboard.pdf
      ...
  /source-files/
    /psd/ or /figma/
      ...
```

---

## 10. Production Timeline

### 10-Day Creative Production Plan

Production begins upon strategy approval. All creatives must be ready for launch by Day 10.

| Day | Task | Owner | Deliverables |
|---|---|---|---|
| **Day 1 (Mon)** | Strategy review + approval. Photo asset review. Finalize which 8-10 ads launch Week 1. | Strategist + Client | Approved strategy doc. Confirmed launch ads. |
| **Day 2 (Tue)** | Write all ad copy (primary text, headlines, descriptions) for 12 statics + 5 carousels. Compile into copy doc. | Copywriter | NB-ad-copy-all.md |
| **Day 3 (Wed)** | Design 6 priority statics (S01-S06) in both sizes (SQ + PT). 12 files total. | Designer | 12 static ad files |
| **Day 4 (Thu)** | Design remaining 6 statics (S07-S12) in both sizes. 12 files total. | Designer | 12 static ad files |
| **Day 5 (Fri)** | Design Carousel C01 (Transformation, 5 cards x 2 sizes) + C03 (Cost Guide, 5 cards x 2 sizes). | Designer | 20 carousel card files |
| **Day 6 (Sat)** | Internal creative review. Strategist + copywriter review all 44 files for brand consistency, copy accuracy, CTA clarity. | Strategist + Copywriter | Review feedback doc |
| **Day 7 (Sun)** | Designer implements review feedback. Revisions round 1. | Designer | Revised files |
| **Day 8 (Mon)** | Final approval on all Week 1 creatives (S01-S10 + C01 + C03). Set up Ads Manager campaigns, ad sets, audiences. Upload creatives. Configure Instant Forms. | Media Buyer | Campaigns ready in draft |
| **Day 9 (Tue)** | Design Carousel C02, C04, C05 (for Week 2 launch). QA all campaign settings: pixel, budget, schedule, placements, exclusions. | Designer + Media Buyer | Week 2 creatives + QA checklist |
| **Day 10 (Wed)** | **LAUNCH DAY.** Publish all campaigns. Monitor first 4 hours for delivery issues, ad rejections, pixel fires. | Media Buyer | Live campaigns |

### Post-Launch Production (Ongoing)

| Week | Task | Deliverables |
|---|---|---|
| Week 1 (Days 11-17) | Monitor performance. Identify winning hooks/themes. Begin planning alternate creatives. | Performance report |
| Week 2 (Days 18-24) | Produce 2-3 refreshed statics based on winning hooks with new photo variants. Launch carousels C02, C04, C05. Set up retargeting campaign. | 4-6 new ad files + retargeting live |
| Week 3 (Days 25-31) | Creative refresh round 2. If video assets are available, produce V01 (15-sec reel). Launch lookalike audiences. | 2-4 new ad files + V01 if applicable |
| Week 4 (Days 32-38) | Final optimization. Urgency-based creative variants. Month-end performance report. Month 2 strategy planning. | Final report + Month 2 plan |

---

## Appendix A: Photo Asset Reference

Quick reference for the creative team mapping photos to their best use cases.

| File | Description | Best For | Used In |
|---|---|---|---|
| P1291276.jpg | Double-height atrium with chandelier | HERO shots, transformation reveals, premium lifestyle | S01, S10, C01 Card 3, C03 Card 5, C05 Card 6 |
| P1291385.jpg | Lattice wall with chandelier, symmetrical | Authority, premium, portfolio showcase | S07, C04 Card 2 |
| P1291304.jpg | Modern living room with marble | Lifestyle, aspiration, cost guide | S06, C02 Card 4, C04 Card 3 |
| P1291319.jpg | Grand foyer with wood doors | End-to-end, process, offer-led | S02, S12, C01 Card 2 |
| P1291461.jpg | Elegant dining room, green chairs | Fear resolution, transformation, portfolio | S03, S11, C01 Card 4, C04 Card 4 |
| P1291491.jpg | Lit staircase with stone wall | Data/educational, portfolio | S05, C04 Card 5 |
| P1291550.jpg | Herringbone floor landing | Offer-led, detail shots, craftsmanship | S08, C02 Card 5, C04 Card 6 |
| P1291734.jpg | Commercial shop interior (arched niches) | Question hooks, commercial capability | S09 |
| P1291697.jpg | Modern exterior architecture | Educational, exterior, before/after | S04, C01 Card 1, C02 Card 3 |

---

## Appendix B: Instant Form Fields (Meta Lead Gen)

### Form for Offer 1: Rs.4,999 Design Consultation

**Form Name:** NB-Form-Consultation
**Form Type:** Higher Intent (includes review screen)

| Field | Type | Required | Options |
|---|---|---|---|
| Full Name | Short text (pre-filled) | Yes | -- |
| Phone Number | Phone (pre-filled) | Yes | -- |
| Email | Email (pre-filled) | No | -- |
| Project Budget | Multiple choice | Yes | Rs.30L-50L / Rs.50L-1Cr / Rs.1Cr-3Cr / Rs.3Cr-5Cr / Rs.5Cr+ |
| When do you plan to start? | Multiple choice | Yes | Immediately / 1-3 months / 3-6 months / 6+ months |
| Project Type | Multiple choice | Yes | New Construction / Renovation / Interiors Only / Commercial |
| Plot/Property Location | Short text | No | -- |

**Thank You Screen:**
- Headline: "Thank you! We'll call you within 2 hours."
- Description: "In the meantime, take a look at our recent projects."
- CTA Button: "View Our Portfolio" -- links to https://nubuildco.netlify.app/#portfolio

### Form for Offer 2: Free Cost Guide

**Form Name:** NB-Form-CostGuide
**Form Type:** More Volume (simpler, fewer fields)

| Field | Type | Required | Options |
|---|---|---|---|
| Full Name | Short text (pre-filled) | Yes | -- |
| Phone Number | Phone (pre-filled) | Yes | -- |
| Are you planning to build in 2026? | Multiple choice | Yes | Yes, actively planning / Exploring options / Just researching |

**Thank You Screen:**
- Headline: "Your free cost guide is on its way!"
- Description: "We'll send it to your WhatsApp within 5 minutes."
- CTA Button: "Visit Our Website" -- links to https://nubuildco.netlify.app

---

## Appendix C: UTM Parameters

All ad links should include UTM tracking for analytics.

**Structure:**
```
https://nubuildco.netlify.app/?utm_source=meta&utm_medium=paid&utm_campaign=[CAMPAIGN]&utm_content=[AD_ID]&utm_term=[AD_SET]
```

**Examples:**
```
utm_campaign=consultation_leadgen
utm_campaign=costguide_leadgen
utm_campaign=retargeting

utm_content=NB-S01-TRANSFORM-CONSULT
utm_content=NB-C01-TRANSFORM-CONSULT

utm_term=interest_interior_design
utm_term=interest_business_owners
utm_term=interest_luxury_realestate
utm_term=interest_home_improvement
utm_term=interest_architecture
utm_term=interest_high_income
utm_term=retarget_website_visitors
utm_term=retarget_engagers
```

---

*End of Document*

**Prepared by:** ZippyScale Performance Marketing Team
**For internal use only. Do not share with client without review.**
