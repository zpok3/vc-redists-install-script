# vc-redists-install-script
Simple script for installing VC++ Redistributables using Microsoft's WinGet package manager. It's literally a single command you can enter into a terminal.

# Installation
You can install this without downloading anything by opening either cmd.exe or Windows Terminal and entering the following command:
```pwsh
winget install Microsoft.VCRedist.2005.x64 Microsoft.VCRedist.2005.x86 Microsoft.VCRedist.2008.x64 Microsoft.VCRedist.2008.x86 Microsoft.VCRedist.2010.x64 Microsoft.VCRedist.2010.x86 Microsoft.VCRedist.2012.x64 Microsoft.VCRedist.2012.x86 Microsoft.VCRedist.2013.x64 Microsoft.VCRedist.2013.x86 Microsoft.VCRedist.2015+.x64 Microsoft.VCRedist.2015+.x86
```
Alternatively you can download one of the files from the releases. Right click and select `Run as administrator` for the `.bat` file or `Run with PowerShell` for the `.ps1` file.
