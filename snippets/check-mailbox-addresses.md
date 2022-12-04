REM Check Mailbox addresses
set /p "username=enter username:"
Get-Mailbox <username> | select -exp emailaddresses | sort