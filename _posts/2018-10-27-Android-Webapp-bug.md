---
layout:     post
title:     Android Webapp Bug
subtitle:  Android develop 
date:       2018-10-27 
author:     张宁
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Android
    - Java
    - Programming Language
---
## BUG
<img src='/img/android-webapp-bug-found.gif'>
Our team member ask my why can't open menu,it's problem for JS,because i not add support javascript ,so the Js plugin can't work normal.now ,i will refesh it .
## Repair
enter Java file,and insert code about webview support javascript.
<img src="/img/android-webapp-bug-repair.gif">
add code <br><code> WebSettings wvset = wv_page.getSettings();</code>
 <br> <code>wvset.setJavaScriptEnabled(true);</code>
 and run it again.
 ## Done
 <img src='/img/android-webapp-bug-repair-again.gif'>
 yes now it's working normal.