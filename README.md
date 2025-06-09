# 🌐 Crystalline — Science-Centric Landing Page

Crystalline is a clean, modern landing page designed using **Tailwind CSS**. Ideal for educational platforms, it blends clarity with customization. The design emphasizes readability, minimalist aesthetics, and an engaging user interface.

---

## ✨ Key Features

### 📌 1. **Sticky, Glass-Like Header**

* Uses `sticky`, `top-0`, `bg-white/20`, and `backdrop-blur` to create a semi-transparent floating header.
* Responsive padding and layout with `p-4 sm:p-5.5 flex justify-between`.
* Elegant button with custom shadows (`.blueShadow`) and smooth hover animation via pseudo-elements (`.lightShadow`).

---

### 🧠 2. **Custom Font Pairing**

* Title font: 🎮 **Press Start 2P** — for a pixel-art, retro academic vibe.
* Body font: 🧑‍💻 **JetBrains Mono** — clean monospace for maximum clarity.
* Both fonts loaded via Google Fonts with proper fallbacks.

---

### 🗺 3. **Background Grid**

* Custom `.bgGrid` class to simulate a graph-paper background using CSS gradients.
* Tailored to match a light blue theme with soft contrast (`#eef2ff` lines).

---

### ⭐ 4. **Dynamic Star Rating**

* Five-star system built using **Font Awesome** icons.
* Partial fill (e.g., 4.6 stars) achieved via `absolute` positioning and `w-[40%]` overlay.
* Looks sharp, responsive, and elegant without JavaScript.

---

### 📊 5. **Responsive Design**

* Designed to look great across devices:

  * Text resizes via `sm:`, `md:`, `lg:` breakpoints.
  * Button layout shifts from column (`grid-cols-1`) to row (`sm:grid-cols-2`).
  * Margin and padding scales up on larger screens.

---

## 🧰 Customization Guide

Want to make it yours? Here's how:

### 🎨 Change Branding

* Update the `<h1>` inside the header for your brand name.
* Modify the favicon in the `<head>` or remove it.

### 🎯 Edit Call-to-Action (CTA)

* Change button text inside both `Book now` and `Get in touch`.
* Adjust colors via Tailwind classes: `bg-white`, `bg-sky-600`, `text-white`, etc.

### ✍ Change Fonts

* Edit the `link` tag inside `<head>` to use your preferred Google Fonts.
* Update the font stack in your CSS overrides (`font-family`) accordingly.

### 🌈 Customize the Color Theme

* Change the grid line color in `.bgGrid`.
* Adjust Tailwind utility classes like `text-sky-600`, `bg-white/60`, `text-amber-400`, etc.

---

## ⚙️ Dependencies

| Tool               | Purpose                        |
| ------------------ | ------------------------------ |
| \[Tailwind CSS]    | Utility-first CSS styling      |
| \[Google Fonts]    | Beautiful typography           |
| \[Font Awesome]    | Icon set for visual elements   |
| \[Vite (optional)] | Lightning-fast dev environment |

---

## 🚀 Live Demo

👉 [Crystalline](https://crystalline-science.netlify.app/)

---
