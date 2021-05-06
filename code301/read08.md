# What does REST stand for?
REST or RESTful API design (Representational State Transfer) is designed to take advantage of existing protocols. While REST can be used over nearly any protocol, it usually takes advantage of HTTP when used for Web APIs.

# REST APIs are designed around
REST APIs are designed around resources, which are any kind of object, data, or service that can be accessed by the client. REST APIs use a uniform interface, which helps to decouple the client and service implementations.
![img](https://api.zestard.com/wp-content/uploads/2015/12/What-is-Rest-API-02-1.jpg)


# What are the most common HTTP verbs
The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

#
In RESTful HTTP the client should never construct URIs. The service should be well-connected, which means that the client should only ever follow URIs given by the server and make requests to those URIs.
# What status code does a successful GET request return?

The resource has been fetched and is transmitted in the message body.
A successful GET method typically returns HTTP status code 200 (OK). If the resource cannot be found, the method should return 404 (Not Found).
# What status code does a successful POST request retur
it returns HTTP status code 201 (Created), as with a POST method. If the method updates an existing resource, it returns either 200 (OK) or 204 (No Content).
![img](https://www.abbreviations.com/images/47386_204.png)

# References and Resorces 
* M, S., A., J., A., Shah, K., & A. (2020, December 22). HTTP Status 200 (OK). REST API Tutorial.[status link] (https://restfulapi.net/http-status-200-ok/#:%7E:text=The%20HTTP%20Status%20200%20)(OK,which%20was%20selected%20for%20request.