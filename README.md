# 🌿 Aqiqah Invitation Pages

> A monorepo of digital Aqiqah invitation pages built with Next.js and TypeScript — one for a baby boy, one for a baby girl.

[![GitHub Repo](https://img.shields.io/badge/GitHub-aqiqah--invitation-181717?style=for-the-badge&logo=github)](https://github.com/zakiulfahmijailani/aqiqah-invitation)
[![Next.js](https://img.shields.io/badge/Next.js-14+-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](./LICENSE)

---

## 📖 About

**Aqiqah** is an Islamic tradition of welcoming a newborn child by sacrificing livestock and hosting a celebration to express gratitude. This repository is a collection of beautifully designed **digital invitation pages** for Aqiqah ceremonies.

Two themed versions are included:

- 🧒 **Boy version** — A majestic blue and gold theme for **Muhammad Izhan**
- 👧 **Girl version** — An elegant pink and rose theme for **Rumaisha**

Each invitation is a fully standalone Next.js application with animated components, responsive layouts, and support for RSVP features.

---

## 🎬 Demo

https://github.com/user-attachments/assets/26c24393-cafa-4347-a041-87c520f0e344

---

## 📦 Projects

| App | Theme | Baby |
| --- | --- | --- |
| `apps/izhan` | 🔵 Boy (blue/gold) | Muhammad Izhan |
| `apps/rumaisha` | 🩷 Girl (pink/rose) | Rumaisha |

---

## 🛠 Tech Stack

| Technology | Purpose |
| --- | --- |
| [Next.js 14+](https://nextjs.org/) | React framework with App Router |
| [TypeScript](https://www.typescriptlang.org/) | Type-safe development |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first styling |

---

## 🚀 Getting Started

### Prerequisites

- **Node.js** 18+ ([download](https://nodejs.org/))
- **npm** 9+

### Installation

```bash
# Clone the repository
git clone https://github.com/zakiulfahmijailani/aqiqah-invitation.git
cd aqiqah-invitation

# Install all dependencies (workspaces)
npm install
```

### Running Locally

```bash
# Run boy version (Izhan)
npm run dev:izhan

# Run girl version (Rumaisha)
npm run dev:rumaisha
```

### Building for Production

```bash
# Build a specific app
npm run build:izhan
npm run build:rumaisha

# Build all apps
npm run build:all
```

---

## 📁 Folder Structure

```
aqiqah-invitation/
├── apps/
│   ├── izhan/                # 🧒 Boy invitation (blue/gold theme)
│   │   ├── public/           #    Static assets (images, audio)
│   │   ├── src/
│   │   │   ├── app/          #    Next.js App Router pages
│   │   │   └── components/   #    React components
│   │   ├── package.json
│   │   └── tsconfig.json
│   │
│   └── rumaisha/             # 👧 Girl invitation (pink/rose theme)
│       ├── public/           #    Static assets (images, audio)
│       ├── src/
│       │   ├── app/          #    Next.js App Router pages
│       │   └── components/   #    React components
│       ├── package.json
│       └── tsconfig.json
│
├── docs/
│   ├── demo/                 # Demo videos / GIFs
│   └── screenshots/          # Screenshots for documentation
│
├── .gitignore
├── package.json              # Workspace root configuration
└── README.md
```

---

## 🤝 Contributing

Contributions are welcome! Each sub-app follows its own coding conventions. Feel free to open a pull request if you'd like to:

- Add new invitation themes
- Improve animations or UI components
- Fix bugs or improve performance
- Add new features (RSVP, photo galleries, etc.)

### Steps

1. Fork the repository
2. Create a feature branch (`git checkout -b feat/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feat/amazing-feature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

<p align="center">
  Made with ❤️ for celebrating new beginnings
</p>
