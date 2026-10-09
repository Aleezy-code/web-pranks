# 🎭 Web Pranks — Unleash the Chaos!

<p align="center">
  <img src="public/jester-320.png" alt="Web Pranks Mascot" width="150" />
</p>

<h3 align="center">Turn Ordinary Web Pages Into Extraordinary Pranks ✨</h3>

<p align="center">
  A playful, interactive web experience powered by React, TypeScript, Phaser 3, and physics-based animations.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-6-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Phaser-3-8B5CF6?style=for-the-badge" alt="Phaser 3" />
  <img src="https://img.shields.io/badge/Vite-Powered-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/License-See%20Repository-lightgrey?style=for-the-badge" alt="License" />
</p>

---

## 🌟 About the Project

**Web Pranks** is a fun, browser-based visual effects playground that transforms ordinary web pages into interactive chaos.

Imagine a wrecking ball smashing through a page, website elements falling under gravity, a birthday celebration bursting onto the screen, or a retro arcade invasion taking over your view.

That's the experience Web Pranks is designed to deliver!

The project combines modern frontend development with animation, physics simulations, and playful interactive effects to create an entertaining web experience.

> 🎯 **The idea:** Big visual chaos, playful creativity, and no intentional changes to the original website's content on its actual server.

**[webfun.click](https://webfun.click/)** — Prank any website with wild visual effects. Watch CNN get smashed by a wrecking ball. Make Reddit fall to pieces. Throw a surprise birthday party on your least-favorite homepage.


## 🎮 Features

| Feature | Description |
|---|---|
| 💥 Wrecking Ball | A physics-inspired wrecking ball effect that smashes page elements apart. |
| 🪂 All Fall Down | Watch webpage elements detach and fall under gravity. |
| 🎂 Happy Birthday | Add a festive birthday surprise with balloons, confetti, and a cake. |
| 👾 BTC Invaders | Experience a Bitcoin-themed, Space Invaders-inspired arcade effect. |
| 🦖 Dino Rampage | Explore a dinosaur-themed page destruction effect. |
| 🎨 Interactive Visuals | Enjoy animated scenes and playful visual transformations. |
| 🧩 Extensible Architecture | Add new prank effects using the project's effect module structure. |
| ⚛️ Modern Frontend | Built with React, TypeScript, and Vite. |

*Note: Available effects and browser behavior depend on the implementation, browser restrictions, and the target page.*

## 🛠️ Tech Stack

- **React** — Component-based user interface.
- **TypeScript** — Typed JavaScript for maintainable code.
- **Vite** — Fast development server and production build tooling.
- **Phaser 3** — Interactive 2D scenes and animation.
- **Matter.js** — Physics simulation support.
- **React Router** — Client-side navigation.
- **Bootstrap & React Bootstrap** — UI styling and components.
- **html2canvas** — Webpage rendering and capture support.
- **Netlify Functions** — Serverless function support.

## 🚀 Getting Started

Run the project locally and explore the code.

### Prerequisites

Install the following first:

- [Node.js](https://nodejs.org/) — preferably an LTS version.
- [Git](https://git-scm.com/).
- [pnpm](https://pnpm.io/installation).

### 1. Clone the Repository

```bash
git clone https://github.com/Aleezy-code/web-pranks.git
```

```bash
cd web-pranks
```

### 2. Install Dependencies

```bash
pnpm install
```

### 3. Start the Development Server

```bash
pnpm dev
```

Open the local URL printed in your terminal, usually:

`http://localhost:5173`

### 4. Create a Production Build

```bash
pnpm build
```

### 5. Preview the Production Build

```bash
pnpm preview
```

## 📂 Project Structure

```text
web-pranks/
├── public/
│   └── assets/             # Images, sounds, and game assets
├── src/
│   ├── layouts/            # Shared application layouts
│   ├── pageEffects/        # Individual prank effect modules
│   ├── pages/              # Application pages
│   ├── App.tsx             # Application routes
│   ├── App.css             # Application styling
│   ├── index.css           # Global styles
│   └── main.tsx            # Application entry point
├── netlify/
│   └── functions/          # Serverless functions
├── index.html
├── package.json
├── pnpm-lock.yaml
├── tsconfig.json
└── vite.config.ts
```

## 🧪 Available Scripts

| Command | Purpose |
|---|---|
| `pnpm dev` | Run the development server. |
| `pnpm build` | Build the production application. |
| `pnpm preview` | Preview the production build. |
| `pnpm lint` | Run ESLint checks. |

## 🧩 Want to Add Your Own Prank?

Web Pranks includes an effect-module architecture designed to make adding new visual effects easier.

1. Explore the existing modules in `src/pageEffects/`.
2. Study an existing effect that is similar to your idea.
3. Create a new TypeScript or JavaScript module.
4. Implement the effect using the project's `doPageEffect` convention.
5. Register the new effect in `src/pageEffects/modulelist.ts`.
6. Run the development server and test it.
7. Build the project and verify the effect before sharing your changes.

Each effect should follow the interfaces and conventions used by the existing project.

## 🔐 Responsible Use

Web Pranks is intended for entertainment, experimentation, and creative demonstrations.

- Use it only on websites you are authorized to test or demonstrate.
- Visual effects should not be represented as actual modifications to a website's server.
- Respect browser security restrictions and other websites' terms.
- Do not use the project to mislead people, disrupt services, or interfere with other users' sessions.

## 🗺️ Roadmap Ideas

Potential ideas for future development:

- [ ] Add more interactive prank effects.
- [ ] Introduce customizable animation settings.
- [ ] Improve accessibility and reduced-motion support.
- [ ] Add more responsive layouts.
- [ ] Expand the effect library with community contributions.
- [ ] Add preview images and demonstrations for individual effects.

These are possible future improvements, not claims that the features are already implemented.

## 🤝 Contributing

Have a creative prank idea?

Contributions, suggestions, bug reports, and improvements are welcome, subject to the repository owner's contribution guidelines.

1. Fork the repository.
2. Create a feature branch.
3. Make and test your changes.
4. Submit a pull request describing your improvement.

## 💖 Support the Project

If you enjoy this project, consider giving the repository a ⭐ on GitHub and sharing it with other developers.

Every bit of feedback helps inspire new ideas!

## 👩‍💻 Developer

**Created and shared by [Aleezy-code](https://github.com/Aleezy-code)**

Explore more projects on [GitHub](https://github.com/Aleezy-code?tab=repositories).

## 📜 License

Please check the repository's existing license and the licenses of its dependencies before redistributing or using this project commercially. No specific license is asserted by this README.

---

<p align="center">
  <strong>🎭 Break the boring. Keep the fun. Let the pranks begin!</strong>
</p>
