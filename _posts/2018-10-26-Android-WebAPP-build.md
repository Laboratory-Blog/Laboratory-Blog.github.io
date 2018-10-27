---
layout:     post
title:     Android Webapp
subtitle:  Android develop 
date:       2018-10-26  
author:     张宁
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Android
    - Java
    - Programming Language
---
## Create project
<img src='/img/android-webapp-create-project.gif'>
<br>
let's start android studio and create a project it's name for you self.and then, choose your build version,and then ,setup.finish.
## Visit main file locations
<img src='/img/android-webapp-visit-location.gif'>
<br>
when us created it ,we can found the main file,  the main file has  Java file,and Layout file,and Manifests file.
<br>
the Java file at  <code>Java/packagename.computerusername.project/MainActivity.java</code>
<br>
the Layout file at <code>Res/layout/layout_main.xml</code>
<br>
the Manifests file at <code>manifests/AndroidManifests.xml</code>
## Starting code write
layout has some type,but today,we're only need linearlayout.it's control easy.
<br>
enter layout edit text page.
<img src='/img/android-webapp-choose-layoutfile.gif'>
and then to change code.
change line 2 code<br><code>android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android</code><br>
change to 
<code>LinearLayout xmlns:android="http://schemas.android.com/apk/res/android</code>
<img src='/img/android-webapp-change-layout.gif'>
## Write first
<img src="/img/android-webapp-create-webviewid.gif">
del textview code to create webview and new ID for it .
write code 
<br>
<code>
    <WebView
        android:id="@+id/wv_page"
        android:layout_width="match_parent"
        android:layout_height="match_parent">

    </WebView>

</code>