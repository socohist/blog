---
title: UPDATED: Share Big Files Fast & Safely with Firefox Send
author: Tim Blevins
date: 2019-11-28T19:38:50.251Z
disqus: true
tags: ["file sharing", "Firefox", "security"]
---
**UPDATE: Mozilla [suspended Firefox Send](https://support.mozilla.org/en-US/kb/what-happened-firefox-send) during September 2020.**

[Firefox Send](https://send.firefox.com/) is a free service that permits users to securely share files up to 2.5GB from any web browser (not just Firefox). There is also an Android app (in beta) available on [Google Play](https://play.google.com/store/apps/details?id=org.mozilla.firefoxsend&hl=en_US).

## What you need to know

A Firefox account is optional. No account is needed to share files up to 1GB. Just upload the files that you want to share by using Drag and Drop into the browser, or by clicking the "Select files to upload" button and choosing the files from the file explorer window. Multiple uploaded files are automatically combined into a zipped file.

Before you click on the "Upload" button at the bottom of the screen you can change the expiration defaults for the number of downloads and the duration for how long your file will be accessible by the forthcoming download link. The defaults are set so that access expires after one download or one day. You can increase the number of downloads to up to 100 (1, 2, 3, 4, 5, 20, 50, or 100), and you can increase, or decrease, the duration of access from five minutes to seven days (5 min., 1 hour, 1 day, 7 days). There is an additional option to password protect the file.

After you make your expiration and password selections, click the "Upload" button. The file is uploaded and a unique url is provided for you to copy and send to the recipient. The file is encrypted end-to-end, from your browser to the recipient's browser, whether or not you selected additional password protection.

There are a a few benefits to logging in to Firefox Send:

* Uploaded files can be larger than 1GB (up to 2.5GB)
* Ability to recopy links to files that have not expired
* Ability to delete active files that you no longer want to be accessible
* If a file was limited to one download, and is not listed among your active files prior to the end of the duration that you set, then you know that the recipient of the link has downloaded the file

If you do not log in to Firefox Send the unique urls to uploaded files are not accessible again after the browser tab is closed. This is not an issue if you copied the link and pasted it somewhere, but the benefits listed above may be good reasons to log in before uploading.

## There's a Glitch

When attempting to log in to Firefox Send from the Firefox browser (v. 70.0.1 64-bit) on Windows 10 I experienced an error: ["Something went wrong!"](https://send.firefox.com/error). A web search resulted in only a few instances of others experiencing this error, and none of them provided a solution. Firefox Send worked fine with Chrome and Firefox on Linux.

There may be many potential reasons why the error occurs. The fix that has worked consistently is to clear the history by opening the menu in the upper right corner, selecting Options->Privacy & Security, scrolling down to History and click the "Clear History" button. For "Time range" clear "everything" and select all History and Data options and click the "Clear Now" button. BE WARNED! This will clear everything that you select and may have unintended consequences. Do not do this unless you understand what you are doing. After following these instructions you should be able to log in to Firefox Send in the Firefox browser. Hopefully this error will be corrected soon.
