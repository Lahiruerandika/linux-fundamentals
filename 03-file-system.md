# Linux File System Structure 📂

The Linux file system follows a hierarchical structure, with everything organized under the root (`/`) directory.

## 📌 Understanding the Linux File System
```
/
├── bin/        # Essential command binaries (ls, cp, mv, etc.)
├── boot/       # Boot loader files (kernel, initrd, etc.)
├── dev/        # Device files (hard drives, USBs, etc.)
├── etc/        # Configuration files
├── home/       # Home directories for users
├── lib/        # Shared libraries needed by the system
├── media/      # Mount points for removable media (CDs, USBs, etc.)
├── mnt/        # Temporary mount points
├── opt/        # Optional software packages
├── proc/       # Virtual directory for system processes
├── root/       # Home directory for the root user
├── sbin/       # System binaries (administrative commands)
├── tmp/        # Temporary files
├── usr/        # User binaries and applications
├── var/        # Variable files (logs, caches, etc.)
```

## 🔎 Navigating the File System
Here are some essential commands for working with the Linux file system:
```bash
pwd       # Print the current directory path
ls        # List directory contents
cd /path  # Change directory
mkdir dir # Create a new directory
rmdir dir # Remove an empty directory
rm -r dir # Remove a directory and its contents
find /path -name filename  # Search for a file
```

## 🛠️ Managing Files
```bash
touch file     # Create a new empty file
cp file1 file2 # Copy a file
mv file1 file2 # Move or rename a file
rm file        # Remove a file
cat file       # Display file contents
less file      # View file contents one page at a time
stat file      # Get detailed file information
```

## 📝 File System Permissions
Linux controls access to files using permissions:
```bash
ls -l         # View file permissions
chmod 755 file # Change file permissions
chown user file # Change file owner
chgrp group file # Change file group
```

## 📌 Conclusion
Understanding the Linux file system is crucial for system navigation and management. Mastering these commands will enhance your ability to work efficiently.

🚀 **Next Steps:** Explore file permissions and user management in the next section!
