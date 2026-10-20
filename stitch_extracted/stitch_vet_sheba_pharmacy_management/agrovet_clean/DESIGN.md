---
name: AgroVet Clean
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
  on-surface-variant: '#3e4943'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#6e7a73'
  outline-variant: '#bdc9c1'
  surface-tint: '#006c4e'
  primary: '#005d42'
  on-primary: '#ffffff'
  primary-container: '#047857'
  on-primary-container: '#9ffdd3'
  inverse-primary: '#7bd8b1'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#0047bf'
  on-tertiary: '#ffffff'
  tertiary-container: '#1e5fe7'
  on-tertiary-container: '#e6e9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#97f5cc'
  primary-fixed-dim: '#7bd8b1'
  on-primary-fixed: '#002115'
  on-primary-fixed-variant: '#00513a'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 30px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Inter
    fontSize: 17px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
  currency-display:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes a high-trust, functional, and modern SaaS aesthetic tailored for veterinary pharmacists and agro-retailers across Bangladesh. It addresses users working in fast-paced retail counters, often in bright outdoor light or low-lit rural pharmacies, requiring immediate legibility, error prevention, and frictionless one-thumb mobile workflows.

The design movement merges **Modern Corporate Utility** with **Tactile Functionalism**. It avoids clinical coldness by utilizing rich emerald tones tied to agricultural health, vitality, and financial growth. Interfaces feel crisp, organized, and dependable, conveying professional software standards without overwhelming operators accustomed to physical ledgers (খাতা). High-contrast touch targets, generous hit surfaces, and bilingual balance eliminate cognitive strain during high-volume counter sales and stock entry.

## Colors
The palette centers around deep agricultural emeralds, cool technical slates, and vivid contextual status indicators.

- **Primary Canvas & Surfaces:** Application canvas is set to Soft Off-White (`#F8FAFC`), layering cleanly against Subsurface Slate (`#F1F5F9`) and elevated cards in Pure White (`#FFFFFF`). Boundaries are delineated by crisp hairline borders (`#E2E8F0`).
- **Brand Accents:** Deep Forest Emerald (`#047857`) establishes primary brand ownership, interactive primary fills, and header elements. Secondary Mint (`#10B981`) and Mint Tint (`#ECFDF5`) provide luminous highlights, active pills, and focus ring definitions.
- **Status Tiers:**
  - **Success / Paid / Synced:** Forest Green (`#059669`) over Pale Mint (`#D1FAE5`).
  - **Warning / Near-Expiry / Due (বাকি):** Deep Amber (`#D97706`) over Soft Amber (`#FEF3C7`).
  - **Danger / Expired / Out of Stock (স্টক শেষ):** Rich Crimson (`#DC2626`) over Soft Rose (`#FEE2E2`).
  - **Info / Cloud Sync Pending:** Royal Blue (`#2563EB`) over Soft Sky (`#DBEAFE`).
- **Text & Contrast:** Primary content and numerical values use Dark Navy Slate (`#0F172A`). Secondary supporting text, manufacturer names, and metadata use Muted Slate (`#64748B`). Hairline dividers utilize `#CBD5E1`.

## Typography
The system supports dual-script balance. In runtime environments, standard font stack declarations pair **Hind Siliguri** (or system Bengali fallback) with **Inter** for Latin numerals, batch codes, and currency formatting.

- **Bengali Baseline:** Bengali letterforms require generous vertical room to avoid clipping vowel diacritics (কার ও ফলা). Line heights are scaled 1.4x to 1.5x of font size.
- **Data & Numeric Displays:** All financial numbers, stock units, and barcode references enforce tabular lining (`font-variant-numeric: tabular-nums`) using Inter for vertical alignment in POS lists and ledgers.
- **Bengali Labels:** UI controls utilize medium-to-semibold weights (`500` or `600`) in Hind Siliguri to maintain legibility against light-tint backgrounds.

## Layout & Spacing
The layout relies on a mobile-first fluid shell optimized around a **390px** baseline viewport, scaling cleanly up to tablet and desktop POS monitors.

- **Mobile Viewport (320px - 640px):** Single-column fluid architecture. Outer margin is locked to `1rem` (16px) to maximize screen area. Gaps between grid cards default to `0.75rem` (12px).
- **Tablet & POS Stations (641px - 1024px):** 6-column grid with `1.5rem` outer margins. POS sales entry screens convert into a 2/3 billing register and 1/3 quick-inventory access drawer.
- **Desktop (1025px+):** 12-column structured layout with maximum content container width of `1280px`, anchored by a compact collapsible sidebar.
- **Thumb Zone Compliance:** Key operational CTAs (e.g., "বিক্রয় নিশ্চিত করুন" / Confirm Sale, "বারকোড স্ক্যান" / Scan) remain pinned within bottom sticky sheets, resting comfortably inside thumb reach.

