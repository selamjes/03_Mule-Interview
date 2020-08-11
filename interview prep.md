1. mulesoft?
mule soft provides integration platform, its light weight but highly scalable. also its Java based. Mule enables the reuse of component

2. ESB? Mule ESB is a Java-based enterprise service bus (ESB) and integration platform,developer can connect their application with ESB
Apart from of the different technologies the applications use, including JMS, Web Services, SMTP, HTTP
RAML? -stands for restful api modeling launguage and for discribe your API. its yaml based. it can be easily readable by human and computer.
it containes end point url,request/response,http methods, query & uri parameters. -raml can also used for documentation purpose -it help for the client to know (a consumer of service) know what the service is and what how all operations can be invoked.
trait? it used to define commen attributs for http method which is get, post, put, delete

dataType?

allow the user to define objects and reuse them at any level in a RAML file.
security scheme -security that would be used to secure the api and it its method.

resourceType -It basically focuses on describing your API resources, methods, parameters, media type etc.

Error handling Mule 4 error handling framework directly handles the exception errorhandling types

mule default
application level
global error handling
flow level
error handling mechanisms 1. error continue - On-Error Continue catches the error and does not report it as an error 2. error propagate - On-Error Propagate processes the error message and re-throws the error to its parent flow 3. try catch scope - we can put our component in the try block.
Munit
MUnit is a Mule Application Testing Framework to test our flows. authomated test and inte
Domian
implemented to configure the resources that are shared among different projects.
Domain Project is used to create shared resources, which can reuse across other projects who are referring to domain projects
API
(Application Programming Interface)which is a software intermediary that allows two applications to talk to each other. that help to communicate server side and client side.
API led conectivity
It is an approach for connecting and exposing assets through reusable and purposeful APIs. three types of API. system API, Process API Experience API. -Drive outcomes with Api led connectivity . on time and within budget . drives rules vs build . designs in readiness for change . builds in governance, compliance, security and scalability . meets the needs of your business
C4E center for enablement.(central IT, LOB, Developers) C4E is a cross functional team. C4E ENSURES that assets are - - productized and published

consumable
consumed broadly
fully leveraged . Success of C4E measured on assets consumption
An API proxy is an application that controls access to a web service, restricting access and usage through the use of an API gateway

The API Gateway is a runtime designed and optimized to host an API or to open a connection to an API deployed to another runtime

types of flow

flow both synchronous and a synchronous, with resource, it has error handling
sub flow:is always synchronous, no error handling
a synchronous flow: same as subflow the only differece
private flow
DataWeave
DataWeave is a MuleSoft tool for accessing and transforming data.
tramsformer
A transformer takes care of translating the content of a message from one form to another
are simple objects that convert the current message from one type to another.
API life cycle:
Router in Mule -Routers (Flow Controls in Anypoint Studio)

Api kit router based on our raml and based on resource and method trigger our flows

Endpoint in Mule An endpoint is a flow-level element that is configured to receive and/or send messages from and/or to external resources.

scatter Gather -is a routing message processor in Mule ESB runtime that sends a request message to multiple targets concurrently.

choice if/else condition

secure Properties

RESTful it is a Web Services. standard http method. stateless cachable http method

SOAP Web Service?
SOAP stands for Simple Object Access Protocol. It is XML-based protocol for accessing web services.
SOAP web services can be written in any programming language and executed in any platform.
WSDL dependent: SOAP uses WSDL and doesn’t have any other mechanism to discover the service.
What is the difference between SOAP and REST? SOAP -> REST

SOAP is a protocol. -> REST is an architectural style.
SOAP stands for Simple Object Access Protocol. -> REST stands for REpresentational State Transfer.
SOAP can’t use REST because it is a protocol. -> REST can use SOAP web services because it is a concept and can use any protocol like HTTP, SOAP
webservice is allows two software system to exchange data over the internet
Batch
Batch processing is a technique for automating and processing multiple transactions as a single group. Batch processing helps in handling tasks like payroll, end-of-month reconciliation, or settling trades overnight.
Batch jobs split large messages into records which Mule processes asynchronously,just as flows process messages, batch jobs process records.
File
Email
data base configuraton salesforce
caching
mule event is nithing a logical a. message - payload - body - attributes - header b. variable

dependencies