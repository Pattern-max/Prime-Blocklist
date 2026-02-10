# 🛡️ Prime Blocklist

**A balanced DNS blocklist designed for a seamless web experience.**

![GitHub last commit](https://img.shields.io/github/last-commit/ron-png/BigBlockList)
![GitHub license](https://img.shields.io/github/license/ron-png/BigBlockList)

## 🚀 Overview

Prime Blocklist is an automatically updated aggregation of high-quality blocklists. I wanted to combine multiple "functionality over blocking" lists to create the ultimate fire and forget list. It aims to provide robust protection against ads, trackers, and malicious domains without breaking your favorite websites.

### 🎯 Philosophy

> **Usability First:** I believe that online protection shouldn't come at the cost of usability. This list is carefully curated to minimize false positives, ensuring that your internet works exactly as expected—just cleaner and safer.

## 📦 Sources

This list combines the following sources:

- **[HaGeZi's Pop-Up Ads DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/popupads.txt)**: Blocks annoying and malicious pop-up ads. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)
- **[HaGeZi's Threat Intelligence Feeds DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)**: Increases security significantly! Blocks Malware, Cryptojacking, Spam, Scam and Phishing. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)
- **[HaGeZi's Fake DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/fake.txt)**: Protects against internet scams, traps & fakes! Blocks fake stores, -streaming, rip-offs, cost traps and co. [Report false positive](https://github.com/hagezi/dns-blocklists/issues)
- **[HaGeZi's Pro DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)**: Big broom - Cleans the Internet and protects your privacy! Blocks Ads, Affiliate, Tracking, Metrics, Telemetry, Phishing, Malware, Scam, Fake, Crytojacking and other "Crap". [Report false positive](https://github.com/hagezi/dns-blocklists/issues)

## 🔄 Updates

The list is automatically updated **every hour** to ensure it stays up-to-date.

## 📥 Usage

**Raw URL:**
```
https://github.com/Pattern-max/Prime-Blocklist/raw/refs/heads/main/list/Prime_Blocklist.txt
```

Add this URL to your Pi-hole, AdGuard Home, or any other DNS blocker.

## 🤝 Contributing

- **Add an Entry:** Please suggest any change to the upstream blocklist provider directly. I currently don't plan to maintain my own list.
- **False Positives:** Please suggest any change to the upstream blocklist provider directly. I currently don't plan to maintain my own list.
- **Recommend a List:** You can suggest a blocklist to be added to the Prime Blocklist. Just open an issue or pull request.
