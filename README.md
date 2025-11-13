# 🚀 CodeFlow

A modern, responsive landing page for an AI-powered code editor built with React, Vite, and Tailwind CSS.

## ✨ Features

- **Modern UI/UX** - Clean, gradient-rich design with glassmorphism effects
- **Fully Responsive** - Optimized for mobile, tablet, and desktop devices
- **Interactive Components** - Dynamic hero section with live code preview
- **Syntax Highlighting** - Beautiful code display using react-syntax-highlighter
- **Smooth Animations** - Engaging hover effects and transitions
- **React 19** - Built with the latest React features and compiler optimizations

## 🛠️ Tech Stack

- **React 19.2.0** - UI library with React Compiler enabled
- **Vite 7.2.2** - Lightning-fast build tool
- **Tailwind CSS 4.1.17** - Utility-first CSS framework
- **Lucide React** - Beautiful icon library
- **React Syntax Highlighter** - Code syntax highlighting

## 📦 Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd codeflow
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## 🚀 Build for Production

Build the project for production:
```bash
npm run build
```

Preview the production build:
```bash
npm run preview
```

## 📁 Project Structure

```
codeflow/
├── public/          # Static assets
├── src/
│   ├── assets/      # Images and media files
│   ├── components/  # React components
│   │   ├── Hero.jsx
│   │   ├── Navbar.jsx
│   │   ├── Features.jsx
│   │   ├── Pricing.jsx
│   │   ├── Testimonials.jsx
│   │   └── Footer.jsx
│   ├── data/        # Data files and configurations
│   │   └── CodeExamples.js
│   ├── App.jsx      # Main app component
│   ├── main.jsx     # Entry point
│   └── index.css    # Global styles
├── eslint.config.js
├── vite.config.js
└── package.json
```

## 🎨 Components

- **Hero** - Landing section with interactive code editor preview
- **Navbar** - Responsive navigation with mobile menu
- **Features** - Showcase of key features with alternating layouts
- **Pricing** - Pricing plans and tiers
- **Testimonials** - Customer reviews and feedback
- **Footer** - Contact information and links

## 🔧 Configuration

### React Compiler
The React Compiler is enabled for optimized performance. See [React Compiler documentation](https://react.dev/learn/react-compiler) for more details.

### ESLint
ESLint is configured with React-specific rules. Run linting with:
```bash
npm run lint
```


---

Made using React + Vite
