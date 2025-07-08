# BLCE
B.L.C.E (Bash Line Command Editor)

## GO TO RELEASES TO DOWNLOAD!

blce (Bash Line Command Editor)
blce is a simple interactive Bash script that lets you perform common system management tasks from a user-friendly command-line menu.
Type help inside blce to see all available commands.

# Features
System update and upgrade

Install and remove packages

Display system information (requires neofetch)

Show the first 20 lines of a file

Create new files

Auto-update your system in the background

# Usage
Make the script executable:

```
chmod +x main.sh
Run the script:
```
```
./main.sh
```

# Commands
Command	Description
```
b	Quit blce
up	Update your system (sudo apt update -y)
in <package>	Install a package (e.g., in nano)
del <package>	Remove a package (e.g., del nano)
neo	Show system/OS info (requires neofetch)
head <file>	Show the first 20 lines of a file (e.g., head myfile.txt)
th <file>	Create a new file (e.g., th newfile.txt)
auto	Automatically update and upgrade system every 2 minutes (press Ctrl+C to stop)
help	Show the help menu
Notes
Sudo privileges are required for most system commands.

Make sure neofetch is installed if you want to use the neo command.

If your terminal behaves oddly after quitting, restart your terminal session.
```

# Example Session
```
Welcome to blce (bash line command editor) type help for help
: help
: up
: in nano
: del nano
: neo
: head myfile.txt
: th newfile.txt
: auto
: b
```
