---
visibility: public
---
Possible Arrangement API Problems
=================

To learn more see general guidance on [error handling](common-getstarted.html#error-handling).
Range of problem codes for this API is `55000-55199`.

Common problems
---------------

First 50 codes in a range `55000-55049` are reserved for situations described by standard http status codes.

Literal |  Code | Description                                          
------------------------------------ | -----:| ---------------------------------------------------  
bad-request                      | 55000 | Request is not valid. Field {field:} failed following validation {error:}
forbidden                        | 55001 | User is not authorized to access resource or perform such a command on a resource
not-found                        | 55002 | Requested resource could not be found
gone                             | 55003 | Requested resource is no longer available
internal-error                   | 55004 | Unexpected error condition has occurred
not-implemented                  | 55005 | Service does not currently implement the operation, or it lacks the capability to fulfil the request. This implies possible future implementation
service-unavailable              | 55006 | Service is currently unavailable (because it is overloaded or down for maintenance). This is a temporary state
