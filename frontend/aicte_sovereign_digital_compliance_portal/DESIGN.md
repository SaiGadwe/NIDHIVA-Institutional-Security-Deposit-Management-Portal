---
name: AICTE Sovereign Digital Compliance Portal
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#44464f'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#465d91'
  primary: '#00163d'
  on-primary: '#ffffff'
  primary-container: '#0f2b5c'
  on-primary-container: '#7c94cb'
  inverse-primary: '#afc6ff'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#001e08'
  on-tertiary: '#ffffff'
  tertiary-container: '#003514'
  on-tertiary-container: '#45a75f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#afc6ff'
  on-primary-fixed: '#001944'
  on-primary-fixed-variant: '#2d4678'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#95f8a7'
  tertiary-fixed-dim: '#79db8d'
  on-tertiary-fixed: '#00210a'
  on-tertiary-fixed-variant: '#005323'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
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
    lineHeight: 16px
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.025em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-tablet: 1.25rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 1.5rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 2rem
---

## Brand & Style

This design system establishes a high-assurance, sovereign Indian GovTech interface engineered for statutory transparency, non-repudiation, and rigorous compliance auditing. Designed specifically for institutional registrars, chartered accountants, apex banking partners, and AICTE scrutiny officers managing institutional Security Deposits and Fixed Deposit Receipts (FDR), the aesthetic bridges sovereign authority with next-generation Digital Public Infrastructure (DPI) efficiency.

### Visual Philosophy & Tone
- **Statutory Authority & Institutional Gravitas:** Draws visual vernacular from premier national infrastructures such as GSTN, DigiLocker, and modern RBI digital rails. The interface relies on deliberate structure, crisp delineation, and institutional trust markers rather than decorative whimsy.
- **Audit-First Utilitarianism:** Information density is treated as a core virtue. Critical data points—lien status, joint-name hypothecation, maturity dates, interest reinvestment mandates, and penalty counters—must be visible with zero ambiguity.
- **National Tri-Color Anchors:** Heritage saffron, navy, and forest green are applied structurally as state-machine status indicators, compliance checkpoints, and authenticators, preventing visual noise while upholding statutory dignity.
- **Zero-Ambiguity Feedback:** High-contrast alerts, verified digitally signed badges, and explicit lifecycle counters reassure users during high-stakes financial operations.

## Colors

The palette balances sovereign dignity, legal consequence, and absolute clarity under strict WCAG AAA guidelines for state platforms.

### Palette Architecture
- **Primary Sovereign Navy (`#0F2B5C`, `#1E3A8A`):** The primary anchor for top navigation rails, high-level headers, active statutory tabs, primary CTAs, and secure transaction panels. Conveying unyielding institutional stability.
- **Heritage Saffron & Gold (`#D97706`, `#EA580C`):** Denotes secondary emphasis, statutory caveats, pre-expiry alerts (e.g., "FDR Expiring in < 30 Days"), verification-in-progress indicators, and procedural cautions.
- **Tri-Color Compliance Green (`#15803D`, `#166534`):** Designates confirmed status: "Lien Marked to AICTE", "Joint Name Validated", "Principal Deposited", and cryptographically signed artifacts.
- **Regulatory Crimson (`#B91C1C`, `#991B1B`):** Reserved for statutory default, encashment notice, missed renewal, KYC mismatch, or defective instrument rejection.
- **Surface & Canvas Neutrals (`#F8FAFC`, `#F1F5F9`, `#FFFFFF`):** High-efficiency workspace backgrounds reducing cognitive fatigue in tabular scrutiny.
- **Borders & Delineations (`#E2E8F0`, `#CBD5E1`):** Structural borders separating data cells, verification blocks, and signature timelines.

### Functional States
- `state-verified`: `#DCFCE7` (Fill) / `#15803D` (Text/Stroke)
- `state-pending-scrutiny`: `#FEF3C7` (Fill) / `#B45309` (Text/Stroke)
- `state-lien-defective`: `#FEE2E2` (Fill) / `#B91C1C` (Text/Stroke)
- `state-encashed`: `#F1F5F9` (Fill) / `#475569` (Text/Stroke)

