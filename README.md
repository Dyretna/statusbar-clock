# statusbar-clock

**statusbar-clock** is a lightweight and practical VS Code extension that displays the current time directly in the status bar. Ideal for developers who want to keep track of time without leaving their coding environment.

---

## 🕒 Features

- Displays current time in the status bar (HH:MM format)
- Automatically updates every minute
- Positioned on the far right of the status bar
- Minimal performance impact

---

## 📦 Requirements

No external dependencies required. Works out of the box with VS Code version `^1.102.0` or later.

---

## ⚙️ Extension Settings

Currently, this extension does not include any configurable settings. Future versions may offer:

- Toggle between 12-hour and 24-hour formats
- Custom color or icon
- Option to display seconds

---

## 🐞 Known Issues

- The clock may not appear if the extension is not properly activated (check `activationEvents` in `package.json`)
- May be hidden if the status bar is crowded with other high-priority items

---

## 📋 Release Notes

### 0.0.1

- Initial release
- Displays time in the status bar
- Updates automatically every minute

---

## 💡 Tips

To test the extension, press `F5` in development mode. To use it in your regular VS Code setup, package it with `vsce` and install the `.vsix` file via the Command Palette.

---

**Built with by Dyretna with co-pilot assistance.**
