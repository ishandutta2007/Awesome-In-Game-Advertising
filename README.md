<div align="center">
  <img src="assets/banner.svg" alt="Awesome In-Game Advertising Banner" width="100%" />
</div>

# 🎮 Awesome In-Game Advertising Platforms

<div align="center">

<a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

</div>

**In-Game Advertising Platforms** enable game developers and publishers to monetize through dynamic, brand-safe ad placements inside games (banners, interstitials, rewarded video, and especially immersive/3D in-game ads). Leading platforms include Anzu, Bidstack, AdInMo, Frameplay, Venatus, Admix, Unity Ads, AppLovin, Chartboost, and Google AdMob.

Below is a **curated list** of notable platforms and their open-source equivalents. Fully featured open-source solutions for dynamic 3D in-game advertising are rare due to the complexity of real-time rendering, brand safety, and ad network integrations. Most open-source activity focuses on ad mediation, general ad servers, and SDK wrappers.

## 🏢 SaaS / Hosted Platforms

| Platform | Description | Pricing | Free Tier Limit | Company Size (Revenue/Valuation) |
| --- | --- | --- | --- | --- |
| **[Google AdMob](https://admob.google.com/)** | Major mobile and cross-platform ad network | Revenue Share | No limit | ~$305B (Alphabet Revenue) |
| **[AppLovin](https://www.applovin.com/)** | Major mobile and cross-platform ad network | Revenue Share | No limit | ~$3.3B Revenue |
| **[Unity Ads](https://unity.com/products/unity-ads)** | Major mobile and cross-platform ad network | Revenue Share | No limit | ~$2.2B Revenue |
| **[Admix](https://admixplay.com/)** | In-game and interactive advertising platforms | Custom / Revenue Share | N/A | ~$450M (Acquisition/Exit Valuation) |
| **[Chartboost](https://www.chartboost.com/)** | Major mobile and cross-platform ad network | Revenue Share | No limit | ~$250M (Acquisition) |
| **[Anzu](https://anzu.io/)** | Dynamic, immersive, and brand-safe in-game advertising | Custom / Revenue Share | N/A | ~$120M Valuation |
| **[Venatus](https://www.venatus.com/)** | In-game and interactive advertising platforms | Custom / Revenue Share | N/A | ~$30M Revenue |
| **[Bidstack](https://www.bidstack.com/)** | Dynamic, immersive, and brand-safe in-game advertising | Custom / Revenue Share | N/A | ~$30M Valuation |
| **[Frameplay](https://frameplay.com/)** | Dynamic, immersive, and brand-safe in-game advertising | Custom / Revenue Share | N/A | ~$11.8M Revenue (~$8M Funding) |
| **[AdInMo](https://adinmo.com/)** | Dynamic, immersive, and brand-safe in-game advertising | Custom / Revenue Share | N/A | ~$8.2M Funding (~$3.5M Revenue) |
| **[Adsun](https://adsun.io/)** | Rewarded and interstitial advertising for games built as Telegram Mini Apps; not a native or 3D in-game SDK | Custom / Performance-based (CPM/CPC) | No free tier (min. campaign spend / payout threshold) | ~$1M - $2M Revenue (11-50 employees) |

## 🔓 Open-Source Software

### 🔄 Ad Mediation & Mobile Game Monetization
- **[Prebid](https://github.com/prebid/Prebid.js)** [![GitHub stars](https://img.shields.io/github/stars/prebid/Prebid.js?style=social&color=white)](https://github.com/prebid/Prebid.js/stargazers) — Leading open-source header-bidding framework. Primarily web-focused but also supports mobile app monetization and can be part of a broader programmatic stack.
- **[Revive Adserver](https://github.com/revive-adserver/revive-adserver)** [![GitHub stars](https://img.shields.io/github/stars/revive-adserver/revive-adserver?style=social&color=white)](https://github.com/revive-adserver/revive-adserver/stargazers) — Mature, widely used open-source ad server for managing campaigns, banners, targeting, and reporting. Can be self-hosted and adapted for certain game inventory use cases.
- **[OpenAdServer](https://github.com/seanZhang414/openadserver)** [![GitHub stars](https://img.shields.io/github/stars/seanZhang414/openadserver?style=social&color=white)](https://github.com/seanZhang414/openadserver/stargazers) — A modern, self-hosted alternative to Google Ad Manager featuring ML-powered CTR prediction and real-time eCPM bidding.
- **[OpenMediation](https://github.com/OpenMediationProject/OpenMediation)** [![GitHub stars](https://img.shields.io/github/stars/OpenMediationProject/OpenMediation?style=social&color=white)](https://github.com/OpenMediationProject/OpenMediation/stargazers) — Fully open-source mediation platform with SDKs, server, and dashboard. Supports multiple major ad networks, waterfall optimization, and header bidding.
- **[GreenRobot Ad Server](https://github.com/greenrobotllc/adserver)** [![GitHub stars](https://img.shields.io/github/stars/greenrobotllc/adserver?style=social&color=white)](https://github.com/greenrobotllc/adserver/stargazers) — A PHP/Laravel-based system designed for yield optimization, specifically for rotating ads between networks like AdMob.
- **[Volt Adserver](https://github.com/krish512/volt)** [![GitHub stars](https://img.shields.io/github/stars/krish512/volt?style=social&color=white)](https://github.com/krish512/volt/stargazers) — A newer open-source project built with GoLang, aiming to provide a fast, modern ad server experience.

### 🛠️ Supporting Tools & Building Blocks
- Open-source Unity ad integration kits and plugins (e.g., community “Ads Kit” projects) that provide a unified API across AdMob, AppLovin, Unity LevelPlay, and other networks.
- Open-source attribution and analytics tools that help measure ad-driven installs and in-game events.
- Custom ad-serving proxies and simple game-specific ad servers developed by the community for particular titles or engines.
- General advertising technology components (auction logic, creative serving, consent management) that developers can assemble into a custom in-game ad pipeline.

### 🧠 Reality Check
True dynamic 3D in-game advertising platforms (like Anzu or Bidstack) that handle real-time texture replacement, brand safety, and sophisticated inventory packaging remain largely proprietary. Most independent or smaller studios currently combine:

1. 💰 Commercial mediation / networks (AdMob, AppLovin, Unity Ads, etc.) for fill and demand
2. 🎛️ Open-source mediation layers (OpenMediation) or custom wrappers for control
3. 🏠 Self-hosted ad servers (Revive) for direct-sold or house inventory
4. ⚙️ Custom engine integrations for any special in-game placements

This hybrid approach gives developers more ownership while still accessing major advertiser demand.

---

**🤝 How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to in-game advertising, mobile ad mediation, ad servers, or game monetization SDKs.

**📄 License**  
This list is public domain / CC0. Feel free to copy into your own [awesome list](https://github.com/ishandutta2007/Awesome-Awesome-Awesome) or README.

⭐ Star the projects you find useful — open ad tools help game developers monetize more transparently! 🎮

## 📈 Star History
<div align="center">
<a href="https://www.star-history.com/?repos=ishandutta2007/Awesome-In-Game-Advertising&type=date&legend=bottom-right">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-In-Game-Advertising&type=date&theme=dark&legend=bottom-right" />
<source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-In-Game-Advertising&type=date&legend=bottom-right" />
<img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-In-Game-Advertising&type=date&legend=bottom-right" />
</picture>
</a>
</div>
