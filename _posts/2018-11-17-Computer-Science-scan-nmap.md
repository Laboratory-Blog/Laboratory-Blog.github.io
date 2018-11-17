---
layout:     post
title:     Computer Science the Nmap
subtitle:  
date:       2018-11-17
author:     张宁
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Computer-Science
---
## Descriptions
today. i will share how to scan other peoples hostname.and i will recommend a kit, it's name  Nmap .
<br>
ok,i will to connect move device.
<br>
<img src="/img/connect-move-device.gif">
and i need to copy some date for virtual machine ,it's consume some time,because this disk has the private software repository I need.
<br>
if you has internet,you can install it on your pro repo.just like debian (up 8) sudo apt-get install nmap
## Get the system type and open port of the remote host
nmap -sS -P0 -sV -O target
<img src="/img/computer-science-nmap-sS-P0-sV-O-target.gif">
Here target can be a single IP, or hostname, or domain name, or subnet

-sS TCP SYN scan (also known as semi-open, or stealth scan)
-P0 allows you to turn off ICMP ping.
-sV open system version detection
-O tries to identify the remote operating system

Other options:

-A simultaneously open operating system fingerprint and version detection
-v Detailed output scan situation.
## List the list of hosts with the specified ports open
nmap -sT -p 80 -oG – 192.168.1.* | grep open<br>
my host has opened the apache2 service, so he started port 80 by default. Let's scan it
<img src="/img/computer-science-nmap-sT-p80-oG-taget-grep-open.gif">

## Quickly to scan
nmap -sP target
let's do it in my test space has 2 phone 2 computer and 1 router scan now.
the result
[root@localhost aslt]# nmap -sP 192.168.1.0/24

Starting Nmap 7.40 ( https://nmap.org ) at 2018-11-17 10:09 EST
Nmap scan report for 192.168.1.1
Host is up (0.0022s latency).
MAC Address: CC:34:29:3C:76:50 (Tp-link Technologies)
Nmap scan report for 192.168.1.104
Host is up (0.00045s latency).
MAC Address: 60:67:20:C8:45:9C (Intel Corporate)
Nmap scan report for 192.168.1.105
Host is up (0.20s latency).
MAC Address: 88:33:14:31:D6:73 (Texas Instruments)
Nmap scan report for 192.168.1.126
Host is up (0.15s latency).
MAC Address: 20:5D:47:52:4E:0A (vivo Mobile Communication)
Nmap scan report for 192.168.1.132
Host is up.

Nmap done: 256 IP addresses (5 hosts up) scanned in 5.22 seconds

yes it's scan get  5 target .  and i said in my space has 5 device.
let's looking progress
<img src="/img/computer-science-nmap-sP-target.gif">