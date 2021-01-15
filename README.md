# Requirements
Requires **[PowerShell 5.1](https://github.com/PowerShell/PowerShell#get-powershell)** or above.

A valid CrowdStrike **[OAuth2 API key](https://falcon.crowdstrike.com/support/api-clients-and-keys)** with appropriate permissions.

# Installation
1. Download the files in this repository as a ZIP
2. Extract the contents of `psfalcon-master.zip` into the appropriate PowerShell modules folder:

Linux/MacOS:
```powershell
Expand-Archive ./psfalcon-master.zip $HOME/.local/share/powershell/Modules/psfalcon/2.0.0
```
Windows (PowerShell Core/6+):
```powershell
Expand-Archive .\psfalcon-master.zip $HOME\Documents\PowerShell\Modules\psfalcon\2.0.0
```
Windows (PowerShell Desktop/5.1):
```powershell
Expand-Archive .\psfalcon-master.zip $HOME\Documents\WindowsPowerShell\Modules\psfalcon\2.0.0
```

# Commands
Retrieve a list of commands:
```powershell
Get-Command -Module PSFalcon
```

Retrieve simplified help information about a command:
```powershell
<Command> -Help
```