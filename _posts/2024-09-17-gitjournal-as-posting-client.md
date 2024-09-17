---
layout: post
title: GitJournal as a "Posting Client"
tags: meta, jekyll
date: 2024-09-17
categories: null
---

I've been using GitJournal for several years now as an Android client to my Obsidian notes repo - before the Obsidian mobile client existed, and also since I didn't want to pay for their sync service anyways. It works pretty well, it's just a markdown editor on top of a git client - not as slick as Obsidian, sure, but more than functional.

In talking about posting with a static site generator on cohost, I sort of talked through potentially using GitJournal to handle static site posts too - after all, with Jekyll (and most static site generators), your post is just a markdown file with a bit of front matter so Jekyll knows to parse the file (it can even be entirely blank, it just has to have those dashed lines). GitJournal even happens to support custom metadata so I *should* be able to have it generate the appropriate front matter and automatically fill in the title, date, layout, etc.

Now, admittedly, the front matter part hasn't seemed to have worked - I can "hard code" the `layout: post` but it's not actually picking up that information. It may be that I need to save the file first, or that custom metadata is only used for parsing other application's metadata format into GitJournal's own displays?

Well - here's the test! Let's see if it works ^^
