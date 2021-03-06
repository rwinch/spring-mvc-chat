
### Overview

A chat sample using Spring MVC 3.2, Servlet-based, async request processing.

### Note

There is a bug that affects Tomcat 7.0.29 (see [Bug 53623](https://issues.apache.org/bugzilla/show_bug.cgi?id=53623). To use Tomcat to run the sample you will need Tomcat 7.0.30 or a nightly 7.0.x snapshot (not yet available at the time of writing).

### Instructions

To start the sample run `mvn tomcat7:run` and then access it at [http://localhost:8080/spring-mvc-chat](http://localhost:8080/spring-mvc-chat).

Eclipse users run `mvn eclipse:eclipse` and then import the project. Or just import the code as a Maven project into IntelliJ, NetBeans, or Eclipse.

Also see the [redis](https://github.com/rstoyanchev/spring-mvc-chat/tree/redis) branch for a distributed chat with persistence and pub-sub notifications via [Redis](http://redis.io) instance. 