## Typography

The type system pairs **Inter** for clean UI readability with **JetBrains Mono** for all regulatory financial values, FDR account numbers, IFSC codes, SHA-256 digital signature hashes, and transaction identifiers.

- **Legibility at Scale:** Dense bureaucratic verification demands extreme typographic clarity. Inter's tall x-height and distinct glyph disambiguation (e.g., `0` vs `O`, `l` vs `1`) ensure zero misread values during multi-crore deposit reviews.
- **Financial Monospace Usage:** Every currency sum (`₹ XX,XX,XXX`), maturity value, FDR receipt number, and validation timestamp is rendered in **JetBrains Mono** via `label-lg`, `label-md`, or `label-sm` to maintain columnar alignment in balance tables and audit grids.
- **Hierarchy Rules:** Section headers always enforce uppercase tracking (`tracking-wider`) at `12px` font size for statutory category demarcation (e.g., `INSTITUTION LEGAL IDENTIFIERS`, `BANK LIEN DECLARATION`).

## Layout & Spacing

The portal adopts an authoritative **12-column fluid grid system** anchored by explicit container constraints to prevent sprawling on ultra-wide supervisory monitors.

### Screen Adaptations & Breakpoints
- **Desktop (≥ 1280px):** 12-column layout with `2.5rem` (`margin-desktop`) canvas margins and `1.5rem` (`gutter-desktop`) gutters. Three-tier split views: navigation sidebar (fixed 260px), central master ledger / verification workspace (dynamic fluid), and contextual audit-log / e-signature drawer (collapsible 380px).
- **Tablet (768px – 1279px):** 8-column layout with `1.5rem` margins and `1.25rem` gutters. The audit drawer moves into an expandable modal bottom sheet; tabular layouts unlock horizontal scroll with frozen primary identification columns (Institution Code + FDR Number).
- **Mobile (< 768px):** 4-column layout with `1rem` margins and `1rem` gutters. Complex multi-field data cards replace continuous table rows; high-priority compliance status badges collapse into a standardized sticky top action-banner.

### Rhythmic Density
A base 4px metric underpins all component paddings. Strict data-entry screens employ `space-sm` (8px) between form labels and inputs, with `space-md` (12px) separating cell contents to maximize vertical viewport utilization during document audits.

## Elevation & Depth

Visual hierarchy rejects excessive, diffused floating shadows in favor of **structural boundaries and low-contrast surface nesting**, reflecting official Indian administrative integrity.

### Depth Archetypes
1. **Level 0 (Base Bedrock):** Slate background (`#F8FAFC`). Provides the structural canvas.
2. **Level 1 (Card & Ledger Surfaces):** Pure White (`#FFFFFF`) with a 1px crisp outline (`#E2E8F0`) and an ambient anchor shadow: `0px 1px 3px rgba(15, 43, 92, 0.05)`. Used for FDR detail cards, statutory declaration boxes, and tabular datasets.
3. **Level 2 (Active Scrutiny & Focused Panels):** Enhanced definition with `border-color: #CBD5E1` and `box-shadow: 0px 4px 6px -1px rgba(15, 43, 92, 0.08), 0px 2px 4px -2px rgba(15, 43, 92, 0.04)`. Applied to active draft reviews, document sidebars, and verification panels.
4. **Level 3 (Modal Overlays, OTP Approvals & Digital Signers):** Backdrop filter `blur(4px)` with `#0F2B5C` at 30% alpha tint. Elevates high-stakes dialogs (e.g., "Encashment Authorization", "Lien Foreclosure Approval") with `box-shadow: 0px 20px 25px -5px rgba(15, 43, 92, 0.15)`.

