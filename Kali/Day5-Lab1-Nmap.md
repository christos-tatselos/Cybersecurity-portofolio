# 🧪 Kali Linux – Day 5 Lab 1  
## 🔍 Nmap Host Discovery & Port Scanning

📅 **Ημερομηνία**: 8 Σεπτεμβρίου 2025  
👨‍💻 **Φοιτητής**: Christos Tatselos  
📂 **Κατηγορία**: Kali Linux Labs → Network Scanning  

---

## ⚙️ Περιβάλλον

- 🖥️ Kali Linux (VirtualBox)  
- 🌐 Δίκτυο: Mobile Hotspot (10.72.60.0/24)  
- 📁 Shared Folder: `/media/sf_VMSHARE` για screenshots  

---

## ⚒️ Εργαλεία / Εντολές

### 1. Host Discovery:
```bash
nmap -sP 10.72.60.0/24
```

### 2. Service Detection:
```bash
nmap -sV -p 22,23,80,443,8000,8443 10.72.60.168
```
