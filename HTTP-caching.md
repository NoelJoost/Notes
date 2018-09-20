HTTP Caching

Cache processing

* Receive request message.
* Parse the URL and headers.
* Lookup a local copy; otherwise, fetch and store locally
* Do a freshness check to determine the age of the content in the cache; make a request to refresh the content only if necessary.
* Create the response from the cached body and updated headers.
* Send the response back to client.
* Optionally, log the transaction.

Server Revalidation:
Cached document expires, cache must revalidate  documents.

