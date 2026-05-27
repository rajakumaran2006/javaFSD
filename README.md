# Day 1 Front-End Exercises: HTML5 & CSS3
## Theme: Local Community Event Portal

This repository contains two fully resolved, professionally designed modules submitted for the **Day 1 College Group Exercises**. Both projects focus on the theme **"Local Community Event Portal"** and are designed with modern, clean, semantic markup and premium CSS3 styling rules.

---

## Project Architecture

```
/Users/raja/javaFSD/
├── HTML5-Exercises/
│   ├── index.html        # Interactive Event Portal implementing HTML5 APIs & Event Handlers
│   └── help.html         # External FAQ help document linked to navigation
├── CSS3-Exercises/
│   ├── index.html        # Clean, modular markup for the styled event dashboard
│   ├── styles.css        # Pristine, formatted external stylesheet with section labels
│   └── help.html         # CSS3-styled Help Desk using modern visual attributes
└── README.md             # Review guide and exercise roadmap (this document)
```

---

## Module 1: HTML5 Exercises (`/HTML5-Exercises`)

Designed to satisfy the **HTML5 Exercises** assignment requirements using native HTML5 tags and secure browser APIs.

### Covered Exercises & Implementations:
1. **Semantic Foundation (`Task 1`)**: Complete structure using modern semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) labeled with human-written HTML comments.
2. **Smooth Navigation & External Links (`Task 2`)**: Direct jump-links (`#welcome`, `#events`, `#register`, `#mapping`) and a separate `help.html` page opened securely in a new tab (`target="_blank"`).
3. **Banner Promos & Emphases (`Task 3`)**: Integrated `#welcomeBanner` styled with a deep-blue gradient, inline-styled promotional highlights (`bold` and `red`), and `.highlight` selector labels.
4. **Grid-Like Image Gallery Table (`Task 4`)**: A beautiful 2-row, 3-column event photo gallery table incorporating proper `alt` descriptions, hover title attributes, custom border classes, and sub-captions.
5. **Autofocus Event Registration (`Task 5`)**: Complete client-side input validations using standard HTML5 tags (e.g. `type="email"`, `type="date"`, `type="tel"`). Form input automatically highlights and starts on the "Full Name" input box (`autofocus`).
6. **Robust Interactive Event Handlers (`Task 6`)**:
   * **`onblur`**: Triggers immediate pattern validation on the phone number input box, verifying if the user matches the requested phone layout (`123-456-7890`).
   * **`onchange`**: Evaluates categories in the Event Type selector box and immediately calculates the registration fee in a styled banner.
   * **`onclick`**: Emits operational audits to the console log on submission attempts.
   * **`ondblclick`**: Enlarges gallery thumbnails into a custom high-resolution lightbox popup window.
   * **`onkeyup`/`onkeydown`**: Provides a live character counter on the special requirements text field, capping entries at 250 characters.
7. **Promo Video & Before-Unload Hooks (`Task 7`)**: Features a clean high-definition video player that outputs status reports when `oncanplay` fires. An `onbeforeunload` listener detects unsaved keystrokes in the form and warns the user prior to leaving.
8. **LocalStorage Preference Cache (`Task 8`)**: Saves the selected event category preference inside `localStorage`. Upon page reload, the script restores the choice. A "Reset Saved Preferences" button wipes both local and session storage.
9. **High-Accuracy Geolocation (`Task 9`)**: Includes a "Find Nearby Events" widget querying the secure browser Geolocation sensor with high-accuracy parameters and comprehensive error feedback (for timeouts or permission blocks).
10. **Console Logging (`Task 10`)**: Embedded semantic log reports inside the developer console for easy inspection and debugging.

---

## Module 2: CSS3 Exercises (`/CSS3-Exercises`)

Designed to satisfy the **CSS3 Exercises** assignment requirements using advanced design systems, modern grids, responsiveness, and fluid layouts.

### Covered Exercises & Implementations:
1. **Three Inclusion Methods (`Task 1`)**: Incorporates inline text color styling, embedded/internal `<style>` backgrounds, and a linked external `styles.css` sheet.
2. **Indented CSS Clean Layout (`Task 2`)**: High-quality formatted syntax inside `styles.css` using consistent tab indentation and clear segment dividers (e.g. `/* --- Typography --- */`).
3. **Pristine Selector Priority (`Task 3`)**: Implements:
   * **Universal Reset (`*`)** for zero margin/padding bounds.
   * **Element Selector (`h2`)** for elegant section headers.
   * **ID Selector (`#mainHeader`)** for styling the primary banner block.
   * **Class Selector (`.eventCard`)** to lay out individual card components.
   * **Grouping Selector (`h3, p`)** for uniform text colors and spacing.
4. **Rich Visual Backgrounds & Gradients (`Task 4`)**: Employs warm linear gradients for text headers, translucent RGBA background shading, and a body background image texture with a fallback color.
5. **Modern Typography (`Task 5`)**: Loads the premium Google Font **Outfit** via `@import` styling, editing sizes, weights, heights, tracking (letter-spacing), and case states.
6. **Pseudo-Class Link Control (`Task 6`)**: Custom navigation buttons with specific `:link`, `:visited`, `:hover`, and `:active` rules. Bullet dots are removed and replaced with balanced margins.
7. **Premium Table Data (`Task 7`)**: Uses a table layout styled with collapsed borders, centered alignment, vertical padding, and custom `nth-child(even)` row striping for clean visual scanning.
8. **Interactive Box Model Sandbox (`Task 8`)**: Features borders, paddings, margins, and highlight outlines on focused forms. Includes a live interactive playground displaying the behavioral differences between `visibility: hidden` and `display: none`.
9. **Newspaper Gazette Columns (`Task 9`)**: A community section styled using multi-column properties (`column-count: 2`, `column-gap: 30px`, and `column-rule`).
10. **Responsive Styling & Viewports (`Task 10`)**: Media queries targeting screens `< 768px`. The layout dynamically switches from a 3-column Grid to a vertical Flexbox stack, shrinking images and typography relative to the screen.

---

## How to Run & Verify

1. **Prerequisites**: No special servers are required! The projects run as pure, modern client-side HTML5/CSS3/JS pages.
2. **Reviewing**: 
   * Simply double-click `index.html` inside `HTML5-Exercises/` or `CSS3-Exercises/` to open them directly in Google Chrome.
   * Open the Chrome Developer Tools (`Cmd+Option+I` on Mac or `Ctrl+Shift+I` on Windows) and select the **Console** tab to view the live log traces.
   * Toggle **Device Mode** in the Inspector to test the responsive styling.
