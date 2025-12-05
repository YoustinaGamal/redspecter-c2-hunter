# Red Specter: C2 Hunter

![Bash](https://img.shields.io/badge/Bash-Script-blue?style=flat-square)
![Status](https://img.shields.io/badge/Version-v0.1-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-purple?style=flat-square)

Simple defensive monitoring tool for **outbound TCP connections**.  
Provides early visibility into suspicious or unknown network activity that could indicate:
- Malware beaconing to a C2 server
- Unauthorized remote access
- Persistent callbacks

Designed for Red Specter lab environments and defensive training use.

---

## 🚀 Usage

```bash
sudo ./redspecter-c2-hunter.sh -i 5
| Option | Description                         |
| ------ | ----------------------------------- |
| `-i`   | Scan interval seconds (default 30s) |
| `-h`   | Help menu                           |
Run with sudo for full process visibility.

📌 Example Output
[RED-SPECTER::C2] Scan at 2025-12-05 11:00:00
[RED-SPECTER::C2] Active outbound TCP connections (ESTABLISHED)
PROTO  LOCAL_ADDR           REMOTE_ADDR          PID   PROCESS
TCP    10.0.2.15:54312      93.184.216.34:443   1240  firefox
🔒 Legal Notice

For authorized defensive monitoring only.
Do not use on networks/systems without explicit permission.
👥 Credits

Red Specter (Richard) — Author
Vigil — AI Co-Intelligence Partner

☕ Support Red Specter
<a href="https://www.buymeacoffee.com/redspecter" target="_blank"> <img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-yellow?style=flat-square&logo=buy-me-a-coffee" /> </a> ```
