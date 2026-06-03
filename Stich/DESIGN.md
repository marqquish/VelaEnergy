---
name: Industrial Innovation
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
  on-surface-variant: '#44474d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#75777e'
  outline-variant: '#c5c6cd'
  surface-tint: '#515f78'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0d1c32'
  on-primary-container: '#76849f'
  inverse-primary: '#b9c7e4'
  secondary: '#006e16'
  on-secondary: '#ffffff'
  secondary-container: '#00f93f'
  on-secondary-container: '#006d16'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#002022'
  on-tertiary-container: '#00929b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b9c7e4'
  on-primary-fixed: '#0d1c32'
  on-primary-fixed-variant: '#39475f'
  secondary-fixed: '#72ff70'
  secondary-fixed-dim: '#00e639'
  on-secondary-fixed: '#002203'
  on-secondary-fixed-variant: '#00530e'
  tertiary-fixed: '#7df4ff'
  tertiary-fixed-dim: '#00dbe9'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  deep-navy: '#0A192F'
  electric-green: '#00FF41'
  circuit-cyan: '#00F0FF'
  slate-gray: '#E9ECEF'
  off-white: '#F8F9FA'
typography:
  display-lg:
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
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system embodies a "High-Tech Industrial" aesthetic, positioning the product as a leader in electrical engineering. It balances the rugged, reliable nature of electrical services with a cutting-edge, tech-forward interface. 

The brand personality is **expert, precise, and energetic**. It moves away from the traditional, static feel of utility services toward a dynamic "Energy-as-a-Service" model. 

The visual style is **Corporate / Modern** with a lean toward **Minimalism**, characterized by:
- **Clean Industrialism:** High whitespace and structured grids that suggest architectural blueprints and circuit precision.
- **Vibrant Accents:** Utilizing high-frequency colors to represent electricity and movement.
- **Professional Transparency:** Clear hierarchy and open layouts that build trust through technical clarity.

## Colors

The palette is anchored by **Deep Navy (#0A192F)**, providing a foundation of stability and professional authority. This is contrasted by **Electric Green (#00FF41)**, used strategically for primary actions and "live" status indicators to mimic electrical current and energy.

**Circuit Cyan (#00F0FF)** serves as a tertiary accent for data visualization, technical details, and secondary highlights, reinforcing the high-tech narrative. The neutral scale relies on **Off-White (#F8F9FA)** for backgrounds and **Slate Gray (#E9ECEF)** for subtle borders and structural dividers, ensuring the interface feels airy and modern rather than cluttered and industrial.

## Typography

This design system uses a dual-font strategy to maximize contrast and legibility. **Montserrat** is utilized for headlines, using its geometric structure to convey confidence and modernity. Headlines should always use high-contrast weights (SemiBold to Bold) to establish a clear information hierarchy.

**Inter** is the workhorse for body text and labels. Its high x-height and neutral tone ensure technical specifications and long-form service descriptions remain highly readable. Labels and small metadata should utilize uppercase styling with increased letter spacing to evoke a technical, "schematic" feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain a controlled, professional presentation of technical data. A 12-column system is used with 24px gutters.

- **Desktop (1024px+):** 12 columns, 64px side margins.
- **Tablet (768px - 1023px):** 8 columns, 32px side margins.
- **Mobile (Up to 767px):** 4 columns, 20px side margins.

Spacing follows an 8px linear scale. Generous vertical padding (80px - 120px) between sections is encouraged to prevent the "industrial" content from feeling heavy, allowing the "clean and innovative" brand pillars to shine.

## Elevation & Depth

Hierarchy is established through **Tonal Layers** and **Ambient Shadows**. 

- **Level 0 (Background):** Solid `off-white` (#F8F9FA).
- **Level 1 (Cards/Surfaces):** White background with a very soft, diffused shadow (0px 4px 20px rgba(10, 25, 47, 0.05)). This shadow uses a `deep-navy` tint rather than pure black to maintain color harmony.
- **Level 2 (Interactive/Floating):** Higher elevation shadow (0px 12px 32px rgba(10, 25, 47, 0.12)) used for active states or hover effects on cards.

Low-contrast outlines in `slate-gray` are used for input fields and static containers to define boundaries without adding visual weight.

## Shapes

The shape language is **Rounded (0.5rem base)**. This softens the industrial tone, making the expert services feel accessible and customer-friendly.

- **Small Components (Buttons, Inputs):** 8px (0.5rem) radius.
- **Medium Components (Cards, Modals):** 16px (1rem) radius.
- **Large Components (Hero sections, Containers):** 24px (1.5rem) radius.

Icons should follow a consistent "Linear" style with slightly rounded terminals to match the UI's geometry.

## Components

### Buttons
- **Primary:** Deep Navy background, White text. High-contrast hover state using Electric Green.
- **Secondary:** Transparent background, Deep Navy 2px border. 
- **CTA/Urgent:** Electric Green background, Deep Navy text. Reserved for "Urgencies" and "Call Now."

### Cards
Cards are the primary container. They feature a white background, 16px corner radius, and Level 1 elevation. For technical services, cards should include a small icon in Circuit Cyan and a bold Montserrat headline.

### Input Fields
Standardized with an 8px radius and a 1px `slate-gray` border. On focus, the border transitions to `deep-navy` with a subtle `circuit-cyan` outer glow.

### Chips & Status Indicators
Small, pill-shaped elements. Use `electric-green` for "Online" or "Available" statuses and `deep-navy` for category labels.

### Lists
Use custom iconography (e.g., stylized checkmarks or circuit nodes) instead of standard bullets to reinforce the engineering theme. Vertical spacing between list items should be a minimum of 12px.