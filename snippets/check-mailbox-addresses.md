# Check Mailbox addresses
```
Get-Mailbox <username> | select -exp emailaddresses | sort
```