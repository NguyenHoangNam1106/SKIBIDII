---
name: Academic Horizon
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dde9ff'
  surface-container-highest: '#d5e3fd'
  on-surface: '#0d1c2f'
  on-surface-variant: '#444653'
  inverse-surface: '#233144'
  inverse-on-surface: '#ebf1ff'
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
  tertiary: '#532a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#743d00'
  on-tertiary-container: '#ffa85d'
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
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77d'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#f8f9ff'
  on-background: '#0d1c2f'
  surface-variant: '#d5e3fd'
  match-high: '#059669'
  match-medium: '#2563EB'
  match-low: '#64748B'
  deadline-urgent: '#E11D48'
  deadline-warning: '#D97706'
  surface-subtle: '#F8FAFC'
  surface-card: '#FFFFFF'
  border-subtle: '#E2E8F0'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '800'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  badge-match:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '700'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an inspiring, trustworthy, and student-first digital environment tailored for Vietnamese higher education students seeking life-changing academic opportunities. The brand personality blends institutional reliability with youthful momentum—demystifying the complex scholarship application process through clarity, optimism, and proactive guidance. 

The aesthetic is built on a refined modern educational movement: ample breathing room, crystal-clear visual hierarchy, high legibility, and purposeful micro-interactions. It rejects bureaucratic clutter and institutional stiffness in favor of an approachable, empowering space where students feel seen, supported, and motivated to achieve their potential.

## Colors

The palette balances academic prestige with dynamic growth:
- **Primary (`#1E40AF` - Academic Blue):** Represents institutional authority, stability, and intellectual pursuit. Applied to primary calls-to-action, active navigational anchors, and dominant interactive elements.
- **Secondary (`#0D9488` - Emerald Teal):** Signifies personal growth, opportunity, and scholarship attainment. Used for key achievements, filter highlights, and progression indicators.
- **Tertiary (`#D97706` - Warm Amber):** Serves as an energetic prompt for critical actions, time-sensitive alerts, and application deadlines nearing closure.
- **Neutral (`#334155` - Slate):** Anchors body copy and structured UI containers, offering superior contrast and readability over sterile blacks.

### Functional Roles & Named States
- `match-high` (`#059669`): Denotes match suitability of 80% and above.
- `match-medium` (`#2563EB`): Denotes match suitability between 50% and 79%.
- `match-low` (`#64748B`): Denotes match suitability below 50%.
- `deadline-urgent` (`#E11D48`): Used exclusively when a deadline falls within 7 calendar days.
- `deadline-warning` (`#D97706`): Flags deadlines closing within 14 calendar days.

## Typography

The type system addresses the dual needs of contemporary visual appeal and flawless Vietnamese diacritic rendering:
- **Headlines (`Plus Jakarta Sans`):** Delivers clean geometry, crisp letterforms, and an optimistic tone across headers, page titles, and scholarship match tags.
- **Body & Labels (`Be Vietnam Pro`):** Engineered natively for Vietnamese diacritics and Latin typography. Prevents vertical clipping and uneven baseline heights when rendering tone marks (`dấu hỏi`, `ngã`, `nặng`, `sắc`, `huyền`).

Mobile breakpoints dynamically downscale all display and primary headline sizes above 24px to ensure headers remain legible without wrapping awkwardly across short viewports.

## Layout & Spacing

The layout is built on a responsive 12-column fluid grid system on desktop that gracefully collapses into 4 columns on mobile devices:
- **Desktop (>= 1024px):** 12-column grid with a 320px fixed or sticky sidebar for filter parameters (academic field, scholarship value slider, requirements checklist) alongside an 8-column or 9-column scholarship card feed.
- **Tablet (768px - 1023px):** 8-column layout where filter controls transform into a top-level horizontal scroll drawer or popover modal sheet.
- **Mobile (< 768px):** 4-column layout with 16px lateral padding. Search and urgent deadline filters pin to a condensed top app bar with expandable filter bottom-sheets.
- **Vertical Rhythm:** Rooted in an 8pt step system (`space-xs` = 4px through `space-xl` = 40px) to govern internal card paddings, list separations, and badge alignments.

