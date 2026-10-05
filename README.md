# Awesome-Video-Game-Subscription-Service

## Top Video Game Subscription Service Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Game Streaming, Self-Hosted Cloud Gaming & Unified Game Libraries*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Video Game Subscription Services**. These tools provide access to game libraries, cloud streaming, and unified game launchers — from commercial subscription services to self-hosted cloud gaming platforms that let you play your own games on remote hardware.



**Examples** include Xbox Game Pass Ultimate, PlayStation Plus Premium, EA Play, Ubisoft+, Nintendo Switch Online, Apple Arcade, Google Play Pass, Amazon Luna+, Antstream Arcade, and GeForce NOW (the category leaders).



**Open-source emphasis**: Cloud gaming is one of the fastest-growing open-source domains, with **Cloudy Pad** leading as a free alternative to GeForce Now and Blacknut , **CloudMorph** providing self-hosted browser-based game streaming , and unified launchers like **Heroic Games Launcher** and **Lazap** consolidating Steam, Epic, GOG, and Amazon libraries . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Xbox Game Pass Ultimate](https://www.xbox.com/game-pass)**  

  Microsoft's all-in-one subscription with 400+ games across console, PC, and cloud. Includes unlimited cloud gaming, day-one new titles, online multiplayer, EA Play, Fortnite Crew, and Ubisoft+ Classics. **The most comprehensive game subscription service** . Cloud gaming now out of beta with Game Pass Essential, Premium, and Ultimate plans . Note: Microsoft is reducing cloud gaming support on older Samsung TVs (2020 models) from November 2026 .



- **[PlayStation Plus Premium](https://www.playstation.com/ps-plus/)**  

  Sony's premium tier with Cloud Streaming for select PS5 games to PS5 consoles and PlayStation Portal remote player . Requires minimum 5 Mbps connection; 4K recommended at 52 Mbps. Available in US, Canada, Japan, and select European countries. Includes Game Catalogue, Classics Catalogue, and Game Trials .



- **[EA Play](https://www.ea.com/ea-play)**  

  EA's subscription service with access to EA's game library, early trials, and discounts. Included with Xbox Game Pass Ultimate .



- **[Ubisoft+](https://www.ubisoft.com/ubisoftplus)**  

  Ubisoft's subscription with access to new releases and classic titles. Ubisoft+ Classics included with Xbox Game Pass Ultimate .



- **[Nintendo Switch Online](https://www.nintendo.com/switch/online/)**  

  Nintendo's subscription for online play and classic game libraries (NES, SNES, N64, Sega Genesis).



- **[Apple Arcade](https://www.apple.com/apple-arcade/)**  

  Apple's game subscription with 200+ premium games across iPhone, iPad, Mac, and Apple TV. No ads, no in-app purchases.



- **[Google Play Pass](https://play.google.com/store/pass/get)**  

  Google's subscription for 1,000+ premium Android games and apps without ads or in-app purchases.



- **[Amazon Luna+](https://www.amazon.com/luna/)**  

  Amazon's cloud gaming service with channel-based subscriptions (Luna+, Ubisoft+, etc.) and Prime Gaming integration.



- **[Antstream Arcade](https://www.antstream.com/)**  

  Retro game streaming service with 1,300+ classic arcade and console games from the 80s and 90s.



- **[GeForce NOW](https://www.nvidia.com/geforce-now/)**  

  NVIDIA's cloud gaming service that streams games you already own from Steam, Epic, and other stores. **No subscription required for free tier** (1-hour sessions); Priority and Ultimate tiers for longer sessions and RTX.



## Open-Source GitHub Projects



- **[Cloudy Pad](https://github.com/PierreBeucher/cloudypad)**  

  **Free, open-source alternative to GeForce Now, Blacknut, and similar cloud gaming platforms** . Deploy your own gaming instance on AWS, Azure, Google Cloud, Scaleway, Paperspace, or any server via SSH. Play your own Steam, Epic, GOG, and Lutris games without a powerful gaming machine. **Pay by the hour, no subscription** — play 30 hours/month for ~$15 or less using spot instances (up to 90% cheaper) . Includes automated cost alerts, network speed control, and deploys a **Sunshine or Wolf** video-game streaming server with **Moonlight client** support .



- **[CloudMorph](https://github.com/giongto35/cloud-morph)**  

  **Decentralized, self-hosted cloud gaming service on web browser** . Runs any Windows game or application on a remote server and streams to the browser with no installation, no console, no plugins. Uses P2P mesh networking for providers and consumers. **OpenEnv-compatible Wine environment** allows RL agents to interact with Windows applications through standard HTTP API . One-line command deployment via Docker. Sister project **CloudRetro** for retro game streaming.



- **[Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher)**  

  **Free, open-source, cross-platform launcher for Epic, GOG, and Amazon Games** . Manage and launch games without installing the official Epic Games Launcher, GOG Galaxy, or Amazon Games app. Supports Windows, macOS, and Linux (including Steam Deck). **GNU GPLv3 licensed** with advanced options for Wine compatibility, Easy Anti-Cheat, BattleEye, DXVK, VKD3D, and Proton . **The de facto open-source alternative for managing non-Steam game libraries.**



- **[Lazap](https://github.com/LegItMate/Lazap)**  

  **Lightweight, cross-platform launcher unifying Steam, Epic, Ubisoft, and Rockstar** . Rewritten in C++ for native-like performance with GPU-accelerated UI. **Fully offline-capable** — access and launch games without internet. Supports Windows and Linux (Wayland and Xorg), with installation via MSI, WinGet, .deb, .rpm, .tgz, AppImage, and AUR . **Best for users wanting a fast, unified game library without official launcher bloat.**



- **[Cartridges](https://github.com/kra-mo/cartridges)**  

  **Elegant GTK4/Libadwaita game launcher for Linux** . Imports games from Steam, Lutris, Heroic, RetroArch, Flatpak, and Desktop Entries. Features filtering by source, searching/sorting, cover art auto-download from SteamGridDB, animated covers, and GNOME search provider integration . **The best-looking open-source launcher for GNOME users.**



- **[moonlight-web-stream](https://github.com/MrCreativ3001/moonlight-web-stream)**  

  **Web server that streams games via Sunshine to any browser** . Companion to **Cloudy Pad** and other Sunshine-based streaming setups. Enables browser-based access to Moonlight streams without installing a client.



- **[Stratix](https://github.com/nafields/stratix)**  

  **Native tvOS Xbox Game Pass cloud gaming client for Apple TV** . Built in Swift with xCloud and xHome streaming. Uses Microsoft's device-code authentication flow. **Note**: requires active Game Pass Ultimate subscription and is a third-party client, not officially supported by Microsoft.



- **[CloudRetro](https://github.com/giongto35/cloud-game)**  

  Sister project to CloudMorph, providing **cloud gaming service specifically for retro games** . Runs on dedicated cloud infrastructure with low-latency streaming to browsers.



### Additional Strong Open-Source Options



- **Legendary** — Free and open-source replacement for the Epic Games Launcher, Python-based . Command-line tool for installing and managing Epic games without the official launcher.

- **Playnite** — Open-source video game library manager supporting Steam, Epic, GOG, EA App, and more under a unified interface . Windows-only.

- **Lutris** — Open-source game manager for Linux supporting Steam, GOG, Epic, and emulators .

- **selkies-project/docker-nvidia-glx-desktop** — KDE Plasma Desktop container for Kubernetes with OpenGL, Vulkan, and Wine/Proton for NVIDIA GPUs through WebRTC and HTML5 . **Open-source remote cloud/HPC graphics or game streaming platform.**

- **Joyflix-CloudGaming** — Open-source cloud gaming service .

- **IndieGameStream** — Stream your games using the Cloud .



**Frameworks for building custom game subscription solutions**: Combine **Cloudy Pad** for turnkey cloud gaming deployment on your own cloud infrastructure with Sunshine/Moonlight streaming , **CloudMorph** for browser-based game streaming without client installation , and **Heroic Games Launcher** or **Lazap** for unified game library management across stores . For retro gaming, **CloudRetro** provides dedicated infrastructure . For Apple TV users, **Stratix** enables native xCloud client access . Note that true commercial game subscription services with curated catalogs, day-one releases, and publisher deals remain primarily commercial territory; open-source stacks provide strong cloud gaming infrastructure, unified launchers, and self-hosted streaming foundations that require integration for complete game subscription experiences.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Game subscription services vary by region and platform. **Cloud gaming requires stable broadband** — PlayStation Plus Premium recommends minimum 5 Mbps, with 4K at 52 Mbps .

- **Self-hosted cloud gaming requires cloud infrastructure costs** — Cloudy Pad estimates ~$15/month for 30 hours using spot instances, but costs vary by provider and region .

- **Third-party clients like Stratix are not officially supported** by Microsoft and may break with API changes .

- The open-source ecosystem provides strong cloud gaming infrastructure and unified launchers, but **curated game catalogs, day-one releases, and publisher licensing** remain primarily commercial offerings.



---



**Made for gamers, cloud gaming enthusiasts, and self-hosting advocates.**  

Let's make game subscription services more open, transparent, and accessible.
