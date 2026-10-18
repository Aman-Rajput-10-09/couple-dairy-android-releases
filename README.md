# Couple Diary — Official Android APK Releases 📱💕

Official production distribution repository for **Couple Diary** on Android.

---

## 🚀 Latest Release: `v1.2.4`

- **Filename**: [`app-release.apk`](./app-release.apk)
- **Version Name**: `1.2.4`
- **Version Code**: `9`
- **File Size**: `12.33 MB` (12,930,486 bytes)
- **Package Status**: Signed & Production Ready
- **SHA-256 Checksum**:
  ```text
  a32800de08d0ed6fc053a73e24ad706cde88af5524a37784e892b620d39ad2f0
  ```

---

## ⚡ Direct Download Links

Choose either link to download directly to your Android device:

1. **[Direct GitHub Release Asset Download (Recommended)](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/releases/download/v1.2.4/app-release.apk)**
2. **[Direct Raw Repository Download](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/raw/main/app-release.apk)**

---

## 📲 How to Install on Android

1. Download [`app-release.apk`](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/releases/download/v1.2.4/app-release.apk) directly on your Android phone.
2. Tap the downloaded file in your browser's notification bar or inside your **Files / Downloads** app.
3. If prompted with *"Install unknown apps"*, tap **Settings** and allow your browser to install apps.
4. Tap **Install** and launch Couple Diary!

---

## ✨ What's New in Version 1.2.4

- 🛡️ **Community Post Reporting & Auto-Removal System**:
  - Full Google Play UGC Safety Policy compliance for the public anonymous couple feed.
  - Added a 3-dots menu (`...`) on every question card with an instant **"Report Question"** action.
  - Comprehensive report dialog supporting policy categories:
    - 🚫 *Inappropriate or sexually explicit*
    - 💔 *Harassment, bullying or hate speech*
    - 📢 *Spam or advertisement*
    - 🔒 *Exposes private personal information*
    - ⚠️ *Other safety concern* (with optional details input)
- ⚡ **Optimistic 0ms Local Hide**:
  - The moment a user reports a question, it is instantly removed from their UI and local cache—the user never sees it again.
- 🤖 **Auto-Takedown Threshold (Soft-Delete)**:
  - When any question receives **3 independent reports**, the backend immediately marks `is_hidden = TRUE`, auto-removing it platform-wide from all users' public feeds.
  - Retains relational integrity for shared partner games and provides an audit trail for moderation.
