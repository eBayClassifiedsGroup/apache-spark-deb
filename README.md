# Apache Spark packaged for debian

This is a minimal wrapping around the .tar.gz files distributed from spark.

It installs spark into /usr/share/spark.

Maven downloads the .tar.gz from the network each time the build is run.  So run
it once and then add the .deb to your debian repo.

The only other files are src/deb/control which is required for jdeb.
