---
name: Robertsganj Retail Commerce
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#444653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#2d3449'
  on-tertiary: '#ffffff'
  tertiary-container: '#434b60'
  on-tertiary-container: '#b4bbd5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#dae2fd'
  tertiary-fixed-dim: '#bec6e0'
  on-tertiary-fixed: '#131b2e'
  on-tertiary-fixed-variant: '#3f465c'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '800'
    lineHeight: 34px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 26px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 22px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-sm: 0.75rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system powers a vibrant, approachable, and authoritative omnichannel retail experience for local tech commerce in Tier-2/Tier-3 tech hubs. It bridges high-end consumer technology aesthetics (deep midnight flagship showcases, clean Apple/Samsung tier product presentations) with regional retail trust patterns: transparent localized EMI plans, genuine brand warranty seals, in-store pickup assurances, and instant WhatsApp/call assistance.

The aesthetic blends **Modern Commercial Minimalism** with **Tactile Depth and Vibrant Tech Accents**:
- **Confidence & Credibility:** High-contrast deep navy surfaces for hero banners create instant prestige, while crisp, airy canvas backgrounds ensure high readability for pricing and technical specs.
- **Friendly & Transactional:** Clean typography paired with accessible pill badges (e.g., "0% No-Cost EMI", "Robertsganj In-Store Pickup in 2 Hours", "Official Brand Warranty") lowers purchase friction.
- **Micro-Delight:** Smooth card elevations, pristine product photography cutouts with subtle ambient drop shadows, and lively emerald highlights signify savings and availability.

## Colors

The palette establishes a balance of high-tech digital authority, energetic shopping triggers, and crystal-clear transaction cues.

- **Primary (`#1E40AF` - Tech Cobalt):** Anchors primary call-to-actions, category active states, interactive links, and key branded messaging.
- **Secondary (`#0D9488` - Emerald Teal):** Signifies finance trust, festive savings, zero-interest EMI badges, cashback tags, and genuine warranty verifications.
- **Tertiary (`#0F172A` - Midnight Slate):** Powers flagship product showcases, hero banners, dark contrast cards, and high-impact countdown modules.
- **Neutral (`#64748B` - Slate Grey):** Controls secondary metadata, model specs, muted icon outlines, and inactive borders.
- **Canvas & Containers:** Base canvas is pure `#F8FAFC`, stepping up to `#FFFFFF` for product tiles, with `#F1F5F9` for secondary utility rails and review badges.
- **Status & Utility:** Amber gold (`#F59E0B`) dedicated exclusively to customer review star ratings and flash-deal timers.

## Typography

The design system standardizes on **Plus Jakarta Sans** across all levels. Its balanced geometric proportions and friendly apertures deliver high legibility on mobile screens, even in dense multi-currency specs and dual Hindi-English shop vernacular.

- **Display & Hero Units:** Weighted at `800` (ExtraBold) for flagship device models, headline offers, and high-impact campaign statements.
- **Section Headers & Product Titles:** Weighted at `700` (Bold) with tight line height for quick scanning of model names (e.g., "Galaxy S24 Ultra", "OnePlus 12R").
- **Pricing & Numbers:** Price points utilize `label-lg` or `headline-md` at `700` weight to stand out clearly against device cards.
- **Specifications & Trust Badges:** Set in `body-sm` or `label-sm` with slightly boosted letter spacing for clarity on compact screens.

## Layout & Spacing

The layout follows a fluid-first mobile approach adapting upward to tablet and desktop storefront viewports:

- **Grid Architecture:** 4 columns on mobile viewport with a default outer margin of `1rem` (`16px`) and `0.75rem` gutters. On tablets, transitions to 8 columns; on desktop, locks to a maximum 1200px centered 12-column canvas with `1.5rem` gutters.
- **Horizontal Scrolling Carousels:** Category rails, promotional banners, and peer collections allow edge bleed past the margin on mobile with right-side snap boundaries.
- **Vertical Rhythm:** Sections are partitioned by `space-xl` (`32px`) vertical separation to allow distinct visual breathing room between device categories, finance banners, and customer validation strips.

