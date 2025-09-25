The Maven Wrapper consists of scripts (mvnw, mvnw.cmd), a properties file
(.mvn/wrapper/maven-wrapper.properties) that points to the Maven distribution,
and a small jar (.mvn/wrapper/maven-wrapper.jar) that bootstraps the wrapper.

This repository includes scripts and the properties file. The binary
.mvn/wrapper/maven-wrapper.jar is not included and must be generated locally
or downloaded from a trusted source. To generate it, run:

    mvn -N io.takari:maven:wrapper

or, if you have the wrapper jar already, place it at
.mvn/wrapper/maven-wrapper.jar
