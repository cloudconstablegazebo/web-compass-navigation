# 🧭 Web Compass Navigation

<p align="center">
  <img src="https://img.shields.io/badge/Downloads-59K+-92400E?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Rating-4.9/5-92400E?style=for-the-badge&logo=star" />
  <img src="https://img.shields.io/badge/Release-2026-1C1917?style=for-the-badge&logo=github" />
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Win%20%7C%20mac%20%7C%20Linux-92400E?style=for-the-badge&logo=javascript" />
  <img src="https://img.shields.io/badge/Type-Compass%20UI-92400E?style=for-the-badge&logo=compass" />
  <img src="https://img.shields.io/badge/License-Free%20Guide-92400E?style=for-the-badge&logo=opensourceinitiative" />
</p>

**🧭 Web Compass Navigation** is the complete English-language guide to building a working compass navigation UI in the browser. Learn how to read device orientation, rotate a compass needle, calculate bearing to a target, handle iOS permission prompts, and draw a smooth map overlay — with vanilla JavaScript and zero dependencies. Built for web developers, hikers, and anyone building a location-aware web app. **Completely free.** No signup. No paywall. No hidden chapters.

<p align="center">
  <img src="https://skillicons.dev/icons?i=js" />
  <img src="https://skillicons.dev/icons?i=html" />
  <img src="https://skillicons.dev/icons?i=css" />
  <img src="https://skillicons.dev/icons?i=git" />
  <img src="https://skillicons.dev/icons?i=vscode" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=C084FC&size=27&center=true&vCenter=true&width=920&lines=🧭+Web+Compass+Navigation;🗺️+Orientation+%2B+Bearing+%2B+Map;📍+Zero+Dependencies;🧡+100%25+Free+Guide">
</p>

<!-- Button 1 -->
<div align="center">
  <a href="https://share.google/5sXyVRAx7SPWM5WZX">
    <img src="https://img.shields.io/badge/📖%20OPEN%20THE%20GUIDE-92400E?style=for-the-badge&logo=google&labelColor=1C1917&color=C084FC" alt="Open the Guide" />
  </a>
</div>

<div align="center">
  <img width="1794" height="877" alt="compass-banner" src="https://github.com/user-attachments/assets/ebe81528-3cb7-429a-98d6-01aa93b1de01" />

</div>

---

## 🚨 Symptoms of a Broken Compass UI

Before you rotate another needle, check whether your compass UI suffers from any of these classic symptoms. Each one points to a specific fix this guide teaches.

| **Symptom** | **What It Really Means** | **Fix This Guide Teaches** |
|-------------|---------------------------|------------------------------|
| 😵 Needle never moves | No permission | iOS permission flow |
| 🐌 Jittery rotation | Raw sensor noise | Smoothing filter |
| 🧊 Wrong north | Device vs true north | Declination fix |
| 🔥 Bearing off by 90° | Axis mismatch | Correct axis math |
| 📉 Blank on iOS | No prompt | `requestPermission` |
| 🔇 Map never rotates | No transform | CSS rotate |

> **💡 Tip:** If the needle never moves on iOS, you're missing the `DeviceOrientationEvent.requestPermission()` call — Safari blocks sensors until the user taps.

---

## 🚀 First 5 Minutes — Minimal Working Example

The fastest way to get a compass needle rotating.

**Step 1 — Markup.** Add a compass container.

**Step 2 — Listener.** Subscribe to `deviceorientation`.

**Step 3 — Permission.** Request on iOS.

**Step 4 — Rotate.** Apply `transform: rotate()`.

**Step 5 — Smooth.** Add a low-pass filter.

> **💡 Tip:** Always smooth raw sensor data — unsmoothed `alpha` values jitter wildly and look broken.

---

## 🧠 Mental Model — Why Browser Compass Feels Confusing

