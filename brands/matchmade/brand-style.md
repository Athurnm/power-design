---
brand: Matchmade
slug: matchmade
website: https://matchmade.io
extracted_via: editorial - official product interface
---

---
version: 1.0
name: Matchmade
description: "A dual-canvas B2B enterprise design system for automated ETL data workflows and ledger reconciliation. Marketing hero and presentation surfaces utilize a deep dark slate canvas (#121316) anchored by a glowing Reconciliation Mint (#72E8A6) accent and dark charcoal glass cards (#1E2025). Light marketing sections feature crisp white canvases (#FFFFFF) with pastel chartreuse highlighter accents (#E2F952). In-app enterprise interfaces utilize high-density Slate-50 (#F8FAFC) canvases, crisp white containers, hairline borders (#EAECF0), electric action blue (#2563EB), and a 6-domain pastel taxonomy for ETL DAG worker pipelines."

colors:
  primary: "#72E8A6"
  on-primary: "#0B1912"
  primary-hover: "#4ADE80"
  primary-focus: "#22C55E"
  action-blue: "#2563EB"
  action-blue-hover: "#1D4ED8"
  action-blue-tint: "#EFF6FF"
  lime-highlight: "#E2F952"
  coral-focal: "#F97316"
  coral-tint: "#FFEDD5"
  ink: "#F8FAFC"
  ink-muted: "#94A3B8"
  ink-subtle: "#64748B"
  ink-tertiary: "#475569"
  canvas: "#121316"
  surface-1: "#1E2025"
  surface-2: "#23262D"
  surface-3: "#2A2D35"
  surface-4: "#333742"
  hairline: "#2E323B"
  hairline-strong: "#383D48"
  hairline-tertiary: "#4B5563"
  inverse-canvas: "#FFFFFF"
  inverse-surface-1: "#F8FAFC"
  inverse-surface-2: "#F1F5F9"
  inverse-ink: "#0F172A"
  inverse-ink-muted: "#475569"
  inverse-hairline: "#EAECF0"
  domain-blue: "#2563EB"
  domain-blue-bg: "#EFF6FF"
  domain-cyan: "#0284C7"
  domain-cyan-bg: "#E0F2FE"
  domain-purple: "#9333EA"
  domain-purple-bg: "#F3E8FF"
  domain-amber: "#EA580C"
  domain-amber-bg: "#FFEDD5"
  domain-green: "#16A34A"
  domain-green-bg: "#DCFCE7"
  domain-pink: "#DB2777"
  domain-pink-bg: "#FCE7F3"
  semantic-success: "#16A34A"
  semantic-warning: "#EA580C"
  semantic-danger: "#DC2626"
  semantic-overlay: "rgba(18, 19, 22, 0.8)"

typography:
  display-xl:
    fontFamily: Plus Jakarta Sans, Inter, sans-serif
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.10
    letterSpacing: -2.0px
  display-lg:
    fontFamily: Plus Jakarta Sans, Inter, sans-serif
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -1.4px
  display-md:
    fontFamily: Plus Jakarta Sans, Inter, sans-serif
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: -0.8px
  headline:
    fontFamily: Plus Jakarta Sans, Inter, sans-serif
    fontSize: 28px
    fontWeight: 600
    lineHeight: 1.25
    letterSpacing: -0.5px
  card-title:
    fontFamily: Inter, Plus Jakarta Sans, sans-serif
    fontSize: 18px
    fontWeight: 600
    lineHeight: 1.30
    letterSpacing: -0.2px
  subhead:
    fontFamily: Inter, sans-serif
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: -0.1px
  body-lg:
    fontFamily: Inter, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0
  body:
    fontFamily: Inter, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.50
    letterSpacing: 0
  body-sm:
    fontFamily: Inter, sans-serif
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  caption:
    fontFamily: Inter, sans-serif
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.35
    letterSpacing: 0.3px
  button:
    fontFamily: Inter, sans-serif
    fontSize: 13px
    fontWeight: 600
    lineHeight: 1.20
    letterSpacing: 0.1px
  eyebrow:
    fontFamily: Geist Mono, monospace
    fontSize: 11px
    fontWeight: 500
    lineHeight: 1.30
    letterSpacing: 0.8px
  mono:
    fontFamily: Geist Mono, monospace
    fontSize: 12px
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0

