# Process Management ⚙️

Managing processes in Linux is crucial for optimizing system performance and ensuring smooth operation. This guide covers essential commands for monitoring and controlling processes.

---

## 🔍 Viewing Processes
Processes are instances of running programs. You can view them using:
```bash
ps aux    # Display all active processes
top       # Show real-time process activity
htop      # Interactive process viewer (if installed)
pgrep process_name  # Find process ID by name
```

---

## ❌ Terminating Processes
Kill unresponsive or unnecessary processes using:
```bash
kill PID  # Terminate a process by its Process ID
killall process_name  # Kill all instances of a process
pkill process_name  # Kill processes by name
```
To forcefully terminate a process:
```bash
kill -9 PID  # Force kill a process
```

---

## 🎭 Managing Foreground & Background Processes
```bash
command &   # Run a command in the background
jobs        # List background jobs
fg %1       # Bring job #1 to the foreground
bg %1       # Resume job #1 in the background
```

---

## 🚀 Adjusting Process Priority
### **1️⃣ Starting a Process with a Priority:**
```bash
nice -n 10 process_name  # Start a process with priority 10
```
### **2️⃣ Changing the Priority of a Running Process:**
```bash
renice 5 PID  # Change priority of an active process
```

Lower values indicate higher priority (range: -20 to 19).

---

## 🛠️ Monitoring System Performance
```bash
uptime       # Show system uptime and load average
free -h      # Display memory usage
df -h        # Show disk space usage
vmstat       # Report system performance
```

---

## 📌 Conclusion
Mastering process management helps in optimizing system performance and stability. These commands empower users to control and troubleshoot processes effectively.

🚀 **Next Steps:** Explore system monitoring and advanced administration techniques!
