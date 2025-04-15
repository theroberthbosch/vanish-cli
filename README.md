![](https://img.shields.io/badge/version-v2.1-green?style=flat-square)
# vanish-cli

**Vanish Protocol v2.1** – A stealth Wi-Fi handshake capture tool for ethical hacking and red team ops.

## Features
- Monitor mode setup
- WPA2 handshake capture via airodump-ng
- Deauthentication via mdk4
- Hidden vault for saving .cap files
- Auto WPA cracking with rockyou.txt
- Kill switch (CTRL+C) to stop cleanly
- .deb installer and command-line tool

## How to Install
Download the `.deb` file from the Releases tab and run:
```bash
sudo dpkg -i vanish-cli.deb
