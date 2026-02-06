# 🛡️ NetBlocker

**A balanced DNS blocklist designed for a seamless web experience.**

![GitHub last commit](https://img.shields.io/github/last-commit/ron-png/BigBlockList)
![GitHub license](https://img.shields.io/github/license/ron-png/BigBlockList)

## 🚀 Overview

NetBlocker is an automatically updated aggregation of high-quality blocklists. I wanted to combine multiple "functionality over blocking" lists to create the ultimate fire and forget list. It aims to provide robust protection against ads, trackers, and malicious domains without breaking your favorite websites.

### 🎯 Philosophy

> **Usability First:** I believe that online protection shouldn't come at the cost of usability. This list is carefully curated to minimize false positives, ensuring that your internet works exactly as expected—just cleaner and safer.

## 📦 Sources

This list combines the following sources:

- **[HaGeZi's Pro mini DNS/Browser Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.mini.txt)**: The recommended core list for balanced ad and tracker blocking with minimal false positives. It intelligently integrates filtering from multiple reputable sources. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)
- **[HaGeZi's Threat Intelligence Feeds DNS Blocklist - medium version](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.medium.txt)**: Specialized security reinforcement focusing on blocking emerging threats such as phishing, malware, cryptojacking, and scam domains. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)
- **[HaGeZi's The World's Most Abused TLDs](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/spam-tlds.txt)**: Specialized security reinforcement focusing on blocking emerging threats such as phishing, malware, cryptojacking, and scam domains. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)

## 🔄 Updates

The list is automatically updated **every hour** to ensure it stays up-to-date.

## 📥 Usage

**Raw URL:**
```
https://github.com/Pattern-max/NetBlocker/raw/refs/heads/main/list/NetBlocker.txt
```

Add this URL to your Pi-hole, AdGuard Home, or any other DNS blocker.

## 🤝 Contributing

- **Add an Entry:** Please suggest any change to the upstream blocklist provider directly. I currently don't plan to maintain my own list.
- **False Positives:** Please suggest any change to the upstream blocklist provider directly. I currently don't plan to maintain my own list.
- **Recommend a List:** You can suggest a blocklist to be added to the NetBlocker. Just open an issue or pull request.
