---
title: "4. Setup Top-level Menu"
weight: 1
type: docs
description: >
    How to set up the top level menu.
---

The top level menu (the one that appears in the top navigation bar for the entire site) uses our site’s main menu..

Detailed Instructions:
======================

-   Step 1
>
> Add menu definition into config.toml which is under the root of our project directory. Then it
> will look like this:
>```
>baseURL = "http://DAYUCS.github.io/"
>languageCode = "en-us"
>title = "My New Hugo Site"
>theme = "docsy"
>
>[menu]
>
>  [[menu.main]]
>    identifier = "documentation"
>    name = "Documentation"
>    pre = "<i class='fa fa-book'></i>"
>    url = "/documentation/"
>    weight = 20
>```

-   Step 2
>
> Add _index.md under content/documentation of our project directory. Put following infomation into
> this file:
>```
>---
>title: "Documentation"
>weight: 1
>type: docs
>summary: A Hugo Site.
>---
>
># Contents
>
>Here are the contents:
>```
