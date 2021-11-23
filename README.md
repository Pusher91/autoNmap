# autoNmap

Automatically runs nmap.  Scans for all open ports and then run nmap script scans against them.

### Automatic scans:
+ nmap <target> -p- -oN tcp\_ping\_scan
+ nmap <target> -sV -sC -oN -p \<open ports from previous scan\> -oN tcp\_script\_scan
+ nmap <target> -p- -sU -sV -oN ping\_udp\_scan
+ nmap <target> -sU -sV -sC -p \<open ports from previous scan\> -oN udp\_script\_scan



### Script output:

![screenshot](/screenshot.png)
