---
layout: education
title: High School
image: apeejay.png
---

Recently I had need of a method to quickly and easily convert Gmail messages into PDFs.  In the process, I created a small library of helpful tools for use with [Google Apps Script](https://developers.google.com/apps-script/) that I believe others may benefit from.  What follows is a description of the library and some example usage.

{{ more }}

## TL;DR

I've created a Google Apps Script library to automate the heavy-lifting involved with Gmail message to PDF conversion.  If you aren't interested in the nitty gritty of what goes into the process, you can dive right into the [example project](https://script.google.com/d/1qdkT9ShXl4VWO9XvKefcxmH_oRJe31MPDyIDsOKyGidKr-GHBpULLtvx/edit?usp=sharing), fork it, and play with it yourself.  I've put the library on [GitHub](https://github.com/pixelcog/gmail-to-pdf), of course, and you can find the project IDs needed to include the library in your own project there.

## Converting Emails to PDF

![Gmail to PDF](/img/posts/gmail-to-pdf.jpg)

When I sought out solutions on Google, I was initially led to a [clever idea](http://www.oxhow.com/automatically-backup-emails-as-pdf/) which utilized [IFTTT](https://ifttt.com/) and Gmail filters to send your email to an external service like [pdfconvert.me](http://pdfconvert.me/) for conversion.  In practice, however, the IFTTT recipes ended up being inflexible and buggy.  Also from a security standpoint I really didn't like the idea of sharing my email with two new third party services, no matter how benign their privacy policies may be.

I decided to keep the process in-house, so I looked into [Google Apps Script](https://developers.google.com/apps-script/).  Google, after all, is already hosting my email so I am not involving any new parties.  If you've never used Google Apps Script before, I urge you to check it out.  It is an indispensable tool for automating processes involving any of Google's cloud services, and all that is needed is some basic familiarity with JavaScript.
