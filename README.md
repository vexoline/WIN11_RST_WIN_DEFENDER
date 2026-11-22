# Windows Defender History Cleanup

`RESET_WIN_DEFENDER.cmd` is a Windows 11 CMD/PowerShell hybrid that elevates itself and removes Microsoft Defender Protection history data, including detection history, quarantine data, Controlled Folder Access history, and the matching scan database files. It can prompt to restart Windows afterward.

## Important warning

This permanently removes local Defender history and quarantine data. Do not use it to respond to an active threat or when you need to preserve evidence. Review and resolve detections in Windows Security first. Only run the script if you understand what will be removed and have a specific reason to clear this data.

To run, open `RESET_WIN_DEFENDER.cmd` and approve the Windows UAC prompt. The script pauses before continuing and asks whether to restart Windows after the cleanup.

