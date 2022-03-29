#1. install with winget -

winget upgrade JanDeDobbeleer.OhMyPosh

#- if winget not support on your system then try it -

Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser



#2. Also get PSReadline if you're on PowerShell Core -

Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck



#3. Then run "notepad $PROFILE" and add these lines to the end:

notepad $PROFILE

#- and paste in this code -

Set-PoshPrompt -Theme gmay
$env:POSH_GIT_ENABLED = $true

#4. Then search "gmay" on Everything software and paste gmay theme json i modified.

#DONE




