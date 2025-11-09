# 🌀 VortexTune

> **Lightweight and safe performance optimization module for Android (KernelSU Next).**  
> Inspired by Magnetar — fully recreated from scratch and open-source by **Diego**.

---

## ⚙️ Overview

VortexTune is a minimalist and safe tuning module designed for **KernelSU Next** users who want smoother performance and better system responsiveness without compromising battery or stability.

Unlike heavy tweak packs or closed-source mods, VortexTune runs **entirely through shell scripts** integrated with KernelSU’s native post-boot system — no daemons, no background processes.

---

## 🧩 Features

- 🧠 **Smart memory management**
  - `vm.swappiness = 40`
  - `vm.dirty_ratio = 10`
  - `vm.dirty_background_ratio = 3`

- ⚙️ **Dynamic CPU control**
  - Forces the `schedutil` governor for optimal balance between smoothness and efficiency.

- 🌐 **Network optimization**
  - Enables **TCP BBR** congestion control for faster and more stable data transmission.

- 🔒 **Completely safe**
  - No binaries, no background daemons, no persistent services.
  - 100% open shell-based logic.

---

## 🧾 Installation

1. Download the latest **VortexTune_x.x.zip** from [Releases](../../releases).
2. Open **KernelSU → Modules → Install from storage**.
3. Select the downloaded ZIP and wait for:
