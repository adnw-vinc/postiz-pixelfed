<p align="center">
  <a href="https://github.com/adnw-vinc/postiz-pixelfed" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/765e9d72-3ee7-4a56-9d59-a2c9befe2311">
    <img alt="Postiz Pixelfed Logo" src="https://github.com/user-attachments/assets/f0d30d70-dddb-4142-8876-e9aa6ed1cb99" width="280"/>
  </picture>
  </a>
</p>

<p align="center">
<a href="https://opensource.org/license/agpl-v3">
  <img src="https://img.shields.io/badge/License-AGPL%203.0-blue.svg" alt="License">
</a>
<a href="https://github.com/adnw-vinc/postiz-pixelfed/releases/latest">
  <img src="https://img.shields.io/github/v/release/adnw-vinc/postiz-pixelfed" alt="Version">
</a>
</p>

---

## 🎨 Postiz Pixelfed Edition

> **⚠️ This is a custom fork of [Postiz](https://github.com/gitroomhq/postiz-app)**
> 
> This repository is **NOT** the official Postiz project. It is a community-maintained fork with additional Pixelfed integration.

**Postiz Pixelfed Edition** extends the powerful Postiz social media scheduling platform with native [Pixelfed](https://pixelfed.social) support, enabling you to schedule and manage posts across the Fediverse alongside all major social platforms.

<div class="flex" align="center">
  <br />
  <strong>Supported Platforms:</strong><br />
  <img alt="Instagram" src="https://postiz.com/svgs/socials/Instagram.svg" width="32">
  <img alt="Youtube" src="https://postiz.com/svgs/socials/Youtube.svg" width="32">
  <img alt="Dribbble" src="https://postiz.com/svgs/socials/Dribbble.svg" width="32">
  <img alt="Linkedin" src="https://postiz.com/svgs/socials/Linkedin.svg" width="32">
  <img alt="Reddit" src="https://postiz.com/svgs/socials/Reddit.svg" width="32">
  <img alt="TikTok" src="https://postiz.com/svgs/socials/TikTok.svg" width="32">
  <img alt="Facebook" src="https://postiz.com/svgs/socials/Facebook.svg" width="32">
  <img alt="Pinterest" src="https://postiz.com/svgs/socials/Pinterest.svg" width="32">
  <img alt="Threads" src="https://postiz.com/svgs/socials/Threads.svg" width="32">
  <img alt="X" src="https://postiz.com/svgs/socials/X.svg" width="32">
  <img alt="Slack" src="https://postiz.com/svgs/socials/Slack.svg" width="32">
  <img alt="Discord" src="https://postiz.com/svgs/socials/Discord.svg" width="32">
  <img alt="Mastodon" src="https://postiz.com/svgs/socials/Mastodon.svg" width="32">
  <img alt="Bluesky" src="https://postiz.com/svgs/socials/Bluesky.svg" width="32">
  <img alt="Pixelfed" src="https://upload.wikimedia.org/wikipedia/commons/1/1d/Pixelfed-logo.png" width="32">
</div>

---

## ✨ What's Different in This Fork?

### 🆕 Pixelfed Integration

This fork adds **native Pixelfed support** for decentralized photo sharing:

- ✅ Full Pixelfed provider integration
- ✅ Schedule posts to Pixelfed instances
- ✅ Support for Pixelfed-specific features (2000 character limit)
- ✅ OAuth authentication with custom Pixelfed instances
- ✅ Fediverse-wide content distribution
---

## 💖 Sponsored by

This project is proudly sponsored by **[Adventure Does Not Wait](https://adventuredoesnotwait.com)** - Your gateway to extraordinary adventures and travel gear. Don't wait for the perfect moment – start your adventure today!

---

## 🚀 Quick Start

### Prerequisites

- Docker & Docker Compose
- Pixelfed instance credentials (optional)

### Deployment

```bash
# Clone the repository
git clone https://github.com/adnw-vinc/postiz-pixelfed.git
cd postiz-pixelfed

# Deploy with Docker Compose
docker-compose up -d
```

### Environment Variables

```bash
# Pixelfed Integration
PIXELFED_URL=https://your-pixelfed-instance.com
PIXELFED_CLIENT_ID=your_client_id
PIXELFED_CLIENT_SECRET=your_client_secret
```

---

## 📖 Documentation

- **[Original Postiz Docs](https://docs.postiz.com)** - Core Postiz features
- **[Pixelfed Integration Guide](./docs/pixelfed-integration.md)** - Setting up Pixelfed
- **[Deployment Guide](./docs/deployment.md)** - Docker, Kubernetes, etc.

---

## 🤝 Contributing

Contributions are welcome! Please note:

1. This is a **community fork**, not the official Postiz project
2. For issues related to **core Postiz features**, please report to [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)
3. For **Pixelfed-specific issues**, open issues here

---

## 📄 License

This project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

See [LICENSE](LICENSE) for details.

---

## 🙏 Acknowledgments

- **Original Postiz Project**: [gitroomhq/postiz-app](https://github.com/gitroomhq/postiz-app)
- **Pixelfed**: [pixelfed/pixelfed](https://github.com/pixelfed/pixelfed)
- All contributors and sponsors

---

<p align="center">
  <strong>🔗 Links:</strong>
  <a href="https://github.com/adnw-vinc/postiz-pixelfed">GitHub</a> •
  <a href="https://docs.postiz.com">Docs</a> •
  <a href="https://discord.postiz.com">Discord</a> •
  <a href="https://pixelfed.social">Pixelfed</a>
</p>
