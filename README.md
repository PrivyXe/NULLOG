<div align="center">

<img src="onepage/assets/logo.png" alt="NULLOG" width="120" height="120"/>

<br/>

# NULLOG

### Enterprise On-Device Privacy Firewall for Android

[![Platform](https://img.shields.io/badge/Platform-Android%208.0%2B-3DDC84?style=flat-square&logo=android&logoColor=white)](#)
[![Version](https://img.shields.io/badge/Release-v1.0.0-10B981?style=flat-square)](#)
[![Engine](https://img.shields.io/badge/Engine-100%25%20On--Device-0E1524?style=flat-square)](#)
[![DNS](https://img.shields.io/badge/DNS-DoH%20%2F%20DoT-6366F1?style=flat-square)](#)
[![Logs](https://img.shields.io/badge/Logs-Zero-10B981?style=flat-square)](#)

**Zero cloud routing. Zero logs. Zero compromise.**

[⬇️ Download APK](https://github.com/PrivyXe/NULLOG/blob/main/onepage/assets/NULLOG-1-0-0.apk) · [🌐 Product Page](https://nullog.fyi) · [💬 Telegram](https://t.me/e3x6v)

<br/>

> *NULLOG blocks ads, trackers, and background spyware at the network level — across every app on your phone, simultaneously. No root required.*

<br/>

---

</div>

## What is NULLOG?

NULLOG is a **system-wide network firewall** for Android that works entirely on your device. Unlike traditional ad blockers that only work inside a browser, or cloud VPNs that route all your traffic through a remote server, NULLOG inspects and filters DNS traffic locally — in device memory — before any request even reaches the internet.

No account needed. No subscription until you want Pro. Just install, tap, and breathe easy.

---

## ✨ Features at a Glance

<br/>

### 🛡️ System-Wide Ad & Tracker Blocking
Block ads and trackers across **every app on your device** — not just your browser. Games, social media, news apps, utilities — all filtered through one unified engine.

- Sub-millisecond domain matching (`< 0.4 ms`)
- Powered by EasyList, EasyPrivacy, and Peter Lowe's Ad & Tracker list
- Per-app granular rules — allow or block individual applications
- Banking apps automatically whitelisted to avoid login issues

<br/>

### 🕵️ Background Spyware Radar
Most spyware doesn't pop up ads — it silently calls home in the background while your phone screen is off. NULLOG catches and blocks them in real time.

| SDK Detected | Blocked Domain | Category |
|:---|:---|:---|
| **Firebase Analytics** | `firebaselogging-pa.googleapis.com` | Google Telemetry |
| **Meta / Facebook** | `graph.facebook.com` | Social Tracking |
| **AppsFlyer** | `t.appsflyer.com` | Attribution SDK |
| **TikTok / ByteDance** | `log.musical.ly` | Behavioral Tracking |
| **Yandex AppMetrica** | `appmetrica.yandex.com` | Analytics SDK |
| **Adjust** | `app.adjust.com` | Attribution SDK |

<br/>

### ☕ Silent Sunday Briefing
No notification spam. NULLOG stays completely silent throughout the week and delivers a single consolidated privacy report every **Sunday at 20:00** — giving you a clean overview of what was blocked on your behalf.

<br/>

### 🔐 Encrypted DNS (DoH / DoT)
Every DNS query that passes through NULLOG is encrypted before it reaches your ISP — preventing snooping, man-in-the-middle attacks, and regional domain blocking.

| Resolver | Protocol | Status |
|:---|:---|:---|
| Cloudflare 1.1.1.1 | DNS-over-HTTPS | ✅ Active |
| Quad9 9.9.9.9 | DNS-over-TLS | ✅ Ready |
| AdGuard DNS | DNS-over-HTTPS | ✅ Ready |
| Custom Endpoint | DoH / DoT | ✅ Configurable |

<br/>

### 🔑 Hardware-Bound Licensing
Pro licenses are cryptographically tied to your device hardware — no account, no email, no credit card ever required. Activate via Telegram, use forever.

---

## 📊 How NULLOG Compares

| | NULLOG | Cloud VPN | Browser Extension |
|:---|:---:|:---:|:---:|
| Works on all apps | ✅ | ✅ | ❌ Browser only |
| Zero-log guarantee | ✅ On-device | ⚠️ Trust required | ⚠️ Extension telemetry |
| Battery drain | ✅ < 1% | ❌ High | ✅ Low |
| Latency added | ✅ < 0.4 ms | ❌ 50–150 ms | ✅ Negligible |
| Background spyware block | ✅ | ❌ | ❌ |
| DNS encryption | ✅ DoH / DoT | ⚠️ Varies | ❌ None |
| No account required | ✅ | ❌ | ✅ |

---

## ⬇️ Download

**Android 8.0+ · ARM64 / x86 Universal · 13.5 MB**

👉 [**Download APK (v1.0.0)**](https://github.com/PrivyXe/NULLOG/blob/main/onepage/assets/NULLOG-1-0-0.apk)

### Installation (Sideload)
1. Download the APK to your Android device.
2. Go to **Settings → Security → Install from Unknown Sources** and enable it for your browser or file manager.
3. Tap the APK file and install.
4. Open NULLOG, tap the shield icon, and accept the one-time local VPN permission.

> NULLOG uses Android's `VpnService` API to create a **local-only packet inspection socket**. Your data never leaves your device through NULLOG.

### 🚀 First Launch Bonus
Every new install automatically receives **90 days of Pro** — no activation needed.

---

## 💬 Support & Licensing

| | |
|:---|:---|
| **Telegram** | [@e3x6v](https://t.me/e3x6v) |
| **Pro License** | Purchase lifetime via Telegram |
| **Landing Page** | [nullog.fyi](https://nullog.fyi) |

---

## 🔒 Privacy Promise

- **No data is ever collected** — not even anonymized analytics
- **No remote servers involved** in packet inspection
- **No account required** at any point
- All stats (blocked count, data saved) are stored **only on your device** in a local database you can wipe at any time

---

<div align="center">

**© 2026 NULLOG Security Core. All rights reserved.**

*Made for people who actually care about what their phone is doing.*

</div>
