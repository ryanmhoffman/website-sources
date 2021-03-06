+++
title = "Mobile Development: Native vs Cross-Platform"
date = "2016-11-01T13:07:31+02:00"
tags = ["Mobile-Development", "Android", "iOS"]
categories = ["Mobile-Development"]
banner = "img/banners/mobile-development-banner.jpg"
author = "Ryan M. Hoffman"
+++

### Should You Even Develop for Mobile?
In a word, yes. Mobile development is growing to be more and more important every single year. Every day
people spend more time on their phones, tablets and other mobile devices. As of
[June 2016](https://www.statista.com/statistics/276623/number-of-apps-available-in-leading-app-stores/)
there are over 2.2 million apps available in the Play Store and over 2 million in the App Store.
[This article](http://www.digitaltrends.com/mobile/informate-report-social-media-smartphone-use/) from
back in 2015 says that the average American spends 4.7 hours *per day* on their phone! That's nearly a
third of our waking hours each day! If you want some of that screen time to be dedicated to your app then
you better think very carefully about what type of app you want to deliver to your users. So what will it
be, native or cross-platform?

![](/img/banners/mobile-development.jpg)

### The Case for Native Apps
Native apps, generally speaking, offer a better experience when compared to a similarly developed
cross-platform app. This isn't always true, and it definitely doesn't mean that you should only choose to
launch native apps. These are a few reasons why you should consider going native.

Native apps are designed to be platform specific, so they feel more comfortable for the user. This is
incredibly important because [77% of users will delete your app](http://andrewchen.co/new-data-shows-why-losing-80-of-your-mobile-users-is-normal-and-that-the-best-apps-do-much-better/?utm_content=buffere4fa2&utm_medium=twitter.com&utm_source=social&utm_campaign=buffer)
within 72 hours of downloading it. That number will only go up if the design is not familiar and
comfortable for your users. On Android, Google have created Material Design as the standard. Most of the
popular apps in the Play Store have already shifted to conform to this style, and it has become normal for
Android users. On iOS, Apple have their own design guidelines that is different from Material Design.
There are certain navigation patterns that are different and other animations and visual queues that might
mean something different on each platform. By developing a native app for each os you can bring the little
things from the design standards out and make your app easier and more enjoyable for your users.

Another big bonus for native apps is the increased performance you get from them. When developing for
Android, an app written in Java will *almost* always be faster than one developed in Javascript or some
other web language. The same goes for iOS apps written in Swift or Objective-C; they will *almost* always
be faster than their cross-platform counterparts. This is because the APIs are developed in the native
language by Google or Apple. Usually cross-platform apps are developed using Javascript or a language
that compiles to Javascript, and the large libraries and other code can end up running much slower on
the phone or tablet than well developed native code.

Certain hardware related features like gestures, multi-touch, and various other sensor related components
like GPS, accelerometer and gyroscope are simpler to access and use in native apps. Most of the time
there are very straight forward APIs or libraries that allow access to these components. These are more
advanced functionalities and might not be necessary in all apps, but it is important to keep in mind when
deciding what is right for you and your idea.

### The Case for Cross-Platform
Cross-platform apps are easier to create and can cut down your development time significantly. The main
selling point here is that you have a single code base to maintain for all users on all operating systems.
The idea here is that you create one app, which is then optimized and packaged properly for each platform
and published in each marketplace.

After reading the section about native apps and seeing all the features and speed you might be thinking
that's the way to go, but I challenge you to think about this. You have an idea for an app, maybe you
have a website and you want to take it a step further and turn it into a full on app. You already have
the website to maintain, all the code that goes along with it, and the headaches from hosting it. Now you
decide to make apps for Android and iOS. Maybe you are a code ninja and already know Java and Swift, so
that saves you time and money because you don't have to learn new technology or hire a freelancer to do
it for you. But you start writing the iOS app first and after a couple weeks it is ready to publish, but
you don't want to launch it without the Android app also. So you sit down and bang out that app in a
couple more weeks. Now both are ready to go so you submit them to their respective app stores. The good
news is they look great and are blazing fast, but now every time you want to make a change to your
website you have three different apps in three different code bases to maintain and update. Then a few
of your crazy followers get the new Windows phone and are still on the mobile version of your site
because no app exists for them. What now?

Now contrast this with a cross-platform app. You can use most if not all of your existing Javascript
from your website when creating the app. Once development is complete you can optimize the code for each
platform and publish to each app store. Every time you want to make a change to your website you can make
the changes to the app code also and everything will look great and up to date across all platforms. If
you have users with Windows Phone or Firefox OS or anything else you can use the same code to publish to
their app stores and have good looking apps for them too.

So what's the catch? What you gain in simplicity you will lose in functionality. There may be a trade off
in speed as well although I doubt it if you are simply converting a website into a web app. The biggest
drawback will be trying to implement new features and meet the design standards of each platform.

![](/img/banners/mobile-development-2.png)

### Which Is Right For You?
This is a question that you are going to have to answer for yourself. If your idea is something small and
simple like converting your website into an app then cross-platform might be the way to go for you. Other
things like tip calculators and simple note taking apps usually have simple UI's and are good candidates
for cross-platform apps. More complex apps that rely on sensors in the phone or things like multi-touch
are probably better off as native apps.

At the end of the day you need to evaluate your business or your idea and decide which choice is right
for you. Making a list of required features is a great way to see exactly what will be involved in
development and will probably make the decision much easier for you. Remember that there is no "right"
answer and even if you start out with a simple cross-platform app you can always scale up to a native app
and update from there. Good luck and happy developing!
