# SOAP SERVER and CLIENT example
SOAP WS (spring-boot-soap-service): https://howtodoinjava.com/spring/spring-boot/spring-boot-soap-webservice-example/
<br/>
SOAP CLIENT (spring-boot-soap-client): https://howtodoinjava.com/spring/spring-boot/spring-soap-client-webservicetemplate/

## Technology Stack
1. spring-boot-soap-service
	- JDK 1.8, Maven – Development environment
	- Spring-boot – Underlying application framework
	- wsdl4j – for publishing WSDL for our Service
	- SOAP-UI – for testing our service. Or write your own app from tutorial: https://howtodoinjava.com/spring/spring-boot/spring-soap-client-webservicetemplate/
	- JAXB maven plugin – for code generation
2. spring-boot-soap-client
	- JDK 1.8, Maven – Development environment
	- Spring-boot – Underlying application framework
	- maven-jaxb2-plugin plugin – for JAXB stub generation
	- Spring-boot Command Line Runner – To test the client code

## HOW TO RUN:
- run the web server first (nested project spring-boot-soap-service)
- run the client (nested project spring-boot-soap-client)
- observe the result of the communecation between two app (clients asks for info from the server)
```
Got Response As below ========= : 
Name : Sajal
Standard : 5
Address : Pune
```

## NOTES:
Please refer to the README.md files of the nested projects:
- spring-boot-soap-service
- spring-boot-soap-client
