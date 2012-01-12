Spring Portlet MVC
==================

A minimal Spring Portlet MVC project.

* Java 1.6
* Portlet 2.0
* Spring Framework 3.1
* Annotation-based controller configuration

Usage
-----
```bash
$ git clone http://github.com/miamidade/spring-portlet-mvc.git
$ cd spring-portlet-mvc
$ mvn package
```

Deploy
------
Portlet deployment varies depending on which portal you're using.

If you're using Liferay Portal with Tomcat, just copy the war to the deploy directory.

```
$ cp target/spring-portlet-mvc.war $LIFERAY_HOME/deploy/
```

Configuration
-------------

Default settings are Java 1.6, Portlet 2.0, and Spring 3.1.  All can be configured in [pom.xml](https://github.com/miamidade/spring-portlet-mvc/blob/master/pom.xml)

```xml
<properties>
    <java-version>1.6</java-version>
    <portlet-api.version>2.0</portlet-api.version>
    <servlet-api.version>2.5</servlet-api.version>
    <jsp-api.version>2.1</jsp-api.version>
    <jstl.version>1.2</jstl.version>
    <org.springframework-version>3.1.0.RELEASE</org.springframework-version>
    <org.aspectj-version>1.6.9</org.aspectj-version>
    <org.slf4j-version>1.5.10</org.slf4j-version>
</properties>
```


License
-------

Copyright 2012 Miami-Dade County

Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
