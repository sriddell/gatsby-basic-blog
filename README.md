# gatsby-starter
Gatsby starter for creating a blog

Based on [demo](http://konsumer.js.org/gatsby-starter-drunkenblog/).

Install this starter (assuming Gatsby is installed) by running from your CLI:
`gatsby new gatsby-blog https://github.com/sriddell/gatsby-basic-blog.git`

## Running in development
`gatsby develop`

## deploying to gh-pages

If you have a [custom domain](https://help.github.com/articles/using-a-custom-domain-with-github-pages/), put it in `pages/CNAME`. You can deploy to Google Pages with `npm run deploy`.


## configuration

Go edit `config.toml`. Change it to all of your stuff. change `pages/author.png` to your own picture.

## creating posts

Your content goes in /pages.  This starter defines a default hello world type blog post.

Each post should be in its own directory under pages.  Recommendation is to name it with the date and something descriptions, e.g. "2017-01-23-dns-sd".

Inside the directory, make your post in index.md in markdown, and include the following front matter yaml at the top:

```
---
title: Hello World
date: "2017-01-23T22:12:03.284Z"
layout: post
---
```

You can get more specific with the front matter, for example:

```
---
title: Hello World
date: "2015-05-01T22:12:03.284Z"
layout: post
readNext: "/my-second-post/"
path: "/hello-world/"
tags:
  - Hello
  - world
  - demo
---
```

Instead of using your directly name for the link, it will use /hello-world/ as the path, and provide a read next link to the relative path /my-second-post.  It will also tag the post with 'Hello', 'world', and 'demo'.


