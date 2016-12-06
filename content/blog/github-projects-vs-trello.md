+++
title = "Review of Github Projects"
date = "2016-12-06T13:47:08+02:00"
tags = ["Github", "Trello"]
categories = ["Development"]
banner = "img/banners/banner-github-projects.png"
author = "Ryan M. Hoffman"
+++

# Github Projects vs Trello

I didn't hear about
[Github Projects](https://help.github.com/articles/tracking-the-progress-of-your-work-with-projects/)
until recently. Projects was designed to help teams organize their work and implement their own workflow
directly within Github. The goal was to make it flexible and customizable so it could be useful for any
workflow, team, or project, and to make it a part of Github so developers wouldn't need a new tool to
install and configure and so they wouldn't have to leave Github.

After I heard about Projects I looked into it to see if it could be of any use to me. After a few minutes
with it I had mixed feelings. Honestly it looks promising and it even seems to be useful right now, but it
felt like a very unashamed copy of Trello but without many of the features.

<img src="/img/banners/banner-github-projects.png" style="width: 100%; height: 100%"/>

If you aren't familiar with [Trello](https://trello.com), it is a project management app used for team
collaboration and customizable workflow implementation. Sound familiar? The layout on Trello is list
based; you define lists, and within each list you can add cards. As you work on the cards you can drag
them between the lists to mean different things depending on your setup, and you can do all sorts of other
things like comment on cards, assign users to cards, set due dates and dozens of other things.

<img src="/img/banners/trello.png" style="width: 100%; height: 100%"/>

## How Github Projects is Useful

Even though admittedly I didn't fall in love with Projects right away, I did find it useful enough to
begin using in some of the projects I'm working on. Since I had been using Trello for a while the UI was
familiar and easy to jump into.

I am currently building an app called Friends that I am using Projects with. Friends is basically a
contacts app, but it is only for your starred contacts. My workflow in Projects looks something like this:

TODO: A list of cards with features/bugs/ideas to be implemented eventually.
Queue: This list is usually only 1 card, it is the next item I plan to work on.
In Progress: List of items I am currently working on.
Completed: Once I finish a card it gets moved to the completed list - yay!

As you can see this is a very simple workflow, but it is easy to manage and it helps my stay organized.
With Projects, adding new lists and cards is as simple as clicking the "add" button and typing the name or
content. Once you have a card you can easily turn it into an Issue, link Pull Request, or other git
functions. I do like the fact that it is built in to Github also, so it is part of your repository and you
can access and use it without leaving Github.

Another thing I liked about it was that you can have more than one Project for a repository. You could
have a global project to track the progress of the whole repository, then other sub-projects for different
modules or features or really however you wanted to break it down. It seems like a good way for a manager
to track several teams or developers a bit more individually without it being too much of a nuisance.
Finally there are Organization wide Projects, which can be used to track multiple repositories within an
 organization profile. Unfortunately this is about where the features end.

## How Github Projects Falls Short

The biggest problem I have is that there is no way to comment on cards, which seems like it should be
basic functionality. I don't always want to turn a card into an issue solely so I can go there and
comment on the progress. I wish I could just open the card within Projects and comment on it. I haven't
used projects with a team yet, but I imagine this would be even more useful in a team setting. I can't
see a reason why Github would leave this functionality out.

Another noticeably lacking feature was labels. It would be nice to be able to add a label to certain
cards so you could quickly see visually which cards are related. I understand that cards could be grouped
in columns, but in my case that would add more columns and more clutter to a very simple workflow. Github
already has labels in their issue tracking section so I don't think it should be too difficult to add to
Projects. I'm not sure why it's not there to begin with.

The last thing I noticed that is missing doesn't actually affect me, but I think it would be useful in a
team. That is assigning a user to a card. This would help everyone know what everyone else is doing and
prevent overlap on certain cards.

## Final Thoughts

Maybe I'm just spoiled from Trello since all of these features are included, but it almost feels like
Projects is a stripped down version of Trello. I think Github could make this so much better and more
useful, and honestly I'm not sure why they didn't. What they released feels like it was rushed into
production. I hope they update it and continue to add features to make it more useful. In its current
state it does have value, but it isn't where it could or should be. I will continue to use it in this
basic form, but my main project management is going to remain with Trello.
