---
name: Serene Healthcare System
colors:
  surface: '#f8f9fa'
  surface-dim: '#d8dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f5'
  surface-container: '#eceeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#41484c'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#eff1f2'
  outline: '#71787c'
  outline-variant: '#c0c7cc'
  surface-tint: '#326479'
  primary: '#2f6277'
  on-primary: '#ffffff'
  primary-container: '#4a7b90'
  on-primary-container: '#fbfdff'
  inverse-primary: '#9ccee5'
  secondary: '#49645a'
  on-secondary: '#ffffff'
  secondary-container: '#c8e6d9'
  on-secondary-container: '#4d685e'
  tertiary: '#5b5c5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#747573'
  on-tertiary-container: '#fdfcfa'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bde9ff'
  primary-fixed-dim: '#9ccee5'
  on-primary-fixed: '#001f2a'
  on-primary-fixed-variant: '#154c60'
  secondary-fixed: '#cbe9dc'
  secondary-fixed-dim: '#afcdc0'
  on-secondary-fixed: '#042018'
  on-secondary-fixed-variant: '#314c42'
  tertiary-fixed: '#e3e2e0'
  tertiary-fixed-dim: '#c7c6c5'
  on-tertiary-fixed: '#1a1c1b'
  on-tertiary-fixed-variant: '#464746'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Atkinson Hyperlegible Next
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is built on a foundation of "Restorative Modernism." The brand personality is empathetic, professional, and clinical yet warm, moving away from the cold sterility of traditional medical environments toward a sense of holistic well-being.

The target audience includes patients seeking clarity and reassurance, as well as practitioners who require high-performance tools that don't contribute to cognitive fatigue. The visual style utilizes **Minimalism** enriched with **Tonal Layering**. It prioritizes heavy whitespace to reduce visual noise, creating an atmosphere of quiet competence. The emotional response is one of immediate calm—a "digital deep breath"—achieved through soft geometry and a palette that mirrors natural elements like water, stone, and flora.

## Colors

The color palette is inspired by natural serenity. 

*   **Primary (Soft Blue):** Used for primary actions, navigation indicators, and branding. It evokes stability and clinical trust.
*   **Secondary (Sage Green):** Applied to success states, health-related indicators, and secondary supportive elements. It suggests growth and healing.
*   **Tertiary (Warm White):** This is the foundation of the interface. It replaces pure #FFFFFF to reduce eye strain and provide a softer, more inviting surface.
*   **Neutral (Slate Gray):** Reserved for text and borders to ensure high legibility without the harshness of pure black.

Functional colors (Warning, Error) should be desaturated to fit the aesthetic: a soft terracotta for errors and a muted ochre for warnings.

## Typography

Typography is the primary vehicle for trust. This design system utilizes a dual-font strategy:

1.  **Manrope** for headlines: Its modern, geometric construction provides a precise, professional structure that feels contemporary.
2.  **Atkinson Hyperlegible Next** for body and labels: Selected specifically for the healthcare context to maximize readability for patients with varying visual abilities. 

Headlines use a slight negative letter-spacing to appear more cohesive, while labels use positive letter-spacing to ensure clarity at small scales. All text should maintain a minimum contrast ratio of 4.5:1 against their backgrounds.

## Layout & Spacing

The design system employs a **12-column fixed grid** for desktop (max-width 1440px) and a **4-column fluid grid** for mobile. 

A strict 8px spatial rhythm is used to define all margins and padding. Layouts should lean toward "generous" spacing; when in doubt, increase padding to prevent the interface from feeling cluttered or stressful. 

**Breakpoints:**
*   **Mobile:** 0 - 599px (16px margins, 16px gutter)
*   **Tablet:** 600 - 1023px (32px margins, 24px gutter)
*   **Desktop:** 1024px+ (64px margins, 24px gutter)

Content should be grouped into logical "clusters" using white space rather than lines wherever possible to maintain the serene aesthetic.

## Elevation & Depth

Depth in this design system is handled through **Ambient Shadows** and **Tonal Layers**. We avoid high-contrast shadows to prevent visual "weight."

*   **Surface Level (0dp):** The Tertiary Warm White color.
*   **Floating Level (Low):** Used for cards and secondary navigation. Features a soft, diffused shadow: `0px 4px 20px rgba(90, 139, 161, 0.08)`. Note the subtle blue tint in the shadow to maintain color harmony.
*   **Overlay Level (High):** Used for modals and critical alerts. Features a wider spread: `0px 12px 40px rgba(90, 139, 161, 0.12)`.

Separation is often achieved through subtle shifts in background color (e.g., a slightly darker "Stone" tint) rather than borders, maintaining a soft, seamless feel.

## Shapes

The shape language is defined by **rounded, organic geometry**. Sharp corners are eliminated to remove "visual aggression." 

*   **Standard Elements:** Buttons, inputs, and small widgets use a 0.5rem (8px) radius.
*   **Containers:** Cards and content sections use a 1rem (16px) radius.
*   **Feature Elements:** Hero sections or large banners use a 1.5rem (24px) radius.

This consistency in rounding reinforces the approachable and safe nature of the healthcare provider.

## Components

*   **Buttons:** Primary buttons use a solid Soft Blue background with white text. Secondary buttons use a ghost style with a 1px Sage Green border. Interactive states should involve a gentle shift in saturation rather than brightness.
*   **Chips:** Used for medical tags or status (e.g., "Available"). These should be pill-shaped with a light Sage Green tint and dark text.
*   **Input Fields:** Use a subtle Slate Gray border (20% opacity) that shifts to Primary Blue on focus. Labels always sit above the field for maximum accessibility.
*   **Cards:** Elevated with the "Low" ambient shadow. They should feature generous internal padding (24px) and no borders.
*   **Progress Indicators:** For appointment bookings or health tracking, use soft, rounded progress bars in Sage Green to denote positive movement.
*   **Lists:** Avoid horizontal dividers. Use 16px of vertical spacing between list items to create natural separation.
*   **Appointment Cards:** A specialized component featuring a Primary Blue time-stamp badge and a secondary action for "Reschedule" using the ghost button style.