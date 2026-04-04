# qFlasher 🐬 v2.0

![Logo](https://raw.githubusercontent.com/FunpaySmartBot/qFlasher/refs/heads/main/logo.png)

**Web-based Flipper Zero File Manager** - Real-time SD card browser, upload/download, WebUSB device connection. qFlipper alternative for web.

## 🚀 Features

✅ **Real Device Connection** - WebUSB + Mass Storage
✅ **SD Card File Browser** - Tree view, path breadcrumbs, recursive
✅ **Full File Ops** - Upload/download (export/import), create folder/file, rename, delete
✅ **Real-time Logs** - Console panel for connection/events/errors/debug
✅ **Drag-drop Upload** - To any directory
✅ **qFlipper UI** - Dark theme, sidebar (Files/Apps/Assets/Logs)
✅ **Zero Dependencies** - Pure vanilla HTML/CSS/JS
✅ **HTTPS Ready** - GitHub Pages/Netlify deployment

## 🎯 Quick Start

### 1. Deploy (HTTPS Required for WebUSB)
```
git add .
git commit -m "Deploy qFlasher v2.0"
git push origin main
```
**GitHub Pages:** Settings → Pages → Deploy from `main` → Live at `username.github.io/repo`

### 2. Connect Flipper Zero
1. **Flipper:** Settings → USB → Mass Storage → Connect USB cable
2. **Browser:** Click "Connect Flipper (USB)"
3. **Select:** Flipper SD card drive when prompted
4. **Browse:** Full directory tree + upload/download

## 📱 Usage

```
Header: 🐬 qFlasher [Connected]
Sidebar: Files | Apps | Firmware | Assets
Main: 📁 apps/ 📄 badusb.txt 📁 subghz/
Buttons: [Upload Here] [Download]
```

## 🛠 Setup & Troubleshooting

**Browser:** Chrome 89+ / Edge 89+ (WebUSB + File System Access)
**HTTPS:** Required (GitHub Pages/Netlify)

```
# Local HTTPS dev
npx local-web-server --https

# Local test (no WebUSB)
start index.html
```

**Connection Issues:**
```
❌ "USB not available" → HTTPS required
❌ "No SD card" → Enable Mass Storage on Flipper
❌ "Permission denied" → Chrome/Edge security settings
```

## 📂 File Structure

```
├── index.html          # Main app + qFlipper UI
├── README.md           # This doc
├── css/style.css       # Dark theme (qFlipper style)
├── js/app.js           # WebUSB connect + File System API (browse/upload/delete/rename/create/logs)
├── TODO.md             # Build progress (complete)
```

## 🔮 Roadmap

- [ ] Apps installer (.fap)
- [ ] Firmware updater
- [ ] Wireless (BLE/WiFi)
- [ ] Bulk operations
- [ ] Themes (light mode)

## 🤝 Contributing

1. Fork + PR
2. Test on HTTPS
3. Update README screenshots
4. Follow vanilla JS style

## 📄 License

MIT - Free for all Flipper projects

**Apps:** <a href="https://lab.flipper.net/apps">lab.flipper.net/apps</a><br>
**Author:** <a href="https://github.com/FunPaySmartBot">@FunPaySmartBot</a><br>
**⭐ Star if useful!** · **🐬 Flipper Zero Community**

