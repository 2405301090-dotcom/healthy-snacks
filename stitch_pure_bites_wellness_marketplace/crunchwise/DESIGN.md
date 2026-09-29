---
name: CrunchWise
colors:
  surface: '#fbf9f1'
  surface-dim: '#dcdad2'
  surface-bright: '#fbf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f4ec'
  surface-container: '#f0eee6'
  surface-container-high: '#eae8e0'
  surface-container-highest: '#e4e3db'
  on-surface: '#1b1c17'
  on-surface-variant: '#3f4a3c'
  inverse-surface: '#30312c'
  inverse-on-surface: '#f3f1e9'
  outline: '#6f7a6b'
  outline-variant: '#becab9'
  surface-tint: '#006e1c'
  primary: '#006e1c'
  on-primary: '#ffffff'
  primary-container: '#4caf50'
  on-primary-container: '#003c0b'
  inverse-primary: '#78dc77'
  secondary: '#2a6b2c'
  on-secondary: '#ffffff'
  secondary-container: '#acf4a4'
  on-secondary-container: '#307231'
  tertiary: '#835500'
  on-tertiary: '#ffffff'
  tertiary-container: '#d48c00'
  on-tertiary-container: '#492d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#94f990'
  primary-fixed-dim: '#78dc77'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005313'
  secondary-fixed: '#acf4a4'
  secondary-fixed-dim: '#91d78a'
  on-secondary-fixed: '#002203'
  on-secondary-fixed-variant: '#0c5216'
  tertiary-fixed: '#ffddb4'
  tertiary-fixed-dim: '#ffb955'
  on-tertiary-fixed: '#291800'
  on-tertiary-fixed-variant: '#633f00'
  background: '#fbf9f1'
  on-background: '#1b1c17'
  surface-variant: '#e4e3db'
typography:
  display-lg:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Lexend
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system embodies a **Fresh Premium Wellness** aesthetic. It moves away from the sterile, clinical feel of traditional health supplements toward a warm, culinary-focused experience. The brand personality is optimistic, nourishing, and high-end.

The style leverages **Modern Minimalism** mixed with **Tactile Softness**. It uses generous whitespace to signal premium quality, while soft organic shapes and warm background tones ensure the interface feels approachable rather than cold. The visual narrative focuses on the transition from "raw nature" to "gourmet snack," emphasizing transparency and appetite appeal through high-quality photography and intentional hierarchy.

## Colors
The palette is rooted in a "Gourmet Earth" philosophy. 
- **Primary (Leaf Green):** Used for primary actions, success states, and brand highlights.
- **Secondary (Deep Forest):** Reserved for typography and deep structural elements to provide grounded authority.
- **Background (Cream):** A warm off-white that reduces eye strain and provides a sophisticated, "organic paper" feel compared to pure white.
- **Accents:** Golden Yellow is used for "New" badges and flavor highlights (e.g., honey, roasted elements). Terracotta provides a natural contrast for "Add to Cart" hover states or spicy flavor profiles.

## Typography
**Lexend** is chosen for its specific design intent: maximizing readability and reducing visual noise. Its slightly expanded apertures and geometric foundations make the brand feel modern and friendly. 

- **Headlines:** Use Deep Forest Green (#1B5E20) to maintain high contrast and a premium feel.
- **Body:** Use a dark grey-green (Secondary at 80% opacity) for long-form reading to maintain warmth.
- **Labels:** Use for nutritional facts and UI metadata, ensuring clarity even at small sizes.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid** model. Content is centered in a 1280px max-width container on desktop, while margins expand fluidly. 

- **Grid:** A 12-column grid is used for desktop product listings, collapsing to 2 columns on mobile for "snackable" browsing.
- **Rhythm:** An 8px base unit drives all spacing. For a premium feel, use "Extra-Large" vertical padding (80px–120px) between homepage sections to allow product photography to breathe.
- **Touch Targets:** All interactive elements on mobile must maintain a minimum 44px height.

## Elevation & Depth
This design system utilizes **Tonal Depth** and **Ambient Shadows** to create a tactile, layered feel. 

- **Shadows:** Avoid harsh blacks. Use the Secondary color (#1B5E20) at 4-8% opacity for shadows to maintain a soft, organic appearance. 
- **Cards:** Product cards use a 1px stroke in Earthy Beige (#F2E8CF) combined with a very soft, diffused shadow to appear "resting" on the Cream background.
- **Floating Elements:** Primary Action Buttons (CTAs) use a slightly tighter, more saturated shadow to indicate they are "raised" and ready for interaction.

## Shapes
Shapes are intentionally soft and organic to mirror the natural ingredients of the products.
- **Standard Radius:** 16px for buttons and small components.
- **Large Radius (rounded-lg):** 24px for product cards and ingredient highlights.
- **Extra Large (rounded-xl):** 32px or fully pill-shaped for featured promotional banners and search bars.

## Components
- **Buttons:** Primary buttons are pill-shaped with Leaf Green backgrounds and white text. Secondary buttons use a Deep Forest Green outline with 1.5px thickness.
- **Product Cards:** Must feature a 24px corner radius. The image should occupy the top 60% of the card, using a subtle background tint that matches the flavor profile (e.g., soft yellow for honey-roasted).
- **Nutritional Chips:** Small, rounded-pill labels used to highlight "High Protein," "Vegan," or "Gluten-Free." These should use the Accent Beige background with Deep Forest Green text.
- **Input Fields:** Use the Cream background with a 1px Earthy Beige border. On focus, the border transitions to Leaf Green with a soft glow.
- **Quantity Selector:** A rounded-pill component with a tactile "+" and "-" button, emphasizing the physical act of "gathering" snacks.
- **Iconography:** Use "Linear-Bold" style icons with rounded terminals to match the Lexend typeface.