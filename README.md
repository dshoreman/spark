Spark
=====
This is a bash helper script to make working with Spark on CodeIgniter easier.

Install
------
To install just issue the following command to your /usr/local/bin or any other place that is part of your $PATH in your terminal:

    sudo wget https://github.com/killswitch/spark/raw/master/spark && sudo chmod a+x spark

Usage
------

Usage is very similar to spark's original usage, except instead of the following:

    php tools/spark help

You would do:

    spark help
    
Commands haven't changed much other than install, remove and version.

To get started, you can add sparks to your project by typing:

    spark init

...or you could skip the init completely! Go ahead and install a spark like this:

    spark install example-spark 1.0.0

If you don't already have CI Sparks installed in your project, you'll be asked if you want it installed automatically. Compare that to the old way:

	php tools/spark init
    php tools/spark install -v1.0.0 example-spark

To remove a spark you'll just issue the following command to uninstall all versions of the package (who uses multiple anyway?):

    spark remove example-spark
    
Version does nothing different than the original, except it also tells you the version of this bash script.


Todo:
----
 - Add a way to find the latest spark version and use that when doing "spark install example-spark" that way you do not need to specify the version. (Why this doesn't already exist with spark is beyond me.)
 - Check to see if you're in a proper CodeIgniter project folder.
 - Self version checker to let you know if the version of this script has been updated and if you want to update or not.

Credits:
----
 - [Josh Manders](http://github.com/killswitch) as author.
 - [Marco Monteiro](http://twitter.com/marcogmonteiro) for inspiring me and helping test it.
 - [Dave Shoreman](http://twitter.com/codem0nk3y) Ninja contributor and basically rewrote all of Killswitch's crappy code. Like. A. Boss.