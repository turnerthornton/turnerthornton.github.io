---
layout: draft
title: "Running on Jekyll and GitHub"
date: December 18, 2014 12:23:14
tags:
category:
- Article
link:
---

I wanted to list the tools, links, and tutorials I used to get this site up and running. and a couple of helpful links I found along the way.

## Required Tools
- Jekyll[^1]

[^1]: Jekyll is a simple, blog aware, static site generator. It takes a template directory [...] and spits out a complete, static website suitable for serving with Apache or your favorite web server. This is also the engine behind GitHub Pages, which you can use to host your project’s page or blog right here from GitHub.
 
- [GitHub Pages](https://pages.github.com/)
- [Poole](http://getpoole.com/)
- [Joshua Lande's Poole Fork](https://github.com/joshualande/joshualande.github.io)
- [Bigfoot Footnotes](http://www.bigfootjs.com/)

## Resources
- [Smashing Magazine Tutorial](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/)

## Local Tools
- [GitHub Mac 2](https://mac.github.com/)
- [TextMate](http://macromates.com/)

## Mobile Tools
- [Octopage (App Store Link)](https://itunes.apple.com/us/app/id649843345)
- [Clips](http://www.cleanshavenapps.com/clips/)

## Additional Tools
- [Google Analytics](http://www.google.com/analytics/)
- [TextExpander Touch](http://smilesoftware.com/TextExpander/touch/index.html)

## My Experience

I didn't really want to write a tutorial because, truthfully, I'm surprised I got any of this working at all and don't feel qualified. [This Smashing Magazine tutorial](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/) was without a doubt the best guide I found.

I wanted to add several features in addition to the default [Poole](http://getpoole.com/) template. One of those features was an Archive page. I discovered [Joshua Lande's Poole Fork](https://github.com/joshualande/joshualande.github.io) that already had an Archive page as well as Analytics so I forked from their and went to work.

The additional features I wanted to have were...

**1. Linked List Posts**
	
I wanted to be able to share links with a different post style than a regular blog post. I have categorized these two posts by 'Link' or by 'Article'

**2. Footnotes**
	
Footnotes are cool and eliminate afterthoughts or clarification within parentheses that interrupt the reader. I used [Bigfoot Footnotes](http://www.bigfootjs.com/) to make this possible.

**3. Navigation Bar**

Simple html list with some css style.

**4. Archive**

Having an index of all my posts was necessary. I'd like to eventually have a regular ordered list with differentiating post types instead of separating Articles and Links.	
