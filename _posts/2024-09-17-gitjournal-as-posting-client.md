---
layout: post
title: GitJournal as a "Posting Client"
date: 2024-09-17T04:20:00+00:00
tags: meta jekyll
categories: null
---

I've been using GitJournal for several years now as an Android client to my Obsidian notes repo - before the Obsidian mobile client existed, and also since I didn't want to pay for their sync service anyways. It works pretty well, it's just a markdown editor on top of a git client - not as slick as Obsidian, sure, but more than functional.

In talking about posting with a static site generator on cohost, I sort of talked through potentially using GitJournal to handle static site posts too - after all, with Jekyll (and most static site generators), your post is just a markdown file with a bit of front matter so Jekyll knows to parse the file (it can even be entirely blank, it just has to have those dashed lines). GitJournal even happens to support custom metadata so I *should* be able to have it generate the appropriate front matter and automatically fill in the title, date, layout, etc.

Now, admittedly, the front matter part hasn't seemed to have worked - I can "hard code" the `layout: post` but it's not actually picking up that information. It may be that I need to save the file first, or that custom metadata is only used for parsing other application's metadata format into GitJournal's own displays?

Well - here's the test! Let's see if it works ^^

---

So - the custom metadata definitely didn't work the way I wanted to. Tagging is funky (tried to specify tags in the GitJournal UI, but it didn't seem to propagate to the metadata?), the date didn't get pulled, but I can at least tell it to set the layout to a 'post' every time. If I use the raw editor I can manually edit all that which is what I'm doing now.

Also, I need to see if I can specify a file format to confirm with what Jekyll is expecting there.

That said, solvable problems, and fundamentally I can now make a post by just opening a new "note" in GitJournal. yippee!

---

Oh, I see. There's a number of fields that can be automatically populated but I can't configure that, what I can do is add additional entries to the YAML. So I just use the built-in date rather than redefining it, though unfortunately the format of the built-ins don't seem to be customizable, meaning I'll have to edit the tags manually.

Also there's no custom custom file name format but I can set it to be the date time in ISO-8601 which is honestly good enough
