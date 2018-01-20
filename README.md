tiger-sublime
==

A Sublime Text 3 syntax definition file for the [Tiger language](http://www.cs.tufts.edu/comp/181/tiger.html).

It currently has highlighting support for:

- Integers, strings, comments
- Language operators
- Control flow and scoping keywords
- Braces, brackets, and parentheses
- Function declarations with tyfields/typeid
- Type declarations with typeid/tyfields/array
- Function calls
- Array and record creation

Example
==

![](https://i.imgur.com/yKZLMOi.png)

I've clicked through most of the files in the provided testcases and everything that's implemented looks correct.

Installation
==

* Open Sublime Text 3, click `Preferences -> Browse Packages`
* Drag `Tiger.sublime-syntax` into `User`
* Restart Sublime Text 3
* You may have to manually set the language for already open `.tig` files by clicking the bottom right corner. Creating and opening new files shouldn't be a problem.