<h1 align="center">Cr0mb</h1>

<p align="center">
  Cybersecurity researcher and Python developer focused on game hacking, reverse engineering, and offensive tooling.
</p>

<p align="center">
  <a href="https://github.com/Cr0mb">
    <img src="https://img.shields.io/github/followers/Cr0mb?label=Followers&style=for-the-badge&color=2b3137" alt="GitHub Followers" />
  </a>
  <a href="https://github.com/Cr0mb?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-106-2b3137?style=for-the-badge" alt="Repositories" />
  </a>
  <a href="https://www.youtube.com/@cr0mble">
    <img src="https://img.shields.io/youtube/channel/subscribers/UCQ-4CeZQg1Fb4HtcFJfYBfg?label=YouTube&style=for-the-badge&color=2b3137" alt="YouTube Subscribers" />
  </a>
  <a href="https://www.unknowncheats.me/forum/members/5262305.html">
    <img src="https://img.shields.io/badge/UnknownCheats-Profile-2b3137?style=for-the-badge" alt="UnknownCheats Profile" />
  </a>
</p>

<p align="center">
  <img src="https://github.com/Cr0mb/Cr0mb/blob/main/capture.gif" alt="Banner" width="820" />
</p>

---

## About

Self-taught Python developer working primarily in offensive security and game hacking. I started coding at six out of pure curiosity, never anything malicious, and I have stuck with Python ever since because rapid iteration matters more than runtime when you are reverse engineering and prototyping.

I publish tutorials on YouTube covering CS2 cheat development, memory reading and writing, ESP, and reverse engineering, and maintain open-source projects across game cheats, blockchain tooling, network scanners, and encrypted communications.

**Discord:** `cr0mbleonthegame`

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat-square" alt="Python" />
  <img src="https://img.shields.io/badge/Assembly-525252?logo=assemblyscript&logoColor=white&style=flat-square" alt="Assembly" />
  <img src="https://img.shields.io/badge/PyQt5-41CD52?logo=qt&logoColor=white&style=flat-square" alt="PyQt5" />
  <img src="https://img.shields.io/badge/ctypes-3776AB?style=flat-square" alt="ctypes" />
  <img src="https://img.shields.io/badge/pymem-3776AB?style=flat-square" alt="pymem" />
  <img src="https://img.shields.io/badge/Win32%20API-0078D6?logo=windows&logoColor=white&style=flat-square" alt="Win32 API" />
  <img src="https://img.shields.io/badge/Cheat%20Engine-DC322F?style=flat-square" alt="Cheat Engine" />
  <img src="https://img.shields.io/badge/Reverse%20Engineering-1A1A1A?style=flat-square" alt="Reverse Engineering" />
  <img src="https://img.shields.io/badge/Blockchain-F7931A?logo=bitcoin&logoColor=white&style=flat-square" alt="Blockchain" />
</p>

---

## Featured Projects

