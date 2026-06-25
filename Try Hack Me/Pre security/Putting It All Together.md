# Putting It All Together

## Status

Completed ✅

## What I Learned

* A website request involves multiple components working together behind the scenes.
* DNS is used to find the IP address of a website.
* Web servers use HTTP/HTTPS to communicate with browsers.
* Additional technologies such as Load Balancers, CDNs, Databases, and WAFs improve performance, reliability, and security.
* Web servers can host multiple websites and serve both static and dynamic content.

---

## Key Concepts

### Website Request Process

When a user visits a website:

1. The browser requests the website.
2. DNS resolves the domain name to an IP address.
3. The request may pass through a Load Balancer.
4. A CDN may serve cached content.
5. A WAF filters malicious traffic.
6. The Web Server processes the request.
7. The server may query a Database.
8. The response is returned to the browser.

---

### Load Balancer

* Distributes traffic across multiple servers.
* Prevents individual servers from becoming overloaded.
* Improves availability and fault tolerance.

---

### CDN (Content Delivery Network)

* Stores cached copies of website content.
* Delivers content from servers closer to users.
* Reduces latency and improves loading speed.

---

### Database

* Stores website information and user data.
* Used by dynamic websites to retrieve and update information.
* Common examples include MySQL and PostgreSQL.

---

### WAF (Web Application Firewall)

* Monitors and filters incoming web traffic.
* Blocks malicious requests before they reach the web server.
* Helps protect against common web attacks.

---

## How Web Servers Work

### What is a Web Server?

* A web server receives HTTP/HTTPS requests from clients.
* It processes requests and returns website content.
* Common web servers include Apache, Nginx, and IIS.

---

### Virtual Hosts

* Virtual Hosts allow one server to host multiple websites.
* Multiple domains can share the same server and IP address.
* The server determines which website to display based on the requested hostname.

Example:

* example.com
* blog.example.com
* shop.example.com

---

### Static vs Dynamic Content

#### Static Content

* Content that remains the same for all visitors.
* Stored directly on the server.

Examples:

* HTML pages
* Images
* CSS files

#### Dynamic Content

* Content generated based on user requests or database information.
* Changes depending on the user or situation.

Examples:

* User dashboards
* Social media feeds
* E-commerce websites

---

### Scripting and Backend Languages

Backend languages process requests and generate dynamic content.

Common languages:

* PHP
* Python
* JavaScript (Node.js)
* Java
* C#

Typical process:

1. Browser sends a request.
2. Web server receives the request.
3. Backend code executes.
4. Database is queried if needed.
5. Response is generated and returned.

---

## Lab Activity

* Reviewed the complete lifecycle of a website request.
* Identified the role of DNS, Web Servers, Databases, CDNs, Load Balancers, and WAFs.
* Explored how web servers host multiple websites using Virtual Hosts.
* Learned the difference between static and dynamic content.
* Completed the final quiz by arranging the website request process in the correct order.

---

## Takeaway

A website request involves many components working together, including DNS, web servers, databases, CDNs, load balancers, and security controls such as WAFs. Understanding how these components interact provides a strong foundation for web technologies and web security.

