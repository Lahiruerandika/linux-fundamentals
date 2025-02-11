# Shell Scripting in Linux 🐧

Shell scripting allows users to automate tasks, execute commands efficiently, and manage system operations. This guide covers the basics of writing and executing shell scripts.

---

## 📌 What is a Shell Script?
A shell script is a text file containing a series of commands that can be executed by the shell.

### **1️⃣ Creating a Shell Script**
```bash
touch script.sh      # Create a new script file
echo '#!/bin/bash' > script.sh  # Define the interpreter
chmod +x script.sh  # Make the script executable
nano script.sh      # Open the script for editing
```

### **2️⃣ Writing a Simple Script**
```bash
#!/bin/bash
# This script prints a greeting message
echo "Hello, World!"
```

---

## 🛠️ Executing a Shell Script
```bash
./script.sh     # Execute the script
bash script.sh  # Run the script using Bash
sh script.sh    # Run the script using the default shell
```

---

## 🔄 Variables in Shell Scripts
```bash
#!/bin/bash
name="Alice"
echo "Hello, $name!"
```

### **Reading User Input**
```bash
#!/bin/bash
echo "Enter your name: "
read user_name
echo "Hello, $user_name!"
```

---

## 🔁 Conditional Statements
```bash
#!/bin/bash
num=10
if [ $num -gt 5 ]; then
  echo "Number is greater than 5"
else
  echo "Number is 5 or less"
fi
```

---

## 🔄 Loops in Shell Scripting
### **For Loop**
```bash
#!/bin/bash
for i in 1 2 3 4 5; do
  echo "Iteration $i"
done
```

### **While Loop**
```bash
#!/bin/bash
count=1
while [ $count -le 5 ]; do
  echo "Count: $count"
  ((count++))
done
```

---

## 📌 Conclusion
Shell scripting is a powerful tool for automating system tasks, managing files, and simplifying command execution. Mastering scripting techniques can greatly improve efficiency.

🚀 **Next Steps:** Explore advanced scripting concepts like functions, case statements, and error handling!
