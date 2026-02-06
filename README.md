# Region Time Counter (ReaScript)

**Region Time Counter** is a minimal utility script for REAPER that displays the  
**total unique length of all regions** in the current project.

Overlapping regions are merged, so overlapping parts are **not double-counted**.

Designed as a small, clean, always-on utility window.

---

## Features

- Counts **unique region time** (union of all regions)
- Correct handling of **overlapping regions**
- Time displayed in **HH:MM:SS**
- Window width is fixed to **99:59:59** (no UI jumping)
- Compact, minimal UI (title + time only)
- Auto-refreshes while open
- No popups, no buttons
- No dependencies (no SWS, no js extensions)

---

## Installation

1. Download `Region Time Counter.lua`
2. In REAPER, open:

   ```
   Actions → Show action list → ReaScript → Load…
   ```

3. Select `Region Time Counter.lua`
4. Run the script

You can assign it to a shortcut or add it to a toolbar.

---

## Usage

- Launch the script to open a small floating window
- The displayed time updates automatically
- Close the window using the window close button or `Esc`

---

## Notes

- The window title is intentionally empty to avoid macOS minimum titlebar width limitations.
- The visible title (“Region Time Counter”) is drawn inside the UI.
- Time is always shown in `HH:MM:SS` format.

---

Part of **34tools — Audio Tools by Alexey Vorobyov (34birds)**.

---

## License

MIT License
