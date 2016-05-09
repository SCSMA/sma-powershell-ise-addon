# sma-powershell-ise-addon
The Service Management Automation PowerShell ISE Add-on makes it easy to author and test your runbooks in your local PowerShell ISE

Installation:
You can install the ISE Add-on module from PowerShell Gallery with:
> Install-Module SMAAuthoringToolkit -Scope CurrentUser

Then, if you want the PowerShell ISE to always automatically load the add-on, run:
> Install-SMAIseAddOn

Otherwise, whenever you want to load the add-on, just run the following in the PowerShell ISE:
> Import-Module SMAAuthoringToolkit

For more information about SMAAuthoringToolKit: https://blogs.technet.microsoft.com/orchestrator/2016/04/28/introducing-service-management-automation-ise-add-on/ 
