# DNS in Detail

## Room Overview
This room introduced the fundamentals of DNS (Domain Name System), explaining how domain names are translated into IP addresses and how internet communication relies on DNS infrastructure.

---

# Key Concepts Learned

## What is DNS
DNS (Domain Name System) is responsible for translating human-readable domain names into machine-readable IP addresses.

Example:
google.com → 142.250.x.x

Without DNS, users would need to memorize IP addresses to access websites and services.

---

# DNS Hierarchy

Learned how DNS is structured in a hierarchical model:

- Root Servers
- Top Level Domain (TLD) Servers
- Authoritative Name Servers

Understood how DNS queries travel through multiple servers to resolve a domain name.

---

# Types of DNS Records

Studied the most common DNS record types:

## A Record
Maps a domain name to an IPv4 address.

Example:
example.com → 192.168.1.1

---

## AAAA Record
Maps a domain name to an IPv6 address.

---

## CNAME Record
Used to create aliases for domains.

Example:
www.example.com → example.com

---

## MX Record
Defines mail servers responsible for email delivery.

---

## TXT Record
Stores text-based information, often used for:
- SPF
- Domain verification
- Security configurations

---

# DNS Resolution Process

Learned the complete DNS lookup process:

1. User enters a domain name
2. Browser checks local cache
3. Request goes to recursive DNS resolver
4. Resolver contacts root server
5. Resolver contacts TLD server
6. Resolver contacts authoritative DNS server
7. IP address is returned
8. Browser connects to target server

---

# Recursive vs Authoritative DNS

## Recursive DNS
Responsible for finding the correct answer by querying multiple DNS servers.

## Authoritative DNS
Stores the official DNS records for a domain.

---

# DNS Caching

Learned how caching improves performance and reduces DNS traffic by storing previous query results temporarily.

Concepts covered:
- TTL (Time To Live)
- Local cache
- ISP cache
- Browser cache

---

# DNS Security Concepts

Introduction to security-related DNS concepts:

- DNS spoofing
- DNS poisoning
- Malicious redirection
- Importance of secure DNS infrastructure

---

# Practical Skills Developed

- Understanding DNS architecture
- Reading DNS records
- Troubleshooting DNS resolution issues
- Understanding web communication flow
- Basic networking analysis

---

# Tools & Technologies Mentioned

- DNS
- TCP/IP
- Recursive Resolver
- Authoritative Name Server
- TLD Servers
- Root Servers

---

# Cybersecurity Relevance

DNS knowledge is essential in cybersecurity because attackers frequently abuse DNS for:
- Phishing
- Malware communication
- Command and Control (C2)
- Traffic redirection

Understanding DNS helps identify suspicious network behavior and supports both offensive and defensive security operations.
