+++
title = "Nearly 8 Months with Vim"
date = "2017-12-27T13:47:08+02:00"
tags = ["Vim", "Text Editor", "Development"]
categories = ["Development"]
banner = "img/banners/Vimlogo.svg"
author = "Ryan M. Hoffman"
+++

# How I Feel About Vim Now  

## Introduction  
This post is a follow up on a post I wrote several months ago about my starting point with Vim. If you missed that post, you can 
read it [here]({{<ref "blog/getting-started-with-vim.md" >}}). That details how and when I started with Vim nearly 8 months ago.
Now it is an integral part of my workflow. It is my only text editor, and I don't know how I lived without it before. The intention
isn't to preach Vim here and force it on anyone; I am merely chronicling my adventures in learning this editor.

## How I use Vim  
Vim is my general text editor now, used for pretty much everything but Java and Kotlin (Android development). I use it for 
Python, editing my configs, even writing this post in Markdown. I have personalized my vimrc a little bit, but it is actually 
still very small. I use a few plugins too, but again they are very few. I have found that Vim does a lot of things that many 
people might not know about and try to use plugins for. 

Beyond jusing actual Vim in the terminal, I also have begun using plugins wherever possible to add Vim bindings to different 
applications. I have added IdeaVim to Intellij Idea and Android Studio to configure as many keys as possible to behave like
Vim. It is very good, but not perfect. It definitely is good enough to recommend to about any Vim user out there. I also use 
Vimium extension in Vivaldi, my browser. It is an extension for Chrome technically, but since Vivaldi is based on the 
chromium open source project same as Chrome, the extensions mostly work on it. Vimium uses many of the navigation key bindings 
from Vim and adds some to help with link navigation etc. It makes it possible to use the broswer mostly without a mouse.

## My Vim Configuration 
My Vim config is pretty small, but it does have some changes, almost none are unique to me. I find things from other people's 
configs and use them, just like everyone else does. Some big changes I have made are remapping the escape key to jj. Other 
than typing it right there, I have never had to type two j's together before, so it is a safe string to use. It is on the 
home row so I don't have to stretch for escape every time I want to exit insert mode. For plugins, I have added Nerdtree 
for easy file navigation, I added YouCompleteMe code completion engine, and I have added powerline. I use relative line 
numbers for easy jumping from line to line. The last customizations I made are just visual, I use syntax highlighting and 
the color scheme I have set is darcula, which looks like the theme of the same name in Jetbrains IDEs. 

## Where I'm Going From Here  
Vim is my main editor now, and I can't see myself switching any time soon. That doesn't mean I will never try something else, 
but I have become so much more productive with Vim that it feels like a waste to use anything else now. I don't want to be 
a vim evangelist, preaching it to all. It simply is the best editor for me and my workflow. That does not mean it is for 
everyone, nor should it be. I might make tutorials some day about Vim, but for now, I am just a happy user.
