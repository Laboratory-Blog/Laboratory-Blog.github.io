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