## Elevation & Depth
Elevation conveys physical presence without heavy skeuomorphic clutter. Depth relies on ambient green-tinted shadows and surface boundaries.

- **Tier 0 (Base / Canvas):** Neutral `#F8FAFC`, flat, zero elevation.
- **Tier 1 (Cards, Ledger Rows, Metric Tiles):** Surface `#FFFFFF`, surrounded by border `1px solid #E2E8F0` and subtle shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Tier 2 (Popovers, Sticky Barcode Dock, Floating Action Buttons):** Surface `#FFFFFF`, border `1px solid #CBD5E1`, with shadow: `0 4px 6px -1px rgba(6, 95, 70, 0.08), 0 2px 4px -2px rgba(6, 95, 70, 0.05)`.
- **Tier 3 (Modal Bottom Sheets, Sync Warning Drawers):** Shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)`, paired with a tinted backdrop overlay of `rgba(15, 23, 42, 0.45)`.

## Shapes
A modern, balanced curvature standard (`roundedness: 2`) defines all interaction touchpoints.

- **Standard Elements (Buttons, Inputs, Metric Badges):** `rounded-md` (0.5rem / 8px) to `rounded-lg` (0.75rem / 12px) provide friendly, approachable corners that remain distinct in data grids.
- **Cards & Data Modules:** `rounded-xl` (1rem / 16px) with structural clipping for nested tables and list groups.
- **Bottom Drawers & Modals:** `rounded-t-2xl` (1.5rem / 24px) for tactile upward mobile sheets.
- **Status Pills & Micro Indicators:** Pill-shaped (`rounded-full` / 9999px) for operational state tags like "পরিশোধিত" (Paid) or "বাকি" (Due).

## Components

### Buttons
- **Primary Action (বিক্রয়, যোগ করুন):** Deep Emerald (`#047857`) background, `#FFFFFF` text, subtle inset shadow on active press (`translate-y-[0.5px]`). Height: 48px on mobile for thumb accuracy.
- **Secondary / Actionable Border:** Clean white fill with `#047857` border and text.
- **Destructive (মুছে ফেলুন, স্টক বাতিল):** Soft Rose fill (`#FEE2E2`) with `#DC2626` text, escalating to solid red upon confirmation modals.

### Input Fields & Search Bars
- **POS Search Inputs:** Height 44px, pure white surface, `1px solid #CBD5E1` border, 12px inner padding. Includes leading barcode search icon and trailing Bengali clear trigger.
- **Focus State:** Rings transition to `2px solid #10B981` with an outer mint glow (`rgba(16, 185, 129, 0.15)`).

### Inventory & Sales Cards
- High-density list cards showing:
  - Top row: Medicine brand (e.g., "Renata Animal Health", "Square Vet") in uppercase 11px slate typography.
  - Middle row: Product commercial name (e.g., "Renamycin 100ml") in 16px semibold navy text, paired with price display `৳৪৫০.০০`.
  - Bottom row: Batch code (`#BAT-2024-09`), stock badge (`স্টক: ৪২ পিস`), and expiry tag (`মেয়াদ: ১২/২৫`).

### Status Badges & Chips
- **Due Payment (বাকি):** Amber background (`#FEF3C7`), text `#D97706`, bold display of remaining amount (`৳১,২৫০`).
- **Paid (পরিশোধিত):** Mint background (`#D1FAE5`), text `#059669`.
- **Sync Status:** Pulsing circular indicator in header: Solid Green (`#059669`) for "সংযুক্ত ও সংরক্ষিত" (Synced), pulsing Blue (`#2563EB`) with rotation animation for "ক্লাউড সিঙ্ক হচ্ছে..." (Syncing).

### Navigation & App Bars
- **Top App Bar:** Ultra-compact (52px height) emerald gradient header (`#065F46` to `#047857`), displaying brand logotype, active shop selector ("মেসার্স ভাই ভাই ভেটেরিনারি"), and cloud sync ping badge.
- **Bottom Navigation Bar:** Height 64px, frosted pure white dock (`rgba(255, 255, 255, 0.95)` with backdrop-blur), 4 persistent destinations: বিক্রয় (POS Sale), স্টক (Stock), বাকি খাতা (Ledger/Due), এবং রিপোর্ট (Reports). Active item tinted `#047857` with 4px pill indicator.