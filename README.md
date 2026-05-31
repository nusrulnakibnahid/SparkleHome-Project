<div align="center">

# ✨ SparkleHome
### Professional Cleaning Service — Landing Page

<br/>

[![Webflow](https://img.shields.io/badge/Webflow-146EF5?style=for-the-badge&logo=webflow&logoColor=white)](https://webflow.com)
[![CMS](https://img.shields.io/badge/Webflow_CMS-Powered-146EF5?style=for-the-badge&logo=webflow&logoColor=white)](https://webflow.com/cms)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![MIT License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br/>

**A modern, fully responsive CMS-powered landing page for a professional cleaning service company.**
*Built with Webflow CMS — no custom backend, no build tools, fully visual and content-manageable.*

<br/>

[🔴 Live Demo](https://sparkhome-project.webflow.io/) &nbsp;·&nbsp; [📸 Screenshots](#-screenshots) &nbsp;·&nbsp; [🚀 Getting Started](#-getting-started) &nbsp;·&nbsp; [🎨 Style Guide](#-style-guide) &nbsp;·&nbsp; [🤝 Contributing](#-contributing)

<br/>

</div>

---

## 📋 Table of Contents

- [About The Project](#-about-the-project)
- [Built With Webflow CMS](#-built-with-webflow-cms)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Style Guide](#-style-guide)
- [Screenshots](#-screenshots)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🏠 About The Project

**SparkleHome** is a fully responsive, CMS-powered landing page for a professional cleaning service business — built entirely in **Webflow**. Designed with conversion in mind, the site showcases services, team members, pricing packages, customer reviews, and a quote request form — all wrapped in a clean, trustworthy brand identity.

> *"Professional cleaning you can trust."*

This project leverages **Webflow's visual builder and CMS collections**, meaning all content (team members, services, reviews, pricing, FAQs, and service areas) is managed through the Webflow CMS Editor — no code editing required to update content.

Whether you're a designer looking to learn Webflow CMS architecture, or a business owner adapting this template — SparkleHome is structured, scalable, and easy to maintain.

---

## 🌐 Built With Webflow CMS

This is **not a static HTML project**. It is a fully CMS-driven site built on the [Webflow](https://webflow.com) platform. Here's what that means:

| Concept | Details |
|---|---|
| **Platform** | [Webflow](https://webflow.com) — visual no-code/low-code web builder |
| **CMS Collections** | Dynamic content managed via Webflow CMS (team, reviews, services, FAQs, pricing) |
| **Hosting** | Hosted on Webflow's CDN infrastructure |
| **Designer** | Layout and styling done in Webflow Designer (visual CSS) |
| **Editor** | Non-technical content updates done in Webflow Editor |
| **Export** | HTML/CSS/JS can be exported from Webflow for self-hosting (paid plan required) |
| **Interactions** | Animations and interactions built using Webflow Interactions 2.0 |

> 💡 **To clone or edit this project**, you need a Webflow account. Use the **"Make a Copy"** link (if published as a template) or request access from the project owner.

---

## ✨ Features

| Section | Description |
|---|---|
| 🎯 **Hero** | Bold headline with CTA button and trust badges (4.9★ rating, 100% satisfaction) |
| 🧹 **Services Grid** | House Cleaning, Office Cleaning, Deep Cleaning, Move-In/Move-Out |
| 📊 **Stats** | 99% client satisfaction, 250+ active clients |
| 🔁 **Marquee Banner** | Animated scrolling keywords — Vacuuming · Cleaning · Residential · Corporate · Reliable |
| 💰 **Pricing** | Basic / Standard / Premium tiered pricing cards |
| 👥 **Team** | CMS-powered staff profiles with social media links |
| ⭐ **Reviews** | CMS-powered testimonials with star ratings and reviewer photos |
| 📍 **Service Areas** | CMS-driven local area coverage list |
| ❓ **FAQ** | Expandable accordion — content editable from CMS |
| 📬 **Quote Form** | Name, Email, Phone, Message fields with submit CTA |
| 📱 **Responsive** | Fully optimized for mobile, tablet, and desktop via Webflow breakpoints |
| 🎬 **Interactions** | Scroll-triggered animations and hover effects via Webflow Interactions 2.0 |

---

## 🛠 Tech Stack

| Technology | Role |
|---|---|
| **Webflow Designer** | Visual layout builder — all HTML structure and CSS styling |
| **Webflow CMS** | Content management for team, services, reviews, FAQs, pricing, service areas |
| **Webflow Interactions 2.0** | Scroll animations, hover effects, marquee, accordion behavior |
| **Webflow Hosting** | CDN-hosted deployment with SSL |
| **Custom CSS** | Additional fine-tuned styles added via Webflow's Custom Code panel |
| **Custom JS** | Minor enhancements added via Webflow's `<head>` / `<body>` embed blocks |
| **Google Fonts** | Typography (loaded via Webflow font settings) |
| **Font Awesome** | Icon library embedded via CDN |

---

## 🗂 Webflow CMS Collections

The following **CMS Collections** power the dynamic content on this site:

```
📦 Webflow CMS Collections
│
├── 🧹 Services          → Name, Icon, Short Description, Detail Page (optional)
├── 👥 Team Members      → Name, Role, Photo, Facebook, Instagram links
├── ⭐ Testimonials      → Reviewer Name, Avatar, Star Rating, Review Text
├── 💰 Pricing Plans     → Plan Name, Price, Feature List, CTA Label, Highlighted?
├── ❓ FAQs              → Question, Answer
└── 📍 Service Areas     → Area Name, City/Region
```

All collections are editable from the **Webflow Editor** without touching the Designer.

---

## 📁 Project Structure

> Since this is a Webflow CMS project, there is no traditional file-based project structure. Below is the logical structure of the site inside Webflow:

```
Webflow Project: SparkleHome
│
├── Pages/
│   └── Home (index)            # Main landing page
│
├── CMS Collections/
│   ├── Services
│   ├── Team Members
│   ├── Testimonials
│   ├── Pricing Plans
│   ├── FAQs
│   └── Service Areas
│
├── Symbols (Reusable Components)/
│   ├── Navbar
│   ├── Footer
│   ├── Service Card
│   ├── Pricing Card
│   ├── Team Card
│   └── Review Card
│
├── Assets/
│   ├── Images (hero, team, services, reviews)
│   └── Fonts (via Google Fonts)
│
└── Global Settings/
    ├── Typography
    ├── Colors
    └── Custom Code (head & body embeds)
```

---

## 🚀 Getting Started

### Option 1 — View the Live Site

Simply visit the live demo:
👉 **[https://sparkhome-project.webflow.io/](https://sparkhome-project.webflow.io/)**

---

### Option 2 — Clone to Your Webflow Account

> Requires a free or paid [Webflow account](https://webflow.com/pricing).

1. Open the project's **Webflow share link** (request from the author if not public)
2. Click **"Open in Webflow"** or **"Make a Copy"**
3. The project — including CMS schema and all styles — will be cloned to your workspace
4. Go to **CMS → Collections** to edit your content
5. Publish via **Webflow Hosting** or export HTML/CSS/JS (paid plan)

---

### Option 3 — Use the Exported HTML (Self-Hosting)

If exported from Webflow (requires a paid Webflow plan):

```bash
# 1. Export the project from Webflow Designer → Export Code
# 2. Unzip the exported files
# 3. Serve locally

npx serve .
# or
python -m http.server 5500
```

Then open → `http://localhost:5500`

> ⚠️ Note: Exported HTML is static — CMS dynamic content will be baked in at export time and won't auto-update. For live CMS, use Webflow Hosting.

---

## 🎨 Style Guide

This style guide documents all visual decisions in the project. Use it to ensure consistency when editing in Webflow Designer or adding custom code.

---

### 🎨 Color Palette

| Swatch | Name | Hex Code | Usage |
|:---:|---|---|---|
| ![Primary Blue](https://img.shields.io/badge/-%231A73E8-1A73E8?style=flat-square) | **Primary Blue** | `#1A73E8` | Buttons, links, headings, nav |
| ![Accent Yellow](https://img.shields.io/badge/-%23FFD600-FFD600?style=flat-square) | **Accent Yellow** | `#FFD600` | Highlights, badges, marquee strip, CTA hover |
| ![Success Green](https://img.shields.io/badge/-%2300C853-00C853?style=flat-square) | **Success Green** | `#00C853` | Checkmarks, trust indicators |
| ![Deep Navy](https://img.shields.io/badge/-%230D1B2A-0D1B2A?style=flat-square) | **Deep Navy** | `#0D1B2A` | Footer background, dark sections |
| ![Dark Text](https://img.shields.io/badge/-%23222222-222222?style=flat-square) | **Dark Text** | `#222222` | Primary body copy |
| ![Medium Gray](https://img.shields.io/badge/-%23666666-666666?style=flat-square) | **Medium Gray** | `#666666` | Subtext, placeholders, meta |
| ![Light Gray](https://img.shields.io/badge/-%23F5F7FA-F5F7FA?style=flat-square) | **Light Gray** | `#F5F7FA` | Alternating section backgrounds |
| ![Pure White](https://img.shields.io/badge/-%23FFFFFF-FFFFFF?style=flat-square) | **White** | `#FFFFFF` | Card backgrounds, hero overlay |

> In Webflow, these are saved as **Global Swatches** under **Style Guide → Colors** in the Designer.

---

### 🔤 Typography

```
Headings  → Poppins   (Bold 700, SemiBold 600)
Body      → Open Sans (Regular 400, Medium 500)
```

| Element | Font | Size | Weight | Color |
|---|---|---|---|---|
| H1 (Hero) | Poppins | 48–64px | 700 | `#FFFFFF` |
| H2 (Section Title) | Poppins | 32–40px | 700 | `#222222` |
| H3 (Card Title) | Poppins | 20–24px | 600 | `#222222` |
| Body Text | Open Sans | 15–16px | 400 | `#666666` |
| Button Label | Poppins | 14–16px | 600 | `#FFFFFF` / `#222222` |
| Badge / Tag | Open Sans | 12px | 600 | contextual |

---

### 📐 Spacing System

All spacing follows an **8pt grid**. In Webflow, set these as **CSS variables** via Custom Code or use consistent values in the spacing panel:

| Token | Value | Usage |
|---|---|---|
| `--space-xs` | `8px` | Icon gaps, inline padding |
| `--space-sm` | `16px` | Button padding, small gaps |
| `--space-md` | `24px` | Card padding, form fields |
| `--space-lg` | `48px` | Section inner padding |
| `--space-xl` | `80px` | Section vertical spacing |
| `--space-xxl` | `120px` | Hero top/bottom padding |

---

### 🔘 Button Styles

| Variant | Background | Text | Border | Use Case |
|---|---|---|---|---|
| **Primary** | `#1A73E8` | `#FFFFFF` | none | Main CTA, Get Free Quote |
| **Secondary** | `#FFD600` | `#222222` | none | Accent actions, hover states |
| **Outline** | transparent | `#1A73E8` | `2px solid #1A73E8` | Secondary actions |
| **Ghost** | transparent | `#FFFFFF` | `2px solid #FFFFFF` | Hero / dark backgrounds |

```css
/* Button base — applied via Webflow class */
border-radius: 6px;
padding: 12px 28px;
font-weight: 600;
transition: all 0.3s ease;
cursor: pointer;
```

---

### 🃏 Card Style

```css
/* Webflow class: .card */
background: #FFFFFF;
border-radius: 12px;
padding: 32px 24px;
box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
transition: transform 0.3s ease, box-shadow 0.3s ease;

/* Hover state */
transform: translateY(-4px);
box-shadow: 0 8px 32px rgba(0, 0, 0, 0.12);
```

---

### 📱 Breakpoints (Webflow Responsive)

Webflow uses these built-in breakpoints — match them when writing any custom CSS:

| Webflow Breakpoint | Width | Layout |
|---|---|---|
| **Desktop** (default) | `> 991px` | Full layout, max-width 1200px container |
| **Tablet** | `768px – 991px` | 2-column grids, adjusted font sizes |
| **Mobile Landscape** | `480px – 767px` | Single/2-column, condensed spacing |
| **Mobile Portrait** | `< 479px` | Fully stacked, touch-friendly targets |

---

### 🖼 Image Guidelines

| Image | Recommended Size | Format | Notes |
|---|---|---|---|
| Hero background | `1920×1080px` min | `.webp` / `.jpg` | Dark overlay `rgba(0,0,0,0.5)` |
| Service card images | `600×400px` | `.webp` | Uploaded to Webflow Assets |
| Team photos | `300×300px` (square) | `.webp` / `.jpg` | Circular via `border-radius: 50%` |
| Review avatars | `60×60px` | `.webp` / `.jpg` | Circular crop |
| Logo | `SVG` preferred | `.svg` | For crisp rendering at all sizes |

---

### ✍️ Writing Style

- Use **sentence case** for headings — not Title Case Every Word
- Keep CTAs action-oriented: *"Get Your Free Quote"*, *"Book Now"*, *"Learn More"*
- Italics used for the brand tagline only
- Keep descriptions under 20 words per card
- Avoid jargon — write for a general, non-technical audience

---

## 📸 Screenshots

<div align="center">

<img width="1920" height="10669" alt="SparkleHome Full Page Screenshot" src="https://github.com/user-attachments/assets/ff8747a7-c3cb-4f12-ac23-53b49d547b01" />

*Full-page view of the SparkleHome Webflow landing page*

</div>

---

## 🤝 Contributing

Since this is a Webflow CMS project, contributing works differently from a typical code repository.

### For Content Changes
- Request Editor access from the project owner
- Use the **Webflow Editor** to update CMS content (team, reviews, services, etc.)
- Publish changes directly from the Editor

### For Design / Layout Changes
1. Request **Designer access** or clone the project to your Webflow workspace
2. Make changes in **Webflow Designer**
3. Share a **Read-Only link** or exported diff for review
4. Coordinate publishing with the project owner

### For Custom Code Contributions (JS / CSS)
1. Fork this repo (for exported HTML reference)
2. Create a feature branch
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit your changes
   ```bash
   git commit -m "feat: improve mobile nav behavior"
   ```
4. Push and open a Pull Request

### Commit Message Convention

```
feat:     New feature or section
fix:      Bug or layout fix
style:    Visual/CSS changes only
docs:     README or documentation update
content:  CMS content changes
chore:    Maintenance
```

---

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for full details.

---

## 📬 Contact

<div align="center">

**Nusrul Nakib Nahid**

[![GitHub](https://img.shields.io/badge/GitHub-nusrulnakibnahid-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nusrulnakibnahid)
[![Webflow](https://img.shields.io/badge/Live_Site-Webflow-146EF5?style=for-the-badge&logo=webflow&logoColor=white)](https://sparkhome-project.webflow.io/)

Project Link: [https://github.com/nusrulnakibnahid/sparklehome](https://github.com/nusrulnakibnahid/sparklehome)

Live Site: [https://sparkhome-project.webflow.io/](https://sparkhome-project.webflow.io/)

</div>

---

<div align="center">

Built with ❤️ using [Webflow](https://webflow.com) by [nusrulnakibnahid](https://github.com/nusrulnakibnahid)

<br/>

⭐ **If you found this useful, please give it a star!** ⭐

</div>
