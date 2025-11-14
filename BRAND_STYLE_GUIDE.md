# Website Branding Style Guide

> **Version 1.0** | Last Updated: November 2024
> This style guide defines the visual identity and design standards for the Oxpins website template.

---

## Table of Contents

1. [Brand Overview](#brand-overview)
2. [Color Palette](#color-palette)
3. [Typography](#typography)
4. [Buttons & CTAs](#buttons--ctas)
5. [Spacing & Layout](#spacing--layout)
6. [Iconography](#iconography)
7. [Components](#components)
8. [Imagery Guidelines](#imagery-guidelines)
9. [Accessibility Standards](#accessibility-standards)

---

## Brand Overview

### Brand Identity
The Oxpins website template embodies warmth, trust, and community engagement through its carefully crafted design system. The brand combines earthy tones with vibrant accents to create an approachable yet professional digital presence.

### Design Philosophy
- **Warmth**: Soft, organic color palette with cream and beige backgrounds
- **Approachability**: Rounded corners and friendly typography
- **Impact**: Bold accent colors for calls-to-action
- **Clarity**: Clean layouts with generous white space

---

## Color Palette

### Primary Colors

#### Brand Green
```
Hex: #76397B
RGB: 118, 57, 123
CSS Variable: var(--oxpins-base)
Use: Primary brand color, headers, primary buttons, links
```

#### Accent Yellow
```
Hex: #FBD45A
RGB: 251, 212, 90
CSS Variable: var(--oxpins-primary)
Use: Secondary CTA buttons, highlights, accents, badges
```

### Neutral Colors

#### Black
```
Hex: #283734
RGB: 40, 55, 52
CSS Variable: var(--oxpins-black)
Use: Headings, dark text, footer backgrounds
```

#### Gray
```
Hex: #6F7775
RGB: 111, 119, 117
CSS Variable: var(--oxpins-gray)
Use: Body text, secondary information
```

#### White
```
Hex: #FFFFFF
RGB: 255, 255, 255
CSS Variable: var(--oxpins-white)
Use: Backgrounds, text on dark backgrounds
```

### Background Colors

#### Cream
```
Hex: #F9F4E8
RGB: 249, 244, 232
CSS Variable: var(--oxpins-extra)
Use: Page backgrounds, alternating sections, cards
```

#### Border Beige
```
Hex: #EEE9DB
RGB: 238, 233, 219
CSS Variable: var(--oxpins-bdr-color)
Use: Borders, dividers, subtle separators
```

### Color Usage Guidelines

**Do:**
- Use Brand Green (#76397B) for primary actions and navigation
- Apply Accent Yellow (#FBD45A) sparingly for emphasis
- Maintain minimum 4.5:1 contrast ratio for text
- Use cream backgrounds to reduce eye strain

**Don't:**
- Don't use yellow for large text blocks
- Avoid placing gray text on cream backgrounds (poor contrast)
- Don't combine primary green and yellow without sufficient spacing
- Avoid using more than 3 colors in a single component

---

## Typography

### Font Families

#### Primary Font: Manrope
```
Font Family: 'Manrope', sans-serif
CSS Variable: var(--oxpins-font)
Weights Available: 200, 300, 400, 500, 600, 700, 800
Use: Body text, buttons, UI elements, navigation
Source: Google Fonts
```

#### Secondary Font: Nunito
```
Font Family: 'Nunito', sans-serif
CSS Variable: var(--oxpins-font-two)
Weights Available: 200-900 (Regular & Italic)
Use: Headings, titles, emphasis text
Source: Google Fonts
```

#### Accent Font: Caveat
```
Font Family: 'Caveat', cursive
CSS Variable: var(--oxpins-font-three)
Weights Available: 400, 500, 600, 700
Use: Decorative elements, taglines, special emphasis
Source: Google Fonts
```

### Type Scale

| Element | Font Family | Size | Weight | Line Height | Color |
|---------|------------|------|--------|-------------|-------|
| **H1** | Nunito | 50px | 900 | 1.2 | Black (#283734) |
| **H2** | Nunito | 35px | 700 | 1.3 | Black (#283734) |
| **H3** | Nunito | 28px | 700 | 1.4 | Black (#283734) |
| **H4** | Nunito | 24px | 700 | 1.4 | Black (#283734) |
| **H5** | Nunito | 20px | 700 | 1.5 | Black (#283734) |
| **H6** | Nunito | 16px | 700 | 1.5 | Black (#283734) |
| **Body** | Manrope | 15px | 500 | 30px | Gray (#6F7775) |
| **Body Large** | Manrope | 16-18px | 500 | 1.8 | Gray (#6F7775) |
| **Small Text** | Manrope | 13-14px | 500-600 | 1.6 | Gray (#6F7775) |
| **Button** | Manrope | 14px | 800 | 1.4 | Varies |
| **Accent** | Caveat | 24-50px | 400-700 | 1.3 | Brand Green |

### Typography Guidelines

**Do:**
- Use Nunito for all headings to maintain hierarchy
- Keep body text at 15px minimum for readability
- Use line-height of 30px for body text (2.0 ratio)
- Apply Caveat sparingly for decorative purposes only

**Don't:**
- Don't use Caveat for body text or navigation
- Avoid font sizes smaller than 13px
- Don't use more than 3 font weights in a single section
- Avoid all-caps text longer than 3 words

---

## Buttons & CTAs

### Primary Button (`.thm-btn`)

```css
Background: var(--oxpins-base) (#76397B)
Text Color: var(--oxpins-white) (#FFFFFF)
Font Size: 14px
Font Weight: 800
Padding: 12px 40px (estimated)
Border Radius: 20px
Transition: All 0.4s ease
```

**Hover State:**
```css
Background: var(--oxpins-black) (#283734)
Text Color: var(--oxpins-white) (#FFFFFF)
Transform: Slight lift effect
```

### Secondary Button

```css
Background: var(--oxpins-primary) (#FBD45A)
Text Color: var(--oxpins-black) (#283734)
Font Size: 14px
Font Weight: 800
Padding: 12px 40px
Border Radius: 20px
```

**Hover State:**
```css
Background: var(--oxpins-black) (#283734)
Text Color: var(--oxpins-white) (#FFFFFF)
```

### Button Variants

| Type | Background | Text Color | Use Case |
|------|-----------|------------|----------|
| Primary | #76397B | #FFFFFF | Main actions, "Donate Now", "Get Started" |
| Secondary | #FBD45A | #283734 | Alternative actions, "Learn More" |
| Outline | Transparent | #76397B | Tertiary actions, less emphasis |
| Text Link | None | #76397B | In-text links, minimal emphasis |

### Button Guidelines

**Do:**
- Use primary buttons for the most important action on a page
- Limit to 1-2 primary buttons per section
- Include icon with heart or arrow when appropriate
- Ensure minimum touch target of 44x44px

**Don't:**
- Don't use more than 2 button styles in one section
- Avoid placing buttons on busy background images
- Don't use all-caps for button text
- Avoid buttons narrower than 120px

---

## Spacing & Layout

### Grid System
- **Container Max Width**: 1200px
- **Grid Columns**: 12-column Bootstrap grid
- **Gutter Width**: 30px
- **Breakpoints**:
  - XL: 1200px+
  - LG: 992px - 1199px
  - MD: 768px - 991px
  - SM: 576px - 767px
  - XS: < 576px

### Spacing Scale

```
Base Unit: 5px

4px   (0.8 units)  - Micro spacing
8px   (1.6 units)  - Tiny spacing
12px  (2.4 units)  - Small spacing
16px  (3.2 units)  - Default spacing
20px  (4 units)    - Medium spacing
24px  (4.8 units)  - Large spacing
32px  (6.4 units)  - XL spacing
40px  (8 units)    - XXL spacing
60px  (12 units)   - Section padding
80px  (16 units)   - Large section padding
100px (20 units)   - Major section spacing
```

### Border Radius

```
Default: 20px (var(--oxpins-bdr-radius))
Small: 10px
Large: 30px
Cards: 20px
Buttons: 20px
Images: 20px
```

### Layout Patterns

**Section Spacing:**
- Top Padding: 80-100px
- Bottom Padding: 80-100px
- Mobile: Reduce to 60px top/bottom

**Card Layouts:**
- Padding: 30-40px
- Margin Bottom: 30px
- Border Radius: 20px

**Content Width:**
- Text Content: Max 800px for readability
- Full Width: Use for images and backgrounds
- Narrow: 600px for forms

---

## Iconography

### Icon Fonts

**Primary Icon Set:**
- Font: Oxpins Icons (Custom icon font)
- File: `assets/vendors/oxpins-icons/style.css`
- Usage: `<span class="icon-[name]"></span>`

**Secondary Icon Set:**
- Font: FontAwesome 5
- Usage: Standard FA classes
- Examples: `.fa-heart`, `.fa-phone-call`, `.fa-message`

### Icon Styles

| Icon Type | Size | Color | Use Case |
|-----------|------|-------|----------|
| Navigation | 20px | Brand Green | Menu items, breadcrumbs |
| Feature | 40-60px | Brand Green or Yellow | Service cards, features |
| Social | 16-18px | White or Gray | Social media links |
| Action | 14-16px | Inherits | Buttons, links |

### Icon Guidelines

**Do:**
- Use icons to support text, not replace it
- Maintain consistent icon style (outline or filled)
- Size icons proportionally to accompanying text
- Use brand colors for icons

**Don't:**
- Don't mix icon styles (outlined + filled)
- Avoid decorative-only icons without purpose
- Don't use icons smaller than 14px
- Avoid complex icons at small sizes

---

## Components

### Cards

**Feature Card (`.causes-one__single`)**
```
Structure:
- Image (16:9 ratio)
- Category badge (top-left overlay)
- Title (H3)
- Description text
- Progress bar (optional)
- Stats/metrics

Styling:
- Background: White
- Border Radius: 20px
- Padding: 20px (content area)
- Shadow: Subtle drop shadow on hover
- Transition: 0.4s ease
```

**Blog Card (`.news-one__single`)**
```
Structure:
- Featured image
- Date badge (positioned absolute)
- Meta information (author, comments)
- Title (H3)
- Read more link
- Social share (hover reveal)

Styling:
- Background: White
- Border Radius: 20px
- Shadow: Minimal, increases on hover
```

### Navigation

**Main Menu (`.main-menu`)**
```
Structure:
- Two-tier navigation
- Top bar: Contact info, CTA
- Bottom bar: Logo, menu, actions

Styling:
- Background: White
- Height: Auto (two-tier)
- Sticky on scroll
- Desktop: Horizontal
- Mobile: Hamburger menu
```

### Forms

**Input Fields**
```
Height: 50px
Border: 1px solid #EEE9DB
Border Radius: 10px
Padding: 12px 20px
Font Size: 15px
Font Weight: 500

Focus State:
- Border Color: #76397B
- Outline: None
- Box Shadow: 0 0 0 3px rgba(118, 57, 123, 0.1)
```

### Progress Bars

```
Height: 8px
Background: #EEE9DB
Fill Color: #76397B
Border Radius: 10px
Animation: Smooth fill on scroll
```

### Section Headers

**Section Title (`.section-title`)**
```
Structure:
- Tagline (small text, accent font)
- Title (H2, main heading)
- Optional description

Spacing:
- Tagline margin-bottom: 12px
- Title margin-bottom: 20px
- Section margin-bottom: 50px

Alignment:
- Left: Default
- Center: Add .text-center
```

---

## Imagery Guidelines

### Photography Style

**Characteristics:**
- Warm, natural tones
- Authentic, candid moments
- Diverse representation
- Good lighting, not overly staged
- Focus on people and community

**Technical Specs:**
- Format: JPG (photos), PNG (graphics)
- Resolution: Minimum 1920px width
- Optimization: Compress for web (70-80% quality)
- Aspect Ratios:
  - Hero: 16:9 or 21:9
  - Cards: 4:3 or 16:9
  - Blog: 16:9

### Image Treatment

**Overlays:**
```
Dark Overlay: rgba(0, 0, 0, 0.3-0.5)
Brand Overlay: rgba(118, 57, 123, 0.8)
Use: For text readability on images
```

**Filters:**
- Warmth: +5-10%
- Contrast: Standard to +5%
- Saturation: Standard to -5%
- No heavy filters or effects

### Logo Usage

**Primary Logo**
- File: `assets/images/resources/logo-1.png`
- Use: Header, light backgrounds
- Clear space: Minimum 20px on all sides

**Footer Logo**
- File: `assets/images/resources/footer-logo.png`
- Use: Footer, dark backgrounds

**Mobile Logo**
- File: `assets/images/resources/logo-2.png`
- Use: Mobile navigation

**Guidelines:**
- Never distort or stretch logo
- Maintain aspect ratio
- Don't apply filters or effects
- Use provided versions for different contexts

---

## Accessibility Standards

### Color Contrast

**WCAG 2.1 AA Compliance:**
- Normal text: Minimum 4.5:1 contrast ratio
- Large text (18px+): Minimum 3:1 contrast ratio
- UI components: Minimum 3:1 contrast ratio

**Approved Combinations:**
- ✅ Black text (#283734) on White (#FFFFFF) - 11.8:1
- ✅ Gray text (#6F7775) on White (#FFFFFF) - 4.9:1
- ✅ Brand Green (#76397B) on White (#FFFFFF) - 5.2:1
- ✅ White text (#FFFFFF) on Brand Green (#76397B) - 5.2:1
- ✅ Black text (#283734) on Yellow (#FBD45A) - 8.2:1

**Avoid:**
- ❌ Gray text (#6F7775) on Cream (#F9F4E8) - 4.2:1 (borderline)
- ❌ Yellow (#FBD45A) on White (#FFFFFF) - 1.4:1 (insufficient)

### Keyboard Navigation

**Requirements:**
- All interactive elements must be keyboard accessible
- Visible focus indicators on all focusable elements
- Logical tab order following visual layout
- Skip navigation link for main content

**Focus Styles:**
```css
:focus {
  outline: 2px solid var(--oxpins-base);
  outline-offset: 2px;
}

:focus:not(:focus-visible) {
  outline: none;
}
```

### Screen Readers

**Best Practices:**
- Use semantic HTML5 elements
- Include alt text for all images
- ARIA labels for icon-only buttons
- Proper heading hierarchy (H1-H6)
- Form labels associated with inputs

### Motion & Animation

**Respect User Preferences:**
```css
@media (prefers-reduced-motion: reduce) {
  * {
    animation-duration: 0.01ms !important;
    transition-duration: 0.01ms !important;
  }
}
```

**Animation Guidelines:**
- Duration: 200-400ms
- Easing: ease, ease-in-out
- Purpose: Enhance UX, not distract
- Subtle: Avoid flashy or jarring animations

### Touch Targets

**Minimum Sizes:**
- Buttons: 44x44px
- Links in body text: Adequate padding
- Form inputs: 44px minimum height
- Icon buttons: 44x44px touch area

---

## Design Tokens (CSS Variables)

### Quick Reference

```css
:root {
  /* Typography */
  --oxpins-font: "Manrope", sans-serif;
  --oxpins-font-two: "Nunito", sans-serif;
  --oxpins-font-three: "Caveat", cursive;

  /* Colors */
  --oxpins-base: #76397b;
  --oxpins-base-rgb: 118, 57, 123;
  --oxpins-primary: #fbd45a;
  --oxpins-primary-rgb: 251, 212, 90;
  --oxpins-black: #283734;
  --oxpins-black-rgb: 40, 55, 52;
  --oxpins-gray: #6f7775;
  --oxpins-gray-rgb: 111, 119, 117;
  --oxpins-white: #ffffff;
  --oxpins-white-rgb: 255, 255, 255;
  --oxpins-extra: #f9f4e8;
  --oxpins-extra-rgb: 249, 244, 232;
  --oxpins-bdr-color: #eee9db;
  --oxpins-bdr-color-rgb: 238, 233, 219;

  /* Spacing */
  --oxpins-bdr-radius: 20px;
}
```

---

## Implementation Checklist

### For Designers

- [ ] Use approved color palette only
- [ ] Maintain typography hierarchy
- [ ] Follow spacing scale consistently
- [ ] Ensure 4.5:1 contrast minimum
- [ ] Design for mobile-first
- [ ] Include hover and focus states
- [ ] Document component variations

### For Developers

- [ ] Use CSS variables for all colors
- [ ] Implement responsive breakpoints
- [ ] Add focus styles for accessibility
- [ ] Optimize images for web
- [ ] Test keyboard navigation
- [ ] Validate HTML semantics
- [ ] Test with screen readers
- [ ] Implement loading states
- [ ] Add error states for forms

### For Content Creators

- [ ] Use heading hierarchy correctly
- [ ] Write descriptive alt text
- [ ] Keep paragraphs concise (3-4 lines)
- [ ] Use bullet points for scannability
- [ ] Include clear CTAs
- [ ] Optimize image file sizes
- [ ] Write accessible link text
- [ ] Avoid walls of text

---

## Maintenance & Updates

### Version History

- **v1.0** (November 2024) - Initial style guide creation

### Review Schedule

- **Quarterly**: Review component usage and patterns
- **Bi-annually**: Update color contrast compliance
- **Annually**: Full design system audit

### Questions or Suggestions?

For updates or questions about this style guide, please contact your design team or submit issues through your project management system.

---

**Document Information**
- Template: Oxpins Website Template
- Created: November 2024
- Format: Markdown
- Status: Living Document
