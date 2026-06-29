# PrimeOS — Rufus Configuration

This section documents the **Rufus 4.x** settings used to create a bootable USB installer for **PrimeOS**.

---

## 🔧 Drive Properties
- **Device:** USB (E:) — 16 GB  
- **Boot Selection:** `PrimeOS-2.1.3-64-bit-20220719-BETA.iso`  
- **Persistent Partition Size:** 0 MB *(No persistence)*  
- **Partition Scheme:** **MBR**  
- **Target System:** **BIOS or UEFI**  
- **Image Option:** Standard installation *(auto‑selected by Rufus)*  

---

## 🗂️ Format Options
- **Volume Label:** `PRIMEOS 2.1.3 (x86_64)`  
- **File System:** **FAT32 (Default)**  
- **Cluster Size:** 8192 bytes (Default)  

**Advanced Options**
- Quick Format: Enabled  
- Create extended label and icon files: Enabled  
- Check device for bad blocks: Disabled  

---

## 📦 ISO Extraction Status (Example)
- **Operation:** Copying ISO files  
- **Progress:** ~7%  
- **Current File:** `system.sfs` (1.6 GB)  
- **Elapsed Time:** 00:05  

---

## 📝 Notes
- **FAT32** is required for maximum boot compatibility across older Dell OptiPlex systems and laptops.  
- **MBR** ensures PrimeOS boots on both legacy BIOS and modern UEFI systems.  
- PrimeOS does **not** support persistence in Rufus; leave the persistent partition size at **0**.  
- These settings apply to most PrimeOS builds (Mainline, Standard, Classic). Only the ISO filename and volume label change.
