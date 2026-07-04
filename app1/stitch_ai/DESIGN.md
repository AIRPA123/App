---
name: StyleMe AI
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
  on-surface-variant: '#464554'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#767586'
  outline-variant: '#c7c4d7'
  surface-tint: '#494bd6'
  primary: '#4648d4'
  on-primary: '#ffffff'
  primary-container: '#6063ee'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0c1ff'
  secondary: '#575e70'
  on-secondary: '#ffffff'
  secondary-container: '#d9dff5'
  on-secondary-container: '#5c6274'
  tertiary: '#4f5d70'
  on-tertiary: '#ffffff'
  tertiary-container: '#677689'
  on-tertiary-container: '#fdfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#dce2f7'
  secondary-fixed-dim: '#c0c6db'
  on-secondary-fixed: '#141b2b'
  on-secondary-fixed-variant: '#404758'
  tertiary-fixed: '#d4e4fa'
  tertiary-fixed-dim: '#b9c8de'
  on-tertiary-fixed: '#0d1c2d'
  on-tertiary-fixed-variant: '#39485a'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
---

## Brand & Style

The design system is built for a premium AI-driven fashion concierge. The brand personality is "The Future of Personal Styling"—balancing the precision of high-tech algorithms with the editorial elegance of a luxury fashion magazine. It is professional, trend-conscious, and authoritative.

The visual style follows a **Modern Corporate/Editorial Hybrid**. It utilizes generous whitespace, crisp typography, and high-quality photography to evoke a sense of clarity and sophistication. The interface should feel like a high-end digital atelier: minimal enough to let the user's photos and fashion choices remain the focus, but sharp enough to feel technologically advanced. Interaction is characterized by smooth transitions and a disciplined use of accent colors.

## Colors

The palette is rooted in sophisticated neutrals to provide a high-contrast canvas for fashion photography. 

- **Primary (Electric Indigo):** Used exclusively for high-intent interactive elements, primary buttons, and AI-active states.
- **Secondary (Charcoal):** Used for primary text and structural grounding.
- **Neutral (Soft Grey / Off-White):** Used for backgrounds and surface-on-surface separation to prevent visual fatigue.
- **Success/Warning:** Use muted versions of green and amber, tinted with neutral tones to maintain the sophisticated aesthetic.

Avoid using gradients unless they are used as subtle overlays on imagery to ensure text legibility.

## Typography

The design system utilizes **Inter** exclusively to achieve a clean, systematic, and utilitarian look that resonates with tech-forward services. 

- **Headlines:** Use tight letter-spacing and semi-bold weights to create a strong visual hierarchy.
- **Body:** Standard weight with generous line height for readability, especially during the onboarding and data-input phases.
- **Labels:** Use medium weights and slight tracking for uppercase labels to distinguish them from body copy.
- **Scaling:** On mobile, display sizes should scale down by 15-20% to maintain balance while preserving the bold, editorial feel.

## Layout & Spacing

This design system uses a **Fluid Grid** model with a base-4 spacing scale to ensure mathematical harmony.

- **Desktop:** 12-column grid with 24px gutters. Use large margins (40px+) to create an "editorial" feel with plenty of whitespace.
- **Mobile:** 4-column grid with 16px margins.
- **Alignment:** Content should generally be center-aligned in the container for landing pages, but left-aligned for data-heavy dashboard views. 
- **Rhythm:** Use `xl` (40px) spacing between major sections and `md` (16px) for internal component spacing.

## Elevation & Depth

To maintain a modern, flat-yet-layered look, this design system relies on **Tonal Layers** and **Soft Ambient Shadows**.

- **Surfaces:** Use `#FFFFFF` for the base background and `#F9FAFB` (Neutral) for secondary containers or cards.
- **Shadows:** Use extremely soft, low-opacity shadows (e.g., `y: 4, blur: 20, color: rgba(0,0,0,0.04)`) to lift cards off the background without creating a "heavy" look.
- **Interactive Depth:** When a user interacts with a card or button, use a subtle scale-down (0.98) or a slight increase in shadow depth to provide tactile feedback.
- **Dividers:** Use thin (1px), low-contrast lines in `#E5E7EB` for structural separation where shadows feel too heavy.

## Shapes

The shape language is **Rounded**, striking a balance between friendly accessibility and professional structure.

- **Standard Elements:** Buttons and input fields use a 0.5rem (8px) radius.
- **Large Elements:** Cards and image containers use 1rem (16px) to create a softer, more modern framing for fashion photography.
- **Exceptions:** Use fully rounded (pill-shaped) radii for status chips or tags to differentiate them from interactive buttons.

## Components

- **Buttons:** Primary buttons use the "Electric Indigo" background with white text. Secondary buttons use a ghost style with a Charcoal border.
- **Input Fields:** Use a subtle grey background (`#F3F4F6`) with no border in its default state, moving to a 2px Primary border on focus. Labels should sit clearly above the field.
- **Cards:** Fashion items and outfit suggestions should be presented in cards with a 16px radius and a subtle shadow. The image should be the dominant element, with a small 16px padding area for the title and price.
- **Chips:** Small, pill-shaped markers for sizes, colors, or styles. Use a light grey background with charcoal text for unselected states.
- **Progress Steppers:** For the data-input flow (height/weight/photo), use a minimal linear progress bar at the top of the screen in Primary Indigo.
- **Image Uploaders:** A large, dashed-border container with a clear icon and "Upload Photo" label to encourage user action.