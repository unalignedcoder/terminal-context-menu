# terminal-context-menu
I am sharing here `tcm.reg`, a registry file I've used to create a directory (right-click and background) context menu for `cmd` and `powershell`.

These console commands open at the path, within Windows Terminal dedicated profiles.

<img width="717" height="202" alt="image" src="https://github.com/user-attachments/assets/16781e73-51d2-4bf0-bdc7-44c64d81f439" />

The commands are designed to reuse existing Terminal windows, adding new tabs as needed.

## Installation

Just double click on `tcm.reg` to add the context menu to Windows.

## Requirements

The reg file assumes you have [Windows Terminal](https://github.com/microsoft/terminal) installed, with these profiles:
- Command Prompt
- Windows PowerShell
- Command Prompt (admin)
- Windows PowerShell (admin)

<img width="604" height="280" alt="image" src="https://github.com/user-attachments/assets/fc3ef46c-1f5d-4c53-bda3-036827f151f1" />

You can of course modify the reg file to suit the Windows Terminal profiles you use.
