---
title: An example blog post
cover: https://pixabay.com/static/uploads/photo/2015/12/01/20/28/green-1072828_960_720.jpg
tags: some, dummy, tags
layout: post
---

This is an example post that comes along with the theme.

This theme adds a submenu of projects in the main menu if there is a `projects.yml` file in the `_data` directory and its contents are of the form:

{% highlight yaml %}
- name: Project 1
  url: /project1/

- name: Project 2
  url: /project2/
{% endhighlight %}

Delete this file if you don't want project links.
