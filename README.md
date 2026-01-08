# 🧟 Surface Lazarus
**Resurrecting e-waste into the ultimate open-source student tablet.**

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

## 📖 The Story
As a student in Pakistan, I need a device to annotate thousands of pages of PDF notes and textbooks. Commercial solutions like the iPad Pro are prohibitively expensive ($400+), and cheap writing tablets cannot run desktop software.

**My solution?** Build my own.

I am harvesting the high-resolution display from a broken **Microsoft Surface Pro 3** and driving it with a Linux Single Board Computer to create a distraction-free, privacy-respecting digital notebook.

## 🛠️ The Hardware Stack
*   **The Display:** Samsung LTL120QL01 (12", 2160x1440).
    *   *Why:* It has "Retina" density and a built-in N-Trig Digitizer.
*   **The Brain:** Orange Pi 3 LTS (running Armbian).
*   **The Controller:** Custom HDMI-to-eDP board with USB Touch breakout.
*   **The Pen:** Microsoft Surface Pen (Pressure Sensitive).

## 💻 The Software Stack
*   **OS:** Armbian (Debian Bookworm)
*   **Input Driver:** `ipts-linux` (Intel Precise Touch) or HID-Multitouch.
*   **Primary App:** **Xournal++** (Open Source PDF Annotation).
*   **UX:** Custom minimalist shell (hiding the desktop environment for focus).

## 🗺️ The Roadmap
- [ ] 🛒 **Procurement:** Source the screen locally from Hall Road market.
- [ ] ⚡ **Power:** Build a custom 12V + 5V split-rail power supply.
- [ ] 🔌 **Video:** Interface the LCD via HDMI.
- [ ] 🖊️ **Touch:** Reverse engineer the N-Trig USB protocol for Linux.
- [ ] 📦 **Case:** Laser cut an acrylic sandwich case.

---
*"Built with code, solder, and persistence."*
