markdown

# qFlasher - Flipper Zero File Manager
[![qFlasher Logo](https://raw.githubusercontent.com/FunpaySmartBot/qFlasher/refs/heads/main/logo.png)](https://raw.githubusercontent.com/FunpaySmartBot/qFlasher/refs/heads/main/logo.png)

**qFlasher** is a modern, web-based file manager for Flipper Zero. Connect via Web Serial, browse files, manage storage, and execute RPC commands with a beautiful dark UI.

## ✨ **Features**
```File Management

Device Info

Console

📁 Create Folders

🔋 Live Battery

📡 RPC Console

📄 Create Files

🆔 Device Name

🔄 Expandable

⬆️ Upload Files

📊 Free Space

💬 Command History

⬇️ Download (WIP)

🛠️ Firmware Version

📋 Clear Logs

🗑️ Delete Files

🔌 Connect/Disconnect

🎮 Keyboard Shortcuts
```

```
Ctrl/Cmd + N  → New Folder
Ctrl/Cmd + E  → New File
Ctrl + Click  → Multi-select
🚀 Quick Start
Connect Flipper Zero
```

```
Flipper Zero → USB → Chrome/Edge
Click "🔌 Connect Device"
Browse Files
```

```
Click folders to navigate
Double-click to open
Ctrl+Click for multi-select
Execute RPC Commands
```

```json


{"method":"storage_list","params":{"path":"/"}}    // List root
{"method":"system_info"}                           // Device info
{"method":"power_info"}                         // Battery'
```

📱 Supported Browsers
Browser

Web Serial

Status

Chrome 80+

✅

Full Support

Edge 79+

✅

Full Support

Firefox

❌

No Web Serial

Safari

❌

No Web Serial
```
🔧 Compatible Firmwares

```
✅ qFlipper / Official
✅ Momentum
✅ Unleashed
✅ RogueMaster
✅ Xtreme
✅ ANY RPC-enabled firmware
🎨 UI Features
Dark Theme - Optimized for late-night flashing
Live Updates - Battery, storage, device info refresh automatically
Responsive - Works on desktop/tablet
Smooth Animations - Console expand/collapse
Toast Notifications - Success/error feedback
```
📂 File Operations
Action

Button

Result

New Folder

📁 New Folder

Creates directory

New File

📄 New File

Creates empty file

Upload

⬆️ Upload

Drag & drop or click

Refresh

🔄 Refresh

Reload directory

Delete

🗑️ Delete

Selected files/folders

🖥️ Console Commands
```json


// List directory
{"method":"storage_list","params":{"path":"/apps"}}

// Device info
{"method":"system_info"}

// Battery status
{"method":"power_info"}

// Storage info
{"method":"storage_info"}

// Create folder
{"method":"storage_mkdir","params":{"path":"/test"}}

// Firmware update check
{"method":"system_get_info"}
```
🐛 Troubleshooting
Issue

Solution

"No ports available"

Enable Web Serial in chrome://flags

Battery shows "-"

Try {"method":"power_get_info"} in console

No storage info

Run {"method":"storage_info"}

Console not expanding

Check browser zoom (100%)

🔗 Development
bash

Copy code
# Clone & serve
git clone <repo>
# Open index.html in Chrome/Edge
# Or use live server extension
📄 License

Copy code
MIT License - Free for all Flipper projects
Created by FunpaySmartBot
🙌 Contributing
[ ] Download files
[ ] Firmware flashing
[ ] Bulk operations
[ ] Drag & drop upload
[ ] Theme customizer
⭐ Star if useful! Connects to ANY RPC-enabled Flipper firmware instantly.


qFlasher v1.3 - The ultimate Flipper Zero companion 🚀
