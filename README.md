# 🎧 Universal Audio Downloader & Extractor [State Engine]

A commercial-grade, persistent media automation utility suite for Android built entirely within native Linux terminal layers. This tool provides a swipe-proof background download stream, intelligent network self-healing loops for connectivity blocks (like Airplane Mode drops), and direct local file extraction rules for external app media shares (such as direct video forwards inside WhatsApp chats).

---

## 💻 Path A: If You Are Currently Looking at a Laptop Screen

### 1. Scan to Setup on Mobile
If you are reading this on your computer, pull out your phone, open your mobile camera app, and scan the QR code below. It will instantly open this exact page layout directly on your phone screen so you can download the application and copy the installation scripts with one tap!

<img src="setup-qr.png" width="220" alt="Engine Installation QR Code Matrix">

---

## 📱 Path B: Welcome Mobile Users! (Follow These Steps In Order)

Follow these strict step-by-step instructions to get the entire engine active on your phone natively without any coding knowledge:

#### 1. Download the Correct App (For New Users)
If you do not have Termux active on your device yet, do **NOT** use the Google Play Store (as that version is broken and causes background script crashes). 

⚠️ **CRITICAL NAVIGATION WARNING:** 
On this page, **do NOT tap the large, prominent blue "DOWNLOAD F-DROID" button**! That button will install a completely different app store client instead of Termux. 

Instead, scroll all the way down this page past that button to the **"Versions"** section, look for **"Version 0.118.3"** (or the latest suggested release), and tap the blue text link that says **`Download APK`** to pull the app file directly!

👉 [📥 Direct Download: Termux (Terminal emulator with packages) APK](https://f-droid.org/en/packages/com.termux/)

### 📋 2. Copy the Automated Installer Code
Once you have the app installed, click the native GitHub copy icon on the right side of the highlighted code box block below to copy your master setup command cleanly onto your mobile clipboard:

```bash
curl -sL https://gist.githubusercontent.com/hemu29chandu27/d362167a19633aa8959b0aa6b5ede649/raw/326d4f686941999da5a4fbc881f7a4fc21669e38/install.sh | bash
```

### 🏎️ 3. Paste and Execute inside Termux
Launch your newly installed **Termux (Terminal emulator with packages)** app from your phone's home screen. Long-press on the blank terminal line, tap **Paste**, and press **Enter** on your keyboard layout.
💡 **Crucial Step for Sharing Content:** 
As soon as the setup wizard finishes, your phone will automatically open the Termux App Info settings window. You **must** scroll down and toggle **`Display over other apps`** to **ALLOW**. 

This permission is the core link bridge—without it, Android will block Termux from catching media links and raw video files shared directly from external apps like WhatsApp, Instagram, or YouTube!

The installer script will clear your screen, automatically set up your directory path nodes, and display a green success banner when your system is fully live!
