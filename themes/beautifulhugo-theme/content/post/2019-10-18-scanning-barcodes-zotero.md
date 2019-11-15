---
title: Scanning ISBN Barcodes to Add Books to Your Zotero Library
date: 2019-10-18
author: Tim Blevins
tags: ["bibliography", "research", "Zotero"]
---

There is a fast and easy way to add book sources to your Zotero Library when you are doing research at the library. Just scan the ISBN barcode with your Android device and it will add all of the essential bibliographic data for the book to your online Zotero account! 

## You will need:
* Android device <i class="fab fa-android"></i> with a camera (but I'm an [iOS user!](https://www.zotero.org/blog/scan-books-into-zotero-from-your-iphone-or-ipad/))
* [Zotero](https://www.zotero.org/) account (a free account includes 300MB of storage)
* [Barcode Scanner](https://play.google.com/store/apps/details?id=com.google.zxing.client.android&hl=en_US) app free from Google Play

## Set up the barcode scanner:
1. Install the Barcode Scanner app
2. Open the app
3. Tap the more dots <i class="fas fa-ellipsis-v"></i> in the upper right corner 
4. Tap Settings
5. Scroll to Custom search URL and tap it
{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/img/CustomSearchURL.jpg" caption="Custom search URL" alt="Tap Custom search URL" >}}
{{< /gallery >}}
6. Enter the URL `https://www.zotero.org/save?q=[%s]` and tap DONE[^1]
{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/img/EnterCustomURL.jpg" caption="Enter custom Zotero URL" alt="Enter custom Zotero URL: https://www.zotero.org/save?q=[%s]" >}}
{{< /gallery >}}
7. Exit Settings

## Set up the broswer on the Android device:
1. Open your preferred browser
2. Go to the Zotero [Login](https://www.zotero.org/user/login/) page
3. Enter your username and password
3. Tick the box next to Remember Me Keep me signed in for 30 days
3. Click the Login to Zotero button
4. Keep this tab open (though you can exit the app)

## Add a book to your Zotero Library:
1. Open the Barcode Scanner app
2. Scan the ISBN barcode <i class="fas fa-barcode" ></i> for the book you wish to add
3. Tap Custom Search on the bottom right
4. The browser will open to the Add to Zotero page
5. The title and author of the book will appear
6. Tap Save to add the book to your Library
7. Repeat to add more books to your Zotero Library

---
[^1]: Many thanks to dstillman who provided the URL on the Zotero Forum discussion: [Scanning ISBN Barcode to input books to Zotero library](https://forums.zotero.org/discussion/76471/scanning-isbn-barcode-to-input-books-to-zotero-library).

Please share your comments or time-saving ideas below about scanning ISBNs into your Zotero Library.
