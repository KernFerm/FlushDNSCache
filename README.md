# Flush DNS Batch Script  OR 

This is a simple batch script for Windows that flushes the DNS resolver cache.



# CLICK THE GREEN BUTTON UPPER RIGHT CORNER DOWNLOAD ZIPFILE

## Usage

1. Open a command prompt with administrative privileges.
2. Navigate to the directory containing the `flushdns.bat` file.
3. Run the script by typing `flushdns.bat` and pressing Enter.

## What the Script Does

Here's a breakdown of what each line in the script does:

```bat
@echo off             # Prevents the command prompt from displaying the commands in the script as they run
ipconfig /flushdns    # Flushes the DNS resolver cache
pause                 # Waits for the user to press a key before closing the command prompt window
