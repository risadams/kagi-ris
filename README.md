# kagi-ris

My personal Kagi CSS custom theme, based on my "Ink and Agency" branding

## 🎨 Overview

A custom CSS theme for [Kagi Search](https://kagi.com) featuring:

- **Deep rose/magenta accent color** (#9f1158) with carefully crafted light and dark mode variants
- **Custom typography** using Inter (sans-serif), Fraunces (serif), and JetBrains Mono (monospace) from Google Fonts
- **Light & Dark mode support** with adaptive color schemes
- **Thoughtful UI refinements** for search results, widgets, buttons, and navigation
- **Accessibility-first** with focus rings, proper contrast ratios, and semantic color usage

## 🚀 Installation

### Step 1: Copy the Theme CSS

1. Open [`theme.css`](./theme.css) in this repository
2. Select all the CSS code (Ctrl+A or Cmd+A) and copy it

### Step 2: Apply to Kagi

1. Go to **[Kagi Settings → Custom CSS](https://kagi.com/settings/custom_css)**
2. Paste the entire CSS code into the custom CSS textarea
3. Click **Save**
4. Your Kagi search experience will instantly update with the new theme!

## 📚 How Custom CSS Works in Kagi

Kagi allows you to customize the search interface with your own CSS. For more details and tips, see [Kagi's guide to custom CSS](https://blog.kagi.com/tips/custom-css).

Key things to know:

- Custom CSS applies to both light and dark modes automatically
- Changes are saved to your Kagi account and sync across devices
- You can mix and match multiple themes or create variations
- Use browser DevTools (F12) to inspect elements and customize further

## 🎯 Theme Features

### Color Palette

**Light Mode:**

- Background: `#faf6f8`
- Accent: `#9f1158` (deep rose)
- Text: `#1a0d14` (near black)
- Accent Subtle: `#f5e8ef`

**Dark Mode:**

- Background: `#130e10`
- Accent: `#e0729e` (lighter rose for readability)
- Text: `#f0dce6` (near white)
- Accent Subtle: `#2a1520`

### Styled Elements

The theme customizes:

- Search bar and input fields
- Result titles, URLs, and snippets
- Buttons and interactive elements
- Navigation tabs and pagination
- Sidebar widgets and knowledge panels
- Instant answers and AI results
- Tags, badges, and decorations
- Scrollbar and focus states
- And much more!

## 🔧 Customization

Want to tweak the colors or styling? You can:

1. Edit the CSS variables in the theme (lines 17-58 for light mode, 65-98 for dark mode)
2. Save your changes back to Kagi Settings → Custom CSS
3. Or fork this repo and create your own variation!

Common customizations:

- Change `--ra-accent: #9f1158` to your preferred color
- Adjust font families in the custom properties section
- Modify spacing and sizing in individual sections

## 📖 Technical Details

- **CSS Variables**: Uses CSS custom properties (variables) for easy theming
- **Color Mixing**: Uses `color-mix()` for intelligent color blending
- **Semantic Selectors**: Targets both Kagi's new and legacy CSS class names
- **Dark Mode Support**: Automatically switches between light/dark variants based on Kagi's theme selection

## 👤 About

Created by Ris Adams · [risadams.com](https://risadams.com)  
Philosophy: "Ship Code. Stay Human."
