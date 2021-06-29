---
title: "3. Install Docsy"
weight: 1
type: docs
description: >
    How to install Docsy on Ubuntu.
---

Docsy is a Hugo theme for creating great technical documentaion sites (<https://www.docsy.dev/>).

We'll install it on Ubuntu.

Detailed Instructions:
======================

-   Step 1
>
> To build or update our site's CSS resources, we need PostCSS to create the final assets. Web must have 
> a recent version of NodeJS installed on our machine so we can use npm.
>```
>sudo npm install -D autoprefixer
>sudo npm install -D postcss-cli
>sudo npm install -D postcss
>```

-   Step 2
>
> We've generate a hugo site named *word2md*. Now we'll add the Docs theme as a submodule.
>```
>cd word2md
>git init
>git submodule add https://github.com/google/docsy.git themes/docsy
>echo 'theme = "docsy"' >> config.toml
>git submodule update --init --recursive
>```

-   Step 3
> To build and preview your site locally:.
>```
>hugo server
>```
> By default, your site will be available at http://localhost:1313/