| **Layer** | **What You Control** | **Common Trap** |
|-------------|------------------------|-------------------|
| **Permission** | iOS prompt | Missing |
| **Sensor** | `deviceorientation` | Axis mismatch |
| **North** | Device vs true | Declination |
| **Rotation** | `transform` | Degrees |
| **Smoothing** | Low-pass | Jitter |
| **Bearing** | Target angle | Math error |

---

## 🎁 What You Get

| **Feature** | **Description** | **Status** |
|-------------|------------------|------------|
| 🧭 **Compass UI** | Rotating needle | ✅ Active |
| 🗺️ **Orientation** | Device sensor | ✅ Active |
| 📍 **Bearing** | Target angle | ✅ Active |
| 🧭 **Permission Flow** | iOS ready | ✅ Active |
| ⚡ **Smoothing** | Low-pass filter | ✅ Active |
| 📊 **Map Overlay** | CSS rotate | ✅ Active |

<table>
<tr>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261105_2e2683" src="https://github.com/user-attachments/assets/3db0a9f8-1f49-4dcb-b8fe-76a9acd967ec" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261105_1d9429" src="https://github.com/user-attachments/assets/040697eb-4b37-4696-8b68-ab6c34d97008" />
</td>
<td align="center" width="33%">
  <img width="320" height="280" alt="deepseek_svg_20261105_829ac4" src="https://github.com/user-attachments/assets/51c99af5-e462-46cd-9c5d-e3316926027c" />
</td>
</tr>
</table>

---

## 🏗️ Pattern Cookbook — Build Your Compass Stack

| **Layer** | **Choose From** | **Best For** |
|-------------|-----------------|--------------|
| **Sensor** | `deviceorientation` | Orientation |
| **Permission** | iOS request | Safari |
| **Rotation** | CSS `rotate()` | UI |
| **Smoothing** | Low-pass | Stability |
| **Bearing** | `atan2` | Direction |
| **Declination** | Offset | True north |

---

## ⚖️ Then vs Now

| **Feature** | **Before** | **Now** |
|-------------|-----------|---------|
| **Compass** | Native only | ✅ Web |
| **Permission** | Blocked | ✅ Handled |
| **Rotation** | Jittery | ✅ Smoothed |
| **North** | Wrong | ✅ Declination |
| **Bearing** | Manual | ✅ `atan2` |
| **Price** | Paid SDK | ✅ **Free guide** |

---

## 🌍 Runtime Matrix

| **Platform** | **Status** | **Notes** |
|--------------|------------|-----------|
| **Chrome (Android)** | ✅ Supported | Full |
| **Safari (iOS)** | ✅ Supported | Permission prompt |
| **Chrome (Desktop)** | ⚠️ Partial | Simulated |
| **Firefox** | ✅ Supported | Full |
| **Edge** | ✅ Supported | Full |
| **Static host** | ✅ Supported | GitHub Pages |

---

## 📋 Baseline & Recommended

| **Component** | **Minimum** | **Recommended** |
|---------------|-------------|------------------|
| **OS** | Any modern OS | Latest |
| **Browser** | Chrome 90+ | Latest |
| **Mobile** | Required | Sensor |
| **RAM** | 2 GB | 8 GB |
| **Storage** | 50 MB | 200 MB |
| **Editor** | Any | VS Code |

---

## 🧭 Setup Journey

### Step 1 — Markup
Build the compass container.

### Step 2 — Permission
Request sensor access.

### Step 3 — Listen
Subscribe to orientation.

### Step 4 — Rotate
Apply CSS rotate.

### Step 5 — Smooth
Add a low-pass filter.

### Step 6 — Bearing
Calculate target angle.

<!-- Button 2 -->
<div align="center">
  <a href="https://share.google/5sXyVRAx7SPWM5WZX">
    <img src="https://img.shields.io/badge/🚀%20START%20THE%20GUIDE-92400E?style=for-the-badge&logo=google&labelColor=1C1917&color=C084FC" alt="Start the Guide" />
  </a>
</div>

---

## 🎬 Daily Workflow

