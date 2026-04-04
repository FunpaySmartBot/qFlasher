markdown

 qFlasher - Flipper Zero File Manager ![qFlasher Logo](https://raw.githubusercontent.com/FunpaySmartBot/qFlasher/refs/heads/main/logo.png)

qFlasher is a modern web-based file manager for Flipper Zero. Connect via Web Serial, browse files, manage storage, and execute RPC commands.

## Features
```File Management: 📁 Create Folders | 📄 Create Files | ⬆️ Upload | ⬇️ Download (WIP) | 🗑️ Delete
Device Info: 🔋 Battery | 🆔 Name | 📊 Space | 🛠️ Version
Console: 📡 RPC | 🔄 Expandable | 📋 Logs
```

## Keyboard Shortcuts
Ctrl/Cmd+N = New Folder | Ctrl/Cmd+E = New File | Ctrl+Click = Multi-select

## Quick Start
1. Flipper Zero -> USB -> Chrome/Edge
2. Click "🔌 Connect Device" 
3. Browse / upload / delete files
4. Console: {"method":"storage_list","params":{"path":"/"}}

## Supported
Browsers: Chrome 80+ ✅ | Edge 79+ ✅ | Firefox ❌ | Safari ❌
Firmwares: qFlipper ✅ | Momentum ✅ | Unleashed ✅ | RogueMaster ✅ | ANY RPC ✅

## File Operations
📁 New Folder -> Creates dir | 📄 New File -> Empty file
⬆️ Upload -> Multi-file | 🔄 Refresh -> Reload | 🗑️ Delete -> Selected

## Console Commands
{"method":"storage_list","params":{"path":"/"}}  // List files
{"method":"system_info"}                         // Device info  
{"method":"power_info"}                          // Battery
{"method":"storage_info"}                        // Free space
{"method":"storage_mkdir","params":{"path":"/test"}} // Create folder

## Troubleshooting
No ports? -> chrome://flags -> Web Serial
Battery "-"? -> {"method":"power_get_info"}
No storage? -> {"method":"storage_info"}

## Usage
Save HTML as index.html -> Open in Chrome -> Connect -> Done!

## License
MIT - Free for all Flipper projects
Created by FunpaySmartBot

⭐ Star if useful! qFlasher v1.3 🚀
