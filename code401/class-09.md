# HTTP overview

A URL is used by the DNS system to look up the IP address of a resource. If the resource's address is successfully located on a DNS server, it is returned to the client. If the connection is over TCP, the handshake process initiates the connection and when successful, the client can then make a request either providing data or asking for it from the server.

# Java HTTP requests

Java has built-in support for making HTTP requests in the `java.net` package. It exposes an `HTTPURLConnection` class that allows the user to build a request and send it to the server. Response are done using streams. There is a newer, simpler interface provided by the `HTTPClient` package, however. 