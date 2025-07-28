# 📸 Voice Selfie Web App

Voice Selfie is a browser-based web application that lets users take selfies using **voice commands** instead of manually clicking a button. It uses the browser's Web Speech API and webcam to provide a hands-free photo-taking experience—perfect for accessibility and convenience.

## 🚀 Features

* 🎙️ Voice-activated camera shutter (`"Take a selfie"` command)
* 📷 Live webcam preview
* 💾 Download and save captured selfies
* 📱 Responsive design (mobile & desktop compatible)
* 🔒 Runs entirely in-browser (no data uploaded to a server)

## 🛠️ Technologies Used

* HTML5, CSS3, JavaScript
* Web Speech API (for voice recognition)
* getUserMedia API (for webcam access)
* Canvas API (for image capture)

## 📦 Installation

You can run the app locally by following these steps:

```bash
git clone https://MohitKumar025/voice-selfie-app.git
cd voice-selfie
open index.html
```

Alternatively, use a live server (like the Live Server extension in VS Code) to avoid browser permissions issues.

## 🗣️ How to Use

1. Open the app in a modern browser (Chrome recommended).
2. Allow microphone and camera access when prompted.
3. Say **"Take a selfie"** clearly.
4. Wait for a short countdown (optional).
5. Your selfie will appear on the screen.
6. Click the **Download** button to save it.

## ⚠️ Requirements & Limitations

* Works best in **Google Chrome** (Web Speech API support may vary)
* Requires **microphone** and **webcam** permissions
* Commands must be spoken clearly and in English
* Does not support background noise cancellation

## 📁 Project Structure

```
voice-selfie/
├── index.html
├── style.css
├── script.js
└── README.md
```

## 📄 License

MIT License
Feel free to fork, modify, and use this project for personal or commercial purposes.

---
