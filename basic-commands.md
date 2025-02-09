# Basic Linux Commands 🖥️

Linux commands allow users to interact with the system efficiently. Below are some essential commands categorized for ease of use.

## 📂 File and Directory Management
```bash
ls       # List files and directories
pwd      # Print working directory (current location)
cd       # Change directory
mkdir    # Create a new directory
rm       # Remove files or directories
rmdir    # Remove empty directories
cp       # Copy files or directories
mv       # Move or rename files or directories
```

## 📄 File Operations
```bash
touch    # Create a new empty file
cat      # Display file contents
nano     # Open a file in the nano text editor
vim      # Open a file in the vim editor
head     # Display the first 10 lines of a file
tail     # Display the last 10 lines of a file
echo     # Print text to the terminal
```

## 🔎 Searching and Filtering
```bash
grep 'text' file.txt   # Search for 'text' in a file
find /path -name file  # Find a file by name
locate filename        # Quickly find a file
history               # Show command history
```

## 🛠️ System Monitoring and Management
```bash
top       # Display running processes and resource usage
ps        # Show active processes
kill PID  # Terminate a process by its ID
uptime    # Show system uptime
free -h   # Show memory usage
df -h     # Show disk space usage
```

## 🌐 Networking Commands
```bash
ping google.com       # Test network connectivity
wget URL             # Download a file from the internet
curl URL             # Fetch data from a URL
ifconfig             # Show network interfaces (deprecated, use `ip a`)
ip a                # Show network details
netstat -tulnp      # Display open ports
```

## 🔐 User Management
```bash
whoami     # Display current user
id         # Show user and group ID
adduser username  # Create a new user
passwd     # Change user password
who        # Show logged-in users
```

## 📌 Conclusion
These commands are fundamental to navigating and managing a Linux system. Mastering them will improve efficiency and system control.

🚀 **Next Steps:** Explore file permissions and user management in the next section!
