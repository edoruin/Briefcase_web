---
name: Ivory & Ink
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbdad9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#e9e8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#51443d'
  inverse-surface: '#303031'
  inverse-on-surface: '#f2f0f0'
  outline: '#83746c'
  outline-variant: '#d5c3ba'
  surface-tint: '#80543a'
  primary: '#70472d'
  on-primary: '#ffffff'
  primary-container: '#8c5e43'
  on-primary-container: '#ffe4d6'
  inverse-primary: '#f4ba99'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#52514d'
  on-tertiary: '#ffffff'
  tertiary-container: '#6a6965'
  on-tertiary-container: '#ece9e4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc9'
  primary-fixed-dim: '#f4ba99'
  on-primary-fixed: '#311301'
  on-primary-fixed-variant: '#653d24'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e5e2dd'
  tertiary-fixed-dim: '#c9c6c2'
  on-tertiary-fixed: '#1c1c19'
  on-tertiary-fixed-variant: '#474743'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 64px
    fontWeight: '400'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system is built for "Briefcase" piano lessons, an educational platform that bridges the gap between professional discipline and artistic soul. The brand personality is **sophisticated, academic, yet deeply expressive**. It targets discerning learners who view piano not just as a hobby, but as a craft.

The visual style is **Artistic Minimalism**. It draws inspiration from the high-contrast keys of a piano and the tactile, painterly quality of the reference image. The interface uses expansive whitespace to represent the "silence between notes," punctuated by bold, editorial typography and organic textures. The result is a premium, gallery-like experience that evokes a sense of calm focus and creative prestige.

## Colors

The palette is derived directly from the oil-painting aesthetics of the piano and hands in the reference image.

- **Primary (Accent):** A rich, warm umber (#8C5E43) taken from the skin tones and wood textures. This is used sparingly for primary CTAs and critical highlights.
- **Secondary (Obsidian):** A deep, near-black (#1A1A1A) representing the black keys and ink. It provides the foundation for text and structural elements.
- **Tertiary (Paper):** A soft, warm off-white (#F5F2ED) that serves as the primary background color, providing a more premium, "aged parchment" feel than pure white.
- **Neutral (Slate):** A muted grey for secondary text and borders, maintaining a monochromatic elegance without the harshness of pure black-on-white.

The default mode is **Light**, emphasizing the "sheet music" metaphor, though a dark mode variant would invert these to represent a concert hall stage.

## Typography

The typography system relies on the tension between the classic **Libre Caslon Text** and the modern **Manrope**. 

**Libre Caslon Text** is used for all headlines and display text. It should be set with slightly tighter letter-spacing for large sizes to maintain an editorial, "sheet music title" look. 

**Manrope** provides a functional, balanced counterpoint for body copy and UI labels. It ensures legibility during technical lessons while maintaining a contemporary edge. For instructional labels and navigation, use Manrope in Uppercase with expanded letter-spacing to create a "briefcase" organizational feel.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** on desktop to maintain the integrity of a premium, curated publication. On mobile, it transitions to a fluid model with generous margins.

- **Grid:** A 12-column grid is used for desktop (1280px max-width). Elements should favor asymmetrical placements to mimic the movement of hands across keys.
- **Rhythm:** An 8px linear scale is utilized. However, for "Artistic Minimalism," double the standard padding between sections (using 128px or 160px) to allow content to breathe.
- **Breakpoints:**
  - **Mobile (<768px):** 4 columns, 16px margins, fluid gutters.
  - **Tablet (768px - 1024px):** 8 columns, 32px margins, 24px gutters.
  - **Desktop (>1024px):** 12 columns, 64px+ margins, fixed 24px gutters.

## Elevation & Depth

This design system rejects heavy shadows in favor of **Tonal Layers** and **Ghost Outlines**. Depth is communicated through stacking and subtle contrast rather than physical simulation.

1.  **Surfaces:** The primary background is the Tertiary color. Secondary surfaces (cards, sidebars) use a slightly lighter or darker tint of Neutral with 0.5px borders.
2.  **Outlines:** Use "Ghost Borders"—low-opacity (10-15%) secondary color strokes—to define interactive areas without cluttering the visual field.
3.  **Depth:** In rare cases where elevation is required (e.g., modals), use a very large, soft umber-tinted shadow (32px blur, 4% opacity) to suggest the element is floating just above the "paper" surface.

## Shapes

The shape language is primarily **Soft (0.25rem)**. While a piano has sharp edges, the experience of playing is tactile and human. 

- **Elements:** Standard buttons and input fields use a subtle 4px radius. 
- **Large Containers:** Cards or featured sections may use a slightly larger 8px (rounded-lg) radius to feel more approachable.
- **Imagery:** High-quality photography and video should maintain sharp 0px corners or very large, dramatic 24px corners to look like framed art.

## Components

- **Buttons:** Primary CTAs use the Primary Umber background with white Manrope text (Bold). Secondary buttons are Ghost style: Transparent background, 1px Obsidian border, Obsidian text.
- **Input Fields:** Bottom-border only (minimalist style) or full 1px light neutral border. Label text should always be Manrope Uppercase, positioned above the field.
- **Cards:** No shadows. Use a subtle fill color change (e.g., a 2% darken of the Tertiary background) and a 1px hair-line border.
- **Chips/Badges:** Small, Manrope Bold, with high letter-spacing. Used for "Lesson Level" (e.g., ADVANCED, BEGINNER).
- **Progress Indicators:** Thin, 2px lines. Use the Primary Umber for the active state to represent the "timeline" of a musical piece.
- **Lists:** Clean, separated by hair-line horizontal rules. Icons should be thin-stroke (1px) to match the refined typography.