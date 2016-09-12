# power
$computername = ' '
remove-computer -computer $computername -unjoinDomainCredential $env:USERNAME -workgroupName Local -Restart -Force

