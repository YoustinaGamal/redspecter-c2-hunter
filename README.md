# Red Specter: C2 Hunter

============================================================
   R E D   S P E C T E R   ::   C 2   H U N T E R
            O U T B O U N D   W A T C H
============================================================

![Red Specter Logo](https://img.shields.io/badge/Red%20Specter-Security%20Research-red?style=for-the-badge)
![Language](https://img.shields.io/badge/Bash-Script-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Version-v0.1-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

---

## 🛡️ Red Specter: C2 Hunter (Outbound Threat Monitor)

A lightweight Bash tool that displays **active outbound TCP connections** on Linux.  
Designed for **early detection** of suspicious beaconing behavior where malware tries to phone home.

Ideal for:
- Cyber labs
- Training / demos
- Blue team defensive visibility

---

## 🚀 Usage

```bash
sudo ./redspecter-c2-hunter.sh -i 5
-i <seconds> → scanning interval (default: 30s)

Requires sudo for full process visibility
📌 Example Output
[RED-SPECTER::C2] Scan at 2025-12-05 11:00:00
[RED-SPECTER::C2] Active outbound TCP connections (state: ESTABLISHED)
PROTO  LOCAL_ADDR           REMOTE_ADDR          PID   PROCESS
TCP    10.0.2.15:54312      93.184.216.34:443   1234  firefox

🔥 Roadmap
| Version | Feature                              |
| ------- | ------------------------------------ |
| v0.1    | Basic outbound visibility            |
| v0.2    | Simple alert visibility improvements |
| v0.3    | Beacon streak detection + logging    |
| v0.4    | Whitelist trusted destinations       |
| v1.0    | Full defensive release               |

⚠️ Legal Notice

This tool is for authorized defensive use only.
Do not monitor systems without explicit permission.

🤝 Credits

Built by Richard – Red Specter
Co-developed with Vigil (AI Partner)
☕ Support Red Specter

You can help fund future Red Specter tools:

<a href="https://www.buymeacoffee.com/redspecter" target="_blank"><img src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Donate-yellow?style=for-the-badge&logo=buy-me-a-coffee" /></a>

