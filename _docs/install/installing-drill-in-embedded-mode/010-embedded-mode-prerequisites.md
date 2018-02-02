# Embedded Mode Prerequisites
To use Drill on a single node, install Drill in embedded mode. Installing Drill in embedded mode installs Drill locally on your machine. Embedded mode is a quick way to install and try Drill without having to perform any configuration tasks. A ZooKeeper installation is not required. Installing Drill in embedded mode configures the local Drillbit service to start automatically when you launch the Drill shell. You can install Drill in embedded mode on a machine running Linux, Mac OS X, or Windows.

Before you install Drill, ensure that the machine meets the following prerequisites:

* Linux, Mac OS X, and Windows: Oracle JDK [version 7](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html) or [version 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) if running Drill 1.6 or later.  
* Windows only:  
  * A JAVA_HOME environment variable that points to the JDK installation  
  * A PATH environment variable that includes a pointer to the JDK installation  
  * A utility for unzipping a tar.gz file 

Follow installation instructions in this documentation for your particular operating system.
