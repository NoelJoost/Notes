#HTTP - Hypertext Transfer Protocol

stateless, application-layer protocol for communicating between distributed systems

Communication over TCP/IP
Default Port is 80
Uniform Resource Locators (URLs)


GET: fetch an existing resource
POST: create an existing resource
PUT: update an existing resource
DELETE: delete an existing resource

HEAD: GET without Body
TRACE: Trace back information
OPTIONS: 

HTTPS - additional Layer between HTTP and TCP called SSL
HTTPS - default Port 443

SSL uses RSA and public.key cryptography.

####Certificates
Certificates are needed for HTTPS
They contain:
* the certificate issuer
* the algorithm used for the certificate
* the subject name or organization for whom this cert is created
* the public key information for the subject
* the Certification Authority Signature, using the specified signing algorithm
Client compares Certificate from website with list of known CAs. If CA is unknown a warning will show up.

####Request:
* resolve IP address from host name via DNS
* establish a connection with the server
* send a request
* wait for a response
* close connection


####Response:
* establishing a socket to start listening on port 80 (or some other port)
* receiving the request and parsing the message
* processing the response
* setting response headers
* sending the response to the client
* close the connection if a Connection: close request header was found