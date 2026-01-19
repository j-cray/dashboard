# dashboard
# Dashboard

<div align="center">

**Your Personal Digital HUD**

[![Status](https://img.shields.io/badge/Status-Personal-purple?style=for-the-badge)]()
[![Stack](https://img.shields.io/badge/Tech-React%20%7C%20Node-green?style=for-the-badge)]()

*A centralized startpage and dashboard for my homelab and personal life.*

</div>

---

## 📖 Overview
This is a custom-built dashboard designed to run on a wall-mounted display or as a browser new tab page. It aggregates data from various services (Nextcloud, Weather, Calendar, Server Stats) into a single, glanceable interface.

## ✨ Widgets
*   **Clock & Weather:** Local time and forecast.
*   **Calendar:** Upcoming events from Nextcloud/Google Calendar.
*   **Server Health:** CPU/RAM usage of key nodes (via Glances or Netdata).
*   **Quick Links:** Shortcuts to frequently used self-hosted services.

---

## 🗺️ Roadmap & Todo

### Phase 1: Layout
- [ ] **Grid System:** Implement a responsive CSS Grid layout.
- [ ] **Theming:** Add support for "Day" and "Night" modes based on time.

### Phase 2: Integrations
- [ ] **Nextcloud:** Fetch unread notification count.
- [ ] **Pi-hole:** Show blocked queries statistic.
- [ ] **Home Assistant:** Toggle basic lights/switches.

### Phase 3: Deployment
- [ ] **Docker:** Containerize for easy deployment on the homelab.
- [ ] **Kiosk Mode:** Configure for auto-launch on Raspberry Pi.
