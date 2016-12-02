+++
title = "Android Studio Libraries With Gradle"
date = "2016-12-01T13:47:08+02:00"
tags = ["Gradle", "Programming", "Android Studio"]
categories = ["Android"]
banner = "img/banners/banner_gradle_android.png"
author = "Ryan M. Hoffman"
+++

# Using Libraries in Android Studio

<img src="/img/banners/banner_gradle_android.png" style="width: 100%; height: 100%"/>

## Intro to Gradle for Android Studio

Android Studio switched to a gradle based build system a few years ago, and that made it very simple to
incorporate open source libraries  your Android projects. If you aren't familiar with gradle you can
learn more about it [here](https://gradle.org/getting-started-android-build/). The details of gradle
recipes are beyond the scope of this post, but I will show the very basics of including libraries in
your project. Fortunately gradle makes it dummy-proof to add dependencies in your project. Gradle is not
the only way to add a library to your project, and if you are familiar with eclipse then you are most
likely familiar with adding .jar files to your project. This is still possible in Android Studio, but I
will not be covering that in this post, and I don't recommend it. By using gradle, all you need to do is
include 1 line of code in you ```build.gradle``` file and it does the rest. It pulls in the dependency at
build time so it doesn't need to be downloaded and included as a .jar file. Even more appealing than that
is how easy it is to use it with different versions of libraries. With gradle, if you are using
```my-awesome-library:v1.0``` but then version 2-0 comes out, all you have to do is change that statement
to ```my-awesome-library:v2.0``` and start using the updates immediately. That is much easier than
deleting the .jar and downloading and adding the new version.

So now that we know the differences let's have a look at adding external libraries with gradle.

## Adding Libraries with Gradle

When you create a new project in Android Studio it is already preconfigured to use gradle. If you look
through the project files that are created initially you will find a couple different gradle files. The
first one is probably your high level project file. This is the gradle file to configure project-wide
settings. We will not need to modify this file for what we are going to accomplish in this tutorial. Next
will be the module level gradle files. If you created a simple app with only one module then there will
only be one module level ```build.gradle```. If you included other modules in your project, for example
Android Wear, Android TV, or Android Auto then there should be more than one version of this file for
each module. Each one should be labeled next to it in parentheses describing what it is for.
```
build.gradle (Project: MyProject)
build.gradle (Module: mobile)
build.gradle (Module: wear)
```
The one you need to edit is the ```build.gradle (Module: mobile)``` to add the open source library to our
project. The library we are going to add in this example is Google's
[CardView](https://developer.android.com/training/material/lists-cards.html#CardView) library.

Here's how easy it is to add a library to your project with gradle and Android Studio. Start by opening
the ```build.gradle``` file for the mobile module. Find the section near the bottom labeled
```dependencies``` and add this line to the bottom of that section:
```
compile 'com.android.support:cardview-v7:25.0.1'
```
It should look like this:
```
dependencies {
  // other module dependencies may be listed here
  ...
  compile 'com.android.support:cardview-v7:25.0.1'
}
```
Once you add that line Android Studio will let you know that gradle files have changed and prompt you to
sync your project with gradle. Once you do that you can immediately begin using the library in your code.
If a new version is released just change the version number in your gradle file and sync your project
again and that's it.

## Adding Modules

I have already mentioned modules above a little bit, but I haven't really explained what they are or what
they are used for. Modules are basically just portions of code that are broken out into groups to make
them easily reusable. You can think of them as mini projects within your main project. As I mentioned
earlier, when you create an app for mobile, wear, auto, and tv, Android Studio automatically sets up each
as its own module. This is so you can define activities and views for each in their own module without it
affecting any of the others. But you can also create your own modules. I like to create a module for all
of the logic and data classes in my apps, that way the code can be shared to each portion of the app.

For instance, if I have an app that has a phone portion and a wear portion, most likely it will pull data
from a server and both portions will need to use that data. Rather than retrieve that data and use it in
the phone module, then retrieve and use it in the wear module, I build a separate data module to retrieve
the data from the server and both the phone and wear modules can use it as necessary from there. Pretty
much any logic, data loading/storage can be put in modules this way to save writing it all multiple
times.

Adding a module is quite simple and very similar to adding an external library. In your project there
should be a ```settings.gradle``` file. This file manages what modules are included in your project. It
should look something like this for the most basic project:
```
include ':app'
```
To add your module you have to add this, replacing "myshinynewmodule" with the name of your module or
library.
```
include ':app', ':myshinynewmodule'
```
After this you are almost done. There is one final step before you can use the code in your shiny new
module in your app. As we did with the cardview library earlier, open the ```build.gradle``` file for
your mobile module. In the dependencies section that we modified earlier add this line:
```
compile project (':myshinynewmodule')
```
That's it. You can now start using the code from your module in your app just as if it were an external
library.

## Conclusion
I hope this was clear and you were able to learn something about gradle, dependencies, or using modules
in your Android project. If you have any questions please reach out to me and I'd be happy to help. If
you spot any errors, please let me know about them so I can make this as accurate as possible.
(BE GENTLE!!) As always, please follow me on twitter
[@hoffmanryan1](https://www.twitter.com/hoffmanryan1) and on medium
[@rmhcompaines](https://www.medium.com/@rmhcompanies).