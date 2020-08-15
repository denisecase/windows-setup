# Windows Setup For Developers (The Basics)

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](code-of-conduct.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

> Configure Windows for software development

- [Webpage](https://denisecase.github.io/windows-setup/)
- [Source](https://github.com/denisecase/windows-setup)

## Task 1: Turn on Developer Settings

1. In Windows go to Settings / Update & Security / For Developers. 
1. Scroll down to "File Explorer". Grey checks are enabled, blue checks are not yet enabled.
1. Verify the following settings are checked:
  - "Change settings to show file extensions"
  - "Change settings to show hidden and system files"
  - "Change settings to show full path in title bar"
  
1. Click "Apply". Verify the above settings now have grey checks.
1. Scroll down to "PowerShell".
1. Verify the following option is checked.
  - "Change execution policy to allow local PowerShell scripts to run without signing. Require signing for remote scripts."
  
1. Click "Apply". Check should now be grey.

## Learn about PowerShell

PowerShell allows us to type commands affecting our computer.
It allows us to create new files and folders, install programs, run programs, and more.

## Task 2: Add "Open PowerShell window here as administrator"

Windows File Explorer provides a context menu when you right-click inside a folder.
Open File Explorer, go to "My Documents" and try it.
We want to add an item to this context menu so that when we click in a working folder, we can open a PowerShell window here - ready to execute commands in this specific location on our machine.

- Read [How to Add "Open PowerShell window here as administrator" context menu in Windows 10](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html)

Update your folder context menu:

1. Open the link  [How to Add "Open PowerShell window here as administrator" context menu in Windows 10](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html).
2. Click Download in Step 2.
3. Follow Steps 5-8.

## PowerShell Privileges

By default, Windows will launch PowerShell without administrator privileges.
However, when using PowerShell to perform advanced functions such as installations,
you will need Admin priviledges which allow you to create, delete, and modify settings
and items such as files, folders, and environment variables.
Adding this option to the context menu makes it easily accessible.

## Know These Terms

- Administrator - a user with elevated permissions including create, delete, and modify settings and items
- Context menu - a pop-up menu, typically avaiable when right-clicking on an item
- File name - the complete name + extension of the file OR the part that comes before the . and extension
- File extension - the part at the end of the file that indicates its type (e.g. doc, xls, md, html)
- Folder / directory - a place to store files on your computer
- Hidden files - files not displayed to typical users
- Operating system - software that provides a computer's most basic functions such as connecting devices and executing applications
- Command line interface (CLI)
- PowerShell - a powerful CLI for Windows
- System files - files used by Windows that should not be modified by users
- Windows 10 - a popular operating system
- Windows File Explorer - a graphical interface to folders and files on Windows

## Optional: Add Linux to your Windows System

You can add Ubuntu or another Linux distribution to your Windows system in a couple easy steps.
Microsoft provides instructions for installation.

- See [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10)

## Next Steps

- See [Windows File Management](https://github.com/denisecase/windows-file-management)
- See [Get Setup With Chocolatey](https://github.com/denisecase/get-setup-with-chocolatey)

## See Also

- [Setting Up for Professional Software Development](https://github.com/denisecase/pro-dev-list)
