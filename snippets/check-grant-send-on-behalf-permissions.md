# Adding permissions

Adding the permissions for *'send on behalf'* (WARNING: this is not for *'Send As'* permissions).

### make sure you add each user within *"username"* string.
```
Get-Mailbox <mailboxname> | Set-Mailbox -GrantSendOnBehalfTo @{add="username"}
```