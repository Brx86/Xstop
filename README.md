# Xstop
Pause/resume x11 windows with just one click to reduce CPU usage and heat. Inspired by [xkill](https://man.archlinux.org/man/xkill.1) and [xsuspender](https://github.com/kernc/xsuspender).

## Usage:
Install from AUR：
```bash
paru -S xstop
```
Add a keyboard shortcut in the system settings, the command is `xstop`.

Press the shortcut key, the cursor will become a cross, then click any x11 window with the left mouse button to suspend the process and sub-process of the window; press the shortcut key and click again to resume. The window is unresponsive during the pause, the display may be abnormal, and the operation will be blocked until resumed.