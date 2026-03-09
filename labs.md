---
layout: page
title: Lab Challenges
permalink: /labs/
---

## Lab 1 – SQL Injection Challenge

Problem:
A login form was vulnerable to SQL injection.

Approach:
1. Tested the login form inputs.
2. Injected SQL payloads to bypass authentication.

Example payload:

' OR 1=1 --

Tools Used:
- Burp Suite
- Browser Developer Tools

Lessons Learned:
- Input validation is critical.
- Parameterized queries help prevent SQL injection.

---

## Lab 2 – Network Enumeration

Problem:
Identify services running on a target machine.

Approach:
1. Used Nmap to scan the target machine.
2. Identified open ports and running services.

Tools Used:
- Nmap
- Kali Linux

Lessons Learned:
Enumeration is an important step in penetration testing.
