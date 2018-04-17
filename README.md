# lmvc-example
Model-View-Controller Framework Example

Prerequisites
-------------
* Java JDK 1.9 or greater
http://www.oracle.com/technetwork/java/javase/downloads/index.html

* LMVC
https://github.com/skavanagh/lmvc

Build and Run 
------
Export environment variables

    export JAVA_HOME=/path/to/jdk
    export M2_HOME=/path/to/maven
    export PATH=$JAVA_HOME/bin:$M2_HOME/bin:$PATH

In the directory that contains the pom.xml run

        mvn clean package jetty:run
