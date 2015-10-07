pvEaxampleTestCPP
============

This project provides:

* An EPICS IOC that has both EPICS V3 DBRecords, V4 PVRecords, and pvaSrv for accessing the DBRecords.
* PvaClient examples.
* A test that can be run via "make runtests"

The EPICS IOC is also available for running the examples in pvaClientCPP and pvaClientJava.

Building
--------

If a proper RELEASE.local file exists one directory level above pvExampleTestCPP
then just type:

    make

If RELEASE.local does not exist then look at <b>configure/RELEASE</b>
for directions for how to build.

To run the test
---------------

make runtests

To start the database
------------

    mrk> pwd
    mrk> ../../bin/linux-x86_64/exampleDatabase st.cmd 

Status
------

* Readyfor release 4.5.0


