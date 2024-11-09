
# My Tools Repository

This repository contains a collection of tools that I created to quench my curiosity, as well as tools I found interesting and replicated. These tools are designed to make certain tasks easier and are perfect for anyone who wants to explore or automate simple processes.

## Tools in this Repository

### 1. `command_ins_tool`

#### Description

`command_ins_tool` is a simple utility I created to install commands in my Linux distro. It allows you to specify the name of the command you want to check, run, or install directly within the code. If the command doesn't exist, the tool will automatically install it for you.

This tool has proven useful for installing popular commands like `htop`, `at`, and more. It's designed to be both convenient and practical by checking for the existence of a command and installing it if necessary.

#### Features
- Check if a command exists on your system
- Automatically install missing commands
- Simplifies the installation process

#### Installation & Usage

1. **Edit the Script**  
   Open the script using your favorite text editor:
   ```bash
   nano command_ins_tool
   ```

2. **Set the Command**  
   Inside the script, locate the following line:
   ```bash
   command=/usr/bin/<<___>>
   ```
   Replace `<<___>>` with the name of the command you want to install.

3. **Save and Exit**  
   Press `Ctrl + O` to save the file and `Ctrl + X` to exit the editor.

4. **Grant Execution Permissions**  
   Open terminal and make the script executable by running:
   ```bash
   chmod +x command_ins_tool
   ```

5. **Run the Script**  
   You can now run the tool with the following command:
   ```bash
   sudo ./command_ins_tool
   ```

---

## Contributing

Feel free to fork this repository and contribute your own tools or improvements. If you encounter any issues, please open an issue and I'll try to fix it as soon as possible!

---
