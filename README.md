# OpenDesktop4win
### a bat file that kills explorer and opens another program and for example a new desktop

Why hasnt someone made it:
- Windows explorer is good but its unstable. So you can use this framebat and install another desktop

First:
Create the bat file and put in:
```
taskkill /F /IM explorer.exe
cd /path/to/your/desktop-or-program-path
program-desktop.exe
```
Make sure to put admin prompt to off so at startup it wont say: YES OR NO TO OPEN THIS BAT

Note: This works and tested on a windows 10 machine
