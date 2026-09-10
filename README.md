# KateVR — KAT Loco VR Locomotion Landing Page

A responsive landing page for **KAT Loco** — a VR locomotion system that enables natural walking, running, and movement in virtual reality. The project combines an expressive product presentation, interactive scenarios, and clean adaptive layout for various device types.

## Demo

[Open live demo](https://your-username.github.io/layo43ut_KateVR/)

> Replace the link above with the actual published project URL.

## About the Project

The landing page showcases KAT Loco capabilities and guides users through key product benefits: from immersive presentation and use cases to technical specifications, FAQ, and contact form.

The interface is crafted with attention to visual delivery: contrast color palette, branded graphics, animations, refined typography, and thoughtful composition preserve the high-tech VR product feel across all screen sizes.

## Features

- **Responsive Interface** — correct display on wide desktop screens, tablets, and mobile devices starting from 320px.
- **Hero Section** with main product message, price, video play button, and image slider.
- **Interactive Navigation** — anchor links to sections, adaptive menu, and separate language selector.
- **Sliders & Cards** — showcase product images, use cases, and KAT Loco advantages.
- **Technical Specifications** — visual block with interactive elements detailing sensors, battery, and wireless connectivity.
- **Video & Animations** — video presentation modal, animated graphic elements, and smooth visual effects (including tsparticles).
- **Utility Sections** — FAQ, help center, contacts, and feedback form with field validation.
- **Accessible Structure** — semantic markup, labels for interactive elements, and alt texts for images.

## Tech Stack

The project is built on a modern frontend stack:

- **HTML5** — semantic page structure;
- **SCSS / Sass** — modular styles, variables, mixins, and BEM-block organization;
- **TypeScript** — logic for sliders, menus, modals, forms, and animations;
- **Vite** — fast development and production builds;
- **SVG & Responsive Images** — branded graphics, icons, and responsive content;
- **BEM** — clear and scalable class naming methodology;
- **tsparticles** — particle animation effects;
- **Google Fonts (Inter)** — typography;
- **Jest** — testing utilities;
- **Prettier, Stylelint, LintHTML, BEMlint** — automated code style enforcement and consistency.

## Project Structure

```text
.
├── index.html
├── package.json
├── src/
│   ├── images/       # images, icons, and graphic assets
│   ├── scripts/      # TypeScript interface logic
│   │   ├── animation-about-us.ts
│   │   ├── animation-play-button.ts
│   │   ├── animation-slider.ts
│   │   ├── animation-tech-specs.ts
│   │   ├── button-play-video.ts
│   │   ├── dropdowns.ts
│   │   ├── forms.ts
│   │   ├── main.ts
│   │   ├── lib/
│   │   └── myUtils/
│   └── styles/       # SCSS styles, utilities, and BEM blocks
│       ├── _fonts.scss
│       ├── _typography.scss
│       ├── _utils.scss
│       ├── main.scss
│       ├── normalize.scss
│       ├── blocks/
│       └── utils/
└── README.md
```

## Getting Started

Requires **Node.js** and **npm**.

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm start
   ```

3. Open the project in your browser at the URL shown in the terminal.

## Build & Lint

Production build:

```bash
npm run build
```

Lint styles, formatting, and markup:

```bash
npm run lint
```

Run full check including tests:

```bash
npm test
```

## Available Scripts

| Script | Description |
|--------|-------------|
| `npm start` | Start Vite dev server |
| `npm run build` | Production build  |
| `npm run lint` | Run stylelint, prettier |
| `npm run test` | Full lint + test suite |
| `npm run format` | Format code with Prettier |
| `npm run style-format` | Fix SCSS with Stylelint |
| `npm run deploy` | Deploy |

## Code Quality Tools

- **Stylelint** with `stylelint-scss` — SCSS linting
- **Prettier** — code formatting
- **LintHTML** — HTML validation
- **BEMlint** — BEM methodology compliance
- **Jest** + **jsdom** — unit testing environment

## License

Distributed under the **GPL-3.0** license. See `LICENSE` for details.

---

*Built with ❤️ as a portfolio project demonstrating modern frontend development practices.*
