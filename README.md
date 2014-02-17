Yet Another 4chan Thread Image Downloader (YANFTID)
=======

YANFTID is a command-only program that makes filling reaction folders easier. Part of [/g/'s Programming Projects for n00bz](https://github.com/keplr/programming-projects-for-n00bz).
 
Usage
------
First of all, you should grant execute permission to the file:

`$ cd /path/to/yanftid && chmod a+x yanftid`

And you're ready to go!

`$ ./yanftid -i <thread URL> -o <download path>`


TODO
-----

* Make a fancier interface (perhaps showing the thread's OP, or redirecting to archives in case of 404ing)
* Show individual file and/or overall progress
* Create a folder, named after thread number or OP (this would be nice if you want each thread to be in a different folder)
