# Commandski

This is Commandski an alternative to Windows Commando VM

to deploy:

```powershell
. { Invoke-WebRequest -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force
```

```powershell
$Cred = Get-Credential $env:USERNAME
```

```powershell
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/adcouch/Commandski/main/windply/redwin_deploy.choco -Credential $Cred 
```
Full disclosure the source for this project is from RTO and https://github.com/dmaristi/windply/ however updated to suite my needs.
