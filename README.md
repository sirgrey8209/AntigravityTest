# Divider Game

> A puzzle strategy defense game using division and subtraction mechanics

## 🎮 Game Overview

**Divider** is a mobile-optimized web game where players defeat enemies by strategically using numbered weapons to reduce enemy HP to exactly 0 through division and subtraction rules.

## 🚀 Play Now

- **Live Demo**: [GitHub Pages](https://sirgrey8209.github.io/DividerGame/) _(URL will be updated after repository rename)_

## ✨ Key Features

- **Unique Math-Based Combat**: Division and subtraction mechanics
- **Mobile Optimized**: Touch-friendly drag & drop controls
- **Progressive Gameplay**: Tutorial → World Map → Dungeons
- **Boss Battles**: Epic encounters with special animations
- **Dark Theme**: Cybernetic neon visual style

## 🎯 Game Rules

### Weapons
- **Square (Divider)**: Deals damage only if `Enemy HP % Weapon = 0`, then `New HP = HP / Weapon`
- **Circle (Subtractor)**: Always works, `New HP = HP - Weapon`
- **Special Rule**: Division result of 1 instantly becomes 0 (instant kill)

### Objective
Reduce enemy HP to exactly 0 before they reach and attack you!

## 🛠️ Tech Stack

- **React** 19.2 + **TypeScript** 5.9
- **Vite** 7.2 - Lightning fast build tool
- **Zustand** - State management
- **Framer Motion** - Smooth animations
- **GitHub Pages** - Deployment

## 🏃‍♂️ Development

```bash
# Install dependencies
npm install

# Run dev server
npm run dev

# Build for production
npm run build

# Deploy to GitHub Pages
npm run deploy
```

## 📁 Project Structure

```
src/
├── components/      # React components
├── stores/          # Zustand state management
├── types/           # TypeScript definitions
└── utils/           # Utility functions
```

## 📝 Documentation

See [Claude.md](Claude.md) for detailed development logs and project context.

## 📄 License

This project is private and not licensed for redistribution.

---

**Note**: This project was originally a toy project using Google Gemini's Antigravity feature, but has evolved into a full game with original mechanics.
