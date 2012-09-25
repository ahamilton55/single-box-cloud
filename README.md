Single Box Cloud
================

This script will convert a CentOS-6/x86_64 machine into a complete
cloud, including Compute Note management, backing store and network
profiles. 


Assumptions
-----------

* This script expects to ve run on a machine that only has one ethernet device installed and working, and no bridges currently setup

* Expect the machine to have been installed with the CentOS-6 minimal install profile ( either from the CentOS-6/x86_64 dvd1 installer or from the CentOS-6 minimal install iso )

* The script will turn off SELinux

* System hardware requirements : 
 1. kvm enabled, kvm modules loaded
 1. 8 GB or more of RAM
 1. 50 GB or more of disk space in the root (/) mount point

Notes
-----

* This script will download approximately 346 MBytes of data over the internet
* There are no OS images included