rounded:
  xs: 4px
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  xxl: 24px
  pill: 9999px
  full: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary-mint:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
  button-primary-blue:
    backgroundColor: "{colors.action-blue}"
    textColor: "#FFFFFF"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 8px 16px
  button-pill-demo:
    backgroundColor: "{colors.surface-1}"
    textColor: "#FFFFFF"
    borderColor: "rgba(255, 255, 255, 0.4)"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: 8px 20px
  button-secondary-light:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.inverse-ink}"
    borderColor: "{colors.inverse-hairline}"
    typography: "{typography.button}"
    rounded: "{rounded.sm}"
    padding: 8px 14px
  match-badge:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.caption}"
    rounded: "{rounded.xs}"
    padding: 2px 8px
  feature-card-dark:
    backgroundColor: "{colors.surface-1}"
    textColor: "{colors.ink}"
    borderColor: "{colors.hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  feature-card-light:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.inverse-ink}"
    borderColor: "{colors.inverse-hairline}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 24px
  dag-node-card:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.inverse-ink}"
    borderColor: "{colors.inverse-hairline}"
    typography: "{typography.body-sm}"
    rounded: "{rounded.md}"
    padding: 10px 16px
  category-action-card:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.inverse-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.lg}"
    padding: 16px
  top-nav-light:
    backgroundColor: "#FFFFFF"
    textColor: "{colors.inverse-ink}"
    borderColor: "{colors.inverse-hairline}"
    typography: "{typography.body-sm}"
    height: 56px
  top-nav-dark:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-sm}"
    height: 56px
  footer:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink-muted}"
    typography: "{typography.caption}"
    padding: 64px 32px
---

# Matchmade - Brand Style

## Visual Theme & Atmosphere
Matchmade combines the rigor of financial ledger integrity with the velocity of modern automated data engineering.
- **Marketing Hero & Slide Decks**: Deep dark charcoal slate (`#121316`) canvas contrasted with a signature glowing Reconciliation Mint (`#72E8A6`) accent, subtle floating transaction cards (`#1E2025`), smooth bezier workflow connections, and delicate pastel accent particles (mint, lavender, cyan).
- **Marketing Feature Sections**: Crisp pure white (`#FFFFFF`) with pastel chartreuse/lime highlighter boxes (`#E2F952`) on key phrase headers and clean integration tiles.
- **Enterprise In-App Experience**: High-density Slate-50 (`#F8FAFC`) canvas, pure white panels (`#FFFFFF`), hairline slate borders (`#EAECF0`), electric action blue (`#2563EB`), and a 6-color domain taxonomy for DAG worker nodes and data catalog navigation.

---

## Colors

### Dark Marketing & Presentation Palette
| Role | Hex | Purpose |
|:---|:---|:---|
| Background | `#121316` | Main dark hero / deck canvas |
| Primary / Focal Accent | `#72E8A6` | Glowing Reconciliation Mint for key match states & headlines |
| Primary Contrast Text | `#0B1912` | Dark forest text on mint badges |
| Action Accent (Blue) | `#2563EB` | In-app actions, secondary highlights |
| Card Surface 1 | `#1E2025` | Source cards, transaction panels |
| Card Surface 2 | `#23262D` | Center match hub container |
| Inner Card Surface | `#181A1E` | Nested transaction item rows |
| Hairline Border | `#2E323B` | 1px border on all dark cards |
| Text Primary | `#FFFFFF` | Headlines, monetary numbers |
| Text Muted | `#94A3B8` | Subtitles, labels, currency tags |

### Light In-App & Feature Palette
| Role | Hex | Purpose |
|:---|:---|:---|
| Background | `#F8FAFC` | App viewport background, DAG graph canvas |
| Container / Surface | `#FFFFFF` | Tables, modals, DAG node cards |
| Text Primary | `#0F172A` | Slate-900 high contrast body & titles |
| Text Muted | `#475569` | Slate-600 column headers, secondary text |
| Border | `#EAECF0` | Grid hairlines, card dividers |
| Border Strong | `#CBD5E1` | Input outlines, DAG connector lines |
| Action Primary | `#2563EB` | Blue 600 buttons & active tabs |
| Lime Highlighter | `#E2F952` | Editorial highlight box on white marketing pages |

### 6-Domain Pastel Taxonomy (ETL & Catalog)
1. **Blue (`#2563EB` / `#EFF6FF`)**: Upload files / Data processing
2. **Cyan (`#0284C7` / `#E0F2FE`)**: Upload rules / Format mapping
3. **Purple (`#9333EA` / `#F3E8FF`)**: Data sources / Database connectors
4. **Amber (`#EA580C` / `#FFEDD5`)**: Native tables / Editable grids
5. **Green (`#16A34A` / `#DCFCE7`)**: Worker tables / STT transformation
6. **Pink (`#DB2777` / `#FCE7F3`)**: Multiple views / Dual-ledger Matchmap

---

## Typography

- **Display & Headings:** `Plus Jakarta Sans`, `Inter`, `sans-serif` (Weights: 600, 700, negative tracking on display sizes)
- **Body & Tables:** `Inter`, `Geist Sans`, `sans-serif` (Weights: 400, 500, 600, with `font-feature-settings: "tnum"`)
- **Monospace & Code:** `Geist Mono`, `JetBrains Mono`, `monospace` (For `matchmade_bq_id`, SQL, DAG node keys)

| Role | Size | Weight | Line Height |
|:---|:---|:---|:---|
| Hero Display | 56px - 64px | 700 | 1.10 |
| Section H1 | 32px - 36px | 700 | 1.20 |
| Component H2 | 22px - 24px | 600 | 1.25 |
| Card Title H3 | 16px - 18px | 600 | 1.30 |
| Body Text | 14px - 15px | 400 | 1.50 |
| Dense Table Cell | 13px | 400/500 | 1.40 |
| Mono IDs / Tags | 12px | 400/500 | 1.40 |

---

## Spacing & Shapes

- **Base Grid:** 4px / 8px system (4, 8, 12, 16, 24, 32, 48, 64, 96px)
- **Border Radius:**
  - `4px`: Small tags, table checkboxes
  - `6px`: In-app buttons, match badges, filter pills
  - `8px`: DAG worker node cards, modal condition cards
  - `12px - 14px`: Marketing source cards, action cards
  - `9999px`: Marketing demo pill buttons, avatar circles
- **Shadows:** Minimal / border-first. Dark mode uses 1px borders without drop-shadows. Light mode uses hairline `1px solid #EAECF0` with subtle elevation `0 1px 3px rgba(0, 0, 0, 0.04)`.

---

## Voice & Personality

- **Tone:** Authoritative, technical, high-precision, calm, ledger-grade.
- **Energy:** Focused, efficient, enterprise-ready.
- **Audience:** Financial Controllers, Operations Managers, Data Modelers, and Enterprise Reconciliation Specialists.

### Canonical Voice Samples
- *"All in One Reconciliation - Streamline transaction matching, data parsing, reconciliation, and consolidation with automation."*
- *"All Data Sources in One Place. All Reconciliation in One Flow."*
- *"Visual DAG pipelines link multi-source ledgers with automated transformation and exception routing."*

---

## Quick Reference (for AI Generators)

### CSS Custom Properties
```css
:root {
  /* Brand Accents */
  --mm-mint: #72E8A6;
  --mm-mint-dark: #0B1912;
  --mm-mint-tint: #DCFCE7;
  --mm-blue: #2563EB;
  --mm-blue-tint: #EFF6FF;
  --mm-lime: #E2F952;
  --mm-coral: #F97316;
  
  /* Dark Hero / Slide Canvas */
  --mm-dark-bg: #121316;
  --mm-dark-surface-1: #1E2025;
  --mm-dark-surface-2: #23262D;
  --mm-dark-border: #2E323B;
  --mm-dark-text: #FFFFFF;
  --mm-dark-muted: #94A3B8;
  
  /* Light Enterprise Canvas */
  --mm-light-bg: #F8FAFC;
  --mm-light-surface: #FFFFFF;
  --mm-light-border: #EAECF0;
  --mm-light-border-strong: #CBD5E1;
  --mm-light-text: #0F172A;
  --mm-light-muted: #475569;
  
  /* Radii */
  --mm-radius-sm: 6px;
  --mm-radius-md: 8px;
  --mm-radius-lg: 12px;
  --mm-radius-pill: 9999px;
  
  /* Fonts */
  --mm-font-display: 'Plus Jakarta Sans', 'Inter', sans-serif;
  --mm-font-body: 'Inter', sans-serif;
  --mm-font-mono: 'Geist Mono', monospace;
}
```

---

## Reference
**Website:** [https://matchmade.io](https://matchmade.io)
