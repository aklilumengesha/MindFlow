# 🌊 MindFlow – Modern AI Chat Landing Page

A modern, responsive landing page built with React.js, Vite, and Tailwind CSS. Features stunning animations, parallax effects, and a clean, modular architecture.

## ⚙️ Tech Stack

- **Vite**: Fast build tool for modern web projects
- **React.js**: Component-based UI library
- **Tailwind CSS**: Utility-first CSS framework
- **React Router**: Client-side routing
- **React Just Parallax**: Smooth parallax effects
- **Scroll Lock**: Scroll behavior control

## 🔋 Features

- **Beautiful Sections**: Hero, services, features, collaboration, roadmap, pricing, footer, header
- **Parallax Animations**: Mouse and scroll-triggered effects
- **Complex UI Geometry**: Intricate shapes, grids, and lines using Tailwind CSS
- **Latest UI Trends**: Bento grids, gradients, and modern layouts
- **Responsive Design**: Works seamlessly across all devices
- **Reusable Components**: Modular and easy to extend
- **Code Architecture**: Clean, maintainable, and scalable

## 🚀 How to Run

### Prerequisites

- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/)

### Setup

```bash
cd "landing page"
npm install
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
npm run preview
```

## 📂 Project Structure

```
mindflow/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   ├── svg/              # SVG React components
│   │   ├── benefits/         # Benefits section images
│   │   ├── collaboration/    # Collaboration section images
│   │   ├── hero/             # Hero section images
│   │   ├── notification/     # Notification images
│   │   ├── pricing/          # Pricing section images
│   │   ├── roadmap/          # Roadmap section images
│   │   ├── services/         # Services section images
│   │   ├── socials/          # Social media icons
│   │   └── index.js          # Asset exports
│   ├── components/
│   │   ├── design/           # Design-specific components
│   │   ├── Benefits.jsx
│   │   ├── Button.jsx
│   │   ├── Collaboration.jsx
│   │   ├── CompanyLogos.jsx
│   │   ├── Footer.jsx
│   │   ├── Generating.jsx
│   │   ├── Header.jsx
│   │   ├── Heading.jsx
│   │   ├── Hero.jsx
│   │   ├── Notification.jsx
│   │   ├── Pricing.jsx
│   │   ├── PricingList.jsx
│   │   ├── Roadmap.jsx
│   │   ├── Section.jsx
│   │   ├── Services.jsx
│   │   └── Tagline.jsx
│   ├── constants/
│   │   └── index.js          # App constants and data
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🧩 Components Overview

- **Section.jsx**: Layout wrapper with decorative elements
- **Button.jsx**: Customizable button with SVG borders
- **Heading.jsx**: Section heading with optional tagline
- **Header.jsx**: Responsive navigation with mobile menu
- **Hero.jsx**: Hero section with parallax effects
- **Benefits.jsx**: Feature cards with hover effects
- **Collaboration.jsx**: Circular app integration showcase
- **Services.jsx**: AI features with chat mockups
- **Pricing.jsx**: Three-tier pricing cards
- **Roadmap.jsx**: Project timeline with status indicators
- **Footer.jsx**: Social media links and copyright

## 🎨 Customization

### Update Content

Edit `src/constants/index.js` to change:
- Navigation links
- Feature descriptions
- Pricing tiers
- Roadmap items
- Social media links

### Modify Styles

- **Colors**: Update `tailwind.config.js`
- **Fonts**: Modify `src/index.css`
- **Components**: Edit individual component files

### Replace Assets

Add or replace images in `src/assets/` directories and update imports in `src/assets/index.js`

## 📝 License

This project is open source and available for personal and commercial use.

## 🙏 Acknowledgments

Built with modern web technologies and best practices for optimal performance and user experience.

---

**Happy Coding!** 🚀
