# Mintlify Website Clone

This project is a frontend clone of the **mintlify** marketing website, built using **HTML** and **CSS**.

<img width="1906" height="986" alt="image" src="https://github.com/user-attachments/assets/c8a5cdc2-6d0f-4467-b554-ce5e148eb1f0" />

---

## Recreated Sections

The following sections were recreated based on the original Cursor website structure:

- **Header / Navigation**
  - Logo, product name
  - Navigation links (Features, Enterprise, Pricing, Resources)
  - Sign in and Download buttons
  - Fixed header layout with glassmorphism effect

- **Hero Section**
  - Main headline and subtext
  - Primary CTA (Download for Windows)
  - Hero image visualization

- **Partners / Trust Section**
  - “Trusted by developers” text
  - Partner logo grid

- **Features Section**
  - Bento-grid style feature blocks
  - Interactive visual elements (stacks, workflows)
  - Accent links for feature exploration

- **Testimonials / Reviews**
  - Grid-based testimonial cards
  - Author avatars, names, and roles

- **Frontier Features**
  - Three-column feature cards
  - Headings, descriptions, and CTA links

- **Changelog**
  - Version tags
  - Release dates
  - Update descriptions

- **Highlights Overlay**
  - Recent highlights list
  - Research posts with descriptions and dates

- **Call To Action**
  - “Try Cursor now” section
  - Large headline with download button

- **Footer**
  - Product, Resources, Company, Legal, and Connect links
  - Copyright notice

---

## Fonts Used

- **Primary Display Font**
  - `Inter`
  - Used for headings, branding, and UI elements.

- **System Font Stack**
  - `system-ui, -apple-system, sans-serif`
  - Used for body text to ensure native performance and legibility.
## 🎨 Colors Used

The project uses a **Light Theme** color palette defined via **CSS variables** for consistency and easy theming.

### 🌤️ Background Colors

- **Main Background:** `#ffffff` (Clean White)
- **Surface / Cards:** `#f8f9fa` (Off-White)
- **Dark Elements:** `#0e0e0e`


### 📝 Text Colors

- **Primary Text:** `#0f172a` (Dark Slate)
- **Muted Text:**  
  `color-mix(in oklab, #0f172a 60%, transparent)`

- **Accent Color:** `#007a43` (Mint Green)

### 📐 Borders & Effects

- **Borders:** `#e2e8f0`
- **Shadows:** Soft drop shadows used on cards and floating elements

**CSS**

```css
:root {
  /* --- COLORS --- */
  /* Main Backgrounds */
  --bg-main: #ffffff;
  --bg-surface: #f8f9fa;
  --bg-dark: #0e0e0e;

  /* Text Colors */
  --text-main: #0f172a;
  --text-muted: color-mix(in oklab, var(--text-main) 60%, transparent);
  --text-accent: #007a43;
  --text-white: #ffffff;

  /* Borders & Effects */
  --border: #e2e8f0;
  --shadow-sm: 0 4px 12px rgba(0, 0, 0, 0.05);
  --shadow-lg: 0 20px 40px -10px rgba(0, 0, 0, 0.1);
}
```
