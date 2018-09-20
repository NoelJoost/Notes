# Identification and Authentication

* Request headers: From, Referer, User-Agent
* Client-IP - the IP address of the client
* Fat Urls - storing state of the current user by modifying the URL and redirecting to a different URL on each click; each click essentially accumulates state.
* Cookies - the most popular and non-intrusive approach

Cookies contains one or more name=value pairs separated by ;

Basic Authentication = username/password
-> sent in a base-64 encoded format

Digest Authentication = username/password
-> sent in a more secure hashing function