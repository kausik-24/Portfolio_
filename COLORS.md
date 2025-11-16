# Color Scheme Reference

This document outlines the exact color scheme used in the portfolio, matching the original React design.

## Primary Colors

### Violet Palette (Main Brand Color)
- **violet-500**: `#8b5cf6` (rgb(139, 92, 246))
- **violet-600**: `#7c3aed` (rgb(124, 58, 237)) - Primary brand color
- **violet-700**: `#6d28d9` (rgb(109, 40, 217))
- **violet-800**: `#5b21b6` (rgb(91, 33, 182))

### Purple Accent
- **purple-600**: `#9333ea` (rgb(147, 51, 234))

## Background Colors

### Base
- **Black**: `#000000` - Main background
- **Gray-900**: `#111827` (rgb(17, 24, 39))
- **Gray-800**: `#1f2937` (rgb(31, 41, 55))
- **Gray-700**: `#374151` (rgb(55, 65, 81))

### Subtle Gradients
- Top-left glow: `rgba(88, 28, 135, 0.03)` at 20% 50%
- Bottom-right glow: `rgba(109, 40, 217, 0.03)` at 80% 80%

## Text Colors

### Primary Text
- **White**: `#ffffff` (rgb(255, 255, 255))
- **Gray-300**: `#d1d5db` (rgb(209, 213, 219)) - Secondary text
- **Gray-400**: `#9ca3af` (rgb(156, 163, 175)) - Tertiary text
- **Gray-500**: `#6b7280` (rgb(107, 114, 128))

### Accent Text
- **Emerald-400**: `#34d399` (rgb(52, 211, 153)) - Success/Active indicators
- **Emerald-500**: `#10b981` (rgb(16, 185, 129))

## Interactive States

### Hover States
- Violet hover: `rgba(124, 58, 237, 0.1)` - 10% opacity
- Border hover: `rgba(124, 58, 237, 0.2)` - 20% opacity

### Focus States
- Focus ring: `rgba(124, 58, 237, 0.2)` - 20% opacity
- Selection: `rgba(124, 58, 237, 0.3)` - 30% opacity

### Borders
- **white/10**: `rgba(255, 255, 255, 0.1)` - Subtle borders
- **white/20**: `rgba(255, 255, 255, 0.2)` - Medium borders
- **violet-500/10**: `rgba(139, 92, 246, 0.1)`
- **violet-500/20**: `rgba(139, 92, 246, 0.2)`

## Gradients

### Primary Gradient (Buttons, Headers)
```css
background: linear-gradient(135deg, #7c3aed 0%, #6d28d9 100%);
```

### Hover Gradient
```css
background: linear-gradient(135deg, #8b5cf6 0%, #7c3aed 100%);
```

### Skill Bar Gradient
```css
background: linear-gradient(to right, #6d28d9, #8b5cf6);
```

### Glass Effect
```css
background: rgba(15, 15, 15, 0.6);
backdrop-filter: blur(12px);
border: 1px solid rgba(255, 255, 255, 0.05);
```

## Shadow Colors

### Glow Effects
- **shadow-glow**: `0 0 20px rgba(124, 58, 237, 0.3)`
- **shadow-glow-lg**: `0 0 40px rgba(124, 58, 237, 0.5)`
- **card-hover**: `0 20px 40px rgba(124, 58, 237, 0.2)`

### Publication Cards
- **hover-shadow**: `0 18px 48px rgba(124, 58, 237, 0.25)`

## Scrollbar

```css
::-webkit-scrollbar-track {
  background: #0a0a0a;
}

::-webkit-scrollbar-thumb {
  background: linear-gradient(180deg, #7c3aed, #6d28d9);
}

::-webkit-scrollbar-thumb:hover {
  background: linear-gradient(180deg, #8b5cf6, #7c3aed);
}
```

## Usage Guidelines

### Navigation
- Default: `#d1d5db` (gray-300)
- Hover: `#7c3aed` (violet-600) with `rgba(124, 58, 237, 0.1)` background
- Active: `#7c3aed` (violet-600) with border

### Buttons
- Primary: `#6d28d9` (violet-700) to `#7c3aed` (violet-600) gradient
- Hover: Shift gradient lighter
- Text: `#ffffff` (white)

### Cards
- Background: `rgba(255, 255, 255, 0.05)` (white/5)
- Border: `rgba(255, 255, 255, 0.1)` (white/10)
- Hover: Scale 1.02-1.05 with violet shadow

### Tags/Badges
- Background: `rgba(124, 58, 237, 0.1)` (violet-600/10)
- Border: `rgba(124, 58, 237, 0.2)` (violet-600/20)
- Text: `#8b5cf6` (violet-500) or `#7c3aed` (violet-600)

## Accessibility

- Minimum contrast ratio: 4.5:1 for normal text
- Minimum contrast ratio: 3:1 for large text
- Focus indicators: 2px solid `#7c3aed` with 3px offset

## Dark Mode Only

This portfolio uses a dark-only theme with:
- Pure black background (#000000)
- Subtle violet accents
- High contrast white text
- Glassmorphism effects for depth

---

**Note**: All colors are carefully chosen to maintain WCAG AA accessibility standards while providing a modern, professional appearance.
