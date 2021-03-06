# Eureka! Clinical Patient Set Client
[Atlanta Clinical and Translational Science Institute (ACTSI)](http://www.actsi.org), [Emory University](http://www.emory.edu), Atlanta, GA

## What does it do?
It is a library for accessing an implementation of Eureka! Clinical's RESTful APIs for patient set management from Java applications. It provides two REST API clients:

* EurekaClinicalPatientSetClient.java: for web clients to call a patient set service's REST APIs via a Eureka! Clinical proxy.
* EurekaClinicalPatientSetProxyClient.java: for Java applications to call a patient set service's REST APIs directly.

Latest release: [![Latest release](https://maven-badges.herokuapp.com/maven-central/org.eurekaclinical/eurekaclinical-patient-set-client/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.eurekaclinical//eurekaclinical-patient-set-client)

## Version 2.0
Updated dependencies.

## Version 1.1
Updated dependencies.

## Version 1.0
Initial release.

## Build requirements
* [Oracle Java JDK 8](http://www.oracle.com/technetwork/java/javase/overview/index.html)
* [Maven 3.2.5 or greater](https://maven.apache.org)

## Runtime requirements
* [Oracle Java JRE 8](http://www.oracle.com/technetwork/java/javase/overview/index.html)

## Building it
The project uses the maven build tool. Typically, you build it by invoking `mvn clean install` at the command line. For simple file changes, not additions or deletions, you can usually use `mvn install`. See https://github.com/eurekaclinical/dev-wiki/wiki/Building-Eureka!-Clinical-projects for more details.

## Maven dependency
```
<dependency>
    <groupId>org.eurekaclinical</groupId>
    <artifactId>eurekaclinical-patient-set-client</artifactId>
    <version>version</version>
</dependency>
```

## Developer documentation
* [Javadoc for latest development release](http://javadoc.io/doc/org.eurekaclinical/eurekaclinical-patient-set-client) [![Javadocs](http://javadoc.io/badge/org.eurekaclinical/eurekaclinical-patient-set-client.svg)](http://javadoc.io/doc/org.eurekaclinical/eurekaclinical-patient-set-client)

## Getting help
Feel free to contact us at help@eurekaclinical.org.
