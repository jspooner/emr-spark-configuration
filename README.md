# emr-spark-configuration

Common configuration for Spark and Zeppelin on Amazon EMR


## FoxProxy

If you just goto Chrome extensions and search for it there you can still install the free version.


# Running on localhost

### Add Packages to Spark Defaults



    vim /usr/local/Cellar/apache-spark/2.0.1/libexec/conf/spark-defaults.conf

    spark.jars.packages org.elasticsearch:elasticsearch-spark-20_2.11:5.1.1

## Running Zeppelin on localhost

       export SPARK_SUBMIT_OPTIONS="--packages org.elasticsearch:elasticsearch-spark-20_2.10:5.0.0"
