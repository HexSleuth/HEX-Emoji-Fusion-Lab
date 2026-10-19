<div align="center">
# 🧪 HEX Emoji Fusion Lab 🍳
<a href="https://hexsleuth.github.io/HEX-Emoji-Fusion-Lab/">
  <!-- Replace with an actual animated GIF of your app in action -->
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Exploding%20Head.png" alt="Exploding Head Emoji" width="120" />
</a>
**Mix, discover, and fuse your favorite emojis into entirely new, animated creations!**
[![Live Demo](https://img.shields.io/badge/PLAY_LIVE-HEX_Emoji_Lab-FF007F?style=for-the-badge&logo=vercel&logoColor=white)](https://hexsleuth.github.io/HEX-Emoji-Fusion-Lab/)
<div>
  <a href="https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab/stargazers"><img src="https://img.shields.io/github/stars/hexsleuth/HEX-Emoji-Fusion-Lab?style=flat-square&color=F3DA35&logo=github" alt="Stars"></a>
  <a href="https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab/network/members"><img src="https://img.shields.io/github/forks/hexsleuth/HEX-Emoji-Fusion-Lab?style=flat-square&color=F36F35&logo=github" alt="Forks"></a>
  <a href="https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab/issues"><img src="https://img.shields.io/github/issues/hexsleuth/HEX-Emoji-Fusion-Lab?style=flat-square&color=F33535&logo=github" alt="Issues"></a>
</div>
<br/>
*Tap any emoji to copy · Real Emoji Fusion combos load in the background* 🍳
</div>
---
## 🎨 The Interface & Animated Effects
The **HEX Emoji Fusion Lab** isn't just a static page; it's a dynamic, interactive reactor designed with fluid CSS animations and micro-interactions.
### ✨ Visual Highlights
*   **Fusion Flash:** When two ingredients combine, the reactor triggers a satisfying CSS keyframe flash and pop-in animation to reveal the newly fused emoji.
*   **Tactile Hover States:** Emojis subtly scale and bounce on hover (`transform: scale()`), making the ingredient palette feel alive and touch-responsive.
*   **Live Toasts & Feedback:** Actions like "Copied to clipboard" are announced via sleek, sliding toast notifications utilizing `aria-live=polite` for accessibility.
*   **Glassmorphism & Shadows:** The UI panels utilize soft drop-shadows and modern semi-transparent layering to create depth between the reactor, the palette, and the history logs.
> 📸 **Pro-Tip for Repo Owner:** *Drop an animated GIF of your UI right here!*
> `<img src="./assets/fusion-animation.gif" width="600" alt="UI Animation Demo">`
---
## 🔬 Core Mechanics & Features
### ⚛️ The Fusion Reactor
The heart of the lab. Select **Ingredient A** and **Ingredient B**. Once loaded, hit enter or click the reactor button to trigger the fusion sequence. The background engine calculates the resulting combination and visually pops it into existence.
### 📚 Discovery & Progression
*   **120 Stable Discoveries:** The lab tracks your unique combinations. A live counter updates seamlessly in the UI as you uncover new recipes.
*   **Browse Known Combos:** Lock an emoji into Slot A and scan the UI for known compatible pairs. 
*   **Wildcard Custom Inputs:** Want to break the rules? Input your own custom emojis to see if the reactor accepts the wildcard.
### 📜 Session Memory
*   **History Panel:** Your current session's fusions are stored in a scrollable history feed. Re-fuse old combos instantly by tapping the ⚡ icon.
*   **Clipboard Integration:** 
    *   **Tap:** Instantly copies the resulting emoji.
    *   **Hold:** Copies the full "scientific" formula (e.g., 🐢 + 🥷 = 🍕).
---
## ⌨️ Interactive Controls
We built the lab for speed. Keep your hands on the keyboard for rapid prototyping:

| Action | Control | Visual Effect |
| :--- | :--- | :--- |
| **Add Ingredient** | <kbd>Click</kbd> / <kbd>Tap</kbd> | Ingredient smoothly glides into Slot A or B. |
| **Trigger Fusion** | <kbd>Enter</kbd> | The reactor pulses and reveals the new emoji. |
| **Copy Result** | <kbd>Click</kbd> | Subtle green success flash + live toast notification. |
| **Copy Formula** | <kbd>Hold</kbd> | Progress ring/delay followed by success flash. |
| **Randomize** | <kbd>R</kbd> | Slots spin and populate with random base elements. |
| **Clear Slots** | <kbd>Esc</kbd> | Emojis fade out and reactor resets to `?`. |

---
## 🛠️ Technical Details
<details>
<summary><b>Click to expand under-the-hood details</b></summary>
*   **Frontend Magic:** Built with vanilla HTML/CSS/JS (or detail your specific framework if applicable).
*   **A11y (Accessibility):** Fully compliant with semantic HTML, `aria-labels`, `role=button`, and `aria-live` regions so screen readers can experience the fusions too.
*   **State Management:** Discoveries and custom fusions are managed in the browser's local storage (or session storage), ensuring a snappy, reload-resistant experience.
**Local Setup:**
```bash
git clone [https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab.git](https://github.com/hexsleuth/HEX-Emoji-Fusion-Lab.git)
cd HEX-Emoji-Fusion-Lab
# Open index.html in your browser!<img width="534" height="534" alt="image" src="https://github.com/user-attachments/assets/7c273a12-ab1e-4665-89bd-11bbc7228a42" />

