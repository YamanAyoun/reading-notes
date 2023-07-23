# Navigation Properties and Routing
## What is Routing?
Routing in web applications is the process of matching incoming HTTP requests to specific executable code blocks called endpoints. 
Endpoints are units of request-handling logic defined in the application. When a request arrives, 
routing matches it to the appropriate endpoint and allows the request to be processed accordingly. 

To achieve this, routing is registered in the application's middleware pipeline during the startup process. It uses a pair of middleware:

## Using the Default Route Table
When you generate a fresh ASP.NET MVC application, it comes pre-configured to utilize ASP.NET Routing. This setup involves two key steps:

1. Firstly, ASP.NET Routing is enabled in the Web.config file of your application.

2. Secondly, and of significant importance, a route table is established within the Global.asax file of the application. 
The Global.asax file is a special file housing event handlers for various lifecycle events in the ASP.NET application. 

## UseRouting and UseEndpoints. 

* `UseRouting` enables route matching by analyzing the defined endpoints and finding the best match for the incoming request. On the other hand.

* `UseEndpoints` allows for the execution of the delegate associated with the selected endpoint.

## Endpoint
Each endpoint consists of a delegate that handles the request and additional metadata that can be used to implement cross-cutting concerns based on policies and configurations attached to that endpoint.

## URL matching
The process of URL matching is fundamental to routing. It involves comparing the URL path and headers of the incoming request with the defined endpoints to find the most suitable match. 
This process can be extended to consider other data in the request as well.

