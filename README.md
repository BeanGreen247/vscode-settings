# VS Code Settings

This repository contains my customized VS Code `settings.json` file.

---

## How to Use

1. Clone this repo:

```bash
git clone https://github.com/BeanGreen247/vscode-settings.git
```

2. Copy `settings.json` to your VS Code user settings folder:

| OS      | Path                                       |
|---------|--------------------------------------------|
| Windows | `%APPDATA%\Code\User\settings.json`        |
| macOS   | `$HOME/Library/Application Support/Code/User/settings.json` |
| Linux   | `$HOME/.config/Code/User/settings.json`    |

3. Example copy commands:

- **Linux/macOS:**

```bash
cp /path/to/vscode-settings/settings.json ~/.config/Code/User/settings.json
```

- **Windows (PowerShell):**

```powershell
Copy-Item -Path "C:\path\to\vscode-settings\settings.json" -Destination "$env:APPDATA\Code\User\settings.json" -Force
```

4. Restart VS Code to apply changes.

5. Launch parameters
```
 --max-old-space-size=8192 --enable-gpu --enable-gpu-rasterization --disable-software-rasterizer --ignore-gpu-blacklist
```  
- **Example usage**
```
 "C:\Program Files\Microsoft VS Code\Code.exe" --max-old-space-size=8192 --enable-gpu --enable-gpu-rasterization --disable-software-rasterizer --ignore-gpu-blacklist
```
---

## Notes

- Linting is disabled and UI simplified for a minimal setup.
- Modify as needed.

---

© 2025 BeanGreen247
