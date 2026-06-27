# 🛍️ NovaMart — Multi-Vendor E-Commerce Marketplace UI/UX

> **Modern, Intuitive & Conversion-Focused Marketplace Experience (Mobile + Web)**  
> Zidio Development — UI/UX Design Domain | March 2026 | Version 2.0 Industry Edition

---

## 📌 Project Overview

NovaMart is a multi-vendor e-commerce marketplace designed for Indian urban shoppers aged 18–45. It serves three distinct user types — **Customers**, **Vendors**, and **Admins** — across a unified design system with portal-specific visual identities.

The core design challenge: *poor UX causes 70%+ cart abandonment in e-commerce.* NovaMart addresses this through smooth vendor onboarding, smart search, seamless single-page checkout, and real-time order tracking — designed to boost conversion rates by 25–40%.

---

## 🎯 Design Objectives

| Goal | Target |
|------|--------|
| Reduce cart abandonment | 25–40% improvement |
| Vendor onboarding completion | Under 5 minutes, 4 steps |
| Key actions reachable in | ≤ 3 taps from any screen |
| Accessibility standard | WCAG 2.1 AA |
| Performance target | 60fps animations |
| Platform support | Mobile-first + Desktop |
| Theme support | Dark / Light mode |

---

## 👥 Target Users

| Persona | Profile | Key Need |
|---------|---------|----------|
| Priya Sharma | Marketing Manager, 28, Mumbai | Fast visual discovery, no sponsored clutter |
| Arjun Mehta | Engineering Student, 22, Mumbai | Spec comparison, counterfeit protection |
| Sunita Kapoor | Homemaker, 38, Mumbai | Simple navigation, 1-tap reorder |
| Rohit Desai | UX Designer, 31, Bengaluru | Design quality, dark mode, vendor stories |
| Vinod Nair | Retired, 54, Mumbai | Accessible typography, transparent pricing |
| Kavya Reddy | Home Reseller, 26, Mumbai | Brand identity, simple mobile listing |
| Sameer Joshi | Electronics Retailer, 34, Mumbai | Analytics dashboard, inventory alerts |
| Meena Iyer | Artisan Seller, 44, Mumbai | Craft storytelling, custom order flow |

---

## ✨ Core Features

| ID | Feature | Description |
|----|---------|-------------|
| F01 | Vendor Onboarding | 4-step wizard with progress bar, time estimates, save & continue |
| F02 | Smart Product Discovery | Style filters, visual/camera search, zero sponsored top 3 |
| F03 | Seamless Cart & Checkout | Persistent cart drawer, single-page checkout, UPI default |
| F04 | Real-Time Order Tracking | Live map, 5-step timeline, proactive push notifications |
| F05 | Vendor Dashboard | Revenue charts, conversion funnel, inventory alerts |
| F06 | Admin Moderation Panel | Vendor approvals, content flags, platform analytics |

---

## 🗂️ Repository Structure

```
NovaMart-UIUX-Zidio-March2026/
│
├── research/
│   ├── NovaMart_Competitor_Analysis.docx     # Day 1 — Amazon, Flipkart, Meesho, Etsy
│   ├── NovaMart_User_Personas.docx           # Day 2 — 5 customer + 3 vendor personas
│   ├── novamart_journey_maps.pdf             # Day 3 — J1 Shopping, J2 Onboarding, J3 Tracking
│   └── novamart_sitemap.pdf                  # Day 4 — 54 screens across 3 portals
│
├── design-system/
│   └── novamart_design_system.pdf            # Colours, typography, spacing, components
│
├── screens/
│   ├── mobile/                               # 13 mobile screens (390×844px)
│   │   ├── C01_Homepage.png
│   │   ├── C03_SearchResults.png
│   │   ├── C06_ProductDetail.png
│   │   ├── C12_CartDrawer.png
│   │   ├── C13_Checkout.png
│   │   ├── C14_OrderConfirmation.png
│   │   ├── C15_MyOrders.png
│   │   ├── C16_OrderTracking.png
│   │   ├── V01_V04_OnboardingWizard.png
│   │   ├── V05_StoreEditor.png
│   │   ├── V07_ProductListing.png
│   │   ├── V12_Analytics.png
│   │   └── A01_AdminDashboard_mobile.png
│   └── desktop/
│       ├── C01_Homepage_desktop.png
│       ├── C03_SearchResults_desktop.png
│       ├── C06_ProductDetail_desktop.png
│       ├── V05_StoreEditor_desktop.png
│       ├── V12_Analytics_desktop.png
│       └── A01_AdminDashboard.png
│
├── prototype/
│   └── figma_link.txt                        # Public Figma prototype URL
│
├── case-study/
│   └── NovaMart_case_study.pdf               # Full project case study
│
└── README.md                                 # This file
```

---

## 🎨 Design System

### Portal Colour Identity

| Portal | Token | Hex | Screens |
|--------|-------|-----|---------|
| Customer | Primary/Brand | `#4F46E5` | C01–C16 — all CTAs, active nav, hero |
| Vendor | Vendor/Teal | `#0F766E` | V01–V12 — buttons, progress bar |
| Admin | Admin/Navy | `#193B6D` | A01 — sidebar, header |
| Admin | Admin/Coral | `#DC4E3A` | A01 — flagged content, reject |

### Typography
- **Font:** Inter (Google Fonts)
- **Scale:** Display/H1 (32px Bold) → Label/Small (12px SemiBold)
- **Body default:** 14px Regular, 20px line-height

### Spacing Scale
`4px` · `8px` · `12px` · `16px` · `24px` · `32px` · `48px` · `64px`

### Border Radius Scale
`4px` (buttons) · `8px` (cards/inputs) · `12px` (modals) · `16px` (large cards) · `24px` (chips) · `9999px` (pills/badges)

