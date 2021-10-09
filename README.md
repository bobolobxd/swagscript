# Disclaimer
So far this python version is the most effective one, it can detect if you have an internet connection,
it can detect if the UDP connection to the server is made or not,
it will kill both gmod and steam if the UDP connection is lost,
And it will restart gmod automatically. I recommend testing it for a few hours to see if it behaves as intended. And most importantly as i've seen, it does not run out of memory space after running it for extended periods of time like powershell's badly-written-packet-sniffing-utility pktmon does.

## this is a script to use only if you have a solid internet connection, do not use it if your internet connection has alot of frequent downtimes

# Windows Setup
-get python3 on your windows machine (you can use microsoft store to get it)

-This script uses 4 libraries, and you can get them with pip (it comes with python) from a powershell terminal
```
press `WIN+X` and then press `a` (to launch a terminal with admin privileges)
type the line below and hit enter
PS> pip install --upgrade pip
type the line below and hit enter
PS> pip install scapy colorama psutil requests
```
Also, get npcap if something doesnt work here https://nmap.org/npcap/dist/npcap-1.31.exe

Change steampath on line 149 to your current steam directory

Go to https://raw.githubusercontent.com/bobolobxd/swampscript/main/swamp.py and press ctrl-s and save the script

After you finished the steps above, open the powershell terminal again as administrator and type the lines below
```
Type the line below in the terminal to go to the directory where you saved the script Ex. c:\users\windowsuername\downloads
PS> cd C:\path\to\SwampScript\
then type the line below and select which mode you want
python swamp.py
```
