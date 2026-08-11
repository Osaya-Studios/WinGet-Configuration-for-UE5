# WinGet Configuration file for UE5 C++ workflow
> A WinGet Configuration file to set up all UE5 Visual Studio/C++ prerequisites
## How to use the config file?
1. Make sure you have winget installed
```shell
Install-Module -Name Microsoft.WinGet.Client -Force
Repair-WinGetPackageManager -AllUsers
```
2. Run this in an administrator PowerShell or Command Prompt window
```shell
winget configure -f https://github.com/Osaya-Studios/WinGet-Configuration-for-UE5/releases/latest/download/ue5-prereqs-config.yaml
```y
