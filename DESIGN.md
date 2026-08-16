---
name: Botanical Serenity
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#424844'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#727974'
  outline-variant: '#c1c8c3'
  surface-tint: '#466557'
  primary: '#163428'
  on-primary: '#ffffff'
  primary-container: '#2d4b3e'
  on-primary-container: '#99baa9'
  inverse-primary: '#adcebd'
  secondary: '#7b5455'
  on-secondary: '#ffffff'
  secondary-container: '#fecbcb'
  on-secondary-container: '#7a5354'
  tertiary: '#29312f'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f4745'
  on-tertiary-container: '#adb5b2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8ead8'
  primary-fixed-dim: '#adcebd'
  on-primary-fixed: '#012116'
  on-primary-fixed-variant: '#2f4d40'
  secondary-fixed: '#ffdad9'
  secondary-fixed-dim: '#ecbaba'
  on-secondary-fixed: '#2f1314'
  on-secondary-fixed-variant: '#613d3e'
  tertiary-fixed: '#dce4e1'
  tertiary-fixed-dim: '#c0c8c5'
  on-tertiary-fixed: '#161d1c'
  on-tertiary-fixed-variant: '#404846'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
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
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
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
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 80px
---

## Brand & Style

The brand personality is **warm, inviting, and effortlessly sophisticated**, mirroring the transition from a sun-drenched garden entrance to a refined culinary experience. It targets an audience that values aesthetic mindfulness—people seeking a sanctuary for both social gathering and quiet reflection.

The design style is a blend of **Minimalism and Glassmorphism**. We utilize heavy whitespace and a restricted, nature-inspired palette to allow high-quality food photography to remain the focal point. Subtle translucent layers and background blurs evoke the "airy" atmosphere of the cafe's physical space, while precise typography ensures a premium, editorial feel. The goal is to create a digital environment that feels as fresh and welcoming as a morning in a lush, blooming garden.

## Colors

The palette is derived directly from the cafe's botanical environment and vibrant menu offerings. 

- **Primary (Deep Botanical Green):** A grounded, sophisticated green used for primary actions, headlines, and structural elements. It provides the "weight" in the design.
- **Secondary (Soft Petal Pink):** An accent color used for highlights, decorative elements, and interactive states. It adds the "warmth" requested.
- **Tertiary (Mint Mist):** A very pale, desaturated green used for large surface areas and containers to maintain the airy feeling without being clinical white.
- **Neutral (Warm Parchment):** The base background color, providing a softer, more organic feel than pure white.

Use high-chroma colors from photography (like the watermelon or orange drink tones) as transient accents for seasonal promotions or specific menu categories.

## Typography

The typography strategy balances **tradition and modernity**. 

**Libre Caslon Text** is used for headlines to provide a literary, established, and elegant feel. Its high-contrast strokes reflect the "sophisticated" aspect of the brand.

**Plus Jakarta Sans** is used for body copy and UI labels. Its soft, rounded terminals echo the "inviting" nature of the cafe. It remains highly legible even at small sizes, which is critical for menu descriptions and functional UI.

Maintain generous line heights to preserve the "airy" aesthetic. Use the uppercase `label-sm` for category tags (e.g., "VEGAN", "SIGNATURE") to create clear visual hierarchy without overwhelming the page.

## Layout & Spacing

The layout follows a **fluid grid** model with significant breathing room. We use a 12-column grid for desktop and a 4-column grid for mobile.

- **White Space:** Padding should be generous. Avoid crowding food photography; images should feel like they have "room to breathe" on the page.
- **Rhythm:** Use an 8px base unit. Section gaps are intentionally large (80px+) to create a sense of pace and luxury, slowing the user down to appreciate the visuals.
- **Photography:** Images should often break the grid or bleed to the edge of the container to emphasize the "lush" garden feel.

## Elevation & Depth

To achieve the "soft and airy" atmosphere, this design system avoids heavy shadows. Depth is created through:

1.  **Tonal Layering:** Using the Tertiary (Mint Mist) color on top of the Neutral (Warm Parchment) background to define card areas.
2.  **Backdrop Blurs:** For overlays like navigation menus or modal dialogs, use a 16px background blur with a 60% white tint. This mimics the frosted glass of the cafe’s interior.
3.  **Soft Ambient Shadows:** Where elevation is necessary (e.g., a floating "Order Now" button), use a very large, low-opacity shadow tinted with the Primary Green (`rgba(45, 75, 62, 0.08)`) rather than black.

## Shapes

The shape language is **distinctly rounded** to evoke a sense of organic growth and approachability. 

- **Cards & Inputs:** Use the `rounded-lg` (1rem) setting to soften the edges of the UI.
- **Buttons:** Primary buttons should use the `rounded-xl` or pill-shape to feel "squishy" and inviting to touch.
- **Image Masks:** Occasionally use subtle organic or arched masks for hero images to mirror the architectural entrance shown in the reference photos.

## Components

- **Buttons:** High-contrast Primary Green with white text for main actions. Secondary actions use an outline of Primary Green or a ghost style with the Soft Pink background.
- **Cards:** Borderless with a Tertiary color fill. Ensure a minimum of 32px internal padding to maintain the "airy" feel.
- **Input Fields:** Soft Parchment backgrounds with a 1px Primary Green border that thickens slightly on focus.
- **Chips/Tags:** Use the Secondary Pink with Primary Green text for "New" or "Chef's Choice" items. Rounded pill shapes only.
- **Menu Lists:** Use Libre Caslon for item titles and Plus Jakarta for descriptions. Price points should be clearly legible but not dominant.
- **Photography Containers:** Always feature a subtle 1px inner border or a very soft corner radius to ensure images feel integrated into the design.