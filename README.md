Currency Conversion Service leverages the Spring Registration and Discovery in order to introduce service discovery using [Netflix - Eureka library](https://github.com/spring-cloud/spring-cloud-netflix).

## High Level Diagram
Below is a high level on how the services will be registered to the naming-server.

![High Level Diagram](./docs/diagrams/ConversionService.png)

### Server URL
This service will run under 8100 port: http://localhost:8100

### Consuming the API
http://localhost:8100/currency-conversion-feign/from/USD/to/INR/quantity/1000
