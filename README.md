# ⚡ Aura iOS Gaming Optimizer Web App (Lakee Style)

Professional **Apple iOS 18 Cyber-Glassmorphism Gaming Optimizer & Utility Suite** with complete **Admin Control Panel**, **1-Device HWID License Key Lock**, **Live Online Devices Tracking**, **Battery Monitor**, and **Firebase Sync**.

---

## 📱 Features Overview

### 1. Client App (`index.html`)
- **Apple iOS 18 Dark Cyber-Glass UI**: Gorgeous fluid design, dynamic island header, glowing ambient lights, SF Pro typography.
- **Hardware & Battery Monitor**:
  - Live Battery % & Charging state detection (`navigator.getBattery()`) with iOS calibrated fallback.
  - Target device detection (iPhone 11 to 16 Pro Max, iPad Pro) with manual tester switcher for Android/PC users.
  - Persistent Device HWID generator (`IOS-XXXX-XXXX`).
  - Real-time Ping Latency meter.
- **Free vs VIP Access Tiers**:
  - **Free Tier**: Standard 60 FPS configs, Cloudflare 1.1.1.1 DNS profile, live ping radar.
  - **VIP Tier**: Unlocked via VIP License Key. Unlocks 90/120 FPS Extreme configurations, AdGuard Anti-Ad Gaming DNS, Thermal Bypass Engine, and Custom Siri Shortcut.
- **1 Key = 1 Device (Hardware ID Lock)**:
  - Each license key binds permanently to the first device that activates it.
  - Any subsequent attempt from a different device is automatically blocked.
- **Apple Configuration Profile (`.mobileconfig`)**:
  - Downloads genuine signed-ready Apple XML DNS profiles directly in Safari for native 1-tap installation.
- **Live Version Alert Popup**:
  - Whenever the Admin pushes a new version (e.g., `v2.4.0` -> `v2.5.0`), all connected users instantly receive an iOS-style alert: *"නව Version එකක් නිකුත් වී ඇත! කරුණාකර update කරන්න."*
- **Real-Time Heartbeat**:
  - Sends device state every 10 seconds to keep live metrics accurate in Admin.

---

### 2. Admin Control Center (`admin.html`)
- **Admin Authentication**:
  - Default Username: `admin@aura.io`
  - Default Password: `admin123`
- **Dashboard Stats**:
  - Real-time online devices count (green pulse).
  - Total VIP keys created vs active bound devices.
  - Current engine version broadcast.
- **VIP License Key Generator**:
  - Custom Plans: 1 Day Trial, 7 Days Pass, 30 Days Pro, Lifetime VIP.
  - Price & Customer Note tags (e.g. `Rs. 1000 - Kasun`).
  - Generate multiple keys at once with 1-click copy chips.
- **Keys Management & HWID Reset**:
  - View all keys, bound HWID IDs, creation dates, and status.
  - **Reset HWID Button**: Allows Admin to unlock a key if a user changes their phone.
  - Delete key button.
- **Live Connected Devices Monitor**:
  - Displays real-time connected users: Device Model (e.g., iPhone 15 Pro), Live Battery %, HWID, VIP/Free tier, Ping, and Last Seen.
- **Version Broadcaster & Announcement Control**:
  - Change the live version number and notes to trigger the update modal on all user devices.
  - Broadcast live notification banners to the client site.
- **Firebase Realtime Sync**:
  - Input Firebase API credentials to sync with Firestore/Realtime DB, with seamless built-in local fallback that works 100% offline out-of-the-box!

---

## 🚀 How to Run & Test on Mobile

### Option 1: Local Network Test (View on your Phone)
If your PC and Phone are on the same Wi-Fi network:
1. Open terminal in this folder:
   ```bash
   npx serve .
   # or
   python -m http.server 8080
   ```
2. Check your PC's local IP (e.g., `192.168.1.15:8080`).
3. Open Safari or Chrome on your phone and browse to:
   - Client Site: `http://192.168.1.15:8080/index.html`
   - Admin Panel: `http://192.168.1.15:8080/admin.html`

### Option 2: Free Cloud Hosting (1-Click Deployment)
You can deploy this static project for free in 60 seconds to:
- **Vercel** / **Netlify** / **GitHub Pages**
Once uploaded, you get an `https://...` link that you can share with any iPhone user worldwide!

---

## 🔑 Starter License Keys (Ready for Testing)
You can test the VIP login right away using either of these pre-configured keys:
1. `AURA-VIP-2026-X1` (Lifetime VIP)
2. `AURA-VIP-30D-K89` (30 Days Pro)

*Or generate new custom keys inside `admin.html`!*
