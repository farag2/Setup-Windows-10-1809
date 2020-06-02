<div align="center">
  <h1>Windows 10 Setup Script</h1>

**"Windows 10 Setup Script" is a set of tweaks for OS fine-tuning and automating the routine tasks** 🏆

![GitHub release (latest by date)](https://img.shields.io/github/v/release/farag2/Windows-10-Setup-Script)
![GitHub All Releases](https://img.shields.io/github/downloads/farag2/Windows-10-Setup-Script/total)

Version for [20H1](https://gist.github.com/farag2/5a6d9952247aefe42ba81a9d95507765)
</div>

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9cffc84998644839a97d8fcf756eb148)](https://app.codacy.com/manual/farag2/Windows-10-Setup-Script?utm_source=github.com&utm_medium=referral&utm_content=farag2/Windows-10-Setup-Script&utm_campaign=Badge_Grade_Settings)
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Q5Q51QUJC)

## Screenshots

![Image](https://i.imgur.com/azbQLAN.png)
![Image](https://i.imgur.com/nJPs2XV.png)
![intro](https://i.imgur.com/zXCi8SJ.png)

## Videos

<details>
  <summary>YouTube videos</summary>

[![Image](http://img.youtube.com/vi/8MzuDLNH9QU/0.jpg)](http://www.youtube.com/watch?v=8MzuDLNH9QU)
[![Image](http://img.youtube.com/vi/cjyi9nX8sFA/0.jpg)](http://www.youtube.com/watch?v=cjyi9nX8sFA)
</details>

## Core features

- Set up Privacy & Telemetry;
- Turn off diagnostics tracking scheduled tasks;
- Set up UI & Personalization;
- Uninstall OneDrive "correctly";
- Interactive prompts;
- Change %TEMP% environment variable path to %SystemDrive%\Temp
- Change location of the user folders programmatically (without moving user files) within interactive menu using up/down arrows and Enter key to make a selection
  - "Desktop";
  - "Documents";
  - "Downloads";
  - "Music";
  - "Pictures"
  - "Videos.
- Uninstall UWP apps from all accounts with exception apps list with pop-up form written in [WPF](#Images);
- Turn off Windows features;
- Remove Windows capabilities with pop-up form written in [WPF](#Images);
- Create a Windows cleaning up task in the Task Scheduler;
  - A toast notification will pop up a minute before the task [starts](#Images)
- Create tasks in the Task Scheduler to clear
  - %SystemRoot%\SoftwareDistribution\Download
  - %TEMP%
- Unpin all Start menu tiles;
- Pin shortcuts to Start menu using [syspin.exe](http://www.technosys.net/products/utils/pintotaskbar)
  - Three shortcuts are preconfigured to be pinned: Control Panel, "old style" Devices and Printers, and Command Prompt
- Turn on Controlled folder access and add protected folders using dialog menu;
- Add exclusion folder from Microsoft Defender Antivirus scanning using dialog menu;
- Add exclusion file from Microsoft Defender Antivirus scanning using dialog menu;
- Refresh desktop icons, environment variables and taskbar without restarting File Explorer;
- Many more File Explorer and context menu "deep" tweaks.

## Usage

To run the script:

- Download [up-to-date version](https://github.com/farag2/Setup-Windows-10/releases);
- Expand the archive;
- Check whether .ps1 is encoded in **UTF-8 with BOM**;
- Run .ps1 file via PowerShell.exe;
  - Or Start.cmd as Administrator. The script will start immediately.

## Supported Windows versions

|Version|Code name|   Marketing name   |Build|  Arch  |      Editions     |
|:-----:|:-------:|:------------------:|:---:|:------:|:-----------------:|
| 1909  |  19H2   |November 2019 Update|18363|x64 only|Home/Pro/Enterprise|
| 1903  |  19H1   |   May 2019 Update  |18362|x64 only|Home/Pro/Enterprise|

## FAQ

Read the code you run carefully. Some functions are presented as an example only. You must be aware of the meaning of the functions in the code. **If you're not sure what the script does, do not run it**.
**Strongly recommended to run the script after fresh installation**. Some of functions can be run also on LTSB/LTSC and on older versions of Windows and PowerShell (not recommended to run on the x86 systems).

## GUI version (C#)

Still [Cooking](https://github.com/farag2/Windows-10-Setup-Script/tree/GUI-dev)

## Microsoft Docs

- [Release information](https://docs.microsoft.com/en-us/windows/release-information)
- [Known issues](https://docs.microsoft.com/en-us/windows/release-information/status-windows-10-1909)

## Ask a question on

- [Habr](https://habr.com/en/post/465365/)
- [Ru-Board](http://forum.ru-board.com/topic.cgi?forum=62&topic=30617#15)
- [4PDA](https://4pda.ru/forum/index.php?s=&showtopic=523489&view=findpost&p=95909388)
- [My Digital Life](https://forums.mydigitallife.net/threads/powershell-script-setup-windows-10.81675/)
- [Reddit](https://www.reddit.com/r/PowerShell/comments/go2n5v/powershell_script_setup_windows_10/)

## PS

Collection of useful [scripts](https://github.com/farag2/Utilities)
