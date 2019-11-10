---
title: "Spotify"
date: 2019-11-10
lastmod: 2019-11-10
publishdate: 2019-11-10
draft: false
---

Spotify does not currently have an official way of making a backup list of all playlists and songs in an account. For now, 3rd party tools are the only option.


## Unofficial Method - Exportify

* **Difficulty:** Easy
* **Speed:** 5-15 minutes
* **Data exported:**
	* Lists of songs in playlists
* **Official Instructions:** (none)

### Description

This method utilizes a 3rd party app called Exportify. Exportify uses the Spotify API to get your playlists and render them in CSV format. If you'd like to review the source code of the tool, it is available here: https://github.com/watsonbox/exportify 
<br />**Note:** This tool only exports lists of songs in playlists. If you'd like to make a list of all songs in your Spotify library, you'll have to create a new playlist and add all your songs to it.


### Steps

1. Go to: https://exportify.net/
1. Click "Get Started"
1. Spotify should ask you for permission to connect this app to your account
	<br /><br />
	![download](/images/spotify_authorize.png)
	<br /><br />
1. Hit "Agree"
1. You should be greeted with a page of all your playlists. If you'd like to backup only a few playlists, hit the "Export" button on individual playlists. Otherwise, click the "Export All" button in the top-right corner of the table.
	<br /><br />
	![download](/images/spotify_download.png)
	<br /><br />
1. After you're done, it's a good idea to revoke access to the app we used. Go here: https://www.spotify.com/account/apps/ and click "Remove Access" next to Exportify
	<br /><br />
	![download](/images/spotify_revoke.png)
	<br /><br />
