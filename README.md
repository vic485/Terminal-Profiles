# Windows Terminal Profiles
My personal settings for the new Windows Terminal

**NOTE:** Windows terminal will crash if the default profile guid does not match a profile, or a profile exists for a terminal/console which is not installed on the local machine.

## Terminals
- Powershell Core 7 preview
- Windows Powershell
- Windows Command Prompt
- Azure Cloud Shell
- Windows Subsystem for Linux (Ubuntu 18.04 LTS)

## Installation
Install JetBrians Mono font to your system before cloning these settings. This looks better than the defaults in my opinion and each profile uses this font by default.
Backup your old settings.json and clone this repository into `C:\Users\USERNAME\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState` or wherever your original file was located. Make any necessary adjustments prior to launching Windows Terminal again.

To run a different OS in WSL run the command `wsl -l` in powershell and change the "commandline" property of the fifth profile to reflect one of the results.