# Darthvibrius
* Weaponizing kernel level process killing technique based on this [article](https://alice.climent-pommeret.red/posts/process-killer-driver/) and this [code](https://github.com/ZeroMemoryEx/Terminator).
* Darthvibrius terminates all EDR/XDR/AVs processes on its hard-coded list by abusing the driver [wsftprm.sys](https://northwave-cybersecurity.com/blackoutreloaded-exploiting-antifraud-software-of-banks-to-kill-microsoft-defender)
* You can use the also included drivers: [rentdrv2_x64.sys](https://github.com/keowu/BadRentdrv2), kEvP64.sys or the AswArPot.sys loldrivers but you need to modify the code accordingly.

# Usage
* Place the chosen driver in the same directory as the executable and rename it to `sys-mon.sys` - HINT: rename files both to `sys-mon` and put them in `C:\windows\system32\`.
* Run the EXE as an administrator.
* Keep the Darthvibrius running to prevent Windows from restarting the EDR/XDR/AV services and processes.
