# Darthvibrius
* Weaponizing kernel level process killing technique based on this [article](https://alice.climent-pommeret.red/posts/process-killer-driver/) and this [code](https://github.com/ZeroMemoryEx/Terminator).
* Darthvibrius terminates all EDR/XDR/AVs processes on its hard-coded list by abusing the kEvP64.sys or the AswArPot.sys loldrivers (modify the code accordingly).

# Usage
* Place the chosen driver in the same directory as the executable and rename it to `sys-mon.sys`.
* Run the Darthvibrius as an administrator
* Keep the Darthvibrius running to prevent Windows from restarting the EDR/XDR/AV services and processes.
