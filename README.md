This repo is meant for spyware. I do not support putting this on an unconsenting person's computer. **PLEASE DONT SPY ON PEOPLE**

# CURRENT FUNCTIONALITY
The current version (v3) currently just logs the user's keys and stores it in a file called sys_cache.dat and sends it to the user at a specific IP address on a specific port at a certain time. By default (with no altering of the code whatsoever) it sends it to the computer its spying on. The port is 8080 and the time (i haven't read the code in a long time so this might be wrong) is 23:59 (on the user's computer)

# UPCOMING FEATURES

I plan to add self-injection.
Alternatively, I will most likely use a different approach and have 3 different programs:

Eyes.exe -> finds system software like OS and other specifications and injects knife.exe into the boot sector and controls it

Knife.exe -> keylogs the user and saves it in sys_cache.dat. If its not too hard, i also plan to make ot record the screen at all times. At a set time, it will send the log file and the video file to the server running eyes.exe using standard encryption. If the files are sent to eyes.exe, the program will delete the contents of sys.dat and start again. In the event that the server gets compromised or changes hands, it can be accessed with a password from any ip address. The same password system will be used for updates to knife.exe.