### GHax — CS2 External Cheat
[CS2-GHax-Python](https://github.com/Cr0mb/CS2-GHax-Python) · v3.6.1 · 76+ commits

Full-featured external cheat for Counter-Strike 2. PyQt5 GUI with adaptive aimbot (per-weapon recoil learning persisted across sessions), TriggerBot, BHop, full ESP suite (Box, Bone, Skeleton, Glow, Health, Armor, Distance, Weapon, Bomb, Flash, Spectator List, Radar), velocity prediction, FOV control, and configurable colors. Recent versions encrypt the source at runtime with Fernet AES-128 and load all code from memory.

Public release thread on [UnknownCheats](https://www.unknowncheats.me/forum/counter-strike-2-releases/633657-cs2-python-cheat.html) with version-by-version showcase videos on YouTube.

### GFusion — CS2 Cheat Framework
[CS2-GFusion-Python](https://github.com/Cr0mb/CS2-GFusion-Python) · v2.5

Fully external CS2 framework built without `pymem` or `pyMeow` — pure `ctypes` and Win32 calls. DirectX11 overlay (replacing the older GDI implementation) for a major rendering performance jump, plus Aimbot, ESP, Glow, TriggerBot, BHop, Walkbot, player info box, and OBS-proof screen capture handling.

### Cryptonix — BTC/ETH Scanner
[Cryptonix-BTC-ETH-Scanner](https://github.com/Cr0mb/Cryptonix-BTC-ETH-Scanner) · 40 stars · 18 forks

Educational tool that generates Bitcoin and Ethereum keypairs and queries balances against block explorers. The repo documents the absurdity of the keyspace: at roughly 76 trillion possibilities, hitting a funded wallet is statistically less likely than winning a daily lottery every day for life. Built on `hdwallet`, `colorama`, and `pyfiglet`.

### CrumbHub and CrumbShare — Encrypted Communications
[CrumbHub](https://github.com/Cr0mb/CrumbHub) · [CrumbShare](https://github.com/Cr0mb/CrumbShare)

End-to-end encrypted command-line tooling over raw sockets. CrumbHub is a multi-user real-time chat. CrumbShare is a peer-to-peer encrypted file sharing tool.

---

## Project Catalog

### Game Hacking and Cheats

| Project | Description |
| ------- | ----------- |
| [CS2-GHax-Python](https://github.com/Cr0mb/CS2-GHax-Python) | Flagship CS2 cheat — ESP, aimbot, TriggerBot, BHop, PyQt5 GUI |
| [CS2-GFusion-Python](https://github.com/Cr0mb/CS2-GFusion-Python) | CS2 framework, pure ctypes + DirectX11 overlay, no pymem |
| [CS2-Cheat-Python](https://github.com/Cr0mb/CS2-Cheat-Python) | Original CS2 cheat project |
| [Surf-Info-Overlay](https://github.com/Cr0mb/Surf-Info-Overlay) | CS2 surf overlay showing coords, velocity, and speed |
| [CS-GO-Python-Cheat](https://github.com/Cr0mb/CS-GO-Python-Cheat) | CS:GO cheat scripts including ESP features |
| [CS-GO-Wireframe](https://github.com/Cr0mb/CS-GO-Wireframe) | Wireframe wallhack for CS:GO |
| [Assassin-s-Creed-2-Memory-Modifier](https://github.com/Cr0mb/Assassin-s-Creed-2-Memory-Modifier) | God Mode and infinite money via memory editing |
| [Assault-Cube-Client-Memory-Manipulation](https://github.com/Cr0mb/Assault-Cube-Client-Memory-Manipulation) | AssaultCube stat editor |
| [Assault-Cube-Mod-Menu](https://github.com/Cr0mb/Assault-Cube-Mod-Menu) | Tkinter mod menu for AssaultCube |
| [AssaultCube-ESP-Python-Cheat](https://github.com/Cr0mb/AssaultCube-ESP-Python-Cheat) | ESP overlay for AssaultCube |
| [Call-of-Duty-Black-Ops-1-Zombies-Cheat-Script](https://github.com/Cr0mb/Call-of-Duty-Black-Ops-1-Zombies-Cheat-Script) | BO1 Zombies — health, points, ammo, grenades |
| [Far-Cry-3-Memory-Editor](https://github.com/Cr0mb/Far-Cry-3-Memory-Editor) | Far Cry 3 health, money, and ammo editor |
| [Morrowind-ESP-Overlay](https://github.com/Cr0mb/Morrowind-ESP-Overlay) | External ESP for Morrowind |
| [Morrowind-Memory-Editor](https://github.com/Cr0mb/Morrowind-Memory-Editor) | Morrowind stat and attribute editor |
| [Skyrim-Memory-Editor-Python](https://github.com/Cr0mb/Skyrim-Memory-Editor-Python) | Skyrim memory read/write cheats |
| [AOB-Scanning-Tutorial-Minecraft-Java-Edition](https://github.com/Cr0mb/AOB-Scanning-Tutorial-Minecraft-Java-Edition) | Array-of-Bytes scanning tutorial |
| [Minecraft-Bedrock-Cheat-Engine-Table](https://github.com/Cr0mb/Minecraft-Bedrock-Cheat-Engine-Table) | Cheat Engine table for Minecraft Bedrock |
| [MinecraftBedrock-XP-Editor](https://github.com/Cr0mb/MinecraftBedrock-XP-Editor) | XP and stats editor for Minecraft Bedrock |
| [Minecraft-Game-Mode-Toggle-Script](https://github.com/Cr0mb/Minecraft-Game-Mode-Toggle-Script) | Auto-toggle Creative/Survival |
| [mcWizard](https://github.com/Cr0mb/mcWizard) | Minecraft utility automation |

### Cryptography and Blockchain

| Project | Description |
| ------- | ----------- |
| [Cryptonix-BTC-ETH-Scanner](https://github.com/Cr0mb/Cryptonix-BTC-ETH-Scanner) | BTC and ETH keypair generator and balance scanner |
| [BreadCracker](https://github.com/Cr0mb/BreadCracker) | Mnemonic-seed wallet scanner with balance checking |
| [Satoshi-Sweeper](https://github.com/Cr0mb/Satoshi-Sweeper) | Bitcoin blockchain data sweeping and monitoring |
| [Crypto-Sweeper](https://github.com/Cr0mb/Crypto-Sweeper) | Cryptocurrency network scanner |
| [Wallet-Generator-and-Balance-Checker](https://github.com/Cr0mb/Wallet-Generator-and-Balance-Checker) | Wallet generation and balance check |
| [Bitcoin-Buy-Sell-Signal-Predictor](https://github.com/Cr0mb/Bitcoin-Buy-Sell-Signal-Predictor) | ML and technical-analysis based BTC price prediction with live chart |
| [Litecoin-Trading-Bot](https://github.com/Cr0mb/Litecoin-Trading-Bot) | Automated LTC trading via exchange APIs |
| [BreadCrypt-File-Encryptor](https://github.com/Cr0mb/BreadCrypt-File-Encryptor) | AES file encryption and decryption with passphrase |
| [Bread-Logger](https://github.com/Cr0mb/Bread-Logger) | Encrypted Python password manager |

### Networking and Security Tools

| Project | Description |
| ------- | ----------- |
| [Python-Web-Scanner](https://github.com/Cr0mb/Python-Web-Scanner) | Active server discovery and IP organization |
| [Python-Web-Scanner-2.0](https://github.com/Cr0mb/Python-Web-Scanner-2.0) | Async port scanning, geo lookup, proxy detection, subnet discovery |
| [Proxy-Scraper](https://github.com/Cr0mb/Proxy-Scraper) | Proxy server list collector |
| [IP-Lookup](https://github.com/Cr0mb/IP-Lookup) | Geo and ISP info from IP addresses |
| [Windscribe-IP-Changer](https://github.com/Cr0mb/Windscribe-IP-Changer) | Automated Windscribe VPN IP rotation |
| [Browser-Credential-Extractor-Keylogger](https://github.com/Cr0mb/Browser-Credential-Extractor-Keylogger) | Saved credential extraction with activity logging |
| [Browser-Data-Extraction-Scripts](https://github.com/Cr0mb/Browser-Data-Extraction-Scripts) | Bookmarks, passwords, cookies, history, cache, and downloads |
| [Browser-Data-Extraction](https://github.com/Cr0mb/Browser-Data-Extraction) | Earlier browser data extraction tool |
| [How-To-PDANet](https://github.com/Cr0mb/How-To-PDANet) | PDANet tethering guide and scripts |

### Encrypted Communications

| Project | Description |
| ------- | ----------- |
| [CrumbHub](https://github.com/Cr0mb/CrumbHub) | End-to-end encrypted multi-user CLI chat |
| [CrumbShare](https://github.com/Cr0mb/CrumbShare) | End-to-end encrypted P2P file sharing |
| [File-Downloader](https://github.com/Cr0mb/File-Downloader) | HTTP and multi-protocol downloader |

### Automation and Scrapers

| Project | Description |
| ------- | ----------- |
| [GitHub-Repository-Fetcher](https://github.com/Cr0mb/GitHub-Repository-Fetcher) | GitHub repo metadata fetcher, terminal and GUI versions |
| [YouTube-Channel-Video-Viewer](https://github.com/Cr0mb/YouTube-Channel-Video-Viewer) | YouTube channel video scraper |
| [Reddit-Scraper](https://github.com/Cr0mb/Reddit-Scraper) | Reddit post, comment, and user extractor |
| [Automate-Sending-Requests-to-a-Website-Using-Python](https://github.com/Cr0mb/Automate-Sending-Requests-to-a-Website-Using-Python) | HTTP request automation |
| [Simple-Steam-Idler](https://github.com/Cr0mb/Simple-Steam-Idler) | Steam idling automation for playtime and achievements |
| [Steam-Profile-Game-Scraper](https://github.com/Cr0mb/Steam-Profile-Game-Scraper) | Steam profile and game data scraper |
| [Minecraft-Server-Status-Checker](https://github.com/Cr0mb/Minecraft-Server-Status-Checker) | Minecraft server status and latency checker |

---

## GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=Cr0mb&show_icons=true&theme=tokyonight&hide_border=true&count_private=false" height="180" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Cr0mb&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="180" alt="Top Languages" />
</p>

---

## Skills

| Area | Tools and Techniques |
| ---- | -------------------- |
| Languages | Python (primary), Assembly |
| Game Hacking | Memory read/write, AOB scanning, offset chasing, ESP overlays, aimbot logic, recoil control, BHop, TriggerBot |
| Reverse Engineering | Cheat Engine, dynamic analysis, signature scanning, runtime offset extraction |
| GUI and Rendering | PyQt5, Tkinter, Win32 GDI, DirectX11 overlays |
| Security | Keylogging, browser data extraction, obfuscation (PyArmor, Nuitka, base64, Fernet) |
| Networking | Async HTTP (`aiohttp`), web scraping, proxy and port scanning, raw sockets, P2P |
| Blockchain | HD wallet generation, mnemonic recovery, block-explorer APIs, trading bots |
| Build and Distribution | PyInstaller, Nuitka, virtual environments, in-memory code loading |

---

## Connect

- YouTube — <https://www.youtube.com/@cr0mble>
- UnknownCheats — <https://www.unknowncheats.me/forum/members/5262305.html>
- Steam — <https://steamcommunity.com/id/Cr0mbs_Space/>
- Discord — `cr0mbleonthegame`

Active discussion for the CS2 projects happens in the Discord server linked from the GHax and GFusion repos.

---

## Inspiration

The handle comes from Robert Crumb. The Terry Zwigoff documentary *Crumb* set the tone: keep it real, create freely, never sell out. [Watch it here](https://tubitv.com/movies/100007594/crumb).

---

<details>
  <summary><b>Support my work</b></summary>
https://ghaxlabs.com/donate
<br>

</details>

---

## Contributing

Pull requests are welcome on every public repo. For larger contributions or research collaborations, reach out on Discord first.
