# Darthvibrius
* Weaponizing kernel level process killing technique from this [article](https://alice.climent-pommeret.red/posts/process-killer-driver/).
* Darthvibrius terminates all EDR/XDR/AVs processes on its hard-coded list by abusing the kEvP64.sys and AswArPot.sys lol drivers.

# Usage
* Place the driver `sys-mon.sys` in the same path as the executable
* Run the Darthvibrius as an administrator
* Keep the Darthvibrius running to prevent Windows from restarting the target EDR/XDR/AV services and processes.
