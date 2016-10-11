# Spring Boot Starter for Prometheus

This is an unofficial spring-boot-starter for the [Prometheus](https://prometheus.io/)
monitoring system.

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
    <version>0.0.1-SNAPSHOT</version>
</dependency>
```

# Configuration
The following properties can be configured:
```
# the metrics path to be pulled by prometheus defaults to '/prometheus' 
prometheus.metrics.path=/prometheus
```

