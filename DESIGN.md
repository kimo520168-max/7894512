---
name: 禾山黑烏龍 (He Shan Udon)
colors:
  surface: '#fcf9f0'
  surface-dim: '#dddad1'
  surface-bright: '#fcf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ea'
  surface-container: '#f1eee5'
  surface-container-high: '#ebe8df'
  surface-container-highest: '#e5e2da'
  on-surface: '#1c1c17'
  on-surface-variant: '#58413f'
  inverse-surface: '#31312b'
  inverse-on-surface: '#f4f1e8'
  outline: '#8c716e'
  outline-variant: '#e0bfbc'
  surface-tint: '#ac332f'
  primary: '#6b0008'
  on-primary: '#ffffff'
  primary-container: '#8c1b1b'
  on-primary-container: '#ff9c93'
  inverse-primary: '#ffb3ac'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e4e2e1'
  on-secondary-container: '#656464'
  tertiary: '#4b2900'
  on-tertiary: '#ffffff'
  tertiary-container: '#673e0c'
  on-tertiary-container: '#e5ab70'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#8a1a1a'
  secondary-fixed: '#e4e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1c1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdcbd'
  tertiary-fixed-dim: '#f7bb7e'
  on-tertiary-fixed: '#2c1600'
  on-tertiary-fixed-variant: '#663d0b'
  background: '#fcf9f0'
  on-background: '#1c1c17'
  surface-variant: '#e5e2da'
typography:
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

This design system is built to bridge the gap between ancient Japanese tradition and a modern, high-end dining experience. It evokes a sense of "Crafted Warmth," focusing on the artistry of the noodle-making process and the tactile comfort of a ramen shop. 

The visual style is **Minimalist-Tactile**. While the layout remains clean and functional to ensure ease of ordering, the soul of the design is found in organic details: subtle washi paper grains, hand-drawn brush stroke accents (*sumi-e* style), and a vertical rhythm that pays homage to traditional Japanese typesetting. The interface should feel as though it was hand-crafted, moving away from corporate sterility toward a hospitable, artisanal atmosphere.

## Colors

The palette is rooted in the natural materials of a traditional ramen-ya.

*   **Primary (Noren Red):** A deep, oxblood red used for brand callouts, primary buttons, and critical accents. It represents energy, appetite, and the traditional fabric dividers found at restaurant entrances.
*   **Secondary (Sumi Charcoal):** A soft, matte black used for primary text and structural lines. It avoids pure black to maintain a softer, more organic feel.
*   **Tertiary (Golden Oak):** A warm wood tone used for highlights, icons, and interactive hover states, mimicking the polished surfaces of a ramen bar.
*   **Neutral (Washi Cream):** The foundational background color. This is not a flat white, but a warm, textured beige that serves as the canvas for the entire system.

Additional status colors (Success/Error) should be muted to match the desaturated, earthy tone of the primary palette.

## Typography

This system utilizes a high-contrast typographic pairing to balance tradition with legibility.

**Headlines** use **Noto Serif**, chosen for its timeless, refined character. These should be treated with generous leading. For a distinctive "editorial" look, large headlines can occasionally be set vertically in desktop layouts, mimicking Japanese script.

**Body Text** and functional labels use **Be Vietnam Pro**. This sans-serif provides a contemporary, friendly counterpoint to the serif. It maintains high legibility for menu descriptions and pricing. Use the **Label-Caps** style for navigation items and price tags to create a clear visual hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop and a fluid single-column model on mobile. 

We employ a "Quiet Spacing" philosophy—using whitespace not just as a separator, but as a design element to create a sense of calm. Elements should feel uncrowded. 
*   **Asymmetry:** Occasionally break the grid with brush-stroke accents or images that bleed off the edge of the container to mimic the organic nature of calligraphy.
*   **Vertical Dividers:** Use thin, Charcoal-colored vertical lines instead of horizontal ones where possible to reflect traditional Japanese architecture.

## Elevation & Depth

To maintain the "Washi" aesthetic, this design system avoids heavy drop shadows and high-tech blurs. Instead, depth is communicated through:

*   **Tonal Layering:** Using slightly different shades of the Neutral palette (e.g., a "Bone" colored card on a "Cream" background) to create a subtle lift.
*   **Physical Borders:** Using very fine 1px charcoal or wood-toned borders to define containers.
*   **Texture Overlays:** A global, low-opacity paper texture grain applied to the background surfaces, making the UI feel like a physical menu.
*   **Sumi-e Shadows:** If a shadow is absolutely necessary for a modal, use a very soft, tinted "Red-Black" shadow with a large blur and low opacity (5-8%) to mimic an ink wash.

## Shapes

The shape language is primarily **Soft (0.25rem)**. While Japanese design often features sharp right angles (like tatami mats or shoji screens), we introduce a very slight radius to the corners of cards and buttons to make the interface feel warmer and more approachable.

**Specific Shape Rules:**
*   **Primary Action Buttons:** Use the standard soft-rounded corner.
*   **Decorative Accents:** Use "Brush-Stroke" SVG masks for images or section dividers to break the geometric rigidity.
*   **Selection Chips:** Use a pill-shape to distinguish them from structural cards.

## Components

### Buttons
*   **Primary:** Solid Noren Red background with Washi Cream text. No shadow. On hover, the color deepens slightly.
*   **Secondary:** Sumi Charcoal outline (1px) with transparent background.
*   **Text Button:** All-caps label with a Golden Oak underline that grows on hover.

### Menu Cards
Cards should be flat with a 1px border. The dish name is always in Noren Red (Noto Serif), while descriptions and prices are in Sumi Charcoal (Be Vietnam Pro). High-quality photography of the ramen should be the centerpiece, often framed in a square or circular mask with a subtle hand-drawn edge.

### Chips & Tags
Used for dietary labels (e.g., "Vegetarian," "Spicy"). These should use the Golden Oak color palette with a light-tinted background and dark-tinted text.

### Inputs
Text fields should be minimalist—only a bottom border (1px Charcoal) that turns Red on focus. Use a serif font for the input text to make the user’s choice feel intentional and elegant.

### Signature Element: The Stamp
Incorporate a "Hanko" (red square seal) icon as a loading indicator or a "Verified" badge for chef's recommendations to reinforce the authentic Japanese theme.