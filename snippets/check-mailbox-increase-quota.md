# Increase mailbox quotas to ORG's threshhold
```
Get-Mailbox <mailboxname> | Set-Mailbox -IssueWarningQuota <value> -ProhibitSendQuota <value> -ProhibitSendReceiveQuota <value>
```