## Elevation & Depth

Visual hierarchy uses a refined combination of tonal surfaces, crisp hair-thin outlines, and soft ambient drop shadows to communicate elevation without heaviness:

- **Level 0 (Base Canvas):** `#F8FAFC` background tone ensuring default cards and white interactive panels stand out effortlessly.
- **Level 1 (Cards, Standard Surfaces):** White background (`#FFFFFF`) with a 1px border (`#E2E8F0`) and an ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.05)`.
- **Level 2 (Hovered Cards, Interactive Dropdowns):** Subtle upward micro-lift (`translate-y: -2px`) accompanied by a diffuse shadow: `box-shadow: 0 10px 15px -3px rgba(15, 23, 42, 0.08), 0 4px 6px -4px rgba(15, 23, 42, 0.04)`.
- **Level 3 (Modals, Slide-over Filter Sheets, Sticky Match Banners):** Elevated above backdrop with `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)` and subtle backdrop blur (`backdrop-filter: blur(8px)` with `rgba(15, 23, 42, 0.4)`).

## Shapes

The interface embraces a modern, friendly `Rounded` (level 2) geometry:
- **Base Components (Inputs, Buttons, Badges):** 8px (`0.5rem`) corner radius to create an approachable yet clean tactile affordance.
- **Containers & Cards (`rounded-lg`):** 16px (`1rem`) corner radius for scholarship listing cards, sidebar containers, and dashboard metric widgets.
- **Modal Dialogs & Hero Banners (`rounded-xl`):** 24px (`1.5rem`) for high-level framing elements.
- **Match Pills & Status Badges:** Fully rounded capsule styling (`9999px`) to emphasize quantitative indicators and urgency tags.

## Components

### Scholarship Cards
- Contained within `rounded-lg` surfaces on `#FFFFFF` with a 1px `#E2E8F0` border.
- Header row features the scholarship title (`title-lg`), sponsor/university logo, and the floating Match Percentage Badge in the upper-right corner.
- Body details include an icon-paired grid showing award value, applicable majors, and country/location.
- Footer features the deadline tag pinned to the left and a secondary/tertiary bookmark icon alongside the primary "Xem chi tiết" (View Details) button.

### Match Percentage Badges
- Capsule-shaped pills with dedicated color tiers:
  - **High (>= 80%):** `#ECFDF5` background with `#059669` text and icon.
  - **Medium (50% - 79%):** `#EFF6FF` background with `#2563EB` text.
  - **Low (< 50%):** `#F1F5F9` background with `#64748B` text.
- Formatted as `● 95% Phù hợp` with bold weights for rapid scanning.

### Deadline & Urgency Badges
- Standard deadlines use a neutral badge (`#F8FAFC` background, `#475569` text).
- Urgent deadlines (<= 7 days) render with a pulsating dot indicator, `#FFF1F2` background, and `#E11D48` bold text (`Còn 3 ngày`).

### Buttons
- **Primary:** `#1E40AF` background, white text, 8px radius, subtle hover glow, active scale transition (`scale(0.98)`).
- **Secondary (Opportunity/Action):** `#0D9488` background, white text, for application workflows and eligibility checkers.
- **Outline / Ghost:** `#FFFFFF` background, 1px `#CBD5E1` border, slate text.

### Form Inputs & Filters
- Inputs use 44px minimum touch targets, `#FFFFFF` background, 1px `#CBD5E1` stroke, expanding to a 2px `#1E40AF` focus ring with soft glow.
- Checkboxes and radios use `#1E40AF` fills when selected, with high-contrast white checkmarks.
- Value sliders use track styling with `#0D9488` active fill and solid white thumb nodules.

### Application Checklist Items
- Interactive rows with rounded checkboxes, document title, and uploaded status pills (`Chưa nộp`, `Đã tải lên`, `Cần công chứng`).