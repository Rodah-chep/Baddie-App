# Baddie-App
This is AI Powered Solution Project
# Project Summary
The Baddie Mental Health App is an intelligent and compassionate companion designed to support users in managing their mental health. It features daily well-being check-ins, mood tracking, personalized resource recommendations, and an anonymous user experience. With integration of the WHO-5 Well-Being Index, the app empowers users by providing insights into their mental state and connecting them with relevant mental health resources. The recent enhancements focus on creating a more engaging and interactive user experience through a redesigned dashboard.

# Project Module Description
**Daily Check-In**: Users complete an interactive WHO-5 questionnaire with engaging animations and smooth transitions.
**Mood Dashboard**: Visualizes current mood and trends over time, now featuring:
**Circular Mood Meter**: Animated meter with real-time feedback.
**Interactive Mood Trend Chart**: Displays 14-day mood trends with detailed insights.
**Baddie Badges Gamification System**: Rewards users for engagement and consistency.
**Quick Actions Panel**: Provides immediate support options based on mood.
**Resource Recommendation Carousel**: Swipeable cards with mood-specific content.
**Resource Library**: Offers curated mental health resources, including videos, based on user mood scores.
**Support Alert**: Provides immediate support recommendations for users with low mood trends.

# Directory Tree
shadcn-ui/
├── README.md                   # Project overview and instructions
├── components.json             # Component configuration
├── eslint.config.js            # ESLint configuration
├── index.html                  # Main HTML entry point
├── package.json                # Project dependencies and scripts
├── postcss.config.js           # PostCSS configuration
├── public/
│   ├── favicon.svg             # Application favicon
│   └── robots.txt              # Robots.txt for SEO
├── src/
│   ├── App.css                 # Global styles
│   ├── App.tsx                 # Main application component
│   ├── components/              # React components
│   ├── hooks/                  # Custom hooks
│   ├── lib/                    # Utility functions
│   ├── pages/                  # Page components
│   ├── index.css               # Entry CSS file
│   └── main.tsx                # Application entry point
├── tailwind.config.ts          # Tailwind CSS configuration
├── template_config.json        # Template configuration
├── todo.md                    # Project TODOs
└── vite.config.ts              # Vite configuration
# File Description Inventory
**README.md**: Overview and setup instructions.
**package.json**: Lists dependencies and scripts for building and running the app.
**src/components/**: Contains all React components for the app, including enhanced check-in and resource library components.
**src/lib/**: Contains utility functions for mood calculations and local storage management.
**src/pages/**: Contains page components for main application views.
**src/components/MoodTrendChart.tsx**: New component for visualizing mood trends with interactive features.

# Technology Stack
**React**: Frontend library for building user interfaces.
**TypeScript**: Typed superset of JavaScript for better tooling and error checking.
**Shadcn-UI**: A component library for building user interfaces.
**Tailwind CSS**: Utility-first CSS framework for styling.
**Vite**: Build tool for modern web projects.
**Recharts**: Library for data visualization.
**Framer Motion**: Library for animations.

# Usage
1. **Install Dependencies**: Run `pnpm install` to install project dependencies.
2. **Build the Project**: Use `pnpm run build` to create an optimized build of the application.
3. **Run the Application**: Execute `pnpm run lint` to check for errors and ensure code quality.
4. **Run the Application**: Execute `pnpm run lint` to check for errors and ensure code quality.

