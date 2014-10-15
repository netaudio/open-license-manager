![Build Status](https://travis-ci.org/open-license-manager/open-license-manager.png "Build Status"){float : left;}
# Open License Manager

A lincense manager written in C/C++ for Windows and Linux environments.

It allows to protect the software you develop from unauthorized copies,
limit the usage in time, to a specific set of machines, or prevent the usage in 
virtualized environments. It is an Open License Manager that helps to keep your 
software closed ;-)

The software is made by 2 main sub-components:
 * a C library with no (or minimal) external dependencies (the part you have to integrate in your software).
 * a license generator written in C++ (allows you to generate a license).
 
these modules are planned....
 * a license [backoffice](../../issues/7) in php (in order to handle multiple licenses).
 * a license debugger to be sent to the final customer when there are licensing problems. 
 * a [log decriptor](../../issues/8) in order to decrypt logs generated by the license system.

You can notice 2 more sub-projects:
 * bootstrap: allows to generate private keys and modify the library on the fly after the downloading.
 * testing  : runs the tests (and publish the results on cdash)
 
Licensing
=====================
The project comes out with a very large freedom of use for everyone (and it will always be). 
It uses a BSD 3 clauses licensing schema. 

Elsewhere on Internet
=====================
 * Wiki main page:
 * Install and build :
 * Project web site :
 