# How the Web Works

## Overview

This room introduced the fundamentals of how the web functions, covering how users access websites, how browsers communicate with web servers, and the role of HTTP in web communication. It also explored how secure communication is established using HTTPS and provided hands-on experience with constructing HTTP requests.

---

## Topics Covered

* How Websites Work
* DNS (Domain Name System)
* HTTP
* HTTP Requests & Responses
* HTTP Methods
* HTTP Status Codes
* HTTP Headers
* Cookies
* HTTPS
* Making HTTP Requests

---

## Key Learnings

### How Websites Work

When a user enters a URL into a browser, the browser first uses DNS to resolve the domain name into an IP address. It then establishes a connection with the web server, sends an HTTP request, receives an HTTP response, and finally renders the webpage for the user.

---

### DNS (Domain Name System)

DNS translates human-readable domain names into IP addresses, allowing browsers to locate and communicate with web servers.

---

### HTTP (Hypertext Transfer Protocol)

HTTP is the communication protocol used between clients (browsers) and web servers. It defines how requests are sent and how responses are returned.

---

### HTTP Requests & Responses

A client sends an HTTP request to a server, which processes the request and returns an HTTP response containing the requested resource or an appropriate status message.

---

### HTTP Methods

Common HTTP methods include:

* **GET** – Retrieve data from the server.
* **POST** – Submit data to the server.
* **PUT** – Update existing resources.
* **DELETE** – Remove resources.

---

### HTTP Status Codes

Status codes indicate the outcome of a request.

Examples:

* **200 OK** – Request completed successfully.
* **301 Moved Permanently** – Resource has been permanently redirected.
* **404 Not Found** – Requested resource could not be found.
* **500 Internal Server Error** – The server encountered an unexpected error.

---

### HTTP Headers

Headers provide additional information about a request or response, including content type, browser information, authentication details, and caching instructions.

---

### Cookies

Cookies are small pieces of data stored in the browser that help websites remember user sessions, preferences, and authentication information.

---

### HTTPS

HTTPS is the secure version of HTTP. It encrypts communication using TLS/SSL, ensuring confidentiality and integrity of data exchanged between the client and the server.

---

## Practical Exercise

To reinforce these concepts, I used an interactive HTTP request simulator to construct and analyze HTTP requests.

During this exercise, I practiced:

* Sending GET requests
* Working with URL parameters
* Observing request and response headers
* Understanding server responses
* Interpreting HTTP status codes

This practical exercise helped me visualize how browsers and servers communicate during real web interactions.

---

## Reflection

This room provided a solid understanding of how websites function and how communication takes place over the web. Learning about DNS, HTTP, HTTPS, cookies, headers, and request-response cycles has given me a strong foundation for studying web application security concepts such as authentication, session management, and common web vulnerabilities in future learning.