Crisp 1px dividers (`#E2E8F0`) are mandatory between structural zones. Surfaces never appear weightless; every panel feels anchored to the legal ledger.

## Shapes

The portal implements **Roundedness Level 1 (Soft)** with strict geometric precision:
- Standard elements (buttons, inputs, select fields, alert callouts): `0.25rem` (4px).
- Container panels, data cards, and table shells: `0.375rem` (6px) or `0.5rem` (8px).
- Countdown pills and status chips: Full pill-radius (`9999px`) to create an immediate visual distinction between actionable/immutable metadata chips and editable form boundaries.

This compact rounding communicates rigorous administrative formality and software resilience, avoiding consumer-app visual softness while preventing aggressive sharp edges.

## Components

### 1. Buttons
- **Primary Statutory CTA:** Deep Navy background (`#0F2B5C`), text `#FFFFFF`, border `1px solid #0F2B5C`, subtle hover `#1E3A8A`. Text is 14px bold Inter with 4px border-radius. Contains leading icon (e.g., DSC Key or Checkmark).
- **Secondary Regulatory Action:** White background, text `#0F2B5C`, border `1px solid #CBD5E1`, hover `#F1F5F9`.
- **Destructive Statutory Action (Notice of Foreclosure / Rejection):** White background, text `#B91C1C`, border `1px solid #FCA5A5`, hover `#FEF2F2`.

### 2. Status Badges & Countdown Pills
- **Status Badges:** Compact rectangular (`4px` radius) with `font-family: JetBrains Mono`, 11px uppercase bold.
  - *Active AICTE Lien:* Background `#DCFCE7`, border `#86EFAC`, text `#14532D`.
  - *Pending Bank Confirmation:* Background `#FEF3C7`, border `#FDE68A`, text `#78350F`.
  - *Lien Defective / Expired:* Background `#FEE2E2`, border `#FCA5A5`, text `#7F1D1D`.
- **Maturity Countdown Pills:** Pill-shaped (`9999px`), 12px monospaced typography with a pulsing indicator dot.
  - Critical countdown (`< 15 days`): Border and text `#EA580C`, soft background `#FFF7ED`.

### 3. Data Tables (The Scrutiny Ledger)
- **Table Headers:** Background `#F1F5F9`, border-bottom `2px solid #CBD5E1`, text 12px uppercase Inter (`#475569`, bold).
- **Table Cells:** Height 44px (dense) or 52px (standard). Border-bottom `1px solid #E2E8F0`. Hover state `#F8FAFC`.
- **Numeric & Identity Cells:** Monospaced alignment with right-aligned currency calculations and left-aligned fixed-width FDR numbers.

### 4. Form Inputs & Verification Fields
- **Input Architecture:** Height 40px, border `1px solid #CBD5E1`, radius 4px, background `#FFFFFF`. Active focus ring: `2px solid #0F2B5C` with `0px` outline offset.
- **Read-Only / Statutory Locked Fields:** Background `#F8FAFC`, border `#E2E8F0`, text `#64748B`, padlock icon appended to the trailing edge.

### 5. Institutional Header & Emblem Banner
- **GovTech Top Bar:** Top sovereign bar (3px tricolor linear gradient: `#EA580C` 33%, `#FFFFFF` 33% 66%, `#15803D` 66%).
- **Header Structure:** 64px height, Deep Navy base (`#0F2B5C`), gold-stamped AICTE national emblem housing, bilingual portal title ("अखिल भारतीय तकनीकी शिक्षा परिषद / All India Council for Technical Education"), alongside session security timestamp and DSC certificate identifier.

### 6. Alert & Scrutiny Banners
- **Structural Layout:** Left border accented (4px solid), 12px padding, subtle tinted background.
  - *Warning Banner:* Solid `#D97706` left stroke, `#FFFBEB` background, containing statutory Act references and mandatory compliance deadlines.
  - *Cryptographic Verification Strip:* Solid `#15803D` left stroke, showing verification hash, signing officer name, and timestamp.