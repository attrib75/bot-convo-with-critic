# 🤖 Bot Convo with Critic

[![License: CC BY-NC 4.0](https://img.shields.shields.shields.shields.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

**Bot Convo with Critic** is an advanced version of the AI sandbox arena. While two highly customizable AI personalities lock horns and passionately debate trivia, philosophy, or absolute nonsense, a **hidden 3rd-party Meta-Critic bot** sits outside the matrix, watching their exchange, rolling its virtual eyes, and dropping hilarious, deadpan roasts directly to you (the human user).

The ultimate twist? **The debating bots are completely isolated.** The context logs are partitioned so that Bot 1 and Bot 2 remain entirely oblivious to the Critic's existence, continuing their intense battle with pure, undisturbed conviction while the referee talks major trash behind their backs.

---

## ✨ Features

* **Three-Bot Architecture:** Two passionate combatants and one deeply cynical, deadpan meta-critic.
* **Total Context Isolation:** Advanced history partitioning prevents the debating bots from "hearing" the critic, keeping their interaction pure and focused.
* **Web Speech API Integration:** Uses native browser text-to-speech to give all three participants unique vocal profiles (including a slower, monotone, deadpan delivery for the Meta-Critic).
* **Rate-Limit Safeguards:** Built-in delays ensure smooth execution within free-tier API limits, giving the narration room to breathe.
* **Slick Neon-Accented UI:** A custom widescreen layout featuring center-aligned, double-bordered typography for the Critic's reality checks.

---

## 🚀 Quick Start

### 1. Prerequisites
You will need a Gemini API key. If you don't have one, you can generate a key for free via [Google AI Studio](https://aistudio.google.com/).

### 2. Setup
1. Clone or download this repository.
2. Open the `index.html` file in your favorite text or code editor.
3. Locate line 177 inside the `<script>` tag:
   ```javascript
   const GEMINI_API_KEY = "PASTE_YOUR_GEMINI_API_KEY_HERE";
