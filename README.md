# 🔐 Firewall Configuration and Testing (Linux UFW)

## 📘 Objective
Configure and test basic firewall rules to allow or block traffic using **UFW (Uncomplicated Firewall)** on a Linux system.

---

## 🛠️ Tools Used
- **Operating System**: Linux (Ubuntu/Kali/Debian)
- **Firewall Tool**: UFW (Uncomplicated Firewall)

---

## 🔧 Steps Performed

### 1. Enable UFW
```bash
sudo ufw enable
```

### 2. Check Current Firewall Status
```bash
sudo ufw enable
```


### 3. Block Inbound Traffic on Port 23 (Telnet)
```bash
sudo ufw deny 23
```


### 4. Enable UFW
```bash
telnet localhost 23
```


### 5.Allow SSH (Port 22)
```bash
sudo ufw allow 22
```


### 6. Remove the Block Rule (Restore Original State)
```bash
sudo ufw delete deny 23
```

### 7. Final Status Check
```bash
sudo ufw status verbose
```
