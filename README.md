# Fallout Four Theme For Powershell
![image](https://github.com/user-attachments/assets/cfa944c9-e457-4f2b-93e0-a122aecf622f)

This repository will show you how to get the Fallout 4 terminal theme on your Windows Powershell. I give half credit to Lukasedv for the base code. Please read the other files when the step comes because you will get stuck otherwise. Also read BOOT_UP.md to see how to make a custom boot up message and add the Vault Boy in the boot up sequence. (Read the BOOT_UP.md file last.) Please read everything thoroughly to ensure success.

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
2. Paste the following code in the "list" section list and edit the parts that you want that are shown: (If the comments are giving errors, feel free to remove them.)

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
  "guid": "{GENERATE_YOUR_OWN_GUID}", // Visit my other file on how to do this or go to:
  "hidden": false,
  "intenseTextStyle": "all",
  "name": "Windows PowerShell", // Change this to any terminal app you want. For example: Windows Command Prompt
  "scrollbarState": "hidden",
  "useAcrylic": true
},
```
```diff
+ PLEASE VISIT THE GUID_GUIDE.md PAGE TO READ ABOUT HOW TO GENERATE THE GUID.
```
3. Hit Ctrl + S to save.
4. Then, scroll all the way down to the "schemes" section.
5. Paste the following code in the "schemes" list:

```json
{
  "background": "#0C0C0C",
  "black": "#0C0C0C",
  "blue": "#07F523",
  "brightBlack": "#767676",
  "brightBlue": "#07F523",
  "brightCyan": "#07F523",
  "brightGreen": "#07F523",
  "brightPurple": "#07F523",
  "brightRed": "#07F523",
  "brightWhite": "#07F523",
  "brightYellow": "#07F523",
  "cursorColor": "#07F523",
  "cyan": "#07F523",
  "foreground": "#07F523",
  "green": "#022000",
  "name": "Fallout",
  "purple": "#07F523",
  "red": "#07F523",
  "selectionBackground": "#07F523",
  "white": "#07F523",
  "yellow": "#07F523"
}
```
6. Hit Ctrl + S again to save.
7. Then, close out the file.

## Setting up Settings
At this point, you should still have the terminal settings open because it doesn't close when opening the JSON file.
1. Restart the terminal application and make your way back to the settings page.
3. On the sidebar, underneath "Profiles", click on Windows Powershell or the app you used.
4. Then, underneath additional settings, click on "Appearance".
5. Then click on the color scheme drop-down, and pick the scheme that is green and says Fallout.
6. Scroll down to text formatting, click the drop-down, and choose "Bold font with bright colors"
7. Then, enable acrylic material underneath "Transparency".
8. Lastly, hit the save button.
```diff
+ PLEASE VISIT THE FONTS.md PAGE TO LEARN HOW TO ADD THE CUSTOM FALLOUT 4 FONT.
```


