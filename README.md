## Description

This script will redirect "My Documents", "AppData", and "Desktop" to $FR\USERNAME\FOLDER

## Usage

Set the $FR variable to be the location that you want the folders to be redirected to, and then just run the .ps1 file in powershell. You will be prompted to choose which folders you want to be changed.

NOTE: When redirecting "My Documents", this script will also redirect "My Pictures", "My Videos", and "My Music". This is intentional, as these are still classed as system folders, which are currently situated in "My Documents".