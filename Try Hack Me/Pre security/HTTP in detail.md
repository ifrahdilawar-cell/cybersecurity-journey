# HTTP in Detail

## Status
Completed ✅

## What I Learned

- HTTP (HyperText Transfer Protocol) is the foundation of data communication on the web.
- HTTPS is the secure version of HTTP that uses encryption (TLS/SSL) to protect data.
- It defines how clients (browsers) and servers communicate.

---

## Key Concepts

### What is HTTP/HTTPS?

- **HTTP** → Protocol used to transfer data between client and server.
- **HTTPS** → Secure version of HTTP that encrypts communication to prevent interception.

---

### HTTP Request and Response

Communication follows a request–response model:

#### Request (Client → Server)
Sent by the browser when accessing a resource.

Contains:
- Method (GET, POST, etc.)
- URL / Path
- Headers
- Body (optional)

#### Response (Server → Client)
Sent by the server back to the browser.

Contains:
- Status code
- Headers
- Response body (data/content)

---

### HTTP Methods

- **GET** → Retrieve data from a server
- **POST** → Send data to a server (create/login)
- **PUT** → Update existing data
- **DELETE** → Remove data from a server

---

## HTTP Status Codes

### Informational (100–199)
- 100 Continue  
- 101 Switching Protocols  

### Success (200–299)
- 200 OK  
- 201 Created  
- 202 Accepted  
- 204 No Content  

### Redirection (300–399)
- 300 Multiple Choices  
- 301 Moved Permanently  
- 302 Found  
- 304 Not Modified  

### Client Errors (400–499)
- 400 Bad Request  
- 401 Unauthorized  
- 403 Forbidden  
- 404 Not Found  
- 405 Method Not Allowed  

### Server Errors (500–599)
- 500 Internal Server Error  
- 501 Not Implemented  
- 502 Bad Gateway  
- 503 Service Unavailable  
- 504 Gateway Timeout  

---

## Lab Activity

- Practiced making HTTP requests using a simulated environment.
- Used different HTTP methods (GET, POST, PUT, DELETE).
- Modified request parameters and body data.
- Observed how responses change based on request type.
- Identified issues in a mock web application through request manipulation.

---

## Takeaway

HTTP is the foundation of web communication. Understanding methods, headers, cookies, and status codes is essential for both web development and cybersecurity testing.
