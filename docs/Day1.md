#### Installation of WSL2

1. **Enable WSL2:**
   - Open PowerShell as an administrator and run the following commands:
     ```powershell
     wsl --install
     ```
   - Restart your computer after the installation is complete.

2. **Install Ubuntu:**
   - In the Microsoft Store, search for `Ubuntu` and install the latest version.

3. **Open Ubuntu:**
   - After installation, open the Ubuntu application to start the installation process.

### Shell vs Terminal vs Kernel

- **Shell:** A command-line interface that allows you to interact with the operating system. It provides a command prompt and interprets user commands.
- **Terminal:** A window in which a shell is running. It provides a command-line interface and allows you to execute shell commands.
- **Kernel:** The core component of an operating system that manages hardware resources and provides the basic services for applications to run.

### Filesystem Hierarchy

- **/:** The root directory where all other directories and files are contained.
- **/etc:** Contains configuration files for the system and services.
- **/var:** Contains variable data, such as logs, caches, and temporary files.
- **/home:** Contains user home directories.
- **/usr:** Contains user applications, libraries, and data.
- **/tmp:** Contains temporary files that are deleted when the system is rebooted.
- **/proc:** Contains pseudo-files that provide information about the system's processes and system configuration.
- **/dev:** Contains device files that represent system hardware.

### Navigation

- **pwd:** Displays the current working directory.
- **ls -la:** Lists all files and directories in the current directory, including hidden files, with detailed information (permissions, owner, group, size, and date).
- **cd:** Changes the current working directory to the specified path.
- **tree:** Displays a tree-like representation of the directory structure.
- **Absolute paths:** Full paths from the root directory to a file or directory.
- **Relative paths:** Paths relative to the current working directory.

### Getting Help

- **man:** Displays the manual page for a command.
- **--help:** Displays the help for a command.
- **apropos:** Searches for commands related to a topic.
- **tldr:** Displays a simplified version of the manual page.


#### Challenge From Bandit 
### Bandit level 0-> level 1
- The task  is that you need to find  passwords for the nextlevel   which is stored in  file called readme located in home dir
-Commands you may need to solve this level
ls , cd , cat , file , du , find
- The Commands
> ls -a 
- readme .. .
> cat readme
- This is Password : {sdfhbgvshdfmgdsh}

