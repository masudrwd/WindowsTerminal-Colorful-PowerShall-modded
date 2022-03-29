1. install with winget -
<code>
winget upgrade JanDeDobbeleer.OhMyPosh
</code>
<br/>
- if winget not support on your system then try it -
<code>
Install-Module posh-git -Scope CurrentUser
Install-Module oh-my-posh -Scope CurrentUser
</code
<br/>
<br/>
2. Also get PSReadline if you're on PowerShell Core -'
  <br/>
<code>
Install-Module -Name PSReadLine -AllowPrerelease -Scope CurrentUser -Force -SkipPublisherCheck
</code>

<br/><br/>
3. Then run "notepad $PROFILE" and add these lines to the end:
<code>
notepad $PROFILE
</code>
<br/>
- and paste in this code -
<code>
Set-PoshPrompt -Theme gmay
$env:POSH_GIT_ENABLED = $true
</code>
<br/><br/>
4. Then search <code>"gmay"</code> on <code>Everything</code> software and paste gmay theme json i modified.

# DONE




