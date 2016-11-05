+++
title = "Making This Website"
date = "2016-11-01T03:39:46+02:00"
tags = ["Web Development", "Web Design"]
categories = ["Web Development"]
banner = "img/banners/this-site-banner.png"
author = "Ryan M. Hoffman"
+++

## Introduction

I built this website for a couple different purposes. I wanted a place to showcase my portfolio and direct
potential clients for my freelance business. I also wanted to build a blog. I decided that the two ideas
related enough to warrant being one site. I also wanted something simple that wouldn't take weeks to
create and be a nightmare to host. I did some research and settled on using [hugo](https://gohugo.io/), a
static site generator built with the [go programming language](https://golang.org/) by Google. I went with
a static site because I wanted something fast and easy to develop AND fast when being served. Hugo checked
both of those boxes. All in from the time I first discovered hugo to the time I deployed this site on
[github pages](https://pages.github.com/) was about 8 hours of work. That was spread over two evenings,
but you get my point on how easy it was to learn and use.

## Design

I wanted something modern that would scale well across desktop and mobile, and again hugo had me covered.
there are tons of [themes](https://themes.gohugo.io/) for hugo that make design a breeze. I ended up
choosing [universial theme](https://themes.gohugo.io/hugo-universal-theme/). This had everything I was
looking for and was a joy to work with and modify to suit my needs. Shout-out to [Bootstrapious](https://bootstrapious.com/p/universal-business-e-commerce-template)
for creating the original design and to [DevCows](https://www.devcows.com/) for porting it to hugo.
Fantastic job!

## Development

As I mentioned earlier this took me about 8 hours total to build. I was expecting to spend a week or more
easily, as building a portfolio site and a blog is a relatively small project but by no means is it "easy."
The blog is probably my favorite part. Publishing a new blog post is as simple as copying the markdown
file into a folder, rebuilding the site and seeing it pop up.

Since it is a static site and there is no database or php/node.js etc., there aren't any comments... or
so you would think. But with [Disqus](https://disqus.com/) it is very easy to add comments even without
any of the server side scripts. Currently I don't have this enabled, but it is something I might look into
in the future.

Another genius feature included was in the [contact](/contact/) section. Again, no server side scripts to
handle the form, but it was all thought out. [Formspree.io](https://formspree.io/) is included to handle
all of the emails to make sure you get them delivered to your inbox. It is a very straightforward setup,
and the best part is it's free! If you exceed 1000 emails in a month there is a subscription plan, but I'm
not there yet.

## Conclusion

This has been a great experience using hugo to build my website. I'm very happy with the outcome, and I
would highly recommend checking it out. I may come back and update this after spending more time
maintaining and updating the site, but currently I'm thrilled.

In the mean time, please continue to check back periodically. I add new content weekly. For even more
frequent updates follow my on twitter [@hoffmanryan1](https://www.twitter.com/hoffmanryan1) and you can
check out my non-tech related ramblings over at my blog on medium [@rmhcompanies](https://www.medium.com/@rmhcompanies).
