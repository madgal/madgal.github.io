the config documet sets up the main page of my website

putting additional items in posts puts the post on the home webpage


TO CREATE New PAGEs: 
    copy one of the *.md files in the main directory and modify the title and content
    MAKE SURE TO CHANGE THE PERMALINK TO THE CORRECT DIRECTORY

To link to another post go:
 [title that will show up]({% post_url thePostName %})
 [Welcome to Jekyll!]({% post_url /2016-02-16-welcome-to-jekyll %})

To include icons :
	{% include icon-github.html username="jglovier" %} /
	 
git status
git add -A
git commit -m "update"
git push



Example of a blog page:

---
layout: page
title: Blog 
permalink: /blog/
---

[Programming Experience]({% post_url 2016-02-19-coding-experience %})


