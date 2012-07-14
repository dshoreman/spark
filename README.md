Spark
=====
This is a bash helper script to make working with Spark on CodeIgniter easier.

Install
------
To install just issue the following command to your /usr/local/bin or any other place that is part of your $PATH in your terminal:

    sudo wget https://github.com/killswitch/spark/raw/master/spark && sudo chmod a+x spark

Usage
------

You can use it to install Spark right into your CodeIgniter project by cding into your project, and typing:

    spark init

Usage is very similar to spark's original usage, except instead of the following:

    php tools/spark help

You would do:

    spark help
    
Commands haven't changed much other than install, remove and version.

To use install, you do the following:

    spark install example-spark 1.0.0

over:

    php tools/spark install -v1.0.0 example-spark

To remove a spark you'll just issue the following command to uninstall all versions of the package (who uses multiple anyway?):

    spark remove example-spark
    
Version does nothing different than the original, except it also tells you the version of this bash script.


Todo:
====
 - Add a way to find the latest spark version and use that when doing "spark install example-spark" that way you do not need to specify the version. (Why this doesn't already exist with spark is beyond me.)