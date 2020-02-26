---
title: "GitHub"
date: 2020-01-12
lastmod: 2020-01-12
publishdate: 2020-01-12
draft: false
description: Backup your Github data
---

##  Official Method

* **Difficulty:** Easy
* **Speed:** 1-24 hours
* **Data exported:**
	* Commit comments
	* Images included in issues
	* Issues
	* Issue comments
	* Issue events (i.e. "labeled", "opened", "closed")
	* Milestones
	* Projects
	* Pull Requests
	* Pull Request Reviews
	* Releases
	* Repositories
	* Users (who have contributed to the repositories)
* **Official Instructions:** [here](https://help.github.com/en/github/understanding-how-github-uses-and-protects-your-data/requesting-an-archive-of-your-personal-accounts-data)

### Description

GitHub makes it very easy to export a copy of your data. The data export results in a .tar.gz file and in testing the export request was fulfilled in about 20 minutes.<br />
If you are unfamiliar with this file type, this is very similar to a .zip file, though your operating system may not know how to handle .tar.gz files natively. If this is the case, a 3rd party utility such as [7zip](https://www.7-zip.org/download.html) will be needed.

### Steps

1. From a desktop or laptop, log in to https://github.com
1. Go to your profile settings page here: https://github.com/settings/profile
1. On the left side column, click "Account"
1. Under "Export account data" click **Start Export**
	<img src="/images/github_start.png" alt="Data & Privacy" class="bordered centered" />
1. Once the data export is ready, you'll receive an email with a download link. Simply hit that link and your download should start.
	<img src="/images/github_download.png" alt="Data & Privacy" class="bordered centered" />

