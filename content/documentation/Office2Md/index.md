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
> There is file named Office2Md.json in folder opendoc. This file cotains the configuration of the tool. Replace its conten with this:
>```
>{
>  "Toc": {
>    "TocHeading": [
>      "TOC Heading"
>    ],
>    "Toc1": [
>      "TOC 1"
>    ],
>    "Toc2": [
>      "TOC 2"
>    ],
>    "Toc3": [
>      "TOC 3"
>    ],
>    "Toc4": [
>      "TOC 4"
>    ]
>  },
>  "Head": {
>    "Heading1": [
>      "Heading1",
>      "FASEHeading1"
>    ],
>    "Heading2": [
>      "Heading2",
>      "FASEHeading2"
>    ],
>    "Heading3": [
>      "Heading3",
>      "FASEHeading3"
>    ],
>    "Heading4": [
>      "Heading4",
>      "FASEHeading4"
>    ],
>    "Heading5": [
>      "Heading5",
>      "FASEHeading5"
>    ],
>    "Heading6": [
>      "Heading6",
>      "FASEHeading6"
>    ]
>  },
>  "List": [
>    "ListParagraph",
>    "FSBulletlistblacklight",
>    "Bullet1",
>    "Bullet2",
>    "Bullet3"
>  ],
>  "Common": [
>    "Normal",
>    "Emphasis",
>    "Table Grid",
>    "Normal (Web)",
>    "Caption",
>    "Hyperlink",
>    null
>  ],
>  "Image": {
>    "Prefix": "/content",
>    "UsePrefix": false,
>    "Embed" : false,
>    "Convert" : {
>      "UseConversion" : false,
>      "Replace" : [
>        {"From" : ".emf", "To" : ".jpg"},
>        {"From" : ".wmf", "To" : ".jpg"},
>        {"From" : ".tif", "To" : ".jpg"},
>        {"From" : ".tiff", "To" : ".jpg"},
>        {"From" : ".png", "To" : ".jpg"},
>        {"From" : ".bmp", "To" : ".jpg"},
>        {"From" : ".exif", "To" : ".jpg"},
>        {"From" : ".gif", "To" : ".jpg"},
>        {"From" : ".ico", "To" : ".jpg"}
>      ],
>      "Resize" : {
>        "UseResize" : false,
>        "MaxWidth" : 800,
>        "MaxHeight" : 0,
>        "DoNotResizeLessThanMax" : true,
>        "InterpolationMode" : "HighQualityBicubic"
>      }
>    }    
>  },
>  "ReplaceThis": [
>    {"From" : "\u2013", "To" : "-"},
>    {"From" : "\u201c", "To" : "\""},
>    {"From" : "\u201d", "To" : "\""},
>    {"From" : "\u2022", "To" : ""},
>    {"From" : "\u2026", "To" : "..."},
>    {"From" : "\u2014", "To" : "-"},
>    {"From" : "®", "To" : "&copy;"},
>    {"From" : "\u2122", "To" : "&trade;"},
>    {"From" : "°", "To" : "&deg;"},
>    {"From" : "\uffff", "To" : ""},
>    {"From" : "\u2019", "To" : "'"}
>  ],
>  "Table" : {
>    "Standardize" : true
>  },
>  "Colors" : {
>    "UseColors" : true,
>    "Replace" : [
>      {"From" : "#FFFFFF", "To" : "#000000"},
>      {"From" : "white", "To" : "black"}
>    ]
>  },
>  "Workbook" : {
>    "SheetHeading" : {
>      "UseTabName" : true,
>      "Template" : "### {TabName}"
>    }
>  },
>  "Pdf" : {
>    "UsePageNumbers" : true,
>    "Position" : "footer",
>    "Template" : "#### {PageNumber}"    
>  }
>}
>```

-   Step 3
>
> Suppose you have a recent .Net SDK installed on your machine. Under the window opened by Step 1:
>```
>cd opendoc
> .\Office2Md.ps1 -DocPath "D:\Temp\CEV336 Archiving and Recovery.docx" -MdDir D:\Temp\CE -GithubFlawor -IntoSingleOne
>```
> This will covert the docx and put the converted files into D:\Temp\CE

-   Step 4
>
> Rename the md file as index.md and add Docsy header into it.