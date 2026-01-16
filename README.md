# terminal-context-menu
<<<<<<< HEAD
I am sharing here `tcm.reg`, a registry file which creates a <ins>directory context menu</ins> for `cmd` and `powershell` commands, to be opened **within Windows Terminal**.
=======
I am sharing here `tcm.reg`, a registry file which creates a <ins>directory context menu</ins> for `cmd` and `powershell`, to be opened at path **within Windows Terminal**.
>>>>>>> a5fe4b642b67c8a990da3c71d1e39dbd0bb4f759

The context menu is shown when the user right-clicks on a folder or on the folder background.

<img width="717" height="202" alt="image" src="https://github.com/user-attachments/assets/16781e73-51d2-4bf0-bdc7-44c64d81f439" />

<sup>These context menu commands open at the Folder path, within <ins>Windows Terminal dedicated profiles</ins>.</sup>

<<<<<<< HEAD
The commands are designed to <ins>reuse existing Terminal windows</ins>, adding new tabs as needed, to avoid clutter (though by design admin and non-admin profiles will always belong to separate Terminal windows.)
=======
The commands are designed to reuse existing Terminal windows, adding new tabs as needed, to avoid clutter (though by design admin and non-admin profiles will always belong to separate Terminal windows.)
>>>>>>> a5fe4b642b67c8a990da3c71d1e39dbd0bb4f759

**This is NOT meant to open PowerShell or CommandPrompt directly, but only within Windows Terminal**.

## Installation

Just double click on `tcm.reg` to add the context menu to Windows.

Change the path to the custom icons if you want to use your own, or the ones provided in this repository.

## Requirements

The reg file assumes you have [Windows Terminal](https://github.com/microsoft/terminal) installed, with these profiles:
- Command Prompt
- Windows PowerShell
- Command Prompt (admin)
- Windows PowerShell (admin)

<img width="604" height="280" alt="image" src="https://github.com/user-attachments/assets/fc3ef46c-1f5d-4c53-bda3-036827f151f1" />

You can of course modify the `.reg` file to suit the Windows Terminal profiles you use.

The `.reg` file includes comments to identify the relevant parts.

## Uninstallation
Just double click on `remove-tcm.reg` to uninstall this context menu.
