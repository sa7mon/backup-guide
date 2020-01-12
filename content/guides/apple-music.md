---
title: "Apple Music"
date: 2019-11-19
lastmod: 2019-11-19
publishdate: 2019-11-19
draft: false
---

##  Official Method

* **Difficulty:** Easy
* **Speed:** < 5 minutes
* **Data exported:**
	* Song info - Artist, album, genre, year, etc.
	* Play count
	* Album artwork data
	* Sample rate, bit rate
	* Date added, date modified
	* Playlists

* **Official Instructions:** [here](https://support.apple.com/guide/music/save-a-copy-of-your-playlists-mus27cd5060f/mac)

### Description

This method does not backup the audio files for the songs in your library, but rather makes a backup of all song data in your library. This is very useful, for example, if you are moving to a different music streaming service.

The output is an XML file which is machine-readable and can be easily consumed by other applications.

### Steps

1. On a desktop or laptop open iTunes
1. In the menu bar, click **File > Library > Export Library**<br />
<img src="/images/apple-music_export.png" alt="Choose data" class="centered">
1. Choose a location to save the XML file in


## Unofficial Method

* **Difficulty:** Easy
* **Speed:** < 5 minutes
* **Data exported:**
	* Song info - Artist, album, genre, year, etc.
	* Play count
	* Album artwork data
	* Sample rate, bit rate
	* Date added, date modified

### Description

If you'd like to export your library to a spreadsheet instead of an XML file, this method will work for you. **Note:** This method may not work well if a large library is used as it copies all library data temporarily to the clipboard.

### Steps

1. On a desktop or laptop, open iTunes
1. Right-click on the column labels above the library and enable all columns you wish to export<br />
	<img src="/images/apple-music_columns.png" alt="Choose columns" class="centered bordered">
1. Click **Edit > Select All** to select all songs in the library, then click **Edit > Copy**
1. Open Microsoft Excel and create a new spreadsheet
1. In Excel, click **Edit > Paste**
1. Now you have a spreadsheet with all library data. You may wish to create a new row at the top with the column labels<br />
<img src="/images/apple-music_excel.png" alt="Excel spreadsheet" class="bordered centered">