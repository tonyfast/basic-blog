---
layout: post
title:  "the most basic blog"
author: "tonyfast"
---

# how to make the most basic blog

i want you to write! i want to read what you write! you may ask "what if no one sees?" and to that i respond "what does that have to with writing?".

it is easy to make excuses not to write. one excuse is lacking a trophy case for you work. the reality is that your blog is useless without having the work of writing. i encourage you to write and to find your voice. afterwards, display your work later as a collection.

in this work we will talk about a few low-code ways to begin sharing your voice.

## the design constraints

if you desire to have a blog, you should consider what writing tools work best for you. the decor of your blog is secondary to writing.

### gist

gist are a minimal repository provided by github for code snippets. it renders rst, markdown, and notebooks. it is a viable system for storing nascent work or literature.

### hackmd

hackmd is a very good writing tool, and it can be used a content management system too.

### dev.to

if you want a community, if you need an audience, then dev.to is your place to go.

### github pages

the most open source thing we can do is use a real github repository and use github pages to serve our work.

setting up the most basic jekyll blog requires:

1. a readme displaying the posts [`../READMD.md`](https://github.com/tonyfast/basic-blog/blob/main/README.md) contains a minimal example. it uses jekyll's suggestion to bootstrap the list.

        # basic blog
        
        {% raw %}
        {% for post in site.posts %}* [{{ post.title }}]({{site.baseurl}}{{ post.url }})
        {% endfor %}
        {% endraw %}

2. github pages activated in the project settings

  ![](https://i.imgur.com/m4d7FEs.png)

3. a folder containing [posts] with jekyll's `YEAR-MONTH-DAY-title.MARKUP` naming convention

## conclusion

just write! it can be scary to write, right? stop making excuses and find your voice. after you've overcome your fear in writing it will be time to display your work, to have your first art show, to arrange the decor. til then, raymond chandler offers some good advice to “Throw up into your typewriter every morning. Clean up every noon.” .

[posts]: https://jekyllrb.com/docs/posts/