## Elevation & Depth

Visual hierarchy uses a combination of smooth tonal staging and soft ambient shadows to create tactile layers without visual clutter:

- **Level 0 (Flat Canvas):** `#F8FAFC` base surface for main page body and utility strips.
- **Level 1 (Card Default):** Crisp `#FFFFFF` card surfaces bounded by a hairline border (`rgba(226, 232, 240, 0.8)`) and a diffused resting shadow: `0 2px 8px -2px rgba(15, 23, 42, 0.04), 0 1px 3px 0 rgba(15, 23, 42, 0.02)`.
- **Level 2 (Interactive & Hover):** Lifted cards (e.g., tapped phones, active cart triggers) use `0 10px 20px -5px rgba(30, 64, 175, 0.08), 0 4px 6px -2px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Sticky Action Bars & Overlays):** Sticky bottom checkout/booking bars and floating WhatsApp help buttons use `0 14px 28px rgba(15, 23, 42, 0.12)`.
- **Hero Staging:** Dark hero containers apply a subtle inner top light highlight (`inset 0 1px 1px rgba(255, 255, 255, 0.1)`) against deep `#0F172A` to create depth behind floating smartphone cutouts.

## Shapes

The system uses a contemporary **Rounded** geometry (`roundedness: 2` with standard radii of `0.5rem` or `8px`, scaling to `1rem` or `16px` for structural cards, and full pills for badges).

- **Standard Elements (0.5rem / 8px):** Input fields, inline badges, review cards, and countdown digits.
- **Feature Cards & Modals (1rem / 16px):** Product cards, category spotlight cards, EMI promo containers, and the primary hero showcase.
- **Interactive Badges & Main Buttons (Full Pill / 9999px):** Category pill tabs, primary "Shop Now" CTAs, "Claim EMI", and floating communication buttons.

## Components

### Buttons
- **Primary CTA:** High-contrast pill-shaped button in pure tech cobalt (`#1E40AF`) with bold white text (`label-md`). On hero sections, shifts to crisp white `#FFFFFF` with `#0F172A` bold typography and an arrow icon.
- **Secondary / Action Link:** Subtle slate-ghost buttons with right-facing chevrons (`Learn More →`), styled in primary blue or emerald depending on the offer type.
- **Quick Action (Call / WhatsApp):** Floating pill button on mobile containing the local store helpline and instant stock verification.

### Product Showcase Cards
- **Base Grid Card:** White surface with rounded corners (`16px`), containing an isolated device render centered over a soft light-tint background, followed by device brand/model, starting price, and star rating with review count.
- **Badge Overlay:** Top-left placed pills for "5G Ready", "Best Seller", or "₹0 Down Payment" in emerald or cobalt tints.

### Promotion & EMI Feature Tiles
- **Multi-Offer Grid:** Split 3-column or 2-column promo banners featuring soft background tints (lavender, icy cyan, soft gold) paired with 3D product renders or typography highlights (e.g., large "0%" graphic for No-Cost EMI).

### Category Navigation Rail
- **Icon + Label Stacks:** Top navigation horizontal strip featuring clean linear monochrome device icons (Phones, Audio, Wearables, Tablets, Deals) on circular or pill backdrops that invert to Tech Cobalt when active.

### Trust & Assurance Strips
- **Local Credibility Banner:** Horizontal badge ribbon highlighting 4 core pillars: "100% Genuine Devices", "Official Brand Warranty", "Instant Robertsganj Store Pickup", and "Flexible EMI Options" with paired micro-icons.
- **Reviews & Ratings Module:** Clean horizontal testimonial tiles featuring Trustpilot / Google 5-star badges and localized customer feedback quotes.

### Input Fields & Newsletter
- **Store Alert Input:** Full-width rounded field with an inset white surface, muted `#64748B` placeholder, and an attached primary pill "Subscribe" or "Notify Me" button.