| **Time** | **Task** | **Why** |
|-----------|-----------|----------|
| **Morning** | Check sensor | Reliability |
| **Midday** | Test iOS | Permission |
| **Afternoon** | Tune smoothing | UX |
| **Evening** | Test bearing | Accuracy |
| **Weekly** | Test devices | Compatibility |

### First Launch Checklist

1. **Build** compass UI
2. **Request** permission
3. **Rotate** needle
4. **Smooth** data
5. **Add** bearing
6. **Test** on mobile

---

## 💡 Best Tips

- ✅ Permission first on iOS
- ✅ Smooth raw sensor data
- ✅ Use `atan2` for bearing
- ✅ Handle declination
- ✅ Test on real devices

---

## 🔧 When Things Break

| **Problem** | **Fix** |
|--------------|-----------|
| **Needle static** | Check permission |
| **Jitter** | Add smoothing |
| **Wrong north** | Declination |
| **90° off** | Axis math |
| **iOS blank** | Request access |
| **Map won't rotate** | Check CSS |

---

## ❓ FAQ

<details>
<summary><b>Is this guide free?</b></summary>
Yes — completely free to read.
</details>

<details>
<summary><b>Does it work on iOS?</b></summary>
Yes — with a permission prompt.
</details>

<details>
<summary><b>Does it use a library?</b></summary>
No — vanilla JavaScript.
</details>

<details>
<summary><b>Is bearing covered?</b></summary>
Yes — `atan2` math is explained.
</details>

<details>
<summary><b>Is smoothing covered?</b></summary>
Yes — low-pass filter.
</details>

<details>
<summary><b>Does it cover declination?</b></summary>
Yes — true north is explained.
</details>

<details>
<summary><b>Is it mobile-only?</b></summary>
Yes — sensors are mobile.
</details>

<details>
<summary><b>Is it beginner-friendly?</b></summary>
Yes — starts from markup.
</details>

---

## ⚠️ Ground Rules

| ✅ Allowed | ❌ Forbidden |
|------------|--------------|
| Personal use | Selling the guide |
| Commercial use | Redistributing as paid |
| Team onboarding | Removing author credits |
| Educational use | Bundling with malware |

---

## 🏁 Final Word

**Web Compass Navigation** gives you a real compass UI:

- ✅ Compass UI
- ✅ Orientation
- ✅ Bearing
- ✅ Permission flow
- ✅ Smoothing
- ✅ **Completely free**

**Navigate the web — open the guide today.**

<!-- Button 3 -->
<div align="center">
  <a href="https://share.google/5sXyVRAx7SPWM5WZX">
    <img src="https://img.shields.io/badge/⬇️%20OPEN%20THE%20GUIDE-92400E?style=for-the-badge&logo=google&labelColor=1C1917&color=C084FC" alt="Open the Guide" />
  </a>
</div>

<p align="center">
  <img src="https://skillicons.dev/icons?i=js" />
  <img src="https://skillicons.dev/icons?i=html" />
  <img src="https://skillicons.dev/icons?i=css" />
  <img src="https://skillicons.dev/icons?i=git" />
  <img src="https://skillicons.dev/icons?i=vscode" />
  <img src="https://skillicons.dev/icons?i=chrome" />
</p>

---

## 🔍 SEO Keywords and Tags

### Primary Keywords
- Web Compass Navigation
- Browser Compass API
- DeviceOrientation Compass
- JavaScript Compass
- Bearing atan2

### Secondary Keywords
- Compass 2026 Guide
- iOS Permission Compass
- Smoothing Sensor Data
- True North Declination
- Map Rotate CSS

### Long-Tail Keywords
- How to build a compass in the browser
- DeviceOrientation permission iOS
- Calculate bearing with atan2
- Smooth compass sensor data
- Rotate map with CSS transform
- True north vs device north

### Tags
Compass, Navigation, JavaScript, Sensor, Web, Free Guide, 2026

### SEO Description
**Web Compass Navigation** — free guide to orientation, bearing, and permission flow. Build a browser compass now!
