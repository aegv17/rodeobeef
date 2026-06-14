---
name: Prime Heritage
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e3beb8'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#aa8984'
  outline-variant: '#5a403c'
  surface-tint: '#ffb4a8'
  primary: '#ffb4a8'
  on-primary: '#690000'
  primary-container: '#8b0000'
  on-primary-container: '#ff907f'
  inverse-primary: '#b52619'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#bcc3ff'
  on-tertiary: '#001a98'
  tertiary-container: '#0025c8'
  on-tertiary-container: '#9ea9ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#920703'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#dfe0ff'
  tertiary-fixed-dim: '#bcc3ff'
  on-tertiary-fixed: '#000d60'
  on-tertiary-fixed-variant: '#0d2ccc'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
  off-white: '#F9F7F2'
  charcoal-light: '#1A1A1C'
  deep-burgundy: '#4A0404'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
spacing:
  unit: 8px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  section-gap: 160px
---

## Brand & Style

The design system for Rodeo Beef embodies the concept of "Artisanal Authority." It balances the rugged, traditional roots of cattle ranching with the sophisticated precision of a premium gourmet brand. The visual narrative is built on the tension between raw textures and refined layouts, evoking an emotional response of trust, exclusivity, and culinary excellence.

The aesthetic follows a **Minimalist-Premium** movement. It utilizes expansive whitespace to allow high-fidelity food photography to act as the primary emotional driver. The style is characterized by cinematic contrast, editorial-grade typography, and subtle metallic accents that suggest a "gold standard" of quality. The overall feel is modern yet timeless—positioning the product not just as food, but as a luxury experience for the year 2026 and beyond.

## Colors

The palette is anchored in a high-contrast dark mode to simulate the atmosphere of a high-end steakhouse. 

- **Primary (Rich Burgundy):** Used sparingly for focus states, call-to-action buttons, and brand accents. It represents the "marbling" and richness of the product.
- **Secondary (Subtle Gold):** Reserved for premium signifiers, such as "Reserve" labels, icons, and thin borders. 
- **Neutral (Deep Charcoal & Off-White):** The background is a layered charcoal black (`#0A0A0A`) rather than pure black to maintain depth. Off-white (`#F9F7F2`) is used for body text to reduce eye strain while maintaining a stark, elegant contrast.

## Typography

The typographic system uses a classic pairing of a high-contrast serif and a precision-engineered sans-serif.

- **Headlines:** **Playfair Display** provides an editorial, sophisticated feel. Large display sizes should use tighter letter spacing to feel "locked-in" and authoritative.
- **Body:** **Hanken Grotesk** is chosen for its contemporary, clean proportions. It ensures the brand feels modern and tech-forward (the "2026 feel") despite its traditional subject matter.
- **Micro-copy:** Small labels use uppercase Hanken Grotesk with generous letter spacing to act as "stamps" of quality on product cards and headers.

## Layout & Spacing

This design system employs a **Fixed Grid** philosophy for desktop to maintain a controlled, gallery-like presentation. 

- **Grid Model:** A 12-column grid with wide gutters (24px) allows for asymmetrical layouts that feel curated.
- **Vertical Rhythm:** A heavy emphasis on vertical "breathing room." Section gaps are intentionally large (160px+) to ensure the user focuses on one narrative beat at a time.
- **Responsibility:** On mobile, margins shrink to 20px, and the 12-column layout reflows into a single-column stack. Photography should maintain a 4:5 or 1:1 aspect ratio on mobile to occupy significant screen real estate.

## Elevation & Depth

To maintain a minimalist and premium feel, this system avoids traditional drop shadows. Instead, it uses **Tonal Layers** and **Subtle Outlines**:

- **Layering:** Surfaces are separated by slight shifts in darkness (e.g., a charcoal card on a black background).
- **Outlines:** Ghost borders (1px width, 10% opacity white) define product cards and interactive inputs. 
- **Image Depth:** Depth is primarily conveyed through professional food photography with shallow depth-of-field, making the product appear "tangible" and close to the user.

## Shapes

The design system utilizes **Sharp (0px)** corners for all primary containers, buttons, and images. 

This decision reinforces the "Architectural" and "Precise" nature of the brand. Sharp edges evoke the precision of a chef's knife and the structured nature of a premium heritage brand. Curved elements are only permitted in the brand logo itself, allowing the brand mark to stand out as a unique organic element against a rigid, professional grid.

## Components

### Buttons
- **Primary:** Sharp-edged, solid Burgundy background with White text. Hover state shifts to a slightly brighter red or gold border.
- **Secondary:** Transparent background with a 1px Gold or White border. Text in caps for a technical look.

### Product Cards
- Cards feature full-bleed imagery on the top 70%, with a charcoal-light container below. 
- Typography is center-aligned for an "Award" or "Certificate" feel.
- Pricing and weight are displayed in the `label-caps` style.

### Input Fields
- Underline-only style or very low-contrast charcoal boxes.
- Focus state is indicated by a Primary Burgundy bottom border.

### Hero Sections
- Full-height (100vh) sections with centered `display-lg` typography.
- Backgrounds are either high-contrast photography or pure `#0A0A0A` with a gold accent line.

### Lists & Mission
- For history or values, use "The Timeline" or "The Grid"—alternating text and image blocks with significant whitespace to simulate a high-end coffee table book.