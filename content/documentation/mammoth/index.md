---
title: "Mammoth"
weight: 1
type: docs
description: >
    Use mammoth to convert Word document from docx to HTML and Markdown.
---

Mammonth is designed to convert .docx documents, such as those created by Microsoft Word, Google Docs and LibreOffice, and convert them to HTML and Markdown.  Please note that mammoth covert docx by using **semantic information in the document, and ignoring other details**. Mammonth works fine if you only use styles to semantically mark up your document. Please refer to (<https://pypi.org/project/mammoth/>) for the features supported by mammonth.

We'll install it on Ubuntu.

Detailed Instructions:
======================

-   Step 1
>
> Suppose you have a recent version of NodeJS installed on your machine, so you can use NPM.
>```
>sudo npm install -g mammoth
>```

-   Step 2
>
> Convert docx to markdown with mammoth.
>```
>mammoth --output-format=markdown 'CEV336 Archiving and Recovery.docx' index.md
>```
> Or convert docx to HTML.
>```
>mkdir media
>mammoth --output-dir=./media 'CEV336 Archiving and Recovery.docx'
>```