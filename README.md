4chan-dl
=======

A command-line program that makes filling reaction folders easier. Part of [/g/'s Programming Projects for n00bz](https://github.com/keplr/programming-projects-for-n00bz).

**Warning**: This is some kind of broken shit. You might not like my coding at all.

Dependencies
------
* BeautifulSoup

Usage
------
First of all, you should grant execute permission to the file:

`$ cd /path/to/4chan-dl && chmod a+x 4chan-dl`

And you're ready to go!

`$ ./4chan-dl -i <thread URL> -o <download path>`

If you want to keep the original name of the files:

`$ ./4chan-dl -i <thread URL> -o <download path> -k`

CHANGES
-----

June 18th, 2016

* I haven't used this script for a while, until now. Looks like 4chan threw 403 Error to this script when it tried to access threads (thanks, Hiro). This was duly fixed.

March 30th, 2015

* Image fetching regex now is alphanumeric (before this, `4chan-dl` wouldn't work for r9k threads for example). Now it should work for any relevant board.

July 9th, 2014

* Added .webm support
* Added more bloat
* Now it's possible to keep the original filename

April 24th, 2014

* Moved to new namespace.
* Added prettier print messages. Now you can monitor the download progress.
* Exceptions aren't visible to the user now (404 in specific). Instead of that, a rather unintuitive message shows up.  

TODO
-----
* **(Soon, I expect) Use a decent arg parsing method**
* **(Soon, I expect) Use a decent progressbar method**
* Fix exception handling: format messages according to the error, so the user knows what's wrong with his input.
* Make a even fancier interface: perhaps showing the thread's OP, or redirecting to archives in case of 404ing (the latter couldn't be possible for archives that don't store images)
* Improve individual file and/or overall progress
* Create a folder, named after thread number or OP. This would be nice if you want each thread to be in a different folder
