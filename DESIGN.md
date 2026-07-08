---
name: Cyber-Fidelity Portfolio
colors:
  surface: '#11131b'
  surface-dim: '#11131b'
  surface-bright: '#373942'
  surface-container-lowest: '#0c0e16'
  surface-container-low: '#191b24'
  surface-container: '#1d1f28'
  surface-container-high: '#282a32'
  surface-container-highest: '#32343e'
  on-surface: '#e1e1ee'
  on-surface-variant: '#c3c5d8'
  inverse-surface: '#e1e1ee'
  inverse-on-surface: '#2e3039'
  outline: '#8d90a1'
  outline-variant: '#434655'
  surface-tint: '#b4c5ff'
  primary: '#b4c5ff'
  on-primary: '#00297a'
  primary-container: '#135bec'
  on-primary-container: '#e2e6ff'
  inverse-primary: '#0052de'
  secondary: '#5de6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe6'
  on-secondary-container: '#00515d'
  tertiary: '#ddb8ff'
  on-tertiary: '#490080'
  tertiary-container: '#902fe7'
  on-tertiary-container: '#f3e1ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174c'
  on-primary-fixed-variant: '#003daa'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#f0dbff'
  tertiary-fixed-dim: '#ddb8ff'
  on-tertiary-fixed: '#2c0051'
  on-tertiary-fixed-variant: '#6800b4'
  background: '#11131b'
  on-background: '#e1e1ee'
  surface-variant: '#32343e'
  background-dark: '#111318'
  card-dark: '#1a1d26'
  border-dark: '#282e39'
  surface-alt: '#0f1116'
  text-slate-100: '#f1f5f9'
  text-slate-400: '#94a3b8'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 96px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1200px
  section-padding: 5rem
  gutter-md: 1.5rem
  stack-gap: 1rem
  inner-padding: 1.25rem
---

## Brand & Style
The brand personality is **technical, futuristic, and high-performance**. It targets the developer and AI/ML space with a "Dark Mode First" philosophy. 

The visual style is a hybrid of **Glassmorphism** and **Corporate Modern**. It utilizes vibrant neon accents (cyan, purple, blue) against deep, desaturated backgrounds to create a sense of depth and innovation. The interface evokes a "command center" feel while maintaining the professional polish required for an engineering portfolio. High-fidelity gradients and backdrop blurs are used to soften the technical edge, making the UI feel premium and approachable rather than purely utilitarian.

## Colors
The palette is rooted in a **Dark Grey/Black** foundation. The primary brand color is a high-fidelity **Royal Blue** (#135bec), used for primary actions and core branding elements.

**Accent Gradients** are critical to this system, specifically a three-stop linear gradient: `Cyan-400 (#22d3ee)` to `Blue-500 (#3b82f6)` to `Purple-600 (#9333ea)`. This is used for "Display" typography and high-impact visual containers. 

**Surface logic** follows a stepped-up brightness model:
- **Base Background:** #111318
- **Elevated Surfaces (Cards):** #1a1d26
- **Borders:** #282e39
- **Tonal Accents:** Use 10-20% opacity of the primary blue for hover states and chip backgrounds.

## Typography
The system exclusively uses **Space Grotesk**, a geometric sans-serif with a technical, idiosyncratic personality that fits the "futuristic" brand theme.

- **Scale:** Large display sizes (above 48px) should use tighter letter spacing and gradients for a dramatic effect.
- **Hierarchy:** Use font weight (Bold/700) and color (White vs Slate-400) rather than just size to distinguish between headers and metadata.
- **Monospace Influence:** While not a true monospace, Space Grotesk’s tabular qualities are leaned into for labels and tech-stack listings.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy centered within a 1200px container for desktop. 

- **Vertical Rhythm:** Large sections are separated by significant whitespace (80px to 100px) to allow the "glowing" background effects to breathe.
- **Grid System:** Card layouts transition from a 4-column (Desktop) to 2-column (Tablet) to 1-column (Mobile) grid. 
- **Content Density:** Elements within cards use a standard 20px padding. Grouped elements (like icons + text) use a consistent 16px (1rem) gap.

## Elevation & Depth
Depth is created through **Luminance and Blurs** rather than traditional drop shadows.

1.  **Background Blurs:** Navigation bars and hero sections use `backdrop-blur-md` (approx 12px) with a semi-transparent background (#111318/90).
2.  **Glow Accents:** Use large, low-opacity (20%) radial gradients in the background to simulate "light leakage" from behind the UI.
3.  **Tonal Borders:** Borders are not just grey; they are desaturated blue-greys (#282e39) that respond to interaction. On hover, borders should transition to a primary color glow (e.g., `border-primary/50`).
4.  **Shadows:** When used, shadows are "Ambient Primary" — shadows that take on a tint of the primary color with a high blur radius and very low opacity (e.g., `shadow-primary/25`).

## Shapes
The shape language is **Medium-Rounded**, striking a balance between friendly and professional.

- **Standard Elements:** Buttons and small cards use a 0.5rem (8px) radius.
- **Large Containers:** Project cards and educational blocks use 1rem to 1.5rem (16px-24px) for a softer, more modern feel.
- **Pill Shapes:** Status indicators (e.g., "Open to Work") and technology tags use a full pill radius to contrast against the rectangular grid.
- **Images:** Hero imagery should be contained within circles or large 1rem rounded rectangles.

## Components
- **Buttons:**
    - **Primary:** Solid background (#135bec), white text, 8px radius. Includes a subtle shadow tinted with the primary color.
    - **Secondary/Outline:** Border #282e39, background #1a1d26. Ghost borders that lighten on hover.
- **Cards:**
    - Dark background (#1a1d26), 1px solid border (#282e39). Hover state increases border opacity or color to #135bec/50.
- **Status Badges:** 
    - Small, pill-shaped, using 10% opacity of the status color for the background and 100% opacity for the text/icon (e.g., Green for online, Blue for open).
- **Icon Containers:**
    - 48px x 48px square with 8px radius. Use 10% opacity of the icon color for the background to create a "glowing" tile effect.
- **Form Inputs:**
    - Dark-filled backgrounds, 1px borders, and focus states that utilize the primary blue glow.