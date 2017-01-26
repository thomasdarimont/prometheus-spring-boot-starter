# Spring Boot Starter for Prometheus

This is an unofficial spring-boot-starter for the [Prometheus](https://prometheus.io/)
monitoring system.

## Example Project
The [spring-boot-starter-prometheus-example](https://github.com/thomasdarimont/spring-boot-starter-prometheus-example) shows 
an example for using the `prometheus-spring-boot-starter`. 

An example for setting up prometheus can be found in the 
[spring-boot-prometheus-example](https://github.com/thomasdarimont/spring-boot-prometheus-example) repository.

##  Build
```
mvn clean install
```

## Usage
Just add the following dependency to your spring-boot-project.

```
<dependency>
    <groupId>de.tdlabs</groupId>
    <artifactId>prometheus-spring-boot-starter</artifactId>
    <version>0.0.2-SNAPSHOT</version>
</dependency>
```

# Configuration
The following properties can be configured:
```
# the metrics path to be pulled by prometheus defaults to '/prometheus' 
prometheus.metrics.path=/prometheus
```

