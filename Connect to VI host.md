# power

$vmcred = Get-Credential ("$env:username")
Add-PSSnapin vmware.vimautomation.core -ea 'SilentlyContinue'
Connect-VIServer -Server  -Credential $vmcred
