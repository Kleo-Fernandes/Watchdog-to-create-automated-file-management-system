Python Automated File Management System

This Python script is designed to organize, track, and back up files in a specified directory. It uses the **`watchdog`** library to monitor file system events like creation, modification, deletion, and movement in real-time.

Key Features:
- Automatically organizes files based on their naming convention into year and month subfolders.
- Creates backups of original files in a designated backup folder.
- Detects and handles modified files by moving them to a separate folder and restoring the original from backup.
- Logs all file system events to the console.

How It Works:
1. Monitors a specified folder for events.
2. Processes files starting with `GF` and having a length of 12 characters.
3. Extracts the year and month from the file name to categorize files.
4. Ensures modified files are managed and backed up properly.

This script is highly customizable and can be adapted for other naming conventions or workflows. To use it, update the folder paths in the code and run the script. It will run continuously until stopped.

Thankyou
Kleo Fernandes