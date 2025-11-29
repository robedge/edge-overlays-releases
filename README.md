# Edge Overlays

[![Release](https://img.shields.io/github/v/release/robedge/edge-overlays-releases)](https://github.com/robedge/edge-overlays-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/robedge/edge-overlays-releases/total)](https://github.com/robedge/edge-overlays-releases/releases)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/robedge/edge-overlays-releases/blob/main/LICENSE)

Professional transparent telemetry overlays for iRacing. Monitor your car's performance in real-time with customizable, always-on-top displays.

## ✨ Features

### Multiple Overlay Types

- **📊 Telemetry Overlay** - Real-time speed, RPM, gear, and fuel monitoring
- **🎮 Input Overlay** - Visualize steering, throttle, brake, and clutch inputs
- **📡 Radar Overlay** - Track nearby cars with position-aware radar
- **⏱️ Relative Overlay** - Monitor gap times to cars ahead and behind
- **⛽ Fuel Overlay** - Fuel consumption, laps remaining, and pit strategy
- **🌤️ Weather Overlay** - Track conditions, temperature, and forecast

### Core Features

- ✨ **Always-On-Top** - Overlays stay visible while racing in borderless window mode
- 🎯 **Click-Through Mode** - Lock overlays for gaming, unlock to reposition
- 📊 **Real-Time Data** - Direct integration with iRacing SDK for instant telemetry
- 🎨 **Modern Design** - Clean, professional interface with smooth animations
- ⚙️ **Unit Flexibility** - Switch between metric (km/h, L) and imperial (mph, gal)
- 💾 **Smart Persistence** - All positions and settings saved automatically
- 🔄 **Auto-Updates** - Built-in update checker with one-click installation
- 🪶 **Performance** - Minimal CPU/GPU impact during races
- 🎮 **System Tray** - Minimize to tray, quick toggle overlays

## 📥 Download

**[⬇️ Download Latest Release](https://github.com/robedge/edge-overlays-releases/releases/latest)**

### System Requirements

| Requirement | Specification |
|------------|---------------|
| OS | Windows 10/11 (64-bit) |
| iRacing | Active subscription |
| Display Mode | Borderless Window* |

\* **Important**: iRacing must run in Borderless Window mode for overlays to appear on top

## 🚀 Installation

1. Download `Edge.Overlays.Setup.{version}.exe` from [releases](https://github.com/robedge/edge-overlays-releases/releases/latest)
2. Run the installer
3. Follow the installation wizard
4. Launch **Edge Overlays** from Start Menu or desktop shortcut

## 📖 Quick Start Guide

### Getting Started

1. **Launch the App** - Start Edge Overlays before or during your iRacing session
2. **Configure iRacing**
   - Go to iRacing Graphics Settings
   - Set **Display Mode** to **Borderless Window**
   - Apply and restart iRacing if needed
3. **Add Overlays**
   - Click `+ Telemetry`, `+ Inputs`, or other overlay buttons
   - Multiple overlays can be active simultaneously
4. **Position Overlays**
   - Click `🔓 Unlocked` to enable dragging
   - Drag overlays to your preferred positions
   - Positions save automatically
5. **Lock for Racing**
   - Click `🔒 Locked` to enable click-through mode
   - Overlays become transparent to mouse clicks
6. **Race!** - Overlays automatically connect when you enter a session

### Control Panel

The control panel provides:

- **Connection Status** - Green when connected to iRacing, gray when waiting
- **Live Telemetry Preview** - See current speed, RPM, gear, and fuel
- **Overlay Management** - Add, remove, and toggle overlay visibility
- **Settings**
  - 🔒 **Overlay Lock** - Toggle click-through mode
  - 📏 **Units** - Choose metric or imperial measurements
  - 🔄 **Updates** - Check for new versions

### System Tray

Edge Overlays lives in your system tray:

- **Left-click** (Windows/Linux) - Toggle control panel visibility
- **Right-click** - Access menu
  - Show/Hide Control Panel
  - Toggle All Overlays
  - Quit Application

## ⚙️ Configuration

### Unit Preferences

| Setting | Metric | Imperial |
|---------|--------|----------|
| Speed | km/h | mph |
| Fuel | Liters | Gallons |

### Overlay States

| Lock State | Behavior |
|------------|----------|
| 🔒 Locked | Click-through enabled - perfect for racing |
| 🔓 Unlocked | Draggable - reposition as needed |

All settings persist across sessions and app restarts.

## 🔧 Troubleshooting

### Overlays Not Appearing

1. ✅ Ensure iRacing is running in **Borderless Window** mode
2. ✅ Verify you're in an active session (not main menu)
3. ✅ Check Edge Overlays shows "Connected" status
4. ✅ Try toggling overlay visibility with the toggle switch
5. ✅ Unlock overlays and check if they're off-screen

### Connection Issues

- ⏳ Wait for the session to fully load before expecting telemetry
- 🔄 Restart Edge Overlays if connection issues persist
- 🎮 Ensure iRacing is actually running (not just Launcher)
- 💻 Check Windows Event Viewer for any related errors

### Performance Optimization

Edge Overlays is optimized for minimal impact:

- Uses native iRacing SDK integration (no polling)
- Hardware-accelerated rendering via Chromium
- Efficient 30 Hz update rate (lower than iRacing's 60 Hz)
- Low memory footprint (~50-100 MB total)

If you experience performance issues:
1. Close unused overlays
2. Reduce number of active overlays
3. Check Task Manager for other background processes

## 📦 Updates

Edge Overlays includes automatic update checking:

1. Open Settings in the control panel
2. Click **Check for Updates**
3. If available, click **Download**
4. Progress shown in control panel title bar
5. Choose **Restart Now** or **Later** when download completes

Updates are delivered securely through GitHub Releases.

## ❓ FAQ

**Q: Does this work with other racing simulators?**
A: No, Edge Overlays is designed specifically for iRacing using the official SDK.

**Q: Will this affect my iRacing performance or FPS?**
A: No, Edge Overlays uses the official SDK with minimal CPU/GPU impact.

**Q: Can I use this in VR?**
A: The overlays are designed for monitor-based racing. VR support is not currently available.

**Q: Is this allowed by iRacing?**
A: Yes, Edge Overlays uses the official iRacing SDK and doesn't modify any game files or provide unfair advantages.

**Q: How do I uninstall?**
A: Windows Settings → Apps → Edge Overlays → Uninstall

**Q: Can I customize the overlay appearance?**
A: Currently overlays use a fixed professional design. Customization may be added in future versions.

**Q: Does this support multi-monitor setups?**
A: Yes, overlays can be positioned on any monitor. Positions are saved per-monitor.

## 📜 License

MIT License - see [LICENSE](LICENSE) file for details

## 🐛 Support & Issues

Having problems or want to request a feature?

- 📝 [Open an Issue](https://github.com/robedge/edge-overlays-releases/issues/new)
- 📖 Check [existing issues](https://github.com/robedge/edge-overlays-releases/issues)

When reporting issues, please include:
- Windows version
- iRacing version
- Edge Overlays version
- Steps to reproduce
- Screenshots if applicable

## 📝 Changelog

See [Releases](https://github.com/robedge/edge-overlays-releases/releases) for detailed version history.

### Latest Release - v0.4.0

- Rebranded to Edge Overlays
- Added "Check for Updates" button with version display
- Improved update notification system
- Enhanced system tray integration
- Bug fixes and performance improvements

## 🙏 Acknowledgments

- Built with the official [iRacing SDK](http://www.iracing.com/)
- Powered by [Electron](https://www.electronjs.org/), [Svelte](https://svelte.dev/), and [TypeScript](https://www.typescriptlang.org/)
- Icons and UI inspired by modern racing telemetry systems

---

**Built with ❤️ for the iRacing community**

[Download Latest Release](https://github.com/robedge/edge-overlays-releases/releases/latest) | [View All Releases](https://github.com/robedge/edge-overlays-releases/releases) | [Report Issue](https://github.com/robedge/edge-overlays-releases/issues/new)

