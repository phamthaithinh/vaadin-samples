Vaadin Samples
=======================

## Spring Vaadin Integration
Sample project for SpringVaadinIntegration add-on. http://vaadin.com/addon/springvaadinintegration

~~~~
git clone git://github.com/xpoft/vaadin-samples.git vaadin-samples
cd spring-integration
mvn jetty:run
~~~~

Then open http://localhost:9090/


## Spring Security

~~~~
git clone git://github.com/xpoft/vaadin-samples.git vaadin-samples
cd spring-security
mvn jetty:run
~~~~

Then open http://localhost:9090/

## Apache Shiro

~~~~
git clone git://github.com/xpoft/vaadin-samples.git vaadin-samples
cd apache-shiro
mvn jetty:run
~~~~

Then open http://localhost:9090/

## Changes

### Vaadin beta10
#### Spring Security & Apache Shiro
Added ErrorHandler instead of Terminal.
Now you can't customize error page. Exception on UI action is more ugly.