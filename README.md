# Awesome In-Game Advertising Platforms

**In-Game Advertising Platforms** enable game developers and publishers to monetize through dynamic, brand-safe ad placements inside games (banners, interstitials, rewarded video, and especially immersive/3D in-game ads). Leading platforms include Anzu, Bidstack, AdInMo, Frameplay, Venatus, Admix, Unity Ads, AppLovin, Chartboost, and Google AdMob.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully featured open-source solutions for dynamic 3D in-game advertising are rare due to the complexity of real-time rendering, brand safety, and ad network integrations. Most open-source activity focuses on ad mediation, general ad servers, and SDK wrappers.

## 🏢 SaaS / Hosted Platforms

- **[Anzu](https://anzu.io/)**, **[Bidstack](https://www.bidstack.com/)**, **[AdInMo](https://adinmo.com/)**, **[Frameplay](https://frameplay.com/)** — Specialists in dynamic, immersive, and brand-safe in-game advertising (especially 3D placements).
- **[Venatus](https://www.venatus.com/)**, **[Admix](https://admixplay.com/)** — In-game and interactive advertising platforms.
- **[Unity Ads](https://unity.com/products/unity-ads)**, **[AppLovin](https://www.applovin.com/)**, **[Chartboost](https://www.chartboost.com/)**, **[Google AdMob](https://admob.google.com/)** — Major mobile and cross-platform ad networks and mediation platforms widely used by game developers.

## 🔓 Open-Source Software

### Ad Mediation & Mobile Game Monetization
- **[OpenMediation](https://github.com/OpenMediationProject/OpenMediation)** — Fully open-source mediation platform with SDKs, server, and dashboard. Supports multiple major ad networks (AdMob, AppLovin, Unity, Chartboost, etc.), waterfall optimization, and header bidding. One of the most complete open-source alternatives for mobile game ad mediation.
- Open-source Unity ad integration kits and plugins (e.g., community “Ads Kit” projects) that provide a unified API across AdMob, AppLovin, Unity LevelPlay, and other networks.

### General Open-Source Ad Servers
- **[Revive Adserver](https://www.revive-adserver.com/)** (formerly OpenX Source) — Mature, widely used open-source ad server for managing campaigns, banners, targeting, and reporting. Can be self-hosted and adapted for certain game inventory use cases.
- **Prebid** (Prebid.js / Prebid Server / Prebid Mobile) — Leading open-source header-bidding framework. Primarily web-focused but also supports mobile app monetization and can be part of a broader programmatic stack.

### Supporting Tools & Building Blocks
- Open-source attribution and analytics tools that help measure ad-driven installs and in-game events (some community projects aim to replace commercial MMP functionality).
- Custom ad-serving proxies and simple game-specific ad servers developed by the community for particular titles or engines.
- General advertising technology components (auction logic, creative serving, consent management) that developers can assemble into a custom in-game ad pipeline.

### Reality Check
True dynamic 3D in-game advertising platforms (like Anzu or Bidstack) that handle real-time texture replacement, brand safety, and sophisticated inventory packaging remain largely proprietary. Most independent or smaller studios currently combine:

1. Commercial mediation / networks (AdMob, AppLovin, Unity Ads, etc.) for fill and demand
2. Open-source mediation layers (OpenMediation) or custom wrappers for control
3. Self-hosted ad servers (Revive) for direct-sold or house inventory
4. Custom engine integrations for any special in-game placements

This hybrid approach gives developers more ownership while still accessing major advertiser demand.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to in-game advertising, mobile ad mediation, ad servers, or game monetization SDKs.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open ad tools help game developers monetize more transparently! 🎮
