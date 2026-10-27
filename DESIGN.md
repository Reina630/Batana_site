---
name: Batana Élixir Botanique
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#504440'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#827470'
  outline-variant: '#d3c3be'
  surface-tint: '#74584e'
  primary: '#090100'
  on-primary: '#ffffff'
  primary-container: '#2c1810'
  on-primary-container: '#9e7e73'
  inverse-primary: '#e3bfb2'
  secondary: '#845326'
  on-secondary: '#ffffff'
  secondary-container: '#febc85'
  on-secondary-container: '#78491d'
  tertiary: '#000400'
  on-tertiary: '#ffffff'
  tertiary-container: '#0c2209'
  on-tertiary-container: '#728c6a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbce'
  primary-fixed-dim: '#e3bfb2'
  on-primary-fixed: '#2a170f'
  on-primary-fixed-variant: '#5a4137'
  secondary-fixed: '#ffdcc2'
  secondary-fixed-dim: '#fab983'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#683c11'
  tertiary-fixed: '#ceebc3'
  tertiary-fixed-dim: '#b2cea8'
  on-tertiary-fixed: '#0a2008'
  on-tertiary-fixed-variant: '#354d2f'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

### Brand Personality & Emotional Intent
The brand embodies raw, ancestral botanic power synthesized with contemporary Parisian cosmetic luxury. It projects clinical efficacy through organic purity, elevating Batana oil from an indigenous secret to an essential prestige ritual. The interface evokes warmth, deep sensory indulgence, bespoke craftsmanship, and unwavering dermatological confidence. Interactions must feel serene, weighted, and tactile rather than hasty or strictly transactional.

### Visual Style
A refined synthesis of **Luxury Editorial** and **Organic Tactility**. The aesthetic relies on luminous cream canvases, deep espresso typographic contrasts, warm amber micro-interactions, and botanical depth. Rather than cold clinical minimalism, the design leverages atmospheric warmth: gentle warm-toned drop shadows, frosted amber glass overlays, and delicate hairline separators that echo premium packaging and high-end print editorial.

## Colors

### Palette Strategy
- **Primary (`#2C1810` - Terre Torréfiée):** Deep coffee brown delivering regal grounding, high-fashion contrast, and premium typographic weight. Replaces harsh synthetic blacks.
- **Secondary (`#C68B59` - Ambre Huileux):** The vital golden-amber hue of cold-pressed batana oil. Applied to interactive accents, primary conversion badges, active states, and focal highlights. An elevated metallic variant (`#D4AF37`) is reserved strictly for seal icons, certifications, and subtle border glints.
- **Tertiary (`#3B5335` - Palme Sauvage):** An earthy, deep palm frond green used to validate botanical sourcing, natural claims, clinical trial metrics, and ingredient certification tags.
- **Neutral Canvas (`#FAF7F2` - Soie Crème):** A comforting, warm ivory substrate that radiates quiet luxury and eliminates clinical starkness. A darker surface layer (`#F0EAE1`) creates subtle architectural nesting.

### Role Assignments
- **Surfaces:** `#FAF7F2` (Background), `#FFFFFF` (Elevated Cards/Containers), `#F0EAE1` (Subtle Secondary Groupings), `#2C1810` (Dark Editorial Narrative Cards).
- **Text:** `#2C1810` (Primary Headlines & Body), `#63483D` (Muted/Secondary Descriptions), `#FAF7F2` (Inverted on dark substrates).
- **Interactive:** `#C68B59` (Primary Actions), `#3B5335` (Trust/Badges/Affirmations), `#8E2818` (System Error), `#2B5E3F` (System Success).

## Typography

### Hierarchy & Pairing
- **Playfair Display (Headlines):** Classical transitional serif offering distinct editorial authority, sharp serifs, and high-contrast elegance reminiscent of prestige fragrance and beauty publications.
- **Plus Jakarta Sans (Body & UI):** Clean, geometric, contemporary sans-serif engineered for digital legibility. It neutralizes the ornamental weight of the serif, providing clarity for botanical descriptions, usage instructions, and transactional checkout steps.

### Editorial Treatments
- Overlines and category chips utilize `label-sm` or `label-md` forced to uppercase with expansive tracking (`0.08em` to `0.1em`) to create an haute-parfumerie cadence.
- Numeric metrics in clinical results (e.g., "+94%", "48H") are rendered using Playfair Display to celebrate empirical findings with stately grandeur.

## Layout & Spacing

### Layout Structure
A 12-column responsive fluid grid system is anchored to a maximum width of `1280px` for standard editorial reading and `1440px` for high-impact visual showcases. 

