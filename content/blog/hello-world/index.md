---
title: Hello World
date: "2015-05-01T22:12:03.284Z"
description: "Hello World"
---

This is a quick overview of Gatsby. Steps i've taken so far:

- gone to https://www.gatsbyjs.com/
- signed up to gatsby cloud
- create a blog based on a template

The first site i created actually failed to build, so i had to delete it, and the two repos associated with it, and start over again.

## Two repos?

Yes two repos. I had to fight a little bit with the permissions Gatsby asks from Github. Gatsby wants access to **all** your repos, public and private. That's a lot to ask for! Some private repos may contain private data, and it seems a bit rich for a cloud-based blogging platform to gain access to all your sources.

Initially i created a repo named "gatsby" but gatsby decided to create a second one, named after the name of the site. I used the minimal template, and for some reason it failed to build. I then had to grant gatsby access to all my repos (since initially i'd only granted access to 1 repo), used another template and it built correct.

## content/blog/hello-world/index.md

So it seems that the Gatsby repo contains a folder structure with ultimately some .md files. That's pretty awesome as i use a **lot** of .md files with https://obsidian.md. It seems the .md files sadly need to be in a subdirectory, so just dumping all my .md files into my new gatsby repo probably wouldn't do the trick. Nevertheless, it seems Gatsby is definitely on the lightweight side of things, so that's pretty awesome.

## The cloud

I seem to have entirely missed the boat when it comes to having hosted blogs that basically work as small hosted webapps. I'm pretty old-school in this regard, since i have a server and just dump everything on there. But i'm starting to think it's time to move on, and start using all these cloud services since it'll save me the monthly cost on my server.

----------------------------------

Written by: Shyal Beardsley