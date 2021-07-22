---
title: "Office2Md"
weight: 1
type: docs
description: >
    Use Office2Md to convert Word document from docx to Markdown.
---

Office2Md is designed to convert .docx documents, such as those created by Microsoft Word, Google Docs and LibreOffice, and convert them to Markdown. Please refer to (<https://gitlab.com/VeryComplexName/opendoc>) for the features supported by Office2Md.

We'll install it on Windows 10.

Detailed Instructions:
======================

-   Step 1
>
> Suppose you have a recent version of Git installed on your machine. Open Windows PowerShell:
>```
>git clone https://gitlab.com/VeryComplexName/opendoc.git
>```
>This will create a folder named opendoc and clone Office2Md into this folder.

-   Step 2
>
> Suppose you have a recent .Net SDK installed on your machine. Under the window opened by Step 1:
>```
>cd opendoc
> .\Office2Md.ps1 -DocPath "D:\Temp\CEV336 Archiving and Recovery.docx" -MdDir D:\Temp\CE -GithubFlawor -IntoSingleOne
>```
> This will covert the docx and put the converted files into D:\Temp\CE

-   Step 3
>
> Rename the md file as index.md. Open one of your favorite edit tool, e.g. VS Code, replace all "(/content/images/" with "(./images/".