- **Desktop (1024px+):** 12 columns, `1.5rem` (24px) gutters, and `2rem` (32px) margins (expanding fluidly up to 80px on ultrawide displays).
- **Tablet (768px – 1023px):** 8 columns, `1.25rem` (20px) gutters, `1.5rem` (24px) margins.
- **Mobile (< 768px):** 4 columns, `1rem` (16px) gutters, `1.25rem` (20px) margins.

### Spacing Philosophy
Spacing breathes generously to reflect an unhurried, luxury mindset. Product display grids and before/after comparison sliders favor expansive padding (`space-xl` and higher) to frame imagery like works in a contemporary gallery. Component internals maintain structured micro-rhythms with `space-sm` and `space-md` for concise, scannable data.

## Elevation & Depth

### Ambient Warmth & Diffused Depth
Rather than cold synthetic drop shadows, this design system uses double-layered, warm-tinted ambient shadows infused with Terre Torréfiée (`#2C1810` at 4%–8% opacity) mixed with an amber bloom (`#C68B59` at 3%–6% opacity). 

- **Level 1 (Cards, Product Tiles):** Offset `0 4px 16px -2px rgba(44, 24, 16, 0.05)`, backed by a `1px` subtle outline in `#EADECE`.
- **Level 2 (Popovers, Sticky Bar, Dropdowns):** Offset `0 12px 32px -4px rgba(44, 24, 16, 0.08)`.
- **Level 3 (Modals, Before/After Interactive Drawers):** Offset `0 24px 48px -8px rgba(44, 24, 16, 0.14)`.

### Glassmorphism & Translucency
Frosted amber acrylic is applied to sticky navigation ribbons and filter bars using `backdrop-filter: blur(16px)` with an `rgba(250, 247, 242, 0.85)` fill, bound by an ultra-fine `1px solid rgba(198, 139, 89, 0.2)` edge.

## Shapes

### Architecture
A subtle soft-corner profile (`roundedness: 1`, base `0.25rem` / 4px) is employed to preserve tailored, architectural precision while avoiding aggressive sharpness. 

- **Buttons & Form Fields:** `4px` (`rounded-sm`), delivering deliberate, structured sophistication.
- **Cards & Media Panels:** `8px` (`rounded-lg`), softening clinical and transformation photography without appearing playful or bubbly.
- **Badges & Micro-Pills:** Circular / Fully rounded (`9999px`) to offset rigid rectangular layouts and denote organic certitude.

## Components

### Buttons
- **Primary:** Background in `#2C1810` (or `#C68B59` for commercial checkout CTAs), text in `#FAF7F2`, `rounded-sm` (4px). Padding `14px 28px`. Hover shifts background to an enriched gold tone or deep umber with a delicate amber shadow bloom.
- **Secondary / Outline:** Background transparent, border `1px solid #2C1810`, text `#2C1810`. Hover transitions to a soft ivory wash (`#F0EAE1`).
- **Text Link:** Styled with `label-md`, uppercase, tracked `0.08em`, featuring a perpetual hairline underline in `#C68B59` with a `4px` offset.

### Chips & Botanical Badges
- Compact pill-shaped elements (`9999px`). 
- **Ingredient Chip:** Neutral tint (`#F0EAE1`), text `#2C1810`, paired with a botanical micro-dot in `#3B5335`.
- **Clinical Claim Chip:** Pale sage surface (`rgba(59, 83, 53, 0.08)`), text `#3B5335`, border `1px solid rgba(59, 83, 53, 0.25)`.

### Input Fields
- Understated elegance: `#FFFFFF` surface with a `1px` border in `#EADECE`, `rounded-sm` (4px), padding `12px 16px`.
- Active/Focus: Border transitions to `#C68B59` with a `0 0 0 2px rgba(198, 139, 89, 0.15)` ring glow. Placeholder rendered in soft warm taupe `#9B8B82`.

### Selection Controls (Checkboxes & Radios)
- Base border `1.5px solid #63483D` with subtle `2px` corners for checkboxes; circular for radios.
- Checked state: Filled with `#2C1810` featuring an amber checkmark icon or inner dot in `#D4AF37`.

### Cards & Media Blocks
- **Product Card:** Crisp white surface (`#FFFFFF`) framed by a hairline border (`#EADECE`), housing an image slot with a pale cream backplate (`#F5EFEB`). Contains a quick-add amber button, price displayed in `body-md` bold, and rating metric.
- **Clinical Transformation Card (Before/After):** Dual split container featuring an interactive central drag handle in `#C68B59`. Displays clinical trial parameters (e.g., "Jour 1 vs Jour 30") encapsulated in floating glassmorphic tags top-left and top-right.

### Specialized Component: Sensory Accordion
- Minimalist expansion panels for "Rituel d'Application", "Origine Botanique", and "Résultats Cliniques". Separated by delicate hairline borders (`rgba(44, 24, 16, 0.12)`). Expanded states reveal custom illustrative line art tinted with Terre Torréfiée.