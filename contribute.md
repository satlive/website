---
layout: page
title: How to contribute
permalink: /contribute/
---

> If you think that one information should appear on this site, then you
> have two main ways to achieve it.

## The human way (slow publication option, may take days)

Just send your information to [daniel@satlive.org](mailto:daniel@satlive.org)

## The hacker way (fast publication option, may take hours)

The new SAT Live! is built using [Jeckyll](http://jekyllrb.com). All the posts are written using a specific markdown format which is then transformed into HTML. All the content of the website is [stored on a git repository](https://github.com/satlive/website/).

The proper way to submit a new "post" to SAT Live! is thus to:

* [clone](https://github.com/satlive/website/fork) the current SAT Live! web site on github
* write your own post: make sure to [properly adhere the naming conventions](http://jekyllrb.com/docs/posts/)
* send me a pull request :)

Regular contributors will get write access to the git repository to facilitate the integration of their information.

Submitting a news is as simple as providing the following metadata:

    ---
    layout: post
    title: <your title>
    author: <your name>
    tags: <space separated among CFP, PostDoc, PhD, Position, Grants, QBF
    excerpt: <a one or two sentences describing your info>
    link: <an optional link to get more information>
    ---

together with the text of the news, in [markdown format](http://daringfireball.net/projects/markdown/).

Make sure that:

* "sections" are second level (using the `##` prefix
* lists are properly formatted (start with `*` or `+` or `-`)

In order to have a deadline appearing on the "Upcoming deadline" box, some specific metadata are needed:

* The `CFP` tag must be part of the list of tags
* The extra `shorttitle` and `deadline` must be set
* The `link` attribute must be set

Here is for instance a way to announce the upcoming SAT conference

    ---
    layout: post
    title: "18th Int. Conf. on Theory and Applications of Satisfiability Testing"
    shorttitle: SAT'15
    author: "Sean Weaver"
    tags: CFP
    excerpt: "The next SAT conference is taking place in Austin. Check the submission deadline now!"
    link: http://www.cs.utexas.edu/~marijn/sat15/
    deadline: 2015-04-29
    ---
