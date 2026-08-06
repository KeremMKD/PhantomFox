# PhantomFox user.js

A minimalist but powerful **`user.js` configuration** for Firefox.  
Designed as a lightweight alternative to **Arkenfox** and **Betterfox**, focused on **privacy, security, and performance** without breaking usability.  

PhantomFox disables telemetry, Firefox Sync, tracking features, and adds several performance optimizations — while keeping important protections (like Safe Browsing) enabled.  

---

## ✨ Features
- Works on **Linux, macOS, and Windows**  
- **Privacy-first**: disables telemetry, Sync, WebRTC leaks, geolocation, battery API, and more  
- **Performance tweaks**: hardware acceleration, optimized connections, WebRender  
- **Minimal startup**: Firefox opens with `about:blank` for speed and focus  
- **Security**: Safe Browsing (malware & phishing protection) stays enabled  
---

## ❤️ PhantomFox supports all Firefox-based browsers
Yes, you heard right, PhantomFox user.js works on all Firefox-based browsers! It works correctly on all Firefox-based browsers such as Zen, LibreWolf, and WaterFox. My goal here is to achieve a much more user-friendly experience. You can also apply the following download steps to your own Firefox-based browser.

---

## 📥 Installation

### 1. Download the `user.js`
Clone this repository or just download the `user.js` file:

```bash
git clone https://github.com/KeremMKD/PhantomFox.git
cd PhantomFox
```

Or download manually: [user.js](./user.js)

---

### 2. Locate Your Firefox Profile
Find your profile folder:

- **Linux**: `~/.mozilla/firefox/xxxxxxxx.default-release/`
- **macOS**: `~/Library/Application Support/Firefox/Profiles/xxxxxxxx.default-release/`
- **Windows**: `%APPDATA%\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\`

Replace `xxxxxxxx.default-release` with your actual profile name.

---

### 3. Copy `user.js` into Profile
```bash
cp user.js ~/.mozilla/firefox/xxxxxxxx.default-release/
```

For macOS:
```bash
cp user.js ~/Library/Application\ Support/Firefox/Profiles/xxxxxxxx.default-release/
```

For Windows (PowerShell):
```powershell
copy user.js "$env:APPDATA\Mozilla\Firefox\Profiles\xxxxxxxx.default-release\"
```

Restart Firefox. Done ✅

---

## 📌 Why PhantomFox?

Unlike Arkenfox (huge, complex configs) and Betterfox (performance-heavy tweaks), **PhantomFox is simple**:
- Not hundreds of prefs, just the essentials
- Focused on **real-world privacy & security**
- Works **out of the box** — no constant tweaking required

---

## 📜 License

This project is licensed under the **GNU General Public License v3.0**.  
See the LICENSE file for details.
