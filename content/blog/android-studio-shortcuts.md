+++
title = "Android Studio Keyboard Shortcuts"
date = "2016-11-21T13:47:08+02:00"
tags = ["Mobile Development", "Programming", "Android Studio"]
categories = ["Android"]
banner = "img/banners/android-studio.png"
author = "Ryan M. Hoffman"
+++

## Android Studio Shortcuts

<img src="/img/banners/android-studio.png" style="width: 100%; height: 100%"/>

If you have used Android Studio for even a short time I'm sure you have found some shortcuts and hot keys
to speed up your coding and keep your hands on the keyboard where they belong! I'm going to run through
some of the shortcuts I find most useful. Android Studio is built by Google, but it is based on Jetbrains
Intellij Community Edition Java IDE. This means that all of the Intellij shortcut keys work on Android
Studio, but Google have added a few of their own. Let's jump into some of the best ones.

### Searching For A Shortcut
Stop me if this has happened to you before. You read an awesome tutorial on shortcuts and hot keys in
Android Studio and found a few that looked really useful, but when you sit down and start coding you
can't remember what they were. Fortunately someone thought of this and made several several search
functions.

#### Search everywhere:
**Shift Shift** (Windows, Linux, Mac)
This searches literally everywhere. It can even search outside of the scope of your project if you want
it to (every file on your computer). Thankfully it groups what it finds into categories, with the most
recent files first.

#### Search for commands:
**Command + Shift + A** (Mac)
**Control + Shift + A** (Windows, Linux)
This searches for any command. If you know there is a way to jump to the next error in your code but you
can't remember what it is, just use this command and start typing "error" and it will intelligently find
it. This works for any command. If you only want to memorize one shortcut, this is the one.

### Navigation
Here are a few more ways to keep your hands off the mouse and still get around your project quickly.

#### Jump to Class
**Command + O** (Mac)
**Control + N** (Windows, Linux)

#### Jump to File
**Command + Shift + O** (Mac)
**Control + Shift + N** (Windows, Linux)

#### Jump to Method
**Control + Up/Down** (Mac)
**Alt + Up/Down** (Windows, Linux)
Up is the previous method, down is the next method.

### Editing Code
This is the one we try to spend the most time on, and even though searching for the correct command is
easy with the shortcut above, it is still quicker to memorize these shortcuts and add them to our
workflow. These will really help you get *past* the editor and focus only on the editing.

#### Auto-Completion
**Tab** (Mac, Windows, Linux)
**Enter** (Mac, Windows, Linux)

#### Comments
Single Line Comment
**Command + /** (Mac)
**Control + /** (Windows, Linux)
Multi Line Comment
**Command + Alt + /** (Mac)
**Control + Shift + /** (Windows, Linux)

#### Show Parameters
**Command + p** (Mac)
**Control + p** (Windows, Linux)
This one is useful if you can't remember what parameters a method takes.

#### Refactoring
Renaming a variable/method/class etc.
**Shift + F6** (Mac)
**Control + F6** (Windows, Linux)

#### Intelligent Code Generation
**Command + N** (Mac)
**Alt + Insert** (Windows, Linux)

#### Live Templates
There are dozens of these available by default, and the great thing about Android Studio is that you
have the freedom to create more if you wish. If you don't know what live templates are, they are
boilerplate sections of code that gets automatically inserted for you. All you have to do is tab through
to fill in the variable values.

A commonly used one is "Toast". You type "Toast" and hit **Tab** and it automatically gives you this:
```
Toast.makeText(MainActivity.this, "", Toast.LENGTH_SHORT).show();
```
If you hit **Tab** a second time it moves the cursor over to the quotation marks so you can type your
message, and if you hit **Tab** one more time it moves your cursor to the end of the line.

Another common one is to type "fori" and hit **Tab**. That gives you this:
```
for(i = 0; i < ; i++){

}
```
Of course tabbing through allows you to modify the variable name, value, loop length, and finally it
drops you inside the curly brackets to write the code to be executed.

As I mentioned there are dozens more and you can create your own. To find all the live templates
included just search everywhere with **Shift Shift** and type "Live Templates".

### Conclusion
Thank you for reading this. I hope some of these tricks will help you become a better and faster
developer. If you want the full and overwhelming list of shortcuts for Android Studio you can check out
the list [here](https://developer.android.com/studio/intro/keyboard-shortcuts.html).

As always, please follow me on twitter [@hoffmanryan1](https://www.twitter.com/hoffmanryan1) and on
medium [@rmhcompaines](https://www.medium.com/@rmhcompanies).
