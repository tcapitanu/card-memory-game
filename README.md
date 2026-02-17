# 📖 About the Project

This application is a classic matching game where players flip cards to find pairs of emojis. The data is dynamic, fetched from an external API, ensuring a unique board every time the game starts.

### Key Features
*   **Dynamic Gameplay:** Fetches random emojis from the `emojihub` API for infinite replayability.
*   **Game Logic:** Implements the Fisher-Yates shuffle algorithm for unbiased randomization.
*   **Accessibility (a11y):** built with semantic HTML and live regions (`aria-live`) to support screen readers, ensuring the game is playable for visually impaired users.
*   **Responsive Design:** Fully adaptive layout that works on desktop and mobile devices.
*   **Error Handling:** Graceful degradation with custom error UI if the API fails.

## 🛠️ Tech Stack & Concepts Used

### Core Technologies
*   **Runtime:** React 18
*   **Build Tool:** Vite
*   **Language:** JavaScript (ES6+)
*   **Styling:** CSS3 (Custom properties, Flexbox, Grid)

## Getting Started
Install the dependencies and run the project
```
npm install
npm start
```

Head over to https://vitejs.dev/ to learn more about configuring vite
