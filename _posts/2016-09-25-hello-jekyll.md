---
layout:     post
title:      Hello Jekyll
summary:    My first jekyll blog
categories: jekyll
---

## My blogging journey begins with Jekyll

Phewww...

My first jekyll blog is finally up. For the last couple weeks,
I was trying to build a personal blog where I could write about what I have
learnt in web development and show stuff I've done. I find that blogging is a very effective way to learn and remember
things.

Before building this blog, I had few options in mind:

* Use WordPress
* Use static pages
* Develop my own blog using Ruby on Rails

## What is Jekyll and why I chose it?

I came across Jekyll while googling answers for my Ruby on Rails blog
building. I noticed that many web developers' blogs use a platform called Jekyll. So I started to
dig deep and find out what the deal is.

### So what is Jekyll?

In short, Jekyll is a simple static HTML pages generator. The cool thing is that
Jekyll allows you to compose your posts in simple markup languages (Markup,
Textile), which takes less effort than raw HTML. Then Jekyll runs them through a
converter and [Liquid](https://shopify.github.io/liquid/) template engine to
generate a complete static website.

### Why I chose it?

#### Simple and minimalistic

For every day blogging, I find a general purpose CMS like WordPress a bit overkill. Jekyll suits my
needs perfectly for simple blogging. Whenever I have an idea for a post, I simply open my
favorite text editor ([MacVim](http://macvim-dev.github.io/macvim/)) and compose
it in [Markdown](https://daringfireball.net/projects/markdown/syntax). When I'm
done, I could choose to save it for later review or compile it and push to
Github pages by Git.

#### Fast and secure

Serving a Jekyll static blog is ultra fast, the web server only needs to
return a file. On the other hand, WordPress needs database and server side
code, it has to generate content on each request, which means that your blog
would struggle if it experiences high amount of traffic.

Moreover, by not using database, you don't have to worry about exposing security
holes to malicious users. WordPress plugins could also provide potential access
points to hackers.

#### Flexible and customizable

Jekyll static sites are not entirely static. Jekyll provides some degree of
flexibility customization by using [Liquid](https://shopify.github.io/liquid/) renderer to insert dynamic
content to your site.

#### Easy to deploy

Deploying static websites is super easy, and you don't have to go through a lot
of configurations. Or even better, you could host your blog for free using [Github
pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/),
which what I am doing.

---

Jekyll has those many cool features that really convince me to start using. I decided to postpone
my Ruby on Rails blog building for a future project and use Jekyll blog instead.

## Components I use to build my Jekyll blog:

* [Pixyll](https://github.com/johnotander/pixyll) theme by [John Otander](http://johnotander.com/)
* hosted on Github using [Github Pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/)
* custom domain registered at [Google Domain](https://domains.google/#/)


