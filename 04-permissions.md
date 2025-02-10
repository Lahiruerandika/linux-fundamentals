# User Permissions & Process Management 🔐

Managing user permissions and processes in Linux is essential for system security and performance. This guide covers how to handle user access and manage system processes effectively.

---

## 👤 User Permissions
Linux uses a permission system to control access to files and directories. Each file has three permission types for three user categories:

### **1️⃣ Permission Types:**
- **Read (r)** → View file contents
- **Write (w)** → Modify file contents
- **Execute (x)** → Run the file as a program

### **2️⃣ User Categories:**
- **Owner** → The user who created the file
- **Group** → A set of users who share file access
- **Others** → All other users

### **3️⃣ Viewing File Permissions:**
```bash
ls -l filename
```
Example Output:
```
-rwxr--r--  1 user group 1234 Feb 8 12:00 script.sh
```
- `rwx` → Owner has read, write, and execute permissions.
- `r--` → Group has read-only permission.
- `r--` → Others have read-only permission.

### **4️⃣ Changing Permissions:**
```bash
chmod 755 filename  # rwxr-xr-x (Owner: all, Group/Others: read & execute)
chmod u+x script.sh # Add execute permission to the owner
```

### **5️⃣ Changing Ownership:**
```bash
chown user:group filename  # Change file owner and group
chgrp groupname filename   # Change file group
```

---

## ⚙️ Process Management
Linux allows you to manage running processes effectively. A process is an instance of a running program.

### **1️⃣ Viewing Processes:**
```bash
ps aux    # Show all running processes
top       # Dynamic real-time process view
htop      # Interactive process viewer (if installed)
```

### **2️⃣ Managing Processes:**
```bash
kill PID  # Terminate a process by PID
killall process_name  # Kill all instances of a process
pkill process_name  # Kill processes by name
```

### **3️⃣ Running Processes in Background:**
```bash
command &   # Run command in the background
jobs        # Show background jobs
fg %1       # Bring job #1 to the foreground
bg %1       # Resume job #1 in the background
```

### **4️⃣ Process Priority:**
```bash
nice -n 10 process_name  # Start a process with priority 10
renice 5 PID             # Change priority of a running process
```

---

## 📌 Conclusion
Understanding user permissions and process management is crucial for maintaining a secure and efficient Linux system. Mastering these commands will help you manage files and system performance effectively.

🚀 **Next Steps:** Explore networking and system monitoring in the next section!
