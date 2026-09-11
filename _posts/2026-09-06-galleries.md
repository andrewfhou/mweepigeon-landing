---
layout: post
title: Jekyll Image Galleries
date: 2026-09-06 20:59 -0400
categories:
tags: meta
---

I got annoyed by not really having a great spot that others could see the
various art I've commissioned (I don't really like using FA much) and decided
to finally get off my ass and throw them up on my personal blog/site. I'm
getting a liiiiiittle concerned about how much storage I'm using on files (have
to use git LFS already or DigitalOcean fails to deploy the droplet but I guess
that's a problem for when DO starts yelling at me. I'm sure there's a storage
limit somewhere but maybe it's fairly generous?)

Anyways, I browsed the various Jekyll plugins for galleries for awhile, but
several were old and none really did exactly what I wanted. Also there's
a billion—I guess everyone ends up in the same spot as me and codes their own.
Well *I'm* lazy and didn't want to code my own fancy plugin, but I came across
[this blog post](https://dmnfarrell.github.io/software/jekyll-galleries) for an
implementation of an image gallery without using plugins. The functionality is
limited, and doesn't do many of the nicer things I would like (like
tagging/filtering) but it *does* work and it's simple enough that I can
comfortably tweak it and probably fix it if it ever somehow breaks.

And behold: [galleries!]({% link galleries/galleries.md %}) (fair warning: the one labeled
NSFW is)

It is in no way perfect, but it gets the job done and gives me a link I can
share to show off art of my sona, *and* has the bonus benefit of being a set of
hosted reference images so I don't have to link a gdrive link either when
sharing photos with artists. The biggest issue is that I have to order things
manually via file name for now, which is going to make reordering things
a bitch. I'll fix it later. Or I won't!
