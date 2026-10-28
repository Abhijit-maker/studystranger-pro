# Study Stranger Pro — Android Native App

This repository contains the full native Android (Kotlin) app for **Study Stranger Pro** (`https://studystranger-pro.ai.studio`).

## ✨ Features
- **100% Native Android**: Not a PWA or simple shortcut — pure Kotlin codebase.
- **WebGL & 3D Acceleration**: Hardware acceleration enabled for the 3D AI Mentor.
- **WebRTC Voice & Audio Support**: Built-in permission handlers for interactive voice sessions.
- **PDF Study Vault Downloads**: Integrated with Android's system `DownloadManager`.
- **File Upload Support**: Seamless image/document upload file chooser.
- **Custom Splash Screen**: Fast and modern startup screen matching the brand theme.
- **Pull to Refresh**: Swipe down to reload content seamlessly.
- **Native Back Navigation**: Handles web navigation history with double-tap back to exit.
- **Offline Fallback**: Clean UI screen with retry button when internet connection is lost.
- **External Intent Handling**: Automatically routes `tel:`, `whatsapp:`, `mailto:`, and `sms:` links to their respective Android apps.

---

## 🚀 How to Build the APK (2 Simple Methods)

### Method 1: Automatic Cloud Build via GitHub Actions (Recommended & Free)
No need to install heavy Android tools or drain your phone's battery!

1. Create a new GitHub repository (can be public or private).
2. Push this project to GitHub:
   ```bash
   cd /data/user/0/com.termux/files/home/projects/studystranger-pro
   git init
   git add .
   git commit -m "Initial commit for Study Stranger Pro Android App"
   git branch -M main
   git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
   git push -u origin main
   ```
3. Open your GitHub repository in your browser.
4. Go to the **Actions** tab.
5. Click on the latest workflow run (or run it manually via **Run workflow**).
6. Under **Artifacts**, download `StudyStrangerPro-Debug-APK` or `StudyStrangerPro-Release-APK` directly onto your phone and install!

---

### Method 2: Open in Android Studio (PC / Laptop)
1. Clone or copy this folder to your PC.
2. Open Android Studio -> **File** -> **Open** -> select `studystranger-pro`.
3. Click **Build** -> **Build Bundle(s) / APK(s)** -> **Build APK(s)**.
