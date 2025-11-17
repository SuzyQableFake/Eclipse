# Eclipse
🌑 ECLIPSE – Advanced Macro Runner (AFK / Automation Tool)

Created by: Kai_Kurotsuki
Discord: https://discord.com/users/1293589296099491890

🔹 Overview

ECLIPSE is a powerful, lightweight macro automation tool designed for offline, single-player, AFK, and productivity use-cases.
It executes customizable JSON-based macro scripts with precise timing, global hotkeys, safe stopping, and a clean modern UI.

No Python required — fully packaged as a standalone Windows EXE.

✨ Features
✔ JSON Macro Engine

Supports:

"press" – tap a key

"hold" – hold a key for a duration

"wait" – pause the macro

"after" delays

Infinite or custom loop counts

Example:

[
  {"type": "hold", "key": "w", "duration": 2},
  {"type": "hold", "key": "a", "duration": 2},
  {"type": "hold", "key": "s", "duration": 2},
  {"type": "hold", "key": "d", "duration": 2}
]

✔ Global Hotkeys

Start Macro: ALT + E

Stop Macro: ALT + Q
Works everywhere, even when the window is not focused.

✔ Modern GUI (Dark Mode)

ASCII-art ECLIPSE banner

Macro file picker

Repeat settings (0 = infinite)

Live colored console output

Error logs & action logs in real time

Clean splash screen on startup

✔ Fully Offline & Portable

No installation required (one-file EXE)

No Python required

No external dependencies

Works on any Windows machine

Safe exit and crash-proof execution

🔒 Safety Notice

ECLIPSE is intended ONLY for:

Offline / single-player games

AFK automation

Accessibility assistance

Productivity workflows

Not allowed:

Online games

Competitive PvP macros

Anti-cheat bypassing

Cheating, exploiting, or automation that violates ToS

📦 Included Files

ECLIPSE.exe (one-file standalone)

macro.json (editable macro script)

You can create your own macro files and load them through the UI.

🛠 Technical Info

Built in Python 3.10

GUI using Tkinter

Macro engine: pyautogui, pynput

Single-file EXE via PyInstaller

Splash screen + hotkey listener threads

Safe multithreaded stop signals

💬 Support

If you need help, feature requests, or bug reports:
📩 Discord — https://discord.com/users/1293589296099491890

⚖ License / Credits

Created by Kai_Kurotsuki
Copyright © 2025
All rights reserved.
