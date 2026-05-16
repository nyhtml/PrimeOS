## PrimeOS — VirtualBox Configuration

This section documents the VirtualBox settings used for running **PrimeOS**.

### 🖥️ General
- **Name:** PrimeOS  
- **OS Type:** Windows 10 (64‑bit)  
- **VM Path:** `/VirtualBox VMs/PrimeOS`

### ⚙️ System
- **Base Memory:** 2048 MB  
- **Boot Order:** Floppy → Optical → Hard Disk  
- **Acceleration:** VT‑x/AMD‑V, Nested Paging, Hyper‑V Paravirtualization  

### 🖼️ Display
- **Video Memory:** 128 MB  
- **Graphics Controller:** VBoxSVGA  
- **Remote Desktop:** Disabled  
- **Recording:** Disabled  

### 💾 Storage
**Controller: SATA**
- **Port 0:** `PrimeOS.vdi` (Normal, 64.00 GB)  
- **Port 1 (Optical):** `primeos_mainline_0.4.5.iso` (1.07 GB)

### 🔊 Audio
- **Host Driver:** CoreAudio  
- **Controller:** Intel HD Audio  

### 🌐 Network
- **Adapter 1:** Intel PRO/1000 MT Desktop (NAT)

### 🔌 USB
- **Controller:** xHCI (USB 3.0)  
- **Device Filters:** 0 (0 active)

### 📁 Shared Folders
- *(None configured)*

---

### 📸 Screenshot &amp; Video
- [PrimeOS 0.6.1 - YouTube](https://www.youtube.com/watch?v=CnqTYfaLR8s)
