# HTTP in Detail

## Room Overview
This room introduced the fundamentals of HTTP (HyperText Transfer Protocol), explaining how web browsers communicate with web servers and how websites deliver content over the internet.

---

# Key Concepts Learned

## What is HTTP
HTTP is the protocol used for communication between clients and web servers.

It enables browsers to request resources such as:
- Web pages
- Images
- APIs
- Files
- Scripts

Example:
Browser → HTTP Request → Web Server  
Web Server → HTTP Response → Browser

---

# HTTP Request Structure

Learned the components of an HTTP request:

## Request Line
Contains:
- HTTP Method
- Requested Resource
- HTTP Version

Example:
GET /index.html HTTP/1.1

---

## Headers
Provide additional information about the request.

Examples:
- Host
- User-Agent
- Cookie
- Authorization

---

## Body
Optional section used to send data to the server.

Commonly used with:
- POST requests
- API requests
- Login forms

---

# HTTP Methods

Studied the main HTTP request methods:

## GET
Requests data from a server.

Example:
Retrieving a webpage.

---

## POST
Sends data to the server.

Example:
Submitting login credentials.

---

## PUT
Updates existing resources.

---

## DELETE
Removes resources from the server.

---

## PATCH
Partially modifies existing resources.

---

# HTTP Response Structure

Learned how servers respond to requests.

Components include:

## Status Line
Contains:
- HTTP Version
- Status Code
- Status Message

Example:
HTTP/1.1 200 OK

---

## Response Headers
Provide metadata about the response.

Examples:
- Content-Type
- Set-Cookie
- Server

---

## Response Body
Contains the requested resource or returned data.

Examples:
- HTML pages
- JSON API responses
- Images

---

# HTTP Status Codes

Learned the meaning of common status codes.

## 1xx – Informational
Request received.

---

## 2xx – Success
Request completed successfully.

Examples:
- 200 OK
- 201 Created

---

## 3xx – Redirection
Client must take additional action.

Examples:
- 301 Moved Permanently
- 302 Found

---

## 4xx – Client Errors
Problem caused by the client request.

Examples:
- 400 Bad Request
- 401 Unauthorized
- 403 Forbidden
- 404 Not Found

---

## 5xx – Server Errors
Problem occurred on the server.

Examples:
- 500 Internal Server Error
- 502 Bad Gateway

---

# Cookies & Sessions

Introduction to how websites maintain user sessions.

Concepts covered:
- Session cookies
- Authentication tokens
- User tracking
- Persistent sessions

---

# HTTPS

Learned the difference between HTTP and HTTPS.

## HTTPS Features
- Encrypted communication
- Data confidentiality
- Integrity protection
- SSL/TLS usage

Understood why HTTPS is essential for secure communication on modern websites.

---

# Practical Skills Developed

- Understanding browser-server communication
- Reading HTTP requests and responses
- Identifying status codes
- Understanding web application behavior
- Basic web traffic analysis

---

# Cybersecurity Relevance

HTTP knowledge is fundamental in cybersecurity because many attacks target web applications.

Examples include:
- SQL Injection
- Cross-Site Scripting (XSS)
- Session hijacking
- Authentication attacks
- API exploitation

Understanding HTTP helps analyze vulnerabilities, inspect traffic, and identify malicious behavior.

---

# Tools & Technologies Mentioned

- HTTP
- HTTPS
- SSL/TLS
- Web Servers
- APIs
- Cookies
- Sessions
- TCP/IP

---

# Key Takeaway

HTTP is the foundation of web communication. Understanding how requests, responses, headers, methods, and sessions work is essential for both offensive and defensive cybersecurity operations.
