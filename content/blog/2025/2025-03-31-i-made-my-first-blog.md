+++
title = "I made my first blog."
date = 2025-03-31T18:38:00+07:00
+++

## Made my first blog
I'm a newly graduated high school student with almost *zero* knowledge in *computer science* and *computer engineering* one of which is what I applied to study in a university.
But I thought that logging my progress and what I've learnt, will benefit me in the future. So here I am. Writing this blog.

With little to no knowledge, I searched for a simple blogging platform. Which I decided to write them with this [SSG](https://developer.mozilla.org/en-US/docs/Glossary/SSG) called [Gozer](https://git.sr.ht/~dvko/gozer). I found it on this ["awesome" github page](https://github.com/myles/awesome-static-generators). It allows you to write [Markdown](https://spec.commonmark.org/0.31.2/#what-is-markdown-) files and convert them into [HTML](https://html.spec.whatwg.org/multipage/introduction.html#background) files, the standard file format to be displayed on the web. Web pages would look uniform and boring without [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) to style them.

At first, I chose [Writ.css](http://writ.cmcenroe.me/) which is a pre-written CSS file. But resorted to [awsm.css](https://igoradamenko.com/awsm.css/v2/) later, I find both of them stylish, readable, and very simple to use. Just link the CSS file to your HTML and everything is done. No configurations or classes at all. With my combo of writing Markdown and using Gozer to build HTML files from it, it's really fast to both read and write. I don't have to write and deliberately close every tags, and the CSS is very light.

All the hurdles I've been through were just setting up the [blog index page](/blog). It needs a little configurations on its template which I modified from [Danny's template](https://git.sr.ht/~dvko/dannyvankooten.com/tree/main/item/templates/blog.html), the creator of Gozer. I might have to learn more about [Go](https://go.dev/)'s standard [html/template](https://pkg.go.dev/text/template#hdr-Actions) package, or Go entirely, because Gozer uses it.

Another hurdle I have not yet to mention is the process of deploying this site. I chose [Github Pages](https://pages.github.com/), but because I use Gozer, I had to set up my own [Github Actions](https://github.com/features/actions) to deploy the pages by making changes to the site's [source](https://github.com/SaraNotNaras/SaraNotNaras.github.io) which is stored on the repository on [Github](https://github.com/about). And then it builds the static files (HTML, CSS, images), then deploy them to Github Pages.

I have not yet to deploy this site. I have no idea if my site will be deployed correctly or not. Well, I will update about this in "the other post" if I managed to fumble.

Well, see you in another post.
