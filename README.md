# 🚀 Leads Tracker (Chrome Extension)

![Status](https://img.shields.io/badge/status-active-success)
![Tech](https://img.shields.io/badge/tech-JavaScript%20%7C%20Chrome%20API%20%7C%20LocalStorage-blue)

> **Current Version:** 1.0
> A productivity tool to save and manage URLs directly from your browser tab.

## 🎯 Overview
This Chrome Extension allows users to save potential "leads" (URLs) for later use. It utilizes **LocalStorage** to persist data even after the browser is closed and integrates with the **Chrome Tabs API** to grab the current page URL instantly.

## 🛠️ Features
* **Save Input:** Manually type and save a URL or note.
* **Save Tab:** One-click button to save the current active tab's URL.
* **Persistent Storage:** Leads are saved to the browser's LocalStorage.
* **Delete All:** Quickly clear the leads list.

## 📂 Project Structure
* `manifest.json` - The configuration file required by Chrome.
* `index.html` - The popup interface (UI).
* `index.js` - Logic for saving leads and interacting with LocalStorage.
* `index.css` - Styling for the extension popup.

## 🔧 Installation & Testing
Since this is an extension, it doesn't run like a normal website. Here is how to load it:

1.  Clone or download this repository.
2.  Open Chrome and go to `chrome://extensions/`.
3.  Toggle **Developer mode** (top right).
4.  Click **Load unpacked**.
5.  Select the folder containing these files.
6.  The extension is now active in your browser bar!
