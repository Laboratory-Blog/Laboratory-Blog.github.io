---
layout:     post
title:     Hello Python
subtitle:  Python
date:       2018-11-14
author:     Yoo
header-img: img/py.jpg
catalog: true
tags:
    - Python
---

## Introducing
Let's say hello to python first what is python ??? Python is general purpose programming languages this mean you can do
everything with this language from gui to web site. Okay if this sound cool lest beginning with basic syntax of languages.
<br>
First : print('hello python')
<br>
Now its time to tell you who to run this function/command before run our program we need to install python.
On linux you have python2 but you need to install python3
<strong>sudo apt-get install python3</strong><br>
after this line pasted in terminal you need to enter your password (I expect you know how to install apps your your OS).
On windows is more easy (maybe :D ) you must go to <a href="http://www.python.org">python official site</a> and download the installer after you start installation process you need to click on box add python to path (her also number of current version will be included).
<img src="img/py-yoo-inst.jpg">
<br>
Second thin you need is text editor in this post I'll assume you have python3 and text editor to can run code.
IDE is cool but for beginner I recommend hard way type code in text editor and run it via terminal or cmd depend of OS (operation system).
Text editors you can use are Atom, Bracket, Notepad++ , Notepad, Gedit, Geany or your favorite one.
<br>
Let's turn back to code now its time to open terminal/cmd and type python3 or just python if you use windows
after you see triple (>>>) enter print command <em>print('hello python')</em><br>
now you must see just "hello python" to exit form python type <strong>exit()</strong> or <strong>quit()</strong><br>
When you work with python you'll want to create separate files which end with extension <q>.py</q> and contain pure python code python code end with enter no ";" as in other programming language python is super duper cool because look like as English its so easy to be learn!<br>
Now let's we create one file with extension .py and put following code.
<em><b>tip</b> in cmd or terminal run python3 (if you use linux) or just python on window followed by name of file plus extension ".py"</em>
<pre>
print('enter your name:')
name = input()
print('Hello ', name, ' !!!')
</pre>
<br>
<img src="/img/py-yoo-version.png">
<br>
## explanation
First row show our best know function print which show to screen  message in this case "enter your name" in print you can use both single and double quotes.
Second create variable and assign function input. Fist variable is container for data in python you need just to write name of variable and to assign value to it. Python automatically define type of variable we'll talk more about data type and variable in next posts for now just remember that variable is container for data (data could be integer, float or string/text).<br>
<strong>Input</strong> function give to us opportunity to take user input and what user type in terminal will be stored in our variable name so in our case we expect string/text data type.<br>
And  in the end we show message to user which say <b>Hello <i>name</i> !!!</b> here name will be text/string typed by user.<br><br>
Now we know I/O in python so now I'll give you some exercise to practice learned in this post.<br>
<ol>
  <li>Crate program in which you enter your name and age you print them to screen of course feel free to add additional text.</li>
  <li>Try to draw triangle of stars * in python use only print for now. </li>
  <li>Open terminal/cmd and type python command use python as calcualtor /+ - / * / are basic arithmetic operation.<br>Example: 1 +3; 20 * 30; 40 / 5; 100 - 20;</li>
</ol>
