# ILSI Europe Design System

A comprehensive design system for ILSI Europe — the global nonprofit federation advancing evidence-based scientific research on nutrition, food safety, and sustainability.

## 📋 Overview

This design system provides guidelines, components, and assets for consistent brand representation across all digital and print materials. It reflects ILSI Europe's commitment to scientific integrity, collaboration, and thought leadership in global nutrition and health.

**Brand Tagline:** *Collaborative science for safe, nutritious and sustainable food.*

---

## 🎨 What's Included

### Brand Guidelines
- **DESIGN.md** — Complete design system specification including colors, typography, components, and usage guidelines
- **colors.json** — Structured color palette data for developers and designers

### Visual Assets
- **Logo files** (color and reverse variations)
- Color palette specifications with Pantone, HEX, RGB, and CMYK values
- Typography guide with font weights and hierarchy

### Documentation
- **README.md** (this file) — Quick reference
- **LICENSE** — Usage rights and compliance

---

## 🎯 Brand Personality

ILSI Europe is defined by eight core traits:

1. **Credible** — Trustworthy authority in scientific research
2. **Honest** — Transparent and ethical communications
3. **Collaborative** — Working across sectors and disciplines
4. **Pioneering** — Leading innovation in food science
5. **Smart** — Intellectually rigorous and sophisticated
6. **Crisp** — Clear, concise, and well-organized
7. **Open** — Inclusive and accessible
8. **Thoughtful** — Deliberate and considered in approach

---

## 🎨 Primary Colors

| Color | HEX | RGB | CMYK | PMS | Usage |
|-------|-----|-----|------|-----|-------|
| ILSI Indigo | #1F0079 | 31, 0, 121 | 95, 99, 4, 1 | 2685 C | Primary brand color, headlines, CTAs |
| ILSI Orange | #F79F1E | 247, 159, 30 | 4, 36, 86, 0 | 136 C | Accents, highlights, energy |
| ILSI Blue | #1B7AB2 | 27, 122, 178 | 91, 27, 5, 0 | 7689 C | Secondary color, sustainability, trust |

## 🎨 Secondary Colors

| Color | HEX | RGB | CMYK | PMS |
|-------|-----|-----|------|-----|
| ILSI Magenta | #9C037E | 156, 3, 126 | 38, 93, 5, 1 | 241 C |
| ILSI Bright Magenta | #C7187F | 199, 24, 127 | 18, 90, 8, 1 | Rhodamine Red C |
| ILSI Green | #6CC185 | 108, 193, 133 | 58, 3, 47, 0 | 346 C |
| ILSI Light Blue | #2E8EB9 | 46, 142, 185 | 83, 18, 5, 1 | 7688 C |

## 🎨 Neutral Colors

| Color | HEX | RGB | Usage |
|-------|-----|-----|-------|
| White | #FFFFFF | 255, 255, 255 | Backgrounds, text contrast |
| ILSI Charcoal | #393939 | 57, 57, 57 | Use instead of pure black |

---

## 🔤 Typography

### Primary Typeface

**Montserrat** — A modern, versatile sans-serif font
- Designed by Julieta Ulanovsky
- Free and open source from [Google Fonts](https://fonts.google.com/specimen/Montserrat)
- Optimized for both digital and print applications

### Font Weights

- **Light** — Secondary information, subtle elements
- **Regular** — Body text, standard content
- **Medium** — Subheadings, emphasized content
- **Bold** — Headlines, primary headings, strong emphasis

### Fallback Fonts

When Montserrat is unavailable:
1. Helvetica (macOS/professional)
2. Arial (Windows/web-safe)

---

## 📖 Logo Usage

### Logo Variations

1. **Color Version** — Full color logo for light backgrounds
2. **Reverse Version** — White logo for dark backgrounds
3. **Icon Only** — Logo mark alone (when brand name visible nearby)
4. **One Color** — Monochrome version for print

### Logo Guidelines

- **Minimum Size:** 1 inch (print) / 100px (digital)
- **Clear Space:** Equal to height of ILSI wordmark on all sides
- **Never:** Stretch, distort, alter proportions, change colors, add effects

---

## 🧩 Components

### Buttons

**Primary**
- Background: ILSI Indigo
- Text: White
- Padding: 12px 24px
- Border Radius: 4px
- Weight: Montserrat Medium

**Secondary**
- Border: 2px ILSI Orange
- Background: Transparent
- Text: ILSI Indigo
- Padding: 10px 22px
- Border Radius: 4px

### Cards
- Background: White
- Border Radius: 8px
- Padding: 24px
- Shadow: Light (0 2px 8px rgba(31, 0, 121, 0.1))
- Border: 1px solid #E0E0E0

### Typography Styles

| Style | Font | Size | Weight | Color |
|-------|------|------|--------|-------|
| H1 | Montserrat | 32px | Bold | ILSI Indigo |
| H2 | Montserrat | 24px | Bold | ILSI Indigo |
| H3 | Montserrat | 20px | Medium | ILSI Indigo |
| Body | Montserrat | 16px | Regular | ILSI Charcoal |
| Link | Montserrat | 16px | Regular | ILSI Blue |

---

## 🖼️ Imagery

- High-quality photography reflecting sustainability, science, and collaboration
- Themes: food, nutrition, agriculture, scientific research, nature
- Consistent color temperature and visual style
- Overlays with brand colors for visual coherence

---

## ⚙️ Spacing & Layout

- **Grid System:** Multiples of 8px (8, 16, 24, 32, 40, 48px, etc.)
- **Generous white space** for clarity and sophistication
- **Visual hierarchy** through size and weight contrast
- **Alignment:** Left-aligned text, centered headlines

---

## ♿ Accessibility

All designs must meet WCAG AA standards:

- **Contrast Ratio:** Minimum 4.5:1 for text
- **Color:** Never rely on color alone for information
- **Typography:** Readable font sizes and line heights
- **Interactive Elements:** Keyboard accessible
- **Images:** Include descriptive alt text
- **Semantic HTML:** Proper heading structure and ARIA labels

---

## 🚀 Getting Started

### For Designers

1. Download **Montserrat** from [Google Fonts](https://fonts.google.com/specimen/Montserrat)
2. Reference **DESIGN.md** for complete component specifications
3. Use **colors.json** for accurate color definitions
4. Access logo files in the `/assets` folder

### For Developers

1. Import colors from **colors.json** into your project
2. Load Montserrat from Google Fonts CDN or locally
3. Reference component specifications in **DESIGN.md** for CSS/code implementations
4. Ensure WCAG AA compliance in all implementations

### For Claude Design Users

1. Point your Claude Design project to this GitHub repository
2. Claude will automatically extract:
   - Colors and color names
   - Typography specifications
   - Logo assets
   - Component guidelines
3. Use as the foundation for your design system when creating UI prototypes

---

## 📋 File Structure

```
ilsi-design-system/
├── README.md                    ← This file
├── DESIGN.md                    ← Complete design system spec
├── colors.json                  ← Color palette data
├── logo-specs.md               ← Logo specifications
└── assets/
    ├── logo-color.png          ← Color logo
    ├── logo-reverse.png        ← White/reverse logo
    ├── logo-icon.png           ← Icon only
    └── fonts/
        └── montserrat/         ← Font files (if included)
```

---

## 📝 Usage Rights

© 2022 ILSI Europe. All rights reserved.

This design system is for use by ILSI Europe team members, partner organizations, and authorized contractors only. All brand assets must be used in compliance with these guidelines.

For questions or special use cases, contact: **cchang@ilsieurope.be**

---

## 🔄 Version History

| Version | Date | Notes |
|---------|------|-------|
| 1.0 | April 2026 | Initial design system launch |
| — | — | Based on ILSI Europe Style Guide © 2022 |

---

## 📞 Contact & Support

**ILSI Europe**
- Email: cchang@ilsieurope.be
- Organization: ILSI Europe
- Website: www.ilsi.org

For design system questions, updates, or feedback, please contact the communications team.

---

## 🎓 Resources

- [Complete Design System Guide](./DESIGN.md)
- [Color Specifications](./colors.json)
- [Logo Guidelines](./logo-specs.md)
- [Google Fonts - Montserrat](https://fonts.google.com/specimen/Montserrat)
- [WCAG Accessibility Standards](https://www.w3.org/WAI/WCAG21/quickref/)

---

**Last Updated:** April 2026
