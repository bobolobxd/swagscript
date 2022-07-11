# Disclaimer

This python script will keep you connected to Swamp Cinema. It can detect if GMOD is closed, the server is down, or if you lost connection the server by sniffing for UDP packets.

Follow the instructions below to get started.

# Windows Setup
-get python3 on your windows machine (you can use microsoft store to get it)

-This script uses 4 libraries, and you can get them with pip (it comes with python) from a powershell terminal
```
1. press `WIN+X` and then press `a` (to launch a terminal with admin privileges)
2. type the line below and hit enter
PS> pip install --upgrade pip
3. type the line below and hit enter
PS> pip install scapy colorama psutil requests
```
Also, get npcap if something doesnt work here https://nmap.org/npcap/dist/npcap-1.31.exe


Go to https://raw.githubusercontent.com/bobolobxd/swampscript/main/swamp.py and press ctrl-s and save the script

Change steampath on line 149 to your current steam directory

After you finished the steps above, open the powershell terminal again as administrator (step 1 above) and type the lines below:
```
1. Type the line below in the terminal to go to the directory where you saved the script Ex. c:\users\windowsuername\downloads
PS> cd C:\path\to\SwampScript\
2. Then type the line below and select which mode you want
python swamp.py
```
Modes:
1. Active: Normal GMOD
2. Idle: No addons, no chromium
3. Idle Minmalist: Textmode 
