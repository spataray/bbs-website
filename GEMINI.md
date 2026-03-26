# BBS Website - Project Context

BBS Website is a minimalist, retro-style terminal interface designed to simulate a classic Bulletin Board System (BBS).

## 🚀 Project Overview

*   **Purpose:** Provides a nostalgic, interactive BBS experience via a web terminal.
*   **Core Technology:** Static Web Stack (HTML5, CSS3, ES5 JavaScript).
*   **Key Features:**
    *   **Simulated Dial-up:** Interactive modem sounds and handshake text.
    *   **Terminal UI:** CSS-driven terminal appearance with blinking cursor and monospaced fonts.
    *   **Navigation:** Keyboard-based input and menu-driven interface.
*   **Architecture:** Single-page application (SPA) with DOM-based content switching.

## 🛠️ Building and Running

Since this is a static web application, it does not require a compilation step.

*   **Local Development:** Open `index.html` directly in any modern web browser.
*   **Deployment:** Host via GitHub Pages or any static web server.

## 📂 Key Files

*   `index.html`: The main entry point, containing the terminal UI structure, CSS styling, and interaction logic.
*   `README.md`: Basic project link and documentation.
*   `GEMINI.md`: Project-specific context and development guidelines.

## 📜 Development Conventions

*   **Compatibility:** Maintain ES5 JavaScript standards to ensure functionality on older hardware or legacy browsers. Avoid modern ES6+ features like `const`, `let`, or arrow functions if they are not already used or polyfilled.
*   **Version Tracking:** Update the version tag in `index.html` (`#version-tag`) when making changes. The format is `vX.X.X (YYYY-MM-DD HH:mm TIMEZONE)`.
*   **Styling:** Prioritize the "terminal" aesthetic with high-contrast colors and monospaced typography.

## 🧪 Testing

Testing is performed manually by:
1.  Verifying the simulated dial-up sequence triggers correctly.
2.  Testing menu navigation (e.g., pressing '1' for Message Board, 'm' for Menu).
3.  Ensuring audio (modem sounds) play as expected on user interaction.
