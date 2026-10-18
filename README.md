# Couple Diary — Official Android APK Releases 📱💕

Official production distribution repository for **Couple Diary** on Android.

---

## 🚀 Latest Release: `v1.2.3`

- **Filename**: [`app-release.apk`](./app-release.apk)
- **Version Name**: `1.2.3`
- **Version Code**: `8`
- **File Size**: `12.32 MB` (12,914,102 bytes)
- **Package Status**: Signed & Production Ready
- **SHA-256 Checksum**:
  ```text
  219aa4083ace233156ed63430d178a89f7b85aa19f9c136394dfc0a2ec872dc1
  ```

---

## ⚡ Direct Download Links

Choose either link to download directly to your Android device:

1. **[Direct GitHub Release Asset Download (Recommended)](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/releases/download/v1.2.3/app-release.apk)**
2. **[Direct Raw Repository Download](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/raw/main/app-release.apk)**

---

## 📲 How to Install on Android

1. Download [`app-release.apk`](https://github.com/Aman-Rajput-10-09/couple-dairy-android-releases/releases/download/v1.2.3/app-release.apk) directly on your Android phone.
2. Tap the downloaded file in your browser's notification bar or inside your **Files / Downloads** app.
3. If prompted with *"Install unknown apps"*, tap **Settings** and allow your browser to install apps.
4. Tap **Install** and launch Couple Diary!

---

## ✨ What's New in Version 1.2.3

- ⚡ **Instant-On Feed with 0ms Cache Hydration**:
  - Implemented client-side Stale-While-Revalidate (SWR) memory + disk caching.
  - The feed and couple games display immediately from cached storage on app launch—zero blank screens, zero loading spinner lag.
  - Background silent revalidation updates questions and vote stats seamlessly.
- 🚀 **40x Faster Backend Feed Performance**:
  - Eliminated N+1 sequential database roundtrips.
  - Replaced per-question queries with 4 concurrent batch queries executed in parallel via `asyncio.gather`.
  - Added persistent HTTP connection pooling with keep-alive limits to eliminate redundant TLS handshakes.
- 💖 **30+ Diverse Curated Starter Questions**:
  - Seeded over 20 brand-new diverse questions across 5 intimacy categories:
    1. *Flirty & Spicy* (kissing spots, morning cuddles, cheeky dares)
    2. *Couple Quirks & Cute Habits* (stealing food, sleeping positions, bad habits)
    3. *Deep Emotional Connection* (vulnerability, feeling most loved, relationship milestones)
    4. *Concerns, Boundaries & Honesty* (handling bad moods, arguments, communication preferences)
    5. *Future Dreams & Adventures* (bucket list trips, dream home, couple milestones)
  - Supports 2, 3, and 4 interactive options with live public vote breakdown percentages.
- 🛠️ **Rock-Solid Question Saving & Voting**:
  - Fixed ISO UTC timestamp serialization on question creation.
  - Synchronized optimistic UI updates with automatic cache persistence for votes, likes, and couple game plays.
