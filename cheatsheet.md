# 📝 Linux Command Cheat Sheet

A quick reference guide for essential Linux commands.

---

## 📂 File & Directory Management
```bash
ls        # List files in a directory
pwd       # Print working directory
cd dir    # Change directory to 'dir'
mkdir dir # Create a new directory
rm file   # Remove a file
rm -r dir # Remove a directory and its contents
cp src dest # Copy files or directories
mv src dest # Move/rename files or directories
```

---

## 📄 File Operations
```bash
touch file      # Create an empty file
cat file        # Display file contents
less file       # View file contents page by page
head -n 10 file # Show the first 10 lines of a file
tail -n 10 file # Show the last 10 lines of a file
echo 'text' > file  # Write text to a file
```

---

## 🛠️ Process Management
```bash
ps aux       # List running processes
top          # Display active processes interactively
htop         # Enhanced interactive process viewer
kill PID     # Terminate process by PID
killall name # Kill all processes with the given name
```

---

## 🌐 Networking Commands
```bash
ip a        # Show network interfaces and IP addresses
ping host   # Test connectivity to a host
traceroute host # Trace the route to a host
netstat -tulnp  # Show active network connections
```

---

## 🗄️ Permissions & Ownership
```bash
chmod 755 file  # Change file permissions
chown user file # Change file owner
chgrp group file # Change file group ownership
```

---

## 🔍 Searching & Filtering
```bash
grep 'pattern' file   # Search for a pattern in a file
find /path -name file # Find a file by name
awk '{print $1}' file # Process and extract columns from a file
```

---

## 📌 Conclusion
This cheat sheet covers fundamental Linux commands. Keep practicing and exploring for mastery!

🚀 **Next Steps:** Try these commands in a terminal and experiment with different options.
