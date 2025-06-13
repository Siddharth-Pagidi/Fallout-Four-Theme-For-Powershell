# Fallout Four Theme For Powershell
This repository will show you how to get the Fallout 4 terminal theme on your Windows Powershell. I give half credit to Lukasedv for the base code.

## Download Windows Terminal
To download Windows Terminal, go to this link: https://github.com/microsoft/terminal.
This is the GitHub link so you will need to follow their instructions for installation.

## Navigating To The JSON File
1. First, open Windows Terminal.
2. Then, at the very top, click the drop-down arrow next to the plus sign.
3. After that, hit settings.
4. Next, at the bottom left of the application, you should see 'Open JSON File'. Click on this.

## Setting Up The Code
1. After opening up the file, scroll down to the "list" section inside of "profiles".
2. Paste the following code in the "list" section list.

```json
{
  "colorScheme": "Fallout",
  "commandline": "powershell.exe -NoLogo",
  "cursorShape": "filledBox",
  "experimental.retroTerminalEffect": false,
  "font": 
  {
    "face": "Share Tech Mono"
  },
  "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
  "hidden": false,
  "intenseTextStyle": "all",
  "name": "Windows PowerShell",
  "scrollbarState": "hidden",
  "useAcrylic": true
},
```


