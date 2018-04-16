# Client-Server-Architecture
Understanding Client-Server Relationships:



Clients characteristics:

* Always initiates requests to servers.
* Waits for replies.
* Receives replies.
* Usually connects to a small number of servers at one time.
* Usually interacts directly with end-users using any user interface such as graphical user interface.


Server characteristics:

* Always wait for a request from one of the clients.
* Serve clients requests then replies with requested data to the clients.
* A server may communicate with other servers in order to serve a client request.
* If additional information is required to process a request (or security is implemented), a server may request additional       data (passwords) from a client before processing a request.
* End users typically do not interact directly with a server, but use a client.
