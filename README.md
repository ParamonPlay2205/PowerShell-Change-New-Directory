# PowerShell-Change-New-Directory
We would almost always create a new directory through PowerShell (or any other terminal emulator), and then later set it to that location... Well why not have a PowerShell module that would do the work for you? Bascially as you can already tell, this module will create the directory and then after it creates the directory it will set your running directory to the new directory it created.

# Installation
Before you install this module, make sure that you have either Windows PowerShell (5.1) or the Latest version of PowerShell Core (Recommended if you're on Windows, Mac, or Linux). After this, clone this repository. If you have programs like Oh My Posh in your PowerShell Terminal, then you can edit the $PROFILE file and put in "Import-Module [location of powershell module]" (replace what's in the square brackets with the location of the powershell module. Or if you're on Windows (10 or 11) and you have the latest version of PowerShell Core, then put this powershell module in "C:\Users\[YourWindowsUserName]\Documents\PowerShell\Modules\Change-New-Directory\mkcdir.psm1". So that you won't need to import the module everytime you open a new PowerShell Session.

# Customization
If you'd like to change the name of the cmd-let, then in your $PROFILE configration file. You can set an alias for the cmd-let from this module. Let's say you want it to be called "mkchdir" instead of "Set-NewLocation". Well in your $PROFILE enter "Set-Alias -Name [your custom cmd-let name] -Value Set-NewLocation". Now just reload your PowerShell session, and enter the name of the alias you set.
