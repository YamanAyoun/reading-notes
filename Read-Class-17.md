# Testing and Swagger and Deployment

## Swagger
It is a language-agnostic specification for describing REST APIs. Swagger allows you to describe the structure of your APIs so that machines can read them. 
It provides a standard way to document and define the structure of APIs, making it easier for developers to understand and interact with the APIs.

## OpenAPI
OpenAPI is the evolution of Swagger. It is a specification for documenting and defining RESTful APIs, formerly known as the Swagger Specification. 
OpenAPI continues to provide the same features and capabilities as Swagger, but with a broader and more inclusive community of contributors.
The document is based on the XML and attribute annotations within the controllers and models.

## Testing
Three different types of unit tests for the controllers in ASP.NET MVC applications:

* Test the view returned by a controller action.
* Test the View Data returned by a controller action.
* Test whether or not one controller action redirects you to a second controller action.

## Unit tests of controller logic
Unit tests focus on testing the logic of a controller action in isolation from its dependencies and the underlying infrastructure, like databases or external services. They rely on mock objects or test doubles to simulate dependencies and provide controlled responses during testing.
