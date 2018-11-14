---
layout:     post
title:     Linux VI & VIM
subtitle:  Linux 
date:       2018-11-3 
author:     张宁
header-img: img/post-bg-cook.jpg
catalog: true
tags:
    - Linux
    
---
## VI & VIM
The difference between vi and vim
They are all multi-mode editors, the difference is that vim is an upgraded version of vi, it is not only compatible with all the instructions of vi, but also some new features.

These advantages of vim are mainly reflected in the following aspects:
1, multi-level undo
We know that in vi, pressing u can only undo the last command, and in vim you can undo it without restriction.

2, ease of to use

Vi can only run in Unix, and vim can not only run on Unix, windows, mac and other multi-operation platforms.

3, the syntax highlights
Vim can brighten your code with different colors.

4, visual operation
That is to say, vim can run not only in the terminal, but also in x window, mac os, windows.

5, fully compatible with vi
In some cases, you can use vim as vi.

Both vi and vim are editors in Linux. The difference is that vim is more advanced and can be considered an upgraded version of vi. Vi is used for text editing, but vim is more suitable for coding.

Vi has 3 modes: insert mode, command mode, low line mode.

Insert mode: In this mode, you can enter characters and press ESC to return to command mode.
Command mode: You can move the cursor, delete characters, and so on.
Low line mode: can save files, exit vi, set vi, find and other functions (low line mode can also be regarded as in command mode).

First, open the file, save, close the file (used in vi command mode)

<img src='/img/vi-vim-command-vim.gif'><br>
Vi filename //Open the filename file
:w //Save the file
:w vpser.net //Save to vpser.net file
:q //Exit the editor, if the file has been modified, please use the following command
:q! //Exit the editor without saving
:wq //Exit the editor and save the file

 

Second, insert text or line (vi command mode use, execute the following command will enter insert mode, press ESC key to exit insert mode)
`
a //Add text to the right of the current cursor position
i //Add text to the left of the current cursor position
A //Add text at the end of the current line
I //Add text at the beginning of the current line (the beginning of a line that is not a null character)
O //Create a new line above the current line
o //Create a new line below the current line
R //Replace (overwrite) the current cursor position and some text following
J //Merge the line where the cursor is and the next line (still in command mode)