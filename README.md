# Uncrustify for Apex
How to configure Uncrustify in VSCode and example uncrustify.cfg file for APEX.

## Install Uncrustify on your computer with Windows 10.
1. Go to https://sourceforge.net/projects/uncrustify/files/ and download latest version. 
1. It is non instalable ZIP file. Extract its content to `C:\Utils\Uncrustify` or any other folder where you keep your cli tools.
1. Add this location to path. Right click on start menu icon -> System -> Advanced system settings -> Environment Variables -> System variables -> Path -> Edit -> New -> and paste there `C:\Utils\Uncrustify` -> OK -> OK -> OK
1. Open [Windows Terminal](https://www.microsoft.com/pl-pl/p/windows-terminal/9n0dx20hk701?rtc=1&activetab=pivot:overviewtab) or cmd.exe and type `uncrustify --version` you should see Uncrustify-0.72.0_f or any newer version that you have installed.

In case it is not working, check if you correclty added path variable and restart computer.

## Install Uncrustify in VSCode
Install [Uncrustify plugin](https://marketplace.visualstudio.com/items?itemName=zachflower.uncrustify)

## Apex specific configuration
Press Ctrl + Shift + P and type `Uncrustify: Create default config file` which will create `uncrustify.cfg` file in root of your project.
Download uncrustify.cfg from this project and compare it with [WinMerge](https://winmerge.org) or any other tool and import rules that you want to use. 

If this it too hard for you then just overwrite your file with mine. In this repo history you can check which rules I have modified. 
