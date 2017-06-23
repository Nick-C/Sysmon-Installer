# Sysmon Deployment
This uses the [Powershell App Deployment Toolkit](http://psappdeploytoolkit.com/) to handle installing and uninstalling [Sysmon](https://technet.microsoft.com/en-us/sysinternals/sysmon).

All the code changes are in the Deploy-Application.ps1 file.

Everything else is included for the sake of completeness.

Included sample Sysmon config is from https://github.com/SwiftOnSecurity/sysmon-config

Included Powershell App Deployment Toolkit is version 3.6.9

Included Sysmon.exe is version 6.03

## Usage
As with any standard PS App Toolkit, you can call it via either the included .exe or .ps1
This is best installed silently, if you want to show any user popups you will need to modify Deploy-Application.ps1 accordingly.

### Installation
 ``` Deploy-Application.ps1 -DeploymentType "Install" -DeployMode "Silent" ```
 
 or
 
 ``` Deploy-Application.exe -DeploymentType "Install" -DeployMode "Silent" ```
 
 ### Uninstallation
  ``` Deploy-Application.ps1 -DeploymentType "UnInstall" -DeployMode "Silent" ```
  
 or
 
 ``` Deploy-Application.exe -DeploymentType "UnInstall" -DeployMode "Silent" ```
 
 