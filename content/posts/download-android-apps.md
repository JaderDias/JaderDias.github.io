---
title: "How to download Android apps files and analyse them"
date: 2022-01-25T13:42:40+01:00
draft: false
---
With [Apkpure](https://apkpure.com/) we can download the binaries and resources from any Android application on the Play Store. That’s very interesting if you want to re-use some of its assets.

Suppose you need a list of all the words in English and their translation to Spanish. It could be cumbersome to crawl a translation website or make your app depend on a Translation API for such a task. An alternative is to look for an Android app that has an English to Spanish dictionary and re-use its assets.

We can search for such an app with the keyword “Spanish Translator offline”. After downloading and unzipping it, we look for the largest file, which is also compressed. After decompressing it we might find a file that is either plain text or a SQLite3 database.