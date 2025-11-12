## Download BgInfo

Download the latest version from Releases:       
https://github.com/dismtool/BgInfo/releases/tag/4.33

## System requirements

* Requires .NET Framework version 4.6 or higher
* Minimum supported operating systems: Windows Vista or Windows Server 2008

## Introduction

How often have you approached a system in your office only to navigate through multiple diagnostic windows just to recall key details about its configuration, like its name, IP address, or operating system version? If you oversee several computers, BGInfo is likely essential. It automatically presents critical information about a Windows machine directly on the desktop background, including the computer name, IP address, service pack version, and more. You have full control to modify any field, adjust font and background colors, and even place it in your startup folder so it runs at every boot. Additionally, you can configure it to appear as the background on the logon screen.

Because BGInfo merely writes a new desktop bitmap and then exits, you don’t need to worry about it using system resources or interfering with other programs.

## Installation and Use

For a detailed introduction to using BGInfo, see Mark’s article in Windows IT Pro Magazine’s Power Tools. If you encounter questions or issues, the Sysinternals BgInfo Forum is the place to go.

By placing BGInfo in your Startup folder, you can make sure the system information displayed is always current at boot. Once you’ve chosen the data to show, the command-line option /timer:0 allows you to update the display without showing the dialog box.

You can also leverage the Windows Task Scheduler to run BGInfo on a recurring schedule, keeping long-running systems up to date automatically.

If you create a BGInfo configuration file via the File|Save Settings menu, you can easily import and apply those settings on other systems by using the /I<path> or /iq<path> command-line options.

## Using BgInfo

When launched, BGInfo displays a preview of the default desktop background with its configured information. If you make no changes, it automatically applies the settings and exits once the 10-second countdown timer completes.

Interacting with any button or menu item will pause the timer, giving you the opportunity to adjust the layout and content of the background information.
