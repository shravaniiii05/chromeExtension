# Chrome Extension – Core Functionality Setup

This project is a Chrome browser extension built using JavaScript and Chrome Extension APIs.
It follows the Manifest V3 structure and includes a popup, background script, content script,
and an options page.

The purpose of this project is to understand how different components of a Chrome extension
work together and communicate.

---

## Features

- Popup interface for user interaction
- Background service worker for extension-level logic
- Content script to interact with web pages
- Options page for managing extension settings
- Proper configuration using `manifest.json` (Manifest V3)

---

## Project Structure

├── manifest.json # Extension configuration file
├── background.js # Background service worker
├── content.js # Content script
├── popup.html # Popup UI
├── popup.js # Popup functionality
├── options.html # Options page UI
├── options.js # Options page logic
├── icon.png # Extension icon
├── README.md # Project documentation

---

## Technologies Used

- JavaScript (ES6)
- HTML5
- Chrome Extension APIs (Manifest V3)

---

## Learning Outcomes

- Understanding Chrome extension architecture
- Working with background, popup, and content scripts
- Using Chrome Extension APIs
- Managing extension configuration with Manifest V3

---

## Future Improvements

- Add more interactive popup features
- Improve UI and user experience
- Extend content script functionality
- Add persistent storage for user preferences

---
