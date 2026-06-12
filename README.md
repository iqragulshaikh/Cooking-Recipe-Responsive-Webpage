Here is a clean, professional, and well-structured `README.md` file tailored specifically for your **Saffron & Sage** project. It is designed to match the high standards required by the DecodeLabs Industrial Training Track.

---

# Saffron & Sage // Responsive Culinary Journal

A clean, minimalist, and high-end editorial cooking recipe blog built to demonstrate responsive fluid layouts. This project is developed as part of **Project 2: Responsive Web Layout** for the DecodeLabs Industrial Training Track, focusing on the core philosophy that *"Content is Like Water."*

The application smoothly scales across mobile devices, tablets, and wide-screen desktop monitors using pure, native CSS architecture without relying on external UI frameworks.

---

## Features

* **Mobile-First CSS Architecture:** Base layout styling targets the mobile core first to ensure quick loading and minimal layout overhead on small devices, progressively scaling up for larger screens.
* **Pure CSS Responsive Drawer Menu:** A native mobile hamburger navigation bar that toggles into a sleek flyout menu without requiring JavaScript execution.
* **Fluid Alternating Grid Cards:** Implements a clean, horizontal split-screen display on desktop viewports that intelligently alternates image and text positioning for structural visual interest.
* **Premium Editorial Typography:** Utilizes a curated pairing of *DM Serif Display* for elegant article layouts and *Plus Jakarta Sans* for clean, modern interface readability.
* **Flexible Media Elements:** Integrated fluid container architecture using `object-fit: cover` to ensure images shrink or expand dynamically without distortion.

---

## Visual Identity & Color System

The visual theme follows a warm, cozy culinary magazine design system:

* **Background Cream (`#FAF7F2`):** A soft, natural alabaster surface that reduces eye strain.
* **Velvet Sage (`#2C3E35`):** A deep, rich organic tone utilized for bold structural headers, logos, and status states.
* **Toasted Saffron (`#E07A5F`):** A warm, high-contrast terracotta accent color for user interaction focal points, buttons, and badges.
* **Charcoal Smoke (`#333333`):** High-contrast text color ensuring maximum readability.

---

## Project Directory Structure

```text
├── index.html          # Main document skeleton with semantic HTML5 structuring
├── style.css           # Clean stylesheet featuring progressive media queries
├── logo.png            # Navigation branding icon asset
├── img1.jpg            # Optimized visual asset for Creamy Tuscan Garlic Chicken
└── img2.jpg            # Optimized visual asset for Classic Warm Apple Crisp

```

---

## Responsive Breakpoints Built In

The layout applies structural breakpoints tailored around content flow limits rather than strict hardware device frames:

1. **Mobile Core Base Style (`0px` to `767px`):** Stacks all content cards into a clear, single-column alignment for easy one-handed mobile scrolling.
2. **Adaptive Layout Engine (`768px` and up):** Transforms navigation elements from an interactive side drawer into a clean top-row layout. Activates the two-column side-by-side flexbox alignment for main recipe content cards.
3. **Desktop High-Res Layer (`1024px` and up):** Enforces a maximum container layout width boundaries (`1050px`) to preserve optimal line lengths for text readability on ultra-wide screens.

---

## How to Run the Project Local Preview

1. Clone or download this project folder onto your machine.
2. Ensure your image assets (`logo.png`, `img1.jpg`, and `img2.jpg`) are saved inside the exact same root directory.
3. Open `index.html` inside any standard modern web browser (Google Chrome, Firefox, Safari, or Microsoft Edge).
4. Open your browser's Developer Tools (`F12`), toggle Device Toolbar mode, and adjust your display canvas boundaries to preview the seamless fluid scaling.

---

## 📝 Compliance Verification

* [x] Included mandatory `<meta name="viewport" content="width=device-width, initial-scale=1.0">` tag to eliminate physical viewport structural errors.
* [x] Utilized standard relative units (`rem`, `em`, and percentages `%`) for flexible fluid widths and type systems.
* [x] Implemented native CSS media queries to adapt cross-device user experiences gracefully.
