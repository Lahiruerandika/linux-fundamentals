# Networking in Linux 🌐

Networking is a crucial aspect of Linux systems, enabling communication between devices and the internet. This guide covers essential commands for network configuration, monitoring, and troubleshooting.

---

## 📡 Checking Network Interfaces
```bash
ip a        # Show network interfaces and assigned IPs
ifconfig    # Display network interface details (deprecated, use `ip a`)
```

---

## 🌍 Testing Network Connectivity
```bash
ping google.com     # Check if a host is reachable
traceroute google.com # Show the route packets take to a host
```

---

## 📡 Managing Network Connections
```bash
nmcli dev status    # Show network devices and their status
nmcli con show      # List saved network connections
```

---

## 🛠️ Checking Open Ports and Services
```bash
netstat -tulnp    # Show open ports and listening services
ss -tulnp         # Alternative to `netstat` for open sockets
lsof -i :80       # List processes using port 80
```

---

## 🌍 Downloading Files from the Internet
```bash
wget URL  # Download a file from a given URL
curl -O URL  # Fetch data from a URL and save it to a file
```

---

## 🔐 Firewall Management
```bash
ufw status     # Check firewall status
ufw allow 22   # Allow SSH (port 22) through firewall
ufw deny 80    # Block HTTP (port 80)
```

---

## 📌 Conclusion
Understanding Linux networking commands is essential for troubleshooting connectivity issues, managing network services, and ensuring system security.

🚀 **Next Steps:** Explore advanced networking concepts like SSH, VPNs, and network security!
