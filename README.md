Spark
=====
This is a bash helper script to make working with Spark on CodeIgniter easier.

Install
------
To install just wget the raw file from this repo into your /usr/local/bin or any other place that is part of your $PATH. Then issue the following command in your terminal:

    chmod u+x spark.

Usage
------

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