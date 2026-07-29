# PortSwigger Web Security Academy — Lab Reports

Technical lab reports written against the PortSwigger Web Security Academy / Burp Suite Professional curriculum, documenting hands-on exploitation of each major web application vulnerability class.

**Author:** Iliya Dehghani

## Contents

### Section 0 — Orientation

| Lab | Topic | Report |
|---|---|---|
| Lab 0 | Introduction to Burp Suite | [Lab-00-Intro-to-Burp-Suite](Lab-00-Intro-to-Burp-Suite/report.md) |

### Section 1 — Server-Side Vulnerabilities

| Lab | Topic | Report |
|---|---|---|
| 1-1 | SQL Injection | [Lab-01-01-SQL-Injection](Lab-01-01-SQL-Injection/report.md) |
| 1-2 | Authentication | [Lab-01-02-Authentication](Lab-01-02-Authentication/report.md) |
| 1-3 | Directory Traversal | [Lab-01-03-Directory-Traversal](Lab-01-03-Directory-Traversal/report.md) |
| 1-4 | Command Injection | [Lab-01-04-Command-Injection](Lab-01-04-Command-Injection/report.md) |
| 1-5 | NoSQL Injection | [Lab-01-05-NoSQL-Injection](Lab-01-05-NoSQL-Injection/report.md) |
| 1-6 | Business Logic Vulnerabilities | [Lab-01-06-Business-Logic-Vulnerabilities](Lab-01-06-Business-Logic-Vulnerabilities/report.md) |
| 1-7 | Information Disclosure | [Lab-01-07-Information-Disclosure](Lab-01-07-Information-Disclosure/report.md) |
| 1-8 | Access Control | [Lab-01-08-Access-Control](Lab-01-08-Access-Control/report.md) |
| 1-9 | File Upload Vulnerabilities | [Lab-01-09-File-Upload-Vulnerabilities](Lab-01-09-File-Upload-Vulnerabilities/report.md) |
| 1-10 | Race Conditions¹ | [Lab-01-10-Race-Conditions](Lab-01-10-Race-Conditions/report.md) |
| 1-11 | API Testing | [Lab-01-11-API-Testing](Lab-01-11-API-Testing/report.md) |
| 1-12 | XXE Injection | [Lab-01-12-XXE-Injection](Lab-01-12-XXE-Injection/report.md) |

¹ *Source PDF was titled "SSRF" but its actual content covered Race Conditions labs with no SSRF material; retitled to match the real content. See the note at the top of that report.*

### Section 2 — Client-Side Vulnerabilities

| Lab | Topic | Report |
|---|---|---|
| 2-1-A | Cross-Site Scripting (XSS), Part 1 — Labs 1–15 | [Lab-02-01-A-Cross-Site-Scripting](Lab-02-01-A-Cross-Site-Scripting/report.md) |
| 2-1-B | Cross-Site Scripting (XSS), Part 2 — Labs 16–30 | [Lab-02-01-B-Cross-Site-Scripting](Lab-02-01-B-Cross-Site-Scripting/report.md) |
| 2-2 | Cross-Site Request Forgery (CSRF) | [Lab-02-02-CSRF](Lab-02-02-CSRF/report.md) |
| 2-3 | Clickjacking (UI Redressing) | [Lab-02-03-Clickjacking](Lab-02-03-Clickjacking/report.md) |
| 2-4 | CORS | [Lab-02-04-CORS](Lab-02-04-CORS/report.md) |

### Section 3 — Advanced Topics

| Lab | Topic | Report |
|---|---|---|
| 3-1 | OAuth 2.0 Authentication Vulnerabilities | [Lab-03-01-OAuth-2.0-Vulnerabilities](Lab-03-01-OAuth-2.0-Vulnerabilities/report.md) |
| 3-2 | Attacking JWTs | [Lab-03-02-Attacking-JWTs](Lab-03-02-Attacking-JWTs/report.md) |
| 3-3 | Web LLM Attacks | [Lab-03-03-Web-LLM-Attacks](Lab-03-03-Web-LLM-Attacks/report.md) |
| 3-4-A | HTTP Request Smuggling, Part 1 (Labs 1–7) | [Lab-03-04-A-HTTP-Request-Smuggling](Lab-03-04-A-HTTP-Request-Smuggling/report.md) |
| 3-4-B | HTTP Request Smuggling, Part 2 (Labs 8–10) | [Lab-03-04-B-HTTP-Request-Smuggling](Lab-03-04-B-HTTP-Request-Smuggling/report.md) |
| 3-5 | Essential Skills (WAF bypass, Scanner proficiency, Mystery Labs) | [Lab-03-05-Essential-Skills](Lab-03-05-Essential-Skills/report.md) |

## Structure

Each lab directory contains:
- `report.md` — the lab's technical report (objective, background, tools, methodology, findings, references)
- `images/` — screenshots/figures referenced in that report, extracted from the original lab submissions

## Coverage Summary

24 reports across 20 vulnerability classes: SQL/NoSQL injection, authentication, directory traversal, command injection, business logic flaws, information disclosure, access control, file upload, race conditions, API testing, XXE injection, XSS (reflected/stored/DOM-based), CSRF, clickjacking, CORS, OAuth 2.0, JWT attacks, web LLM attacks, and HTTP request smuggling — plus foundational Burp Suite tooling and a capstone "Essential Skills" set combining WAF evasion, Scanner-driven discovery, and unguided vulnerability identification.
