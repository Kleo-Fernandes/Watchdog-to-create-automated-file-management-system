#Python Automated File Management System

This Python script is designed to organize, track, and back up files in a specified directory. It uses the **`watchdog`** library to monitor file system events like creation, modification, deletion, and movement in real-time.

##Key Features:
- Automatically organizes files based on their naming convention into year and month subfolders.
- Creates backups of original files in a designated backup folder.
- Detects and handles modified files by moving them to a separate folder and restoring the original from backup.
- Logs all file system events to the console.

##How It Works:
1. Monitors a specified folder for events.
2. Processes files starting with `GF` and having a length of 12 characters.
3. Extracts the year and month from the file name to categorize files.
4. Ensures modified files are managed and backed up properly.

This script is highly customizable and can be adapted for other naming conventions or workflows. To use it, update the folder paths in the code and run the script. It will run continuously until stopped.

#Run Python Script on Boot (Windows) Using Startup Folder

This repository explains how to **automatically run a Python script on Windows startup using the Startup folder with a `.bat` launcher.** This is the **simplest method** for automating the watchdog file management System 
---



# Run Watchdog Management Project on Boot (Windows)

This guide explains how to **run your `Watchdog_Management_Project.py` automatically on Windows startup using a `.bat` file in the Startup folder**.

---

## 🚀 Steps


1. Create a Batch File
Open Notepad.

Paste:

@echo off
"C:\Path\To\Watchdog_Management_Project.py"

2. Save the file as:

launch_watchdog_project.bat

3. Add the Batch File to the Startup Folder

Press:
Win + R

Type:
shell:startup
Press Enter.

Copy your launch_watchdog_project.bat into the folder displayed

Now, your Watchdog_Management_Project.py will automatically run each time you log in to Windows.