---

## 📱 Screen Inventory (54 screens)

### Customer Portal — 22 screens
`C01` Homepage · `C02` Category Browser · `C03` Search Results · `C04` Filter Panel · `C05` Visual Search · `C06` Product Detail · `C07` Photo Gallery · `C08` Variant Selector · `C09` Vendor Trust Card · `C10` Product Comparison · `C11` Reviews · `C12` Cart Drawer · `C13` Checkout · `C14` Order Confirmation · `C15` My Orders · `C16` Live Tracking · `C17` Push Notification · `C18` Returns · `C19` My Account · `C20` Wishlist · `C21` Saved Addresses · `C22` Reorder Section

### Vendor Portal — 16 screens
`V01–V04` Onboarding Wizard · `V05` Store Visual Editor · `V06` Live Store Preview · `V07` Product Listing Form · `V08` Inventory Manager · `V09` Bulk CSV Upload · `V10` Pending Orders · `V11` Order History · `V12` Revenue Charts · `V13` Conversion Funnel · `V14` Traffic Sources · `V15` Payment Disbursement · `V16` Customer Inbox

### Admin Panel — 10 screens
`A01` Dashboard · `A02` User Manager · `A03` Vendor Approval Queue · `A04` Content Moderation · `A05` Review Flagging · `A06` Platform Analytics · `A07` Payout Manager · `A08` Dispute Centre · `A09` Category Manager · `A10` Notification Blaster

### Auth & Shared — 6 screens
`S01` Login/Register · `S02` OTP Verification · `S03` Forgot Password · `S04` Notification Centre · `S05` Onboarding Splash · `S06` Settings

---

## 🔗 Key Links

| Deliverable | Link |
|-------------|------|
| 🎨 Interactive Figma Prototype | [View Prototype](https://www.figma.com/proto/HY28DFLbuBUwiqa2ZKs7Id/NovaMart-%E2%80%94-UI-UX-Design-System?node-id=6-2&scaling=scale-down&content-scaling=fixed&starting-point-node-id=6%3A2&page-id=2%3A2) |
| 📋 Case Study PDF | [View Case Study](./case-study/NovaMart_case_study.pdf) |

---

## 🔬 Design Process

```
Day 1    Competitor Analysis     Amazon, Flipkart, Meesho, Etsy
Day 2    User Personas           8 personas (5 customer + 3 vendor)
Day 3    Journey Maps            J1 Shopping · J2 Onboarding · J3 Tracking
Day 4    Sitemap & IA            54 screens across 3 portals
Day 5    Wireframing             Mobile-first lo-fi for all P1 screens
Day 8    Design System           Colours, typography, spacing, components
Day 9-13 Hi-Fi Screens          13 P1 screens fully designed
Day 15   Interactive Prototype   68 connections across 4 flows
Day 18   Accessibility Audit     WCAG 2.1 AA compliance check
Day 22   Usability Testing       8-participant test, iteration
Day 26   Case Study              Full documentation
Day 28   Final QA + Submission   Zidio dashboard
```

---

## 🏆 Key Design Decisions

**1. Zero sponsored results in top 3 positions**
Directly addresses Priya's #1 pain point from competitor analysis — Amazon and Flipkart both show sponsored content in positions 1–4, creating banner blindness and distrust.

**2. Single-page checkout with UPI default**
All checkout steps (address, payment, summary, trust row) on one scrollable screen. UPI pre-selected as default. Eliminates the multi-step checkout drop-off identified across all 4 competitors.

**3. Vendor trust card on every product**
Vendor name, rating, response time, and return policy surfaced in a single card on the PDP. Removes the 3-level-deep burial of return policy found on Flipkart and Amazon.

**4. Portal-based colour identity**
Customer (purple #4F46E5) vs Vendor (teal #0F766E) vs Admin (navy #193B6D) — gives users a subconscious orientation cue when switching contexts.

**5. 4-step vendor onboarding wizard**
With time estimate per step, "Save & Continue Later" on every step, and an animated "Go Live" celebration screen. Amazon's 12-step process and Meesho's lack of brand identity were the primary pain points addressed.

---

## ♿ Accessibility

- WCAG 2.1 AA colour contrast on all text elements
- Minimum 14px body text (16px for primary actions)
- Font size toggle in Settings screen (addresses Vinod's pain point)
- Bottom nav icons with visible text labels (not icon-only)
- Touch targets minimum 44×44px across all interactive elements
- No reliance on colour alone to convey status (icons + labels used)

---

## 🛠️ Tools Used

| Category | Tool |
|----------|------|
| Primary Design | Figma (free plan) |
| Prototyping | Figma Prototype + custom plugin |
| Research | Competitor analysis, persona interviews |
| Animation reference | Lottie / After Effects concepts |
| Handoff | Figma Dev Mode |
| Documentation | LaTeX (Overleaf), Markdown |
| Screen generation | Cursor AI (reference), rebuilt in Figma |
| Version control | GitHub |

---

## 📊 Evaluation Alignment

| Criterion | Weight | How this project addresses it |
|-----------|--------|-------------------------------|
| User Research & Empathy | 20% | 8 personas, 3 journey maps, competitor analysis with 20+ pain points documented |
| Design Process & Methodology | 20% | 28-day plan followed, research → wireframe → hi-fi → prototype → testing |
| Visual Design & Aesthetics | 20% | Consistent design system, portal colour identity, WCAG compliant |
| Interaction Design & Prototyping | 20% | 68 prototype connections, 4 user flows, micro-interaction annotations |
| Documentation Quality | 10% | Case study PDF, design system doc, sitemap, journey maps |
| Presentation & Polish | 10% | Annotated screens, professional case study, design system documentation |

---

*Crafted with precision and modern design principles · Zidio Development · March 2026*
