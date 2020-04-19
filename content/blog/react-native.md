+++
title = "Can React Native compare and compete with true native code?"
date = "2018-01-28T13:47:08+02:00"
tags = ["React Native", "Android", "Development", "iOS"]
categories = ["Development", "Mobile"]
banner = "img/banners/Vimlogo.svg"
author = "Ryan M. Hoffman"
+++

# Why Write this Article?
Great question, I'm glad you asked! First, let me say that this is ***NOT*** going to be a 
benchmarking article to compare numbers and load times or anything like that. This article 
is going to be a look into whether a developer who currently works using native code for 
either or both mobile platforms should consider React Native. I am writing this article 
because that is the position I find myself in currently. I am a native Android developer;
I love Kotlin and Java and I am very comfortable developing Android apps. I have some 
experience with iOS, but I find it much less enjoyable, and I am not nearly as comfortable 
with Swift as I am with Kotlin and Java. 

So why would I look at React Native when I'm already a native developer? In reality, I've 
been looking for a way to be able to write an application that can share a majority of its 
code on multiple platforms. I was hopeful that Kotlin could fill that requirement, and it 
looks like this is still promising with transpiling to JavaScript and to native code that 
can be run with c code, but it is not near ready yet and also still very complicated. So...

### Enter React Native
If you don't know what React Native is, it's a framework developed by Facebook that allows 
you to build native apps for both Android and iOS using JavaScript. Yes, it is cross 
platform, and yes, it really is native code. I won't go into the details of how it works, 
but it really does make truly native apps, not hybrid or just webviews. React Native lets 
you write *nearly* all of your code in JavaScript, **and** it lets you share the majority 
of that code across both platforms. This is exactly what I was looking for so I decided to 
give it a try. 

### The Learning Curve
There was only one small problem: I didn't know JavaScript. Not only did I not know 
JavaScript, but I thought I hated it. I had limited exposure to it in passing, but no real 
experience with it. But I had heard plenty of horror stories about its quirks and 
inconsistencies to know it wasn't for me. I decided to put my preconcieved notions about 
the language aside and approach both React Native and JavaScript with an open mind. And 
guess what I found? I...loved it! Yes, I actually enjoyed JavaScript almost immediately 
after spending a couple hours truly messing around in it. It was easy to pick up, had lots 
of examples and tutorials, and seemed intuitive to use to me. 

My main method of learning was just to start with the official React Native docs, which 
are fantastic by the way, and move all the way through their documentation. I got through 
that in about an hour and felt I had a decent grasp of the concept, but I needed more 
practice, so I went in search of a tutorial with some basic ideas like retrieving data 
from an API, parsing JSON, and making an app that could actually be useful. In less than a 
day I felt I had a good enough understanding to work on a real (small) project. That is 
an incredible thing to think about, considering I knew neither React Native nor JavaScript 
before this.

### The *Native* Part
Once I got to this point, I learned something new that blew my mind. I understood that 
React Native creates real Android Studio and Xcode projects, but it hadn't dawned on me 
that I could actualy open them and put native code in the projects there. This is 
important because while React Native is very good, it does not have all of the elements of 
a truly native app. Some more complex or less used components are left out (for now.) By 
being able to still write Kotlin in the Android project and Swift in the Xcode project, 
yet having all logic and much of the UI rendered from a single JavaScript source, I could 
get the 100% native code base I was looking for with a single, shared codebase for both 
mobile platforms. 

## Where I am Going From Here
I am by no means an expert in React Native or JavaScript. I have only been using it a 
little over a week at the time I am writing this, but I plan to continue on this path. It 
can cut down my development time dramatically by allowing me to share code across 
platforms, and that could be a big selling feature to clients. It will also allow me to 
create much better iOS apps which are currently my weak point, because I can use more 
JavaScript and less Swift. I think in the long run this will not only help me become a 
better developer, but it will provide value to my future clients by decreasing development 
time and saving them money.

In the future once I have spent more time with both new technologies (to me) I may provide 
an update on whether my thoughts have changed at all or if I have any new opinions on the 
topics. Until next time, happy coding!
