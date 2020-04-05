---
title: Imbedding PDF in Markdown
date: 2020-04-05 14:10:00 +0800
categories: [Animal, Insect]
tags: [markdown]
seo:
  date_modified: 2020-04-05 02:43:30 -0400
---
## Add an Image
<img src="https://octodex.github.com/images/jetpacktocat.png"
height="300">

## Add a pdf

<object data="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf">Download PDF</a>.</p>
    </embed>
</object>
