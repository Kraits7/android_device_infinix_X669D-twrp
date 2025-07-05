# Infinix Hot 30i (X669D) - TWRP

📌 **A short description of your project** (e.g., TWRP recovery or mods for Infinix Hot 30i X669D).  

---

## 📋 Device Specifications  
- **Model:** Infinix Hot 30i (X669D)  
- **Chipset:** Unisoc T606  
- **RAM:** 4GB/8GB
- **Storage:** 64GB/128GB (UFS 2.2)  
- **Display:** 6.56" IPS (720x1612)  
- **Android:** Stock XOS (10.6)  

---

## ⚙️ Features  
- List key features (e.g., TWRP touch recovery, debloated ROM, overclocked kernel).  
- **For TWRP:**  
  - Decryption support  
  - Backup/restore partitions  
  - ADB & MTP support  

---

---

## 🛠 Installation Guide  
### Prerequisites  
- Unlocked bootloader  
- ADB & Fastboot installed  
- Backup your data  

### Steps  
1. Boot into fastboot:  
   ```bash
   adb reboot bootloader
   fastboot flash vendor_boot_ your slot vendor_boot.img
