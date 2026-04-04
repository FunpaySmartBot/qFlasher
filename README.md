

# qFlasher README - COMPLETE SINGLE FILE

![qFlasher Logo](https://raw.githubusercontent.com/FunpaySmartBot/qFlasher/refs/heads/main/logo.png)

qFlasher - Flipper Zero Web File Manager + RPC Console

# FEATURES:
```
File: 📁 New Folder | 📄 New File | ⬆️ Upload | 🗑️ Delete | 🔄 Refresh
Info: 🔋 Battery | 🆔 Name | 📊 Space | 🛠️ Version
Console: 📡 RPC | 🔄 Expand (⬜/🗗) | 📋 Clear
```

# SHORTCUTS:
```
Ctrl+N = New Folder | Ctrl+E = New File | Ctrl+Click = Multi-select
```
# QUICK START:
```
1. Flipper Zero -> USB -> Chrome/Edge
2. Click 🔌 Connect Device
3. Browse files / console commands
```
# BROWSERS:
```
Chrome 80+ ✅ | Edge 79+ ✅ | Firefox ❌ | Safari ❌
```
# FIRMWARES:
```
qFlipper✅ Momentum🟠 Unleashed✅ RogueMaster✅ ANY RPC✅
```
# FILE OPERATIONS:
```
New Folder (📁) -> Creates directory
New File (📄) -> Creates empty file
Upload (⬆️) -> Multi-file upload
Refresh (🔄) -> Reload directory
Delete (🗑️) -> Selected files/folders
```
# CONSOLE COMMANDS:
```
{"method":"storage_list","params":{"path":"/"}}     List root
{"method":"system_info"}                            Device info
{"method":"power_info"}                             Battery
{"method":"storage_info"}                           Free space
{"method":"storage_mkdir","params":{"path":"/test"}} Create folder
```
# TROUBLESHOOTING:
```
No ports? chrome://flags -> Enable Web Serial
Battery shows -? {"method":"power_get_info"}
No storage? {"method":"storage_info"}
Console not expanding? Browser zoom = 100%
```
# DEVELOPMENT:
Save HTML as index.html -> Open Chrome -> Connect -> Done! or use my site

# OTHER
Free for all Flipper projects
CREATOR: FunpaySmartBot

ROADMAP: Download | Bulk ops | Drag-drop | Themes
VERSION: v1.3 - Ultimate Flipper companion 🚀

⭐ Star if useful! Works with ALL RPC firmwares!
