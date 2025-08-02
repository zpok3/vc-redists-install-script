# vc-redists-install-script
Simple script for installing VC++ Redistributables using Microsoft's WinGet package manager. It's literally a single command you can enter into a terminal.

# Installation
## Option 1
You can run this without downloading anything by opening either cmd/PowerShell/Windows Terminal and entering the following command:
```pwsh
winget install Microsoft.VCRedist.2005.x64 Microsoft.VCRedist.2005.x86 Microsoft.VCRedist.2008.x64 Microsoft.VCRedist.2008.x86 Microsoft.VCRedist.2010.x64 Microsoft.VCRedist.2010.x86 Microsoft.VCRedist.2012.x64 Microsoft.VCRedist.2012.x86 Microsoft.VCRedist.2013.x64 Microsoft.VCRedist.2013.x86 Microsoft.VCRedist.2015+.x64 Microsoft.VCRedist.2015+.x86
```
## Option 2
Alternatively you can download one of the files from the [releases](https://github.com/zpok3/vc-redists-install-script/releases/latest). 
### Batch script
Right click the file and select `Run as administrator`.
### PowerShell script
1. Open PowerShell/Windows Terminal as an administrator.
2. Use the following command to change to the directory to where you downloaded the files (edit the directory as needed, the one provided is just an example):
```pwsh
cd C:\Users\<YOUR_USERNAME>\Downloads
```
3. Run the following command to run the script:
```pwsh
./VC_Redists_Install.ps1
```
> [!note]
> If you've never run a script before you may need to run this command first:
> ```pwsh
> Set-ExecutionPolicy Unrestricted -Force
> ```
You can also just run the scripts normally instead of as an administrator but you'll have to click yes on twelve UAC prompts.
