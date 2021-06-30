---
title: "6. Setup Search"
weight: 1
type: docs
description: >
    How to set up site search.
---

Docsy offers multiple options that let our readers search our site content. In this case, we'll use *Local search with Lunr*.
This is a Javascript-based search option that lets us index our site and make it searchable without the need for external,
server-side search services. This is a good option particularly for smaller or non-public sites.

Detailed Instructions:
======================

-   Step 1
>
> Create a Markdown file as content/documentation/search.md. It only needs a *title* and *layout: search*, as in the following
> example:
>```
>---
>title: Search Results
>layout: search
>---
>```

-   Step 2
>
> Enable local search in *config.toml*:
>```
>[params]
>#Enable offline search with Lunr.js
>algolia_docsearch = false
>offlineSearch = true
>offlineSearchSummaryLength = 200
>offlineSearchMaxResults = 25
>```
> You may find the completed files at <https://github.com/DAYUCS/word2md>.

-   Step 3
>
> Restart our Hugo local server.
>