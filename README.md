sabrabbr
========

Chrome Extension that displays the definition of commonly used baseball acronyms. I have absolutely no idea
how optimal this is. Please let me know if you find a better way of doing this. Thanks!

![SabrAbbr in Action on r/baseball](https://raw.github.com/Alexstre/sabrabbr/master/images/inaction.png)

Installation
-------
There are 2 ways to install in Chrome:

* 	Method 1: Clone this repo directly from github. In `chrome://extensions` activate `Developer mode` and load the extension
	by clicking `Load unpacked extension...`. This will allow you to modify the extension if you so desired. You can also click
	`Pack extension...` to create your own `.crx` file. 

*	Method 2: Download only the `.crx` file. Launch Chrome and drag/drop the file into `chrome://extensions`. Enjoy.

Please note that as of version 0.2, the extension should update automatically when needed. Installing the `.crx` in Chrome should only be needed once.
I also uploaded the file on my personal server so people having issues downloading from GitHub (you must click the file and download as "raw") can grab it [here](http://x5f5.org/sabrabbr/sabrabbr.crx).

Usage
-------
Once installed, the extension will automatically append `<abbr>` tags to commonly used acronyms. Simply mouseovering will
show a more complete definition. All definitions were taken from [this Wikipedia page](https://en.wikipedia.org/wiki/Baseball_statistics "Baseball Statistics at Wikipedia"). Ironically the extension does not work on Wikipedia. Please note that the extension does not force a CSS change for the `abbr` tag so unless the site you're visiting has that tag styled there's no visual clue that you can mouseover an accronym.
I might add it at a later time but for now I want to look at popular websites and see if they have `abbr` tags styled already (r/baseball does now, thanks for u/Fustrate!)