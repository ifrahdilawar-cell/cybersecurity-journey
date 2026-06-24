# How Websites Work

## Status
Completed ✅

## What I Learned

- Websites are built using multiple technologies that work together in the browser and on servers.
- The main components are HTML, JavaScript, and backend systems.
- Security issues like sensitive data exposure and HTML injection happen when data is not handled properly.

---

## Key Concepts

### How Websites Work

A website works through a client–server model:

- **Client (Browser)** → Sends requests and displays the website
- **Server** → Processes requests and sends back responses (HTML, data, files)

When you visit a website:
1. Browser sends an HTTP request
2. Server processes the request
3. Server returns a response
4. Browser renders the page

---

### HTML (HyperText Markup Language)

- HTML is the structure of a webpage.
- It defines elements like text, images, buttons, and forms.
- It is not a programming language.

Example elements:
- Headings
- Paragraphs
- Links
- Forms

---

### JavaScript

- JavaScript makes websites interactive.
- It runs in the browser.
- It can update content without reloading the page.

Examples:
- Form validation
- Pop-ups
- Dynamic content updates
- User interaction handling

---

## Security Concepts

### Sensitive Data Exposure

- Occurs when websites accidentally expose private or sensitive information.
- Examples include:
  - Passwords in plain text
  - API keys in frontend code
  - Sensitive files accessible via URL

Impact:
- Attackers can steal confidential data
- Can lead to account compromise or system breaches

---

### HTML Injection

- Happens when user input is inserted into a webpage without proper validation.
- Attackers can inject malicious HTML code into a page.

Example risk:
- Injecting fake login forms
- Altering page content
- Trick users into clicking malicious elements

Prevention:
- Input validation
- Output encoding
- Sanitizing user input

---

## Lab Activity

- Observed how websites load and render content using HTML and JavaScript.
- Identified how sensitive data can be exposed through improper handling.
- Practiced understanding how HTML injection vulnerabilities occur in web applications.

---

## Takeaway

Websites are built from multiple layers (HTML, JavaScript, backend systems), and security issues often arise when user input is not properly handled or sensitive data is exposed in the frontend.
