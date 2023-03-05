## HTTP STATUS CODE (English Version)

### 1xx Informational

> 100 Continue: The server has received the request headers and the client should proceed to send the request body.
 
> 101 Switching Protocols: The server is changing protocols according to the client's request.

### 2xx Success

> 200 OK: The request has succeeded.

> 201 Created: The request has been fulfilled and a new resource has been created.

> 202 Accepted: The request has been accepted for processing, but the processing has not been completed.

> 203 Non-Authoritative Information: The server is a transforming proxy that received a 200 OK response from the origin server and is returning a modified version of the response.

> 204 No Content: The server has fulfilled the request but there is no response body.

> 205 Reset Content: The server has fulfilled the request and the user agent should reset the document view which caused the request to be sent.

> 206 Partial Content: The server is delivering only part of the resource due to a range header sent by the client.

### 3xx Redirection

>300 Multiple Choices: The requested resource has multiple representations, each with its own specific location, and the user agent should select one.

>301 Moved Permanently: The requested resource has been assigned a new permanent URI and any future references to this resource should use one of the returned URIs.

>302 Found: The requested resource resides temporarily under a different URI.

>303 See Other: The response to the request can be found under a different URI and should be retrieved using a GET method.

>304 Not Modified: Indicates that the resource has not been modified since the version specified in the request headers If-Modified-Since or If-None-Match.

>307 Temporary Redirect: The requested resource resides temporarily under a different URI and the user agent should continue to use the original URI for future requests.

### 4xx Client Errors

> 400 Bad Request: The request could not be understood by the server due to malformed syntax.

> 401 Unauthorized: The request requires user authentication.

> 402 Payment Required: This code is reserved for future use.

> 403 Forbidden: The server understood the request but refuses to authorize it.

> 404 Not Found: The server could not find the requested resource.

> 405 Method Not Allowed: The method specified in the request is not allowed for the resource identified by the URI.

> 406 Not Acceptable: The resource identified by the request is only capable of generating response entities that have content characteristics not acceptable according to the accept headers sent in the request.

> 407 Proxy Authentication Required: The client must first authenticate itself with the proxy.

> 408 Request Timeout: The server timed out waiting for the request.

> 409 Conflict: The request could not be completed due to a conflict with the current state of the resource.

> 410 Gone: The requested resource is no longer available and will not be available again.

> 411 Length Required: The server refuses to accept the request without a defined Content-Length.

> 412 Precondition Failed: The precondition given in the request evaluated to false by the server.

> 413 Payload Too Large: The server will not accept the request because the payload is too large.

> 414 URI Too Long: The server will not accept the request because the URI is too long.

> 415 Unsupported Media Type: The server will not accept the request because the payload format is in an unsupported format for the resource.

> 416 Range Not Satisfiable: The requested range cannot be satisfied.

> 417 Expectation Failed: The expectation given in an Expect request-header field could not be met by this server.

> 418 I'm a teapot: This code is defined in the HTTP/1.1 protocol and is intended to be humorous.

> 421 Misdirected Request: The server was not able to produce a response to the request because the client has sent the request to a server that is not able to produce a response.

> 422 Unprocessable Entity: The server understands the content type of the request entity and the syntax of the request entity is correct but was unable to process the contained instructions.

> 423 Locked: The resource that is being accessed is locked.

> 424 Failed Dependency: The request failed because of a failure of a previous request.

> 426 Upgrade Required: The client should switch to a different protocol.

> 428 Precondition Required: The server requires the request to be conditional.

> 429 Too Many Requests: The user has sent too many requests in a given amount of time.

> 431 Request Header Fields Too Large: The server is unwilling to process the request because either an individual header field, or all the header fields collectively, are too large.

> 451 Unavailable For Legal Reasons: The server is denying access to the resource as a consequence of a legal demand.

### 5xx Server Errors

> 500 Internal Server Error: The server encountered an unexpected condition that prevented it from fulfilling the request.

> 501 Not Implemented: The server does not support the functionality required to fulfill the request.

> 502 Bad Gateway: The server, while acting as a gateway or proxy, received an invalid response from an upstream server it accessed to fulfill the request.

> 503 Service Unavailable: The server is currently unable to handle the request due to a temporary overload or maintenance of the server.

> 504 Gateway Timeout: The server, while acting as a gateway or proxy, did not receive a timely response from an upstream server it accessed to fulfill the request.

> 505 HTTP Version Not Supported: The server does not support the HTTP protocol version used in the request.

> 506 Variant Also Negotiates: The server has an internal configuration error.

> 507 Insufficient Storage: The server is unable to store the representation needed to complete the request.

> 508 Loop Detected: The server detected an infinite loop while processing the request.

> 510 Not Extended: The server requires an extension to fulfill the request.

> 511 Network Authentication Required: The client needs to authenticate to gain network access.