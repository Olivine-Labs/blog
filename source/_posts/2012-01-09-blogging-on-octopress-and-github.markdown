---
layout: post
title: "Blogging on Octopress and Github"
date: 2012-01-09 12:17
comments: true
categories: [meta]
author: Jack Lawson
---

We recently made the switch to move our blog from Wordpress to a Jekyll system
called [Octopress](http://octopress.org/).

We wanted more control over the templates, css, and all of the things that
eventually got into the end html; and being locked-in to a templating system
like Wordpress isn't something that we were quite comfortable with. Jekyll is
a framework for automating the inclusion of files, at its simplest description;
Octopress takes it a step further and provides default plugins and excellent
rake tasks that one can use to quickly set up a blogging platform full of
customizable goodness.

It was easy to set up, and the documentation is fantastic; the default rake
tasks and gem bundling makes it a snap to set up on any system (and doubly
so if you already have ruby set up.) It's as simple as cloning the repository,
installing the gems, and firing off one of a few different rake tasks and you
are set up with the ability to push to Github Pages, Heroku, rsync, or to
output your own html for your own hosting. We're using Github Pages for now,
but we'll be experimenting with setting up jekyll on our own EC2 servers in the
near future.

We'll also be setting up a new Neflaria-specific blog.  We will link to posts
we make there from here, but keep Neflaria news on the Neflaria site and more
generic OL news (such as about our components like
[Alchemy Websockets](http://alchemywebsockets.net)) here.
