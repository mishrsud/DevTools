# What is this

This folder contains the icons and instructions to customise your Cmder shell so that it shows nice icons in the console tabs.

## Tools

- Get Git for windows from **[here](https://git-for-windows.github.io/)**
- Get Cmder from **[here](http://cmder.net/)**
  - Use "Download mini" if you already have Git for windows
  - Use "Download full" if you don't have it
- Get ConEmu from **[here](http://conemu.github.io/)**

## Step-by-step

Note: Instructions apply to Windows 10 64-bit

1. After you have Cmder setup, launch it from "C:\Program Files\Cmder\Cmder.exe"
2. In the bottom left pane, look for the green plus icon and click the little down arrow to bring up the setup tasks dialogue

    ![screen-shot](/images/cmder-customise.PNG)
3. Click the "Setup tasks" from the menu that shows up when you click on the little down arrow

    ![screen-shot-2](/images/cmder-customise-2.PNG)
4. Customise the icon by changing the Task parameters e.g. ` /icon "%CMDER_ROOT%\icons\metro-powershell-logo.ico"`. The CMDER_ROOT environment variable points to the directory where Cmder is installed (see step 1).

    ![screen-shot-3](/images/cmder-customise-3.PNG)
5. Use the icons from cmder-icons folder in this repo! You'll get nice icons on tabs:

    ![screen-shot-4](/images/cmder-customise-4.PNG)