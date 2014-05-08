4chan-dl
=======

A command-line program that makes filling reaction folders easier. Part of [/g/'s Programming Projects for n00bz](https://github.com/keplr/programming-projects-for-n00bz).

**Warning**: This is some kind of broken shit. You might not like my coding at all.
 
Usage
------
First of all, you should grant execute permission to the file:

`$ cd /path/to/4chan-dl && chmod a+x 4chan-dl`

And you're ready to go!

`$ ./4chan-dl -i <thread URL> -o <download path>`

Protip:

* Add this to your .bashrc: `export PATH=$PATH:/path/to/the/repo`
* Run `$ source .bashrc` once
* Launch it as simple as `$ 4chan-dl -i <thread URL> -o <download path>` (no need to go to the source folder again, or put the `./` thingie)


CHANGES
-----

April 24th, 2014

* Moved to new namespace.
* Added prettier print messages. Now you can monitor the download progress.
* Exceptions aren't visible to the user now (404 in specific). Instead of that, a rather unintuitive message shows up.  

TODO
-----

* Fix exception handling: format messages according to the error, so the user knows what's wrong with his input.
* Make a even fancier interface: perhaps showing the thread's OP, or redirecting to archives in case of 404ing (the latter couldn't be possible for archives that don't store images)
* Improve individual file and/or overall progress
* Create a folder, named after thread number or OP. This would be nice if you want each thread to be in a different folder
