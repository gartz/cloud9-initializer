cloud9-initializer
==================

A shell script to start Cloud9 in a folder using that folder as it work directory, very easy and useful for Cloud9 personal compilations.


Requirements
------------

* Cloud9 local installed.
* RunJS local installed.
* run.js shell script in the bin folder from Cloud9.


Install
-------

1. Add the cloud9 shell script file to the `bin` folder.
2. Add the execution permission for the `cloud9` using `chmod +x cloud9`
3. Add the path for the bin folder to your export paths.


How to use
----------

Go to your project folder, type `cloud9` then it will open your cloud9 in the default port 3131.

If you put a port after type cloud9 it will open in the designed port, like `cloud9 8080` will open on port 8080.


Tips
----

* [Local install for Cloud9 tutorial (PT-BR)](http://gartz.com.br/instalando-cloud9-local-com-suporte-a-runjs-no-linux/)
