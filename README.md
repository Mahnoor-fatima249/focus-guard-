# Focus Guard: Distraction Blocker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/Mahnoor-fatima249/focus-guard-/ releases)
[![GitHub stars](https://img.shields.io/github/stars/Mahnoor-fatima249/focus-guard-?style=social)](https://github.com/Mahnoor-fatima249/focus-guard-)

## 🚀 Overview

Focus Guard is a privacy-focused browser extension that helps you regain control of your time by blocking distracting websites during focus sessions. No accounts, no tracking — everything stays locally on your device.

## ✨ Features

- **Website Blocking**: Block YouTube, Facebook, Instagram, TikTok, X, Reddit, and any custom sites
- **Focus Timer**: Simple timer for focused work sessions
- **Pomodoro Technique**: Built-in short and long break cycles
- **Schedules**: Automatically start focus sessions (e.g., weekdays 9am–1pm)
- **One Exception**: Keep one useful page open while blocking the rest of a site
- **Daily Goals & Streaks**: Track your focus habits and build momentum
- **Daily Reports**: See how long you focused, what was blocked, and estimated time saved
- **Privacy by Design**: All data stays on your device. No collection, no tracking, no ads.

## 📦 Installation

### From Source

1. Clone the repository:
   ```bash
   git clone https://github.com/Mahnoor-fatima249/focus-guard-.git
   ```
2. Load the extension in your browser:
   - **Chrome/Edge**: Go to `chrome://extensions/` → Enable "Developer mode" → Click "Load unpacked" → Select the extension directory
   - **Firefox**: Go to `about:addons` → Click the gear icon → "Install add-on from file..." → Select the Firefox zip

### Pre-built Packages

- `focus-guard-chrome-edge.zip` — for Chrome and Edge
- `focus-guard-firefox.zip` — for Firefox

## 📸 Screenshots

| | |
|---|---|
| **Focus Session** | <img src="screenshots/1-focus-session.png" width="200"/> |
| **Set Timer** | <img src="screenshots/2-set-your-timer.png" width="200"/> |
| **Blocked Page** | <img src="screenshots/3-blocked-page.png" width="200"/> |
| **Daily Report** | <img src="screenshots/4-daily-report.png" width="200"/> |
| **Schedules & Settings** | <img src="screenshots/5-schedules-and-settings.png" width="200"/> |
| **Welcome Screen** | <img src="screenshots/6-welcome.png" width="200"/> |

## 🏪 Store Submissions

<div style="display: flex; gap: 16px; flex-wrap: wrap;">

<a href="https://chrome.google.com/webstore/devconsole" target="_blank" style="background: #ff3e00; color: white; padding: 10px 20px; border-radius: 6px; text-decoration: none; font-weight: 500; display: inline-block;">
  Chrome Web Store
</a>

<a href="https://partner.microsoft.com/dashboard/microsoftedge" target="_blank" style="background: #2a2a2f; color: white; padding: 10px 20px; border-radius: 6px; text-decoration: none; font-weight: 500; display: inline-block;">
  Edge Add-ons
</a>

<a href="https://addons.mozilla.org/developers" target="_blank" style="background: #f8a02e; color: #1e1e1e; padding: 10px 20px; border-radius: 6px; text-decoration: none; font-weight: 500; display: inline-block;">
  Firefox (AMO)
</a>

</div>

<p style="margin-top: 12px; font-size: 0.9em; color: #666;">
<strong>Files:</strong> <code>focus-guard-chrome-edge.zip</code> (Chrome/Edge), <code>focus-guard-firefox.zip</code> (Firefox)
</p>

- Build packages: `./build.sh`
- Modify `manifest.firefox.json` for custom Firefox ID
- Add feedback URL in `background.js` (line ~FEEDBACK_URL)
- Screenshots should be 1280×800 px

## 📜 Privacy

Focus Guard does not collect, transmit, sell, or share any personal data. All blocklists, schedules, settings, and focus statistics are stored locally in browser storage. The extension never reads page contents, tracks browsing history, or loads remote code.

Removing the extension deletes all stored data.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the need for focused work in a distracted world
- Built with declarativeNetRequest for efficient site blocking