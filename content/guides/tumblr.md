---
title: "Tumblr - Content"
date: 2019-11-09
lastmod: 2019-11-09
publishdate: 2019-11-09
draft: false
description: Backup your Tumblr content
---

##  Official Method

* **Difficulty:** Easy
* **Speed:** 1-30 days
* **Data exported:**
	* Private Messages
	* Reblogged pictures, songs, and videos
	* Original posts
	* Reblog data
* **Official Instructions:** [here](https://tumblr.zendesk.com/hc/en-us/articles/360005118894-Export-your-blog)

### Description

This method produces a zip file of media, xml, and html files. **Note:** the resulting zip file can be very large. During testing, a 9 year old account with around 30,000 posts was used - the zip file generated clocked in at 32GB. Private conversations are saved in XML while the blog posts are saved in a single XML and individual HTML files.

### Steps

1. Login to Tumblr in a browser on a desktop or laptop
1. Go to the Account Settings page
1. On the right side of the page, click the blog you'd like to export data from
1. Scroll to the bottom of this page and click the "Export {blog}" button
	<!-- ![Request exports](/images/tumblr_content_export.png) -->
	<img src="/images/tumblr_content_export.png" alt="Request exports" class="centered bordered" />
1. In the next 1-30 days (probably 2) you should receive an email pointing you back to the settings page
	<img src="/images/tumblr_content_email.png" alt="Email" class="bordered centered">
1. At the bottom of the page, click the "Download backup" button
	<img src="/images/tumblr_content_download.png" alt="Download" class="bordered centered" />


## Unofficial Methods

* [TumblThree - A Tumblr Backup Application](https://www.jzab.de/content/tumblthree)
* [tumblr-utils](https://github.com/bbolli/tumblr-utils/)