---
name: Pro Pad Music Identity
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#ffb77d'
  on-secondary: '#4d2600'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#d0cecd'
  on-tertiary: '#313030'
  tertiary-container: '#b5b2b2'
  on-tertiary-container: '#454545'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  headline-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 24px
  gutter: 16px
  section-gap: 80px
---

## Brand & Style

The design system is built on a "Premium Modernist" aesthetic that bridges the gap between traditional Indian excellence and international professional standards. The visual narrative centers on a high-end, dark-mode experience that evokes the atmosphere of a professional recording studio or a prestigious concert hall.

The interface utilizes a mix of **Minimalism** and **Glassmorphism**. Deep charcoal surfaces provide a sophisticated stage for elegant gold accents and warm orange highlights. High-fidelity visual hierarchy is achieved through meticulous spacing and subtle depth, ensuring the platform feels trustworthy for parents investing in their children's future, while remaining vibrant and "cool" for aspiring young musicians.

## Colors

This design system utilizes a sophisticated dark palette designed to make gold and orange elements "pop" with a premium glow.

*   **Primary (Gold):** `#D4AF37`. Used for high-level branding, achievement icons, and premium call-to-actions. It represents prestige and the "gold standard" of musical education.
*   **Secondary (Warm Orange):** `#FF8C00`. Used for interactive elements, progress indicators, and active states. It provides energy and warmth, reflecting the passion of music.
*   **Surface (Charcoal/Black):** The background is a deep `#0A0A0A`, while containers use `#121212` and `#1C1C1C` to create subtle layered depth.
*   **Accents:** Success states use a muted forest green; error states use a deep terracotta to maintain the warm, earthy aesthetic.

## Typography

The typography strategy pairs the geometric confidence of **Montserrat** for headings with the contemporary precision of **Hanken Grotesk** for body and UI text. 

Headings should be treated with tight letter-spacing to feel impactful and modern. For editorial sections or "Pro" features, use the `label-md` style with increased tracking to evoke a high-fashion or premium magazine feel. On mobile devices, ensure top-level headlines scale down to prevent awkward word breaks while maintaining their bold weight.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (12 columns, 1200px max-width) to maintain a controlled, high-end look, transitioning to a fluid layout on mobile.

*   **Rhythm:** A 8px base unit governs all dimensions.
*   **Margins:** Use generous white space (or "dark space") between sections (80px+) to allow the content to breathe, emphasizing a premium feel.
*   **Adaptive Behavior:** On tablets, the 12-column grid collapses to 8 columns with 20px gutters. On mobile, a 4-column grid with 16px margins is standard. 
*   **Verticality:** Emphasize vertical hierarchy; prioritize large imagery of instruments or performers, followed by bold typography and then interactive controls.

## Elevation & Depth

Depth is created through **Tonal Layering** and **Ambient Shadows** rather than harsh outlines.

1.  **Base Layer:** `#0A0A0A` (The deep stage).
2.  **Surface Layer:** `#121212` with a 1px border of `#FFFFFF` at 5% opacity.
3.  **Raised Layer:** `#1C1C1C` with a soft, diffused shadow: `0px 12px 32px rgba(0, 0, 0, 0.5)`.

For high-end interactions, use a **Glassmorphism** effect: a backdrop blur of 12px with a 10% translucent gold or white fill. This is particularly effective for navigation bars and floating music player controls.

## Shapes

The shape language is sophisticated and "Rounded" (Level 2). This softens the technical nature of music production and makes the interface more approachable for parents and younger students.

*   **Cards & Modals:** Use `rounded-lg` (1rem/16px) for a modern, friendly structure.
*   **Buttons:** Standard buttons use `rounded-md` (0.5rem/8px), while "Join Class" or "Enrol" buttons should be full-pill (`rounded-xl`) to draw attention.
*   **Inputs:** Use `rounded-md` to maintain consistency with buttons.

## Components

*   **Buttons:** Primary buttons feature a subtle gold gradient (`#D4AF37` to `#B8860B`) with black text. Secondary buttons are charcoal with gold borders.
*   **Cards:** Music course cards should feature a large image ratio (16:9) with a soft gradient overlay at the bottom to ensure text legibility.
*   **Input Fields:** Deep charcoal background with a 1px gold bottom-border that glows (box-shadow) when focused.
*   **Chips:** Used for "Instrument Categories" (e.g., Tabla, Guitar, Piano). Use a subtle orange outline that fills on selection.
*   **Progress Bars:** Instrumental practice trackers should use the warm orange (`#FF8C00`) against a dark track, featuring a slight outer glow to simulate a "live" LED.
*   **Lists:** Course curricula should be displayed in a clean list with gold bullet points or icon indicators (e.g., musical notes).