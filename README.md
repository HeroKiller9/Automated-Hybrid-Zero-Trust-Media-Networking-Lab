# Automated-Hybrid-Zero-Trust-Media-Networking-Lab
My HomeLab✨

جاري الكتابة...
## 📋 نظرة عامة على الخدمات (media-system)

| الخدمة (Service) | الوظيفة (Role) | الوصول (Access) |
| :--- | :--- | :---: |
| **[Jellyfin](https://github.com/linuxserver/docker-jellyfin)** | نظام لبث الوسائط (Media Server) مفتوح المصدر بالكامل | 🌐 Public (Tunnel) |
| **[Jellyseerr](https://github.com/seerr-team/seerr)** | هو نظام إدارة طلبات المحتوى (Overseerr fork). يعمل كواجهة أمامية (Frontend) للمستخدمين | 🌐 Public (Tunnel) |
| **[Prowlarr](https://github.com/linuxserver/docker-prowlarr)** | أداة لإدارة الـ Indexers (مواقع التورنت) | 🔐 Private (Tailscale) |
| **[Transmission](https://github.com/linuxserver/docker-transmission)** | عميل تورنت (BitTorrent Client) خفيف جداً وموثوق| 🔐 Private (Tailscale) |
| **[Sonarr](https://github.com/linuxserver/docker-sonarr)** | أداة إدارة وتنظيم المسلسلات التلفزيونية (TV Shows) | 🔐 Private (Tailscale) |

---
