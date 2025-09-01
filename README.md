# Baddie-App

An AI-powered mental health companion designed to help users track, understand, and improve their well-being through intelligent check-ins, mood tracking, and personalized recommendations.

---

## 🧠 Project Overview

**Baddie-App** is a compassionate mental health assistant offering daily well-being check-ins, mood dashboards, gamified motivation, and tailored resources. Built with a modern React/TypeScript stack, it empowers users to monitor and improve their mental health journey.

---

## ✨ Features

- **Daily Check-In:** Interactive WHO-5 questionnaire with animations and smooth transitions.
- **Mood Dashboard:** Visualizes current mood and trends with:
  - Circular Mood Meter (animated, real-time feedback)
  - Interactive 14-day Mood Trend Chart
- **Gamification:** Earn Baddie Badges for engagement and consistency.
- **Quick Actions Panel:** Immediate support options based on mood.
- **Resource Recommendations:** Swipeable carousel of videos, articles, and tips tailored to mood.
- **Resource Library:** Curated mental health resources, updated dynamically.
- **Support Alerts:** Proactive recommendations for users with low mood trends.

---

## 📂 Directory Structure

```
shadcn-ui/
├── README.md                   # Project overview and instructions
├── components.json             # Component configuration
├── eslint.config.js            # ESLint configuration
├── index.html                  # Main HTML entry point
├── package.json                # Project dependencies and scripts
├── postcss.config.js           # PostCSS configuration
├── public/
│   ├── favicon.svg             # Application favicon
│   └── robots.txt              # SEO configuration
├── src/
│   ├── App.css                 # Global styles
│   ├── App.tsx                 # Main application component
│   ├── components/             # Reusable React components
│   ├── hooks/                  # Custom React hooks
│   ├── lib/                    # Utility functions
│   ├── pages/                  # Page-level components
│   ├── index.css               # Entry CSS
│   └── main.tsx                # Application entry point
├── tailwind.config.ts          # Tailwind CSS configuration
├── template_config.json        # Template configuration
├── todo.md                     # Project TODOs
└── vite.config.ts              # Vite configuration
```

---

## 🛠️ Tech Stack

- **React** & **TypeScript**
- **Shadcn-UI**: Modern UI components
- **Tailwind CSS**: Utility-first styling
- **Vite**: Fast build tool
- **Recharts**: Data visualization
- **Framer Motion**: Animations

---

## 🚀 Getting Started

1. **Clone the repository**
   ```sh
   git clone https://github.com/Rodah-chep/Baddie-App.git
   cd Baddie-App
   ```

2. **Install dependencies**
   ```sh
   pnpm install
   ```

3. **Run in development mode**
   ```sh
   pnpm dev
   ```

4. **Build for production**
   ```sh
   pnpm run build
   ```

5. **Lint and check code quality**
   ```sh
   pnpm run lint
   ```

---

## 📖 File Descriptions

- **README.md**: Project documentation & setup instructions
- **package.json**: Project dependencies & scripts
- **src/components/**: Main UI building blocks
- **src/lib/**: Utilities (mood calculations, local storage, etc.)
- **src/pages/**: Main page components
- **src/components/MoodTrendChart.tsx**: Interactive mood visualization

---

## 🤝 Contributing

Contributions, bug reports, and suggestions are welcome! Please open an issue or submit a pull request.

---

## 📄 License

[MIT](LICENSE)

---

## 🧑‍💻 Maintainer

- [Rodah-chep](https://github.com/Rodah-chep)

---

*Prioritizing mental well-being, one check-in at a time.*