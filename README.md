- ##   there are no issues with this repo, if you want to FORK it GO FORK IT!!!!
- ##   make account to FORK REPO

# Flush DNS Batch Script 

This is a simple batch script for Windows that flushes the DNS resolver cache.



# CLICK THE GREEN BUTTON UPPER RIGHT CORNER DOWNLOAD ZIPFILE

## Usage

1. Open a command prompt with administrative privileges.
2. Navigate to the directory containing the `flushdns.bat` file.
3. Run the script by typing `flushdns.bat` and pressing Enter.

## What the Script Does

Here's a breakdown of what each line in the script does:

```bat
@echo off                        :: Disable displaying commands
echo Flushing DNS Cache...      :: Display message indicating DNS cache flushing process starting
echo.                           :: Output a blank line for formatting
ipconfig /flushdns             :: Flush the DNS resolver cache
echo.                           :: Output a blank line for formatting
echo DNS Cache Is Cleared!!     :: Display message indicating DNS cache is cleared
pause                           :: Pause script execution, allowing user to view output
