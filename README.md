# Currency Conversion Microservice App

* Sleuth            : Tracking logs between services.
* Actuator          : Monitoring our app, gathering metrics, understanding traffic or refresh application.props, etc.
* Spring Cloud Bus  : Refresh each service application.properties using actuator and rabbitmq
* Git based config  : We can use different app.prop for different environment using active.profile
* Ribbon            : Eureka loadbalancer
* Zuul Gateway      : Netflix's gateway server name but we use spring cloud gateway
* Zipkin            : Distributed tracing service
* Hystrix           : Fault tolerance library
* Feign             : Rest client between services 
