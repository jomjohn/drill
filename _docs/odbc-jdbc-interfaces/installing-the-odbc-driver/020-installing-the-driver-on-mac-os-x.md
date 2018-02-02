# Installing the Driver on Mac OS X
Install the Drill ODBC Driver on the machine from which you connect to
the Drill service.

Install the Drill ODBC Driver on a system that meets the [system requirements]({{site.baseurl}}/docs/installing-the-driver-on-mac-os-x/#system-requirements). Complete the following steps, described in detail in this document:

  * [Step 1: Download the Drill ODBC Driver]({{site.baseurl}}/docs/installing-the-driver-on-mac-os-x/#step-1-download-the-drill-odbc-driver)  
  * [Step 2: Install the Drill ODBC Driver]({{site.baseurl}}/docs/installing-the-driver-on-mac-os-x/#step-2:-install-the-drill-odbc-driver) 
  * [Step 3: Check the Drill ODBC Driver Version]({{site.baseurl}}/docs/installing-the-driver-on-mac-os-x/#step-3:-check-the-drill-odbc-driver-version)   


## System Requirements  
To install the driver, you need Administrator privileges on the computer.

  * Mac OS X version 10.9, 10.10, or 10.11  
  * 100 MB of available disk space  
  * iODBC 3.52.7 or later  
    The iodbc-config file in the `/usr/local/iODBC/bin` includes the version of the driver.  
  * The client must be able to resolve the actual host name of the Drill node or nodes from the IP address. Verify that a DNS entry was created on the client machine for the Drill node or nodes. If not, create an entry in `/etc/hosts` for each node in the following format:  `<drill-machine-IP> <drill-machine-hostname>`. 
    
	Example: `127.0.0.1 localhost`


## Step 1: Download the Drill ODBC Driver  

To download ODBC drivers that support both 32- and 64-bit client applications, click 
[Drill ODBC Driver for Mac](http://package.mapr.com/tools/MapR-ODBC/MapR_Drill/).


## Step 2: Install the Drill ODBC Driver

To install the driver, complete the following steps:

  1. Double-click `MapR Drill 1.3.dmg` to mount the disk image.
  2. Double-click `MapRDrillODBC.pkg` to run the Installer.
  3. Follow the instructions in the Installer to complete the installation process.
  4. When the installation completes, click **Close.**


Drill ODBC Driver files install in the following locations:

  * `/Library/mapr/drill/ErrorMessages` – Error messages files directory
  * `/Library/mapr/drill/Setup` – Sample configuration files directory
  * `/Library/mapr/drill/lib` – Binaries directory

## Step 3: Check the Drill ODBC Driver Version

To check the version of the driver you installed, use the following command on the terminal command line:

    $ pkgutil --pkg-info mapr.drillodbc  

    package-id: mapr.drillodbc
    version: 1.3.8 (You may see 3.52.12.)
    volume: /
    location: 
    install-time: 1433465518  
To display information about the iODBC driver manager installed on the machine, issue the following command:  

    /usr/local/iODBC/bin/iodbc-config

### Next Step

[Configuring ODBC on Mac OS X]({{ site.baseurl }}/docs/configuring-odbc-on-mac-os-x/).