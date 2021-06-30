---
title: "7. Publish on Github (Option)"
weight: 1
type: docs
description: >
    How to publish our site on Github.
---

Because Hugo renders static websites, we can host our new Hugo website virtually anywhere. Github provides free and fast static
hosting over SSL for personal, organization, or project pages directly from a GitHub repository via its GitHub Pages service and
automating development workflows and build with GitHub Actions. In this case, we'll deploy our site on GitHub manually.

Detailed Instructions:
======================

-   Step 1
>
> Head over to GitHub and create a new public repository named *username*.github.io, where *username* is our username (or 
> organization name) on Github. In this case, *username* is DAYUCS.

-   Step 2
>
> Clone the new repository:
>```
>cd ~
>git clone https://github.com/DAYUCS/DAYUCS.github.io
>```

-   Step 3
>
> Stop Hugo local server, and build the site (*word2md* is our Hugo project directory):
>```
>cd ~
>cd word2md
>hugo -d ../DAYUCS.github.io
>cd ../DAYUCS.github.io
>git add .
>git commit -m "first commit"
>git push -u origin master
>```
>Go to <https://DAYUCS.github.io> to see our website out in the wild.