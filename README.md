remote-maven-plugin
======================

Just drop in this plugin into your existing Maven project and start running your projects on a remote location.

Requirements
----------

* a server with Maven installed
* a client with Maven installed


How does it work
----------

You add the plugin definition to your pom.xml file and then run the plugin goal. This triggers the process of transfering your project to the remote location and then executing the Maven goals on the remote location.
The idea is to connect to the server with SSH and run the Maven command there. Transfering files should be made incrementally and just sending the changes to save bandwith and time.


Why
---------

* Tired of your laptop getting hot and fans spinning up to max? Then get a server at a distant location that doesnt bother you to run your compilations on.
* The server can be shared so several developers can benefit from same hardware and increase server utilization.
* The entire team will use the same JDK and Maven version, no more missmatch.
* Run server on Linux and have access to all the JDK builds while running the client on a Mac.
* Upgrade server and all developers builds are upgraded aswell.
* Possible to use cheaper, lighter and not so powerful client hardware. Code on a Asus Eee Pc, Macbook Air or suits you.


Project status
---------

Just spawned this idea so there is some work to do :)