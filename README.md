# 🍔 Knight Bite — Late Night Food Delivery Landing Page

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Responsive Design](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-orange?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **"Burgers worth making a mess for."**  
> A sleek, high-conversion, dark-themed responsive landing page for **Knight Bite**, a late-night cloud kitchen delivering cooked-to-order burgers, wraps, shakes, and loaded fries until 4 AM.

---

## 📸 Preview

```
┌─────────────────────────────────────────────────────────────┐
│  [🍔 Knight Bite]    Home  About  Franchise   [Order Now]   │
│─────────────────────────────────────────────────────────────│
│                                                             │
│   BURGERS WORTH MAKING A MESS FOR.                          │
│   Chicken and veg burgers, wraps, loaded fries & shakes     │
│   delivered to your door in under 40 minutes.               │
│                                                             │
│   [ Order Now → ]  [ App Store ]  [ Google Play ]           │
│                                                             │
│   ⏱ 40 min avg delivery    |   🌙 7 PM – 4 AM hours         │
│                                                             │
│─────────────────────────────────────────────────────────────│
│   ★ CHICKEN BURGERS · VEG BURGERS · LOADED FRIES · SHAKES   │
└─────────────────────────────────────────────────────────────┘
```

---

## ✨ Features

- 🌙 **Modern Dark Theme & Glassmorphism**: Built with modern aesthetic standards featuring deep dark tones (`#08080B`), subtle frosted glass headers (`backdrop-filter: blur(18px)`), and crisp borders.
- 📱 **100% Responsive & Mobile-First**: Seamless experience across mobile devices, tablets, and desktop displays with an interactive CSS toggle navigation drawer.
- ⚡ **Zero External Dependencies**: Pure HTML5 and vanilla CSS3 — ultra-fast load times with zero JavaScript bloat.
- 🔄 **Continuous Marquee Animation**: Dynamic smooth infinite scrolling ticker showcasing popular menu highlights.
- ⏱️ **Live Operations Indicator**: Prominently displayed kitchen status and operational schedule (7 PM – 4 AM).
- 📲 **App Showcase & Direct Downloads**: Dedicated badges and links for iOS App Store and Google Play Store apps.
- 🗺️ **"How It Works" & Story Showcase**: Step-by-step 3-stage delivery breakdown with statistics and story sections.
- 📸 **Instagram Grid & Social Feeds**: Visual image grid layout highlighting mouth-watering food media and social links.
- 📞 **Direct Contact & Order Actions**: Instant order redirects and click-to-call direct dial support.

---

## 🛠️ Technology Stack

| Layer | Technologies Used |
|---|---|
| **Structure** | HTML5 Semantic Elements (`<header>`, `<section>`, `<nav>`, `<footer>`) |
| **Styling** | Vanilla CSS3 (Custom Properties, Flexbox, CSS Grid, Media Queries, Keyframe Animations) |
| **Typography** | [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque), [Inter](https://fonts.google.com/specimen/Inter), [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) |
| **Icons & Media** | Inline SVGs & Optimized JPG/PNG Assets |

---

## 📁 Project Structure

```bash
knight-bite_new/
├── index.html          # Main landing page markup
├── style.css           # Complete responsive stylesheet & design system
├── README.md           # Project documentation
└── images/             # Visual assets and branding
    ├── logo-mark.png       # Brand emblem
    ├── insta_icon.png      # Social icons
    ├── facebook_icon.png
    ├── twitter_icon.png
    ├── linkedin_icon.png
    ├── youtube_icon.png
    ├── hero/               # Hero background imagery
    ├── food/               # Menu & story photography
    ├── franchise/          # Franchise page assets
    └── sections/           # Section banner & breaker images
```

---

## 🚀 Getting Started

No build tools, package managers, or compilers are required.

### 1. Clone or Download Repository
```bash
git clone https://github.com/your-username/knight-bite.git
cd knight-bite
```

### 2. Run Locally

#### Option A: Direct in Browser
Simply double-click [`index.html`](file:///Users/abhi/Downloads/knight-bite_new/index.html) or open it directly in any modern browser (Chrome, Edge, Firefox, Safari).

#### Option B: Using VS Code Live Server
1. Open the project folder in VS Code.
2. Right-click [`index.html`](file:///Users/abhi/Downloads/knight-bite_new/index.html).
3. Select **"Open with Live Server"**.

#### Option C: Local HTTP Server (Terminal)
```bash
# Using Python 3
python3 -m http.server 3000

# OR using Node.js npx
npx serve .
```
Visit `http://localhost:3000` in your web browser.

---

## 🎨 Design System & Palette

| Token | Value | Usage |
|---|---|---|
| **Background Primary** | `#08080B` | Body and primary backgrounds |
| **Text Primary** | `#F7F5F2` | Headings and high-emphasis body text |
| **Text Muted** | `#C9C6CF` | Subtitles, descriptions, nav links |
| **Border / Stroke** | `rgba(255, 255, 255, 0.08)` | Glass borders and dividers |
| **Glass Backdrop** | `rgba(8, 8, 11, 0.72)` | Sticky header blur container |

---

## 📱 Supported Pages & Navigation

- **Home (`index.html`)**: Main landing page with full feature walkthrough, ordering steps, and app links.
- **About (`about.html`)**: Brand story and kitchen philosophy *(Linked)*.
- **Franchise (`franchise.html`)**: Cloud kitchen partnership and franchise inquiries *(Linked)*.
- **Order Online**: Quick links redirecting to [Knight Bite Order Portal](https://order.knight-bite.com/).

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Made with ❤️ for night owls & burger lovers.</p>
