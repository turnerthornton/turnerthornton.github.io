---
layout: post
title: "Clips for Mobile Publishing on iOS"
date: November 19, 2014 10:31:17
tags:
category:
- article
link:
---

[Clips](http://www.cleanshavenapps.com/clips/) is an iOS clipboard widget that provides additional copy and paste options. Clips will allow a user to create templates to manipulate text to make life easier on iOS.

I wanted to create a little walkthrough of how I am using Clips to publish to my blog from iOS.

##Follow these simple steps to setup a template.

1. In Clips, go to Settings > Copy Templates > Add new template
2. Paste in the text below and add a title

		---
		layout: post
		title: "%title%"
		date: 
		tags:
		category:
		- link
		link: %source%
		---
		
		> %body%

3. Go to Safari and pick an article. Select a block of text and bring up the iOS share screen. Select Clips and chose your new template, in my case "GitHub Post".

4. Insert date and time for your post.

5. Now simply copy your post, open [Octopage (App Store Link)](https://itunes.apple.com/us/app/id649843345) and add your post.

## Adding the date to Clips

Clips does not have a way to automatically add the date in our template so I have created a [TextExpander Touch](http://smilesoftware.com/TextExpander/touch/index.html) shortcut to automatically insert the date.

When I bring up the TextExpander Touch keyboard, I simply type ```gdate``` to expand the date format I use for the site.

	%B %e, %Y %H:%M:%S

Once your post is complete it might look something like this.

	---
	layout: post
	title: "Clips Review: Actionable Clipboard Management for iOS - Macstories"
	date: November 19, 2014 11:09:17
	tags:
	category:
	- link
	link: http://www.macstories.net/reviews/clips-review-actionable-clipboard-management-for-ios-8/
	---
	
	> Clips is one of the most useful iOS 8 apps I’ve tried in the past couple of months, and it’s become a key piece of my iOS workflow. Rather than mimicking a desktop experience that still can’t happen on iPhones and iPads (even with iOS 8), Clips tries to go back to the underlying problem: how can you shift multiple pieces of information from Point A to Point B with fewer taps and less app-switching?

If you have an easier way of posting link items on iOS or have an idea for an improvement, please do let me know on [Twitter](https://twitter.com/claycarson).