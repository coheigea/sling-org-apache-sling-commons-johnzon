[![Apache Sling](https://sling.apache.org/res/logos/sling.png)](https://sling.apache.org)

&#32;[![Build Status](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-commons-johnzon/job/master/badge/icon)](https://ci-builds.apache.org/job/Sling/job/modules/job/sling-org-apache-sling-commons-johnzon/job/master/)&#32;[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-commons-johnzon&metric=coverage)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-johnzon)&#32;[![Sonarcloud Status](https://sonarcloud.io/api/project_badges/measure?project=apache_sling-org-apache-sling-commons-johnzon&metric=alert_status)](https://sonarcloud.io/dashboard?id=apache_sling-org-apache-sling-commons-johnzon)&#32;[![JavaDoc](https://www.javadoc.io/badge/org.apache.sling/org.apache.sling.commons.johnzon.svg)](https://www.javadoc.io/doc/org.apache.sling/org.apache.sling.commons.johnzon)&#32;[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.sling/org.apache.sling.commons.johnzon/badge.svg)](https://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.apache.sling%22%20a%3A%22org.apache.sling.commons.johnzon%22) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

# Apache Sling Commons Johnzon Wrapper Library

This module is part of the [Apache Sling](https://sling.apache.org) project.

[Apache Johnzon](https://johnzon.apache.org/) powered javax.json library.

This wrapper allows to use [JSON-P 1.1](https://jcp.org/aboutJava/communityprocess/pr/jsr374/index.html) with Apache Johnzon in an OSGi container without requiring an OSGi ServiceLoader Mediator implementation like [SPI Fly](https://aries.apache.org/modules/spi-fly.html) by overwriting the [JSONProvider](https://github.com/apache/sling-org-apache-sling-commons-johnzon/blob/master/src/main/java/javax/json/spi/JsonProvider.java) to always load Apache Johnzon and not relying on the Service Loader.

See also [JOHNZON-108](https://issues.apache.org/jira/browse/JOHNZON-108) and [GERONIMO-6640](https://issues.apache.org/jira/browse/GERONIMO-6560).
