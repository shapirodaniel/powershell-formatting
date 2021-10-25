# Formatting PowerShell With VS Code

This guide walks the user through setting up PowerShell auto-formatting with Microsoft's PowerShell Extension for VS Code.

## Use Case

Teams are more productive and can more easily align and review, debug, and modify/extend an existing and evolving codebase through the use of style-agnostic formatters such as Prettier.

By installing the Microsoft PowerShell Extension and configuring VS Code's format settings, teams can ensure that each individual contributor's code aligns with a global formatting standard.
<br/><br/>

## User Story

As a developer, I want any PowerShell code I write in VS Code to automatically format on save so that my team and I can conduct code reviews and shared problem solving sessions more efficiently.

# Steps

## Install VS Code

Follow this link to get started with Visual Studio Code (VS Code).

[Install VS Code](https://code.visualstudio.com/Download)

<em>Note: Visual Studio and Visual Studio Code are independent integrated development environments (IDEs). Please ensure that you have downloaded and installed VS Code, which is a freely available, open-sourced IDE maintained by Microsoft.</em>
<br/><br/>

## Install the Microsoft PowerShell VS Code Extension

Navigate to the following highlighted icon in the main VS Code blade: in the extension search bar, type <code>PowerShell</code> and select the following extension, then click through to download.

![powershell-extension-installation](./images/01-powershell-extension-installation.png)
<br/><br/>

## Reload VS Code To Initialize The Extension

Hit <code>ctrl + shift + P</code> to open VS Code's command explorer, type <code>Reload Window</code>, and select the option indicated by <code>Developer: Reload Window</code>. VS Code will relaunch; this is expected.
<br/><br/>

## Configure VS Code's Auto Formatting For PowerShell files (.ps1)

There are two ways to configure VS Code's auto formatting feature for PowerShell files. You can replicate the following instructions by hitting <code>ctrl + shift + P</code> and typing <code>Format Document With</code> and following the instructions below, which will be accomplished by right-clicking in an open PowerShell <code>.ps1</code> file.

Right-click and select <code>Format Document With...</code>: this will launch VS Code's command explorer. Next, select <code>Configure Default Formatter...</code> and choose the <code>PowerShell</code> option.
<br/><br/>

## Configure Global Formatting Settings

Hit <code>ctrl + shift + P</code> to launch VS Code's command explorer and type <code>Settings</code>, then select <code>Preferences: Open Settings (UI)</code> to launch VS Code's settings menu.

Next, type format in the search bar at the top of the settings UI and check the boxes for <code>Editor: Format On Paste</code> and <code>Editor: Format On Save</code>.

(Note: you may have to reload your developer window again after updating VS Code's settings from the UI.)

![format-settings](./images/02-format-settings.png)
