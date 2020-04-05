---
title: Imbedding PDF in Markdown
date: 2020-04-05 14:10:00 +0800
categories: [Animal, Insect]
tags: [markdown]
seo:
  date_modified: 2020-04-05 03:07:43 -0400
---
## Add an Image
<img src="https://octodex.github.com/images/jetpacktocat.png"
height="300">

## First try for a pdf view

<object data="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://drive.google.com/viewerng/viewer?embedded=true&url=https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf">Download PDF</a>.</p>
    </embed>
</object>

## Second try for a pdf view
<a href="https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf" target="_blank">PDF.</a>


## Third try for a pdf view
<iframe src="https://docs.google.com/viewer?url=https://github.com/jennyjyounglee/Statistics/blob/master/testintrotostat.pdf&embedded=true" style="width:600px; height:500px;" frameborder="0"></iframe>