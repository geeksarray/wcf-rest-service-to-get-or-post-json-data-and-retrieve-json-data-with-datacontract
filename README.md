# WCF REST service to GET or POST JSON data and retrieve JSON data with DataContract

In this article I will talk about creating WCF RESTful services for CRUD operations which uses JSON and DataContracts. CRUD operations are done by http verbs GET, POST, PUT and DELETE

## Introduction to REST
REST stands for Representational State Transfer. It provides you an architectural principles about how client and service can exchange the resources over http. REST services can be accessed by any language which support http communication and help truly to heterogeneous applications.

## Introduction to JSON
JSON stands for JavaScript Object Notation. It is lightweight data exchange format. It does not create lengthy tags like XML and produce human readable clean data. JSON is completely language independent. It gives you a collection of Name/value pair. 

## Applications

1. **[RESTful WCF service](https://github.com/geeksarray/wcf-rest-service-to-get-or-post-json-data-and-retrieve-json-data-with-datacontract/tree/master/RESTFulWCFService/RESTFulWCFService)** - having Product and Order WCF services and exposed with webHttpBinding

1. **[Client for WCF REST service](https://github.com/geeksarray/wcf-rest-service-to-get-or-post-json-data-and-retrieve-json-data-with-datacontract/tree/master/RESTFulWCFService/DotnetmentorsClient)** - console application as client for Order WCF RESTful service that consumes OrderService using webHttpBinding


![WCF RESTful Service](http://dotnetmentors.com/Images/OrderServiceREST.png)

For more detailed steps visit - https://geeksarray.com/blog/wcf-rest-service-to-get-or-post-json-data-and-retrieve-json-data-with-datacontract

