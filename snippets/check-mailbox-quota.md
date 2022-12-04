# Check mailbox quotas
```
Get-Mailbox <username> | Select IssueWarningQuota, ProhibitSendQuota, ProhibitSendReceiveQuota
```