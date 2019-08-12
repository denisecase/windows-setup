# Windows Setup For Developers (The Basics)

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v1.4%20adopted-ff69b4.svg)](code-of-conduct.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

> Configure Windows for software development - turn on developer mode and get PowerShell ready for projects

- [Webpage](https://denisecase.github.io/windows-setup/)
- [Source](https://github.com/denisecase/windows-setup)

## Learn about Developer Mode

- Read: [What Is “Developer Mode” in Windows 10?](https://www.howtogeek.com/292914/what-is-developer-mode-in-windows-10/)

## Enable Developer Mode

1. In Windows go to Settings / Update & Security / For Developers / select “Developer mode”.
2. Wait until the package finishes installing.
3. Scroll down to "For Developers" and ensure the following options are checked.
4. "Change settings to show file extensions"
5. "Change settings to show hidden and system files"
6. "Change settings to show full path in title bar"
7. Scroll down to "PowerShell" and ensure the following option is checked.
8. "Change execution policy to allow local PowerShell scripts to run without signing. Require signing for remote scripts."

## Learn about PowerShell

PowerShell allows us to type commands affecting our computer. 
It allows us to create new files and folders, install programs, run programs, and more.

- Read: [Table of Basic PowerShell Commands](https://blogs.technet.microsoft.com/heyscriptingguy/2015/06/11/table-of-basic-powershell-commands/)

## Add "Open PowerShell window here as administrator"

Windows File Explorer provides a context menu when you right-click inside a folder.
Open File Explorer, go to "My Documents" and try it.
We want to add an item to this context menu so that when we click in a working folder, we can open a PowerShell window here - ready to execute commands. in this specific location on our machine.

- Read [How to Add "Open PowerShell window here as administrator" context menu in Windows 10](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html)

Update your folder context menu.

1. Open the link  [How to Add "Open PowerShell window here as administrator" context menu in Windows 10](https://www.tenforums.com/tutorials/60177-add-open-powershell-window-here-administrator-windows-10-a.html).
2. Click Download in Step 2.
3. Follow Steps 5-8.

## Terms

- Command line interface (CLI)
- File name - the complete name + extension of the file OR the part that comes before the . and extension
- File extension - the part at the end of the file that indicates its type (e.g. doc, xls, md, html)
- Folder / directory - a place to store files on your computer
- Hidden files - files not displayed to typical users
- Operating system - software that provides a computer's most basic functions such as connecting devices and executing applications
- PowerShell - a powerful CLI for Windows
- System files - files used by Windows that should not be modified by users
- Windows 10 - a popular operating system

## Next Steps

- See [Windows File Management](https://github.com/denisecase/windows-file-management)
- See [Get Setup With Chocolatey](https://github.com/denisecase/get-setup-with-chocolatey)
