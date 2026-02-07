https://darkwingdog.github.io/Stream-Overlay/

# 🐺 Werewolf Hunter Command Center - TJ Edition (terrdog420)

This repository contains the hardened multi-stream relay and interactive overlay for **terrdog420**'s hunter stream setup.

## 🛠️ Project Goals
1. **24/7 Relay Stability**: Maintain a bridge between Twitch, Discord, and TikTok without manual intervention.
2. **Interactive Trophies**: Automated tracking for The Hunter: Call of the Wild.
3. **Wolf-Branded Alerts**: High-energy "Wolf Bursts" for followers and subscribers.

---

## 📂 File Structure
* **`index.html`**: The structural skeleton of the overlay.
* **`style.css`**: The design layer (Positioning, Wolf-Themed Animations).
* **`script.js`**: The brain (Twitch Logic, EST Clock, Trophy Sync).
* **`relay.js`**: The GitHub Actions bridge (Heartbeat & TikTok Persistence).

---

## 🧩 Key Bug Fixes & Standards (Internal reference)
* **TikTok Persistence**: The relay uses a `while(true)` loop to handle TikTok being offline. It must NEVER throw an error that stops the GitHub runner.
* **Heartbeat Engine**: Logs a timestamp every 60s to prevent GitHub Actions from canceling the operation due to "inactivity".
* **Great One Logic**: The 👑 tracker is hidden by default. It only flips to `display: flex` when `!greatone` count > 0.
* **Time Sync**: All clocks are hard-coded to `America/Chicago` (CST).
* **Wolf Bursts**: All burst particles must use wolf-themed emojis (`🐺`, `🐾`, `🌕`, `🌑`). No rabbits or unicorns. //This will be changed

---

## 🤖 AI Initialization String (FOR GEMINI)
*Copy and paste the block below into any new chat to immediately sync the AI with this project:*

> **"I am working on the Werewolf Hunter Project for TJ (terrdog420). The standards are: Full Code Mandate (no snippets), EST Time Lock, Wolf Bursts only, and the TikTok Persistence relay logic. The Trophy Log hierarchy starts with the Great One (hidden until 1+), followed by Diamond, Gold, Silver, and Bronze. Use the 24-hour global tracking window for Amazon affiliate links with tag 'werewolf3788-20'. Ground all code in the saved standards for S&K Ventures."**

---

## 🚀 Deployment for TJ
1. **Fork/Clone**: Clone this repo to TJ's GitHub account.
2. **Secrets**: Add Twitch/Discord/TikTok credentials to GitHub Secrets.
3. **Actions**: Enable the `main.yml` workflow.
4. **OBS**: Add `index.html` as a Browser Source (Width: 100%, Height: 100%).
