# X\_Automate - Twitter Automation Chrome Extension

X\_Automate is a Chrome Extension that automates **Twitter (X)** actions such as:

* Auto-Follow users
* Auto-Unfollow users
* Auto-Like tweets

It provides a simple popup UI with buttons for each action.

---

## 📌 Features

* **Auto-Follow**: Automatically follows users on Twitter.
* **Auto-Unfollow**: Automatically unfollows users.
* **Auto-Like**: Automatically likes tweets.
* Adjustable **max actions** and **delay** for human-like activity.
* Start/Stop automation anytime.

---

## 📂 Project Structure

```
X_Automate/
│── manifest.json          # Chrome extension config
│── background.js          # Background script (manages state)
│── content.js             # Injected into Twitter pages to click buttons
│── popup.html             # Extension popup UI
│── popup.js               # Popup logic (start/stop automation)
│── icons/                 # Extension icons
│── README.md              # Documentation
```

---

## ⚙️ Installation & Setup

### 1. Clone or Download Project

Download this repository or clone it:

```bash
git clone https://github.com/Vaibhav0x/x_automate_js
```

### 2. Open Chrome Extensions Page

1. Open **Google Chrome**.
2. Navigate to: `chrome://extensions/`.
3. Enable **Developer mode** (toggle top-right).

### 3. Load the Extension

1. Click **Load unpacked**.
2. Select the project folder (`X_Automate/`).
3. The extension icon will now appear in your Chrome extensions bar.

---

## ▶️ How to Use

1. Open **Twitter (X)** in your browser.
2. Click the **X\_Automate icon** in the Chrome extensions bar.
3. The popup will show three main buttons:

   * **Follow Users** → starts auto-following users.
   * **Unfollow Users** → starts auto-unfollowing users.
   * **Like Tweets** → starts auto-liking tweets.
4. Enter the following options before starting:

   * `Max Actions` → Number of users/tweets to act on (e.g., 50).
   * `Delay` → Time in milliseconds between actions (e.g., 1000).
5. Click **Stop** at any time to end the automation.

---

## 🔑 Permissions

The extension requests the following permissions in `manifest.json`:

* **activeTab** → To interact with Twitter pages.
* **scripting** → To inject automation scripts.
* **storage** → To save settings.

---

## 🛠 Development Notes

* Make sure you are logged into **Twitter/X** before starting automation.
* Always set realistic **delay times** (1000ms–3000ms) to avoid detection.
* Avoid running automation for too long on your main account.

---

## ⚠️ Disclaimer

This extension is for **educational purposes only**.
Use at your own risk. Twitter’s **Terms of Service** prohibit automation without explicit permission. Accounts may be suspended or banned.

---
