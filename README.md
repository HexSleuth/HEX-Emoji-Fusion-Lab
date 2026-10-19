# 🧪 HEX Emoji Fusion Lab 🍳

<div align="center">

![GitHub Pages](https://img.shields.io/badge/Hosted-GitHub_Pages-success?style=for-the-badge&logo=github)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![License](https://img.shields.io/github/license/hexsleuth/HEX-Emoji-Fusion-Lab?style=for-the-badge&color=blue)
![GitHub last commit](https://img.shields.io/github/last-commit/hexsleuth/HEX-Emoji-Fusion-Lab?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/hexsleuth/HEX-Emoji-Fusion-Lab?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/hexsleuth/HEX-Emoji-Fusion-Lab?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/hexsleuth/HEX-Emoji-Fusion-Lab?style=for-the-badge)

</div>

Welcome to the **HEX Emoji Fusion Lab**—an advanced, highly immersive web experiment that interfaces with the **Google Emoji Kitchen** ecosystem. Mix, match, search, and discover hundreds of unique custom emoji mashups right in your browser with zero bloat!

🌐 **[Experience the Live Demo Here](https://hexsleuth.github.io/HEX-Emoji-Fusion-Lab/)**

<div align="center">
🧪 HEX Emoji Fusion Lab 🧬
Unleash your creativity by combining emojis to discover completely new, mathematically perfect fusions. A fully interactive, real-time emoji alchemy reactor built for the web.
Live Demo

GitHub stars

GitHub forks

GitHub issues

GitHub pull requests

GitHub license

Maintenance
Live Preview • Report Bug • Request Feature
</div>
📖 Table of Contents
 * About The Project
 * Core Features
 * Application Architecture & Modules
 * Keyboard Shortcuts & Navigation
 * Getting Started (Local Development)
 * Technical Stack
 * Contributing
 * License
 * Acknowledgments
🌟 About The Project
HEX Emoji Fusion Lab is an advanced, client-side web application designed to act as a digital crucible for emoji alchemy. Inspired by the joy of visual discovery, this application allows users to select two distinct "ingredient" emojis and smash them together within a virtual reactor to synthesize entirely new, officially supported emoji fusions.
The application operates with a sleek, gamified user interface that tracks your discoveries, loads complex SVG/PNG fusion assets asynchronously in the background, and provides rapid clipboard accessibility. Whether you are searching for the perfect reaction image, exploring the limits of Unicode ligatures, or simply trying to unlock all 120 base discoveries, the Fusion Lab provides a frictionless, zero-latency environment to experiment.
✨ Core Features
The laboratory is equipped with state-of-the-art tools designed to maximize your experimental efficiency:
 * ⚡ Real-Time Fusion Reactor: Select Ingredient A and Ingredient B to instantly compute and render their hybrid offspring. The reactor dynamically fetches high-resolution fusion graphics without refreshing the page.
 * 📋 Instant Clipboard Integration: Designed for speed. A single tap on any generated emoji or ingredient instantly copies it to your clipboard. Holding the click copies the underlying fusion formula (e.g., 🐢 + 🍄).
 * 🔍 Comprehensive HEX Search Engine: A built-in, highly optimized search index allows you to filter and locate specific emojis by name, tag, or hexcode instantly.
 * 🏆 Discovery Gamification: A built-in tracking system monitors your progress, recording your unique syntheses. Attempt to unlock all 120 / 120 core discoveries.
 * 🕰️ Persistent Fusion History: Never lose a great combination. The application logs your session's fusion history, allowing you to instantly re-fuse past combinations or copy previous results.
 * 🎨 Custom Emoji Injection: Break the boundaries of the standard palette. The lab allows users to inject custom emojis or external Unicode characters into the reactor to test for hidden or wild fusions.
 * 🌐 Asynchronous Background Loading: Fusion combo data pre-fetches and loads seamlessly in the background, ensuring that your user experience remains entirely fluid and uninterrupted by network latency.
🏗 Application Architecture & Modules
The interface is logically divided into several functional zones, engineered for intuitive workflow:
| Module | Description | Functionality |
|---|---|---|
| Header Status Bar | The command center. | Displays current discovery counts (e.g., 0 / 120), active loaded combos, and global settings. |
| Fusion Reactor | The core interaction zone. | Houses the [ ? ] + [ ? ] = [ ? ] equation. Visualizes the real-time synthesis of chosen ingredients. |
| Ingredient Palette | The raw materials. | A curated, scrollable grid of base emojis. Tap to add to the reactor, hold to copy directly. |
| Browse Combos | The encyclopedia. | Select a single ingredient in Slot A to actively browse all known viable fusions for that specific emoji. |
| Custom Fusions | The sandbox. | A staging area for user-defined or non-standard emoji inputs. Track wild fusions that fall outside the base 120. |
⌨️ Keyboard Shortcuts & Navigation
For power users and terminal enthusiasts, the HEX Emoji Fusion Lab is fully navigable via an optimized set of keyboard macros to ensure maximum throughput during experimentation sessions:
> Tap / Left Click ➔ Copy the target emoji to clipboard.
> Hold / Long Press ➔ Copy the mathematical formula (A + B) to clipboard.
> Enter ➔ Trigger the Fusion sequence instantly.
> R ➔ Randomize ingredients (Inject chaos into the reactor).
> Esc ➔ Clear the reactor and reset the current slots.
> 
🚀 Getting Started (Local Development)
To deploy your own instance of the HEX Emoji Fusion Lab locally for modification, testing, or offline use, follow these steps:
Prerequisites
 * A modern web browser (Chrome, Firefox, Safari, Edge) with ES6 module support.
 * Basic understanding of HTML/CSS and vanilla JavaScript.
 * Git installed on your local machine.
Installation
 * Clone the repository:
   git clone https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab.git

 * Navigate into the project directory:
   cd HEX-Emoji-Fusion-Lab

 * Launch a local development server:
   Because the application relies on asynchronous background fetching for JSON and media assets, it must be run over a local HTTP server rather than a file:// protocol.
   Using Python 3:
   python -m http.server 8000

   Using Node.js (http-server):
   npx http-server -p 8000

 * Open the Lab:
   Navigate to http://localhost:8000 in your browser.
🛠 Technical Stack
The architecture of HEX Emoji Fusion Lab is intentionally lightweight, ensuring massive accessibility and zero-dependency overhead for end-users:
 * HTML5: Semantic, accessible markup utilizing ARIA labels for screen-reader compatibility (aria-live="polite", role="status").
 * CSS3: Responsive, grid-based layout utilizing native CSS variables and transitions. Completely framework-agnostic.
 * Vanilla JavaScript (ES6+): Handles DOM manipulation, asynchronous state management, clipboard API interactions, and event listeners without the bloat of external libraries.
 * GitHub Pages: Deployed directly from the main branch via GitHub Actions for continuous, seamless delivery.
🤝 Contributing
Contributions are what make the open-source community such an incredible place to learn, inspire, and create. Any contributions you make to the Fusion Lab are greatly appreciated.
If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag enhancement.
 * Fork the Project
 * Create your Feature Branch (git checkout -b feature/AmazingFeature)
 * Commit your Changes (git commit -m 'Add some AmazingFeature')
 * Push to the Branch (git push origin feature/AmazingFeature)
 * Open a Pull Request
📜 License
Distributed under the MIT License. See the LICENSE file in the repository root for comprehensive details. This ensures the project remains open, free, and collaborative.
🙏 Acknowledgments
 * Google Emoji Kitchen for pioneering the concept of vector-based emoji ligatures.
 * Unicode Consortium for standardizing the joy of digital expression.
 * Shields.io for the dynamic repository status badges.
 * The open-source web development community for the endless resources and inspiration.
<img width="534" height="534" alt="image" src="https://github.com/user-attachments/assets/ddf99b41-87fc-40b8-a959-6f0e3cd9ec12" />

