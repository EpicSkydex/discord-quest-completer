# discord-quest-completer
An automated script to complete Discord Quests in parallel by spoofing game and stream statuses.
# Discord Quest Automation / Spoofer

A lightweight JavaScript automation script designed to automatically complete active Discord Quests (such as playing games, streaming on desktop, watching videos, or activity tasks) in parallel, without needing to install or actually play the games.

##  Features
* **Parallel Execution:** Completes multiple quests simultaneously with a 4-second staggered start.
* **Multi-Task Support:** Works with `PLAY_ON_DESKTOP`, `STREAM_ON_DESKTOP`, `WATCH_VIDEO`, and `PLAY_ACTIVITY`.
* **Smart Spoofing:** Safe `.call()` injection to preserve Discord's internal Webpack context and prevent app crashes.
* **Real-time Logging:** Clear console output showing the progress of each active quest.

##  How to Use
1. Open Discord in your Desktop App or Web Browser.
2. Open the Developer Tools (`Ctrl` + `Shift` + `I` or `F12`) and navigate to the **Console** tab.
3. Paste the entire script into the console and press **Enter**.
4. Keep Discord open and watch the console logs to track the progress.

## ⚠️ Disclaimer
**Use at your own risk.** This script interacts with Discord's internal Webpack modules and API endpoints. Automating user actions or using custom scripts inside the Discord client technically violates the Discord Terms of Service (ToS). The author is not responsible for any actions taken against your account.
