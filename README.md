GridMove - Windows 10 version
========

This is a modified version of GridMove. I changed some of the window sizing math to account for the windows in Windows 10 being slightly smaller than the size specified in the WinMove function.

Also, since I only use the middle mouse button method, and because I found middle mouse button to be to easy to trigger, I modified this to be middle mouse + right mouse button to trigger the grids.

------------------------
**Below is the original readme:**

GridMove is a Windows program that aims at making windows management easier. It helps you with this task by defining a visual grid on your desktop, to which you can easily snap windows. It is built with [AutoHotkey](http://www.autohotkey.com "AutoHotKey"), a scripting language for desktop automation for Windows.

More information at [GridMove's homepage](http://jgpaiva.dcmembers.com/gridmove.html).

Source code organization
------------------------

* GridMove.ahk - Main program, most of the functionality
* files.ahk - Configuration and Grid parsing
* command.ahk - Keyboard (command) interface 
* calc.ahk - Evaluates the .grid files
* helper.ahk - Tooltips for first run
* strings.ahk - Language file
* Aero\_lib.ahk - Library for handling Aero look

This work is licensed under a Creative Commons Attribution-Noncommercial-Share Alike 3.0 United States License.
