# Checking rights permissions on user mailbox
```
Get-Mailbox <mailboxmame> | Get-MailboxPermission | Where{$_.isInherited -eq $false} | Select User, AccessRights | Sort User
```