+++
title = "CBT Velocity Android App"
date = "2016-11-15T13:47:08+02:00"
tags = ["Mobile Development", "Programming"]
categories = ["Android"]
banner = "img/banners/layout-editor.png"
author = "Ryan M. Hoffman"
+++

## Android Constraint Layout
There are many different views and view groups in the Android infrastructure. Some are more useful than
others, but they all have their place. Recently, Google released a new layout called ConstraintLayout.

This is still in alpha release stage but it looks very promising. This isn't going to be a tutorial on how
to use it, rather, it's just my thoughts and opinions on the concept and implementation. Keep in mind I
have only been messing around with it for a couple of weeks, so my opinion could change as they update and
improve it.

### Initial Thoughts
When I first heard about ConstraintLayout before I even tried it out I thought it sounded like a rip off
of iOS UI builder in xcode. After learning more about it and using it a little bit I still kind of feel
that way. That's not to say it's a bad thing, but even if it wasn't copied directly from Apple it was at
least *heavily* inspired by xcode. My initial reaction to this was to not like it. At all. I can stumble
my way through iOS development, but I'm not nearly as comfortable with iOS as I am with Android. And my
limited experience with the UI Builder in xcode is not good. I found it a little bit difficult to use and
setting constraints was hard to come to grips with coming from XML layouts in Android. Then Android was
switching to ConstraintLayout to mimic iOS? Not a big fan of that idea.

If you don't know what ConstraintLayout is, you can get more details about it
[here](https://developer.android.com/training/constraint-layout/index.html). Basically you drag views and
widgets onto the design screen and then set "constraints" that tell where each view should be positioned
relative to everything else on the screen. The purpose of it is to flatten the hierarchy of the view tree.
Instead of nesting LinearLayout's and RelativeLayout's trying to position everything properly, this allows
you to position everything relative to whatever you need to in order to lay it all out properly. It is
supposed to help improve performance and make it scale across different screen sizes easier. I have not
tested performance or scalability so I don't know if it is actually better in those regards. If you run
any tests please let me know the results, I'll add them here and credit you.

<img src="/img/banners/layout-editor.png" style="width: 100%; height: 100%"/>

## After Using it to Design Screens
I decided to give it the benefit of the doubt and it appeared to be the future of Android development so I
figured I needed to get on board. Using it was definitely weird at first, but after a while of making
different layouts I started to get used to it a little bit. Sometimes it was a little buggy, but that's to
be expected from an alpha version.

It's going to take some getting used to, but it looks promising. There are a few things I liked, and of
course plenty that I didn't.

### The Good
Overall the experience is good. Setting constraints is as easy as click and drag, and it is pretty
intelligent on knowing what you are trying to do. Linking views together is pretty simple, and pinning a
view to an edge or margin is also straightforward.

I also like that as you make changes in the editor you can still switch over to the XML and see what is
actually changing, and if you really want you could make changes directly to the XML.

### The Not So Good
When editing the screens there are 2 screens shown, one is the blueprint screen and one is the design
screen. The blueprint screen is meant for editing and adding constraints, while the design screen is meant
as a actual preview of what is on the screen, content and all. My problem is that you can edit constraints
(or anything really) on the design screen. It causes some bugs and issues with the layout preview, and
it's just overall confusing. I wish they only allowed editing in the blueprint mode and the preview was
exactly that, just a preview. Perhaps in a future release they will make that change.

## Final Thoughts
It is still going to take some getting used to, but I see this as the future of Android design and
development and I really am excited about what Google is going to add down the road. I'm going to
continue to use it and learn more about it and perhaps start actually using it in projects here soon. At
it's current stage I don't think it is production ready, but that could change with a new release. I'll
keep this updated as new versions come out and I learn more about it. If I get more comfortable with it I
may even write a tutorial.

As always, please follow me on twitter [@hoffmanryan1](https://www.twitter.com/hoffmanryan1) and on medium
[@rmhcompaines](https://www.medium.com/@rmhcompanies).
