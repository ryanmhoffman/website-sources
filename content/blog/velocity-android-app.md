+++
title = "CBT Velocity Android App"
date = "2016-11-02T13:47:08+02:00"
tags = ["Apps", "Programming"]
categories = ["Android"]
banner = "img/banners/velocity-android-banner.png"
author = "Ryan M. Hoffman"
+++

## The Idea

This app was created for high school students. Specifically, the high school students in my church, Canton
Baptist Temple, who are a part of the youth group which is called - as you might have guessed, Velocity.
The thinking behind this is pretty simple and makes a lot of sense if you have ever spent any time around
high school students. The issue is that no matter how many times you tell them something, they still have
no idea what you said - unless you put it right in front of them on their phone.

The problem we had was that we would announce class activities, mail out fliers, and have sign up sheets
in the class, yet we would still have parents and students calling a couple days before hand to ask for
all the details we had already made sure were available. We decided the best way to get them this info
was on their phone in an app with notifications and reminders and all the details they need.

## Development and Vision

CBT Velocity is a native app designed for the Android platform. It is coded in Java and XML, and I host
all of the content used in the app on my LAMP (Linux Apache MySQL PHP) server. As you can tell from the
screenshots I used material design for the UI/UX and I tried to keep it simple with a card based layout.
The cards are set in a RecyclerView and each card is retrieved over the network from my server. The
navigation drawer contains links to other related social media pages, and to the settings, where you can
configure data/wifi usage and turn notifications on/off.

There are a couple things not implemented yet that I plan to add eventually. The first is going to be
in-app sign up for activities. I want the students to be able to log in to the app, click on the activity
and sign up there instead of the paper sheets we have in the class. The next one piggy-backs on that, and
it is to have in app payment for the activities. Instead of remembering to bring $20 to church or to the
activity, they should be able to log in and securely pay us right from within the app.

The whole app is open source, please check it out at [github](https://github.com/ernieb4768/CBTVelocity)
and let me know what you think!

<img src="/img/banners/cbt-velocity-activities.png" style="width: 33%; height: 33%; padding: 5px"/> <img src="/img/banners/cbt-velocity-about-us.png" style="width: 33%; height: 33%; padding: 5px"/> <img src="/img/banners/cbt-velocity-nav-drawer.png" style="width: 33%; height: 33%; padding: 5px"/>