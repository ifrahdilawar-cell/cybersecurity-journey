# DNS in Detail

## Status
Completed ✅

## What I Learned

- DNS (Domain Name System) is used to translate human-readable domain names into IP addresses.
- It acts like the “phonebook of the internet”, mapping domain names to their corresponding servers.
- When you visit a website, DNS is one of the first systems involved in loading it.

---

## Key Concepts

### What is DNS?
DNS is a system that converts domain names (like `example.com`) into IP addresses so that computers can communicate with each other.

---

### Domain Hierarchy

DNS follows a structured hierarchy:

- **Root Domain** → The starting point of DNS
- **Top-Level Domain (TLD)** → `.com`, `.org`, `.net`, `.thm`
- **Second-Level Domain** → The main domain name (e.g., `website` in `website.thm`)
- **Subdomain** → A subdivision of a domain (e.g., `shop.website.thm`)

This hierarchy helps organize and locate resources on the internet efficiently.

---

### DNS Record Types

#### A Record
- Maps a domain to an IPv4 address.

#### CNAME Record
- Points one domain name to another domain (acts as an alias).

#### MX Record
- Specifies mail servers for a domain.
- Uses priority values to determine which server is preferred.

#### TXT Record
- Stores text-based information.
- Often used for verification and security purposes.

---

### Making a DNS Request

- When a user enters a domain name in a browser, a DNS request is made.
- The system queries a DNS server to find the correct IP address.
- Tools like `nslookup` or `dig` can also be used to manually perform DNS lookups.

---

## Lab Activity

- Understood how DNS queries are made in real-time.
- Observed how different record types are returned based on the request.
- Learned how DNS helps browsers locate the correct server for a domain.

---

## Takeaway

DNS is a fundamental part of how the internet works. It enables seamless communication between users and websites by converting readable domain names into machine-readable IP addresses.
