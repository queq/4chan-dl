4chan-dl
=======

A command-line program that makes filling reaction folders easier. Part of [/g/'s Programming Projects for n00bz](https://github.com/keplr/programming-projects-for-n00bz).
 
Usage
------
First of all, you should grant execute permission to the file:

`$ cd /path/to/4chan-dl && chmod a+x 4chan-dl`

And you're ready to go!

`$ ./4chan-dl -i <thread URL> -o <download path>`

Protip:

* Add this to your .bashrc: `export PATH=$PATH:/path/to/the/repo`
* Run `$ source .bashrc` once
* Launch it as simple as `$ 4chan-dl -i <thread URL> -o <download path>` (no need to go to yanftid's folder again, or put the ./ thingie)


CHANGES
-----

* Moved to new namespaces.

TODO
-----

* Make a fancier interface (perhaps showing the thread's OP, or redirecting to archives in case of 404ing)
* Show individual file and/or overall progress
* Create a folder, named after thread number or OP (this would be nice if you want each thread to be in a different folder)
