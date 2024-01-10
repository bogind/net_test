# net_test

Nothing here yet except notes.

1. small app to test network speed (on windows right now)
1. maybe use neutralino, no UI, just background checking and a tray icon that shows a message box

## code

### Windows PowerShell

```
Get-NetAdapter | where Status -eq "Up" | select Name, InterfaceDescription, LinkSpeed | ConvertTo-Json
```