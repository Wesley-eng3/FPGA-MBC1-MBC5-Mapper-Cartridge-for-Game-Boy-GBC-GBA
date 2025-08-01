# FPGA-MBC1-MBC5-Mapper-Cartridge-for-Game-Boy-GBC-GBA
Project for rom creators and game translators

# 🎮 FPGA MBC1/MBC5 Mapper Cartridge for Game Boy / GBC / GBA

This project is an **open-source reprogrammable cartridge** for **Game Boy**, **Game Boy Color**, and **Game Boy Advance** (in backward compatibility mode), using a **Xilinx FPGA** to emulate classic Nintendo mappers like **MBC1** and **MBC5**.

---

## 📌 Project Overview

Classic Game Boy cartridges use **Memory Bank Controllers (MBCs)** to enable larger ROMs, save RAM, and special features like RTC (Real-Time Clock).  
This project replaces original MBC chips with a **configurable FPGA core**, making a single cartridge compatible with multiple games and mapper types.

---

## ⚙️ Key Features

- ✅ **FPGA-based Mapper:** Uses a Xilinx FPGA to emulate MBC1 and MBC5.
- ✅ **Bank Switching:** Supports large ROM sizes — up to 2 MB (MBC1) and 8 MB (MBC5).
- ✅ **Save RAM Support:** Battery-backed SRAM or FRAM for game saves.
- ✅ **Multi-game Ready:** Potential for multi-ROM menus with future firmware.
- ✅ **Upgradeable:** Reprogram the FPGA via USB/JTAG to add new mappers or fixes.

---

## 🗂️ Project Structure

📁 /hardware
├─ PCB design files Altium
📁 /fpga
├─ Verilog / VHDL sources for MBC1, MBC5 cores

ALTIUM View
<img width="620" height="717" alt="Image" src="https://github.com/user-attachments/assets/c109013a-1e0c-4bc7-85ab-0786f6477f07" />

---

## 🧰 Hardware Requirements

- 🧩 **FPGA:** Xilinx CPLD/FPGA.
- 📦 **Flash Memory:** Stores one or multiple ROMs.
- 🔋 **SRAM/FRAM + Battery:** Handles save data.
- 🔌 **JTAG/USB Programmer:** For FPGA bitstream updates.
- 🪛 **Custom PCB:** Cartridge form factor compatible with GB/GBC/GBA slot.

TOP
<img width="585" height="668" alt="Image" src="https://github.com/user-attachments/assets/7536c1ac-701c-4e83-839d-f25881a347a4" />

Bottom
<img width="582" height="667" alt="Image" src="https://github.com/user-attachments/assets/3db9b6ad-19db-44c1-9da7-4b27c6bf6639" />

---

## 💡 Applications

- Play classic Game Boy and Color games with high compatibility.
- Develop and test homebrew ROMs.
- Preserve and play fan translations or hacks.

---

## 🚧 Status

✅ Hardware design — **in progress**  
✅ FPGA cores — **MBC1 functional**, **MBC5 under test**  (Code is not available)

---

## 📫 Contact
  
**LinkedIn:** https://www.linkedin.com/in/your-profile/
