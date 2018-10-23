---
title: "Connect a Data Source Introduction"
date: 2018-10-23
parent: "Connect a Data Source"
---
A storage plugin is a software module for connecting Drill to data sources. A storage plugin typically optimizes execution of Drill queries, provides the location of the data, and configures the workspace and file formats for reading data. Several storage plugins are installed with Drill that you can configure to suit your environment. Through a storage plugin, Drill connects to a data source, such as a database, a file on a local or distributed file system, or a Hive metastore. 

You can modify the default configuration X of a storage plugin and give the new configuration a unique name Y. This document refers to Y as a different storage plugin, although it is actually just a reconfiguration of original interface. When you execute a query, Drill gets the storage plugin configuration name in one of several ways:

* The FROM clause of the query can identify the plugin to use.
* The USE <plugin name> command can precede the query.
* You can specify the storage plugin when starting Drill.

## Storage Plugin Internals
The following image represents the storage plugin layer between Drill and a
data source:

![drill query flow]({{ site.baseurl }}/docs/img/storageplugin.png)

In addition to the previously mentioned functions, a storage plugin performs scanner and writer functions and informs the execution engine of any native capabilities, such
as predicate pushdown, joins, and SQL.
