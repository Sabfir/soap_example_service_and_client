# SOAP CLIENT
https://howtodoinjava.com/spring/spring-boot/spring-soap-client-webservicetemplate/
<br/>
<br/>
NOTES:
- Before running this example, we need one SOAP service ready which we will invoke from this client code. For this, you may download the attached maven project (at end of article) and run that in Local and use that.
- As a SOAP WEB SERVICE use this soap service: https://howtodoinjava.com/spring/spring-boot/spring-boot-soap-webservice-example/
- Once you run this SOAP server project, you will get the WSDL from http://localhost:8080/service/studentDetailsWsdl.wsdl. Download the WSDL somewhere as studentDetailsWsdl.wsdl and later we will place this in resources/wsdl folder of the client project which we will create next to generate the client proxy code.

## Technology Stack
- JDK 1.8, Maven – Development environment
- Spring-boot – Underlying application framework
- wsdl4j – for publishing WSDL for our Service
- SOAP-UI – for testing our service. Or write your own app from tutorial: https://howtodoinjava.com/spring/spring-boot/spring-soap-client-webservicetemplate/
- JAXB maven plugin – for code generation
