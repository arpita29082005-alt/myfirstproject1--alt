---
name: Royal Institutional Fintech
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#444650'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#757682'
  outline-variant: '#c5c6d2'
  surface-tint: '#435b9f'
  primary: '#00113a'
  on-primary: '#ffffff'
  primary-container: '#002366'
  on-primary-container: '#758dd5'
  inverse-primary: '#b3c5ff'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#2d0700'
  on-tertiary: '#ffffff'
  tertiary-container: '#501300'
  on-tertiary-container: '#d37758'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b3c5ff'
  on-primary-fixed: '#00174a'
  on-primary-fixed-variant: '#2a4386'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdbd0'
  tertiary-fixed-dim: '#ffb59e'
  on-tertiary-fixed: '#390b00'
  on-tertiary-fixed-variant: '#783018'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  deep-navy-dark: '#001845'
  gold-leaf-light: '#E5C76B'
  slate-gray: '#4A5568'
  success-emerald: '#2D6A4F'
  error-crimson: '#A4161A'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 60px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system is engineered for a high-end loan consultancy, prioritizing an atmosphere of absolute trust, elite service, and modern efficiency. The aesthetic is rooted in **Corporate Modernism** with a focus on precision and high-contrast clarity.

The target audience consists of high-net-worth individuals and business entities seeking reliable financial guidance. To resonate with this demographic, the UI utilizes expansive whitespace to suggest "breathing room" and luxury, paired with sharp, intentional accents. The visual language avoids decorative clutter, ensuring that data and financial terms are the focal point, presented through a lens of sophisticated authority.

## Colors

The palette is anchored by **Deep Navy Blue**, a color synonymous with stability and institutional strength. This serves as the primary driver for navigation, headers, and primary text. **Sophisticated Gold** is used strictly as a high-intent accent—reserved for primary Call-to-Action (CTA) elements, success indicators, and premium tier highlighting. 

The background strategy relies on a "Clean White" base with subtle "Slate Gray" and "Neutral" off-whites to differentiate content sections without breaking the flow of the page. High-contrast ratios are maintained throughout to ensure professional-grade accessibility and legibility.

## Typography

The typographic hierarchy uses **Montserrat** for all headlines to provide a sharp, geometric, and modern architectural feel. Headlines should use tighter letter-spacing and heavier weights to command attention.

**Inter** is utilized for body copy and UI labels, chosen for its exceptional legibility in data-heavy environments. To maintain a premium editorial feel, body text is generously spaced (1.5x line height). Labels and small metadata should occasionally utilize uppercase styling with increased letter-spacing to mimic traditional financial reporting aesthetics.

## Layout & Spacing

The design system employs a **Fixed Grid** layout for desktop (12 columns) to project a sense of organized structure and reliability. On mobile devices, the layout transitions to a fluid single-column system with 20px side margins.

A strict 8px base unit (the "spacing scale") governs all padding and margins. Vertical rhythm is emphasized through large "hero" sections and generous padding between content blocks (typically 80px or 120px on desktop) to prevent the interface from feeling crowded, reinforcing the premium brand positioning.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layering** and highly diffused, low-opacity shadows. Surfaces are kept predominantly flat to maintain a modern look, but key interactive elements like "Loan Calculator Cards" or "Application Forms" utilize a "Level 2" shadow (0px 10px 30px rgba(0, 35, 102, 0.08)) to create a subtle lift.

The design avoids heavy borders. Instead, depth is communicated through slight background color shifts (e.g., a Navy header on a White background) or very thin 1px dividers in a faint gray. Interactive states should feel tactile but restrained; a button hover might involve a slight color deepen rather than a dramatic movement.

## Shapes

The shape language is **Soft (0.25rem)**. This "near-sharp" approach maintains a professional, institutional edge while feeling contemporary. 

Buttons, input fields, and cards all share this consistent corner radius. Large-scale containers or images may occasionally use a larger radius (0.5rem) to soften the overall composition, but the primary UI components must remain disciplined and crisp to reflect the precision of financial consultancy.

## Components

### Buttons
- **Primary:** Gold background (#D4AF37) with Navy text. This is reserved for high-value actions like "Apply Now."
- **Secondary:** Transparent with a Navy border and Navy text. Used for "Learn More" or "View Rates."
- **Tertiary:** Navy background with White text for navigation or utility actions.

### Input Fields
Inputs feature a 1px border in a mid-gray, which transitions to Navy on focus. Labels sit clearly above the field in the `label-sm` style. Error states are indicated by a 2px Crimson border and a small supporting text below the field.

### Cards
Cards are the primary container for information. They feature a White background, the standard soft corner radius, and a very light Navy shadow. For "Featured" loan products, a 4px Gold top-border can be added to denote premium status.

### Progress Indicators
For loan application flows, use a clean, horizontal step-indicator using Navy for completed steps and Gold for the active state, ensuring the user always feels guided and informed.