# OWASP Top 10 Labs

## Overview

This repository contains hands-on examples, test cases, exploitation scenarios, and remediation guidance for the OWASP Top 10 vulnerabilities. The purpose of this repository is to demonstrate practical application security testing techniques, secure coding practices, and vulnerability remediation approaches.

## Objectives

* Understand common web application vulnerabilities.
* Learn how vulnerabilities can be identified and exploited in a controlled environment.
* Demonstrate secure coding and remediation techniques.
* Provide practical examples for Application Security assessments.

## Covered Vulnerabilities

| OWASP Category                                        | Description                                                          |
| ----------------------------------------------------- | -------------------------------------------------------------------- |
| A01:2021 - Broken Access Control                      | Unauthorized access to resources and privilege escalation scenarios. |
| A02:2021 - Cryptographic Failures                     | Weak encryption, sensitive data exposure, and insecure transport.    |
| A03:2021 - Injection                                  | SQL Injection, Command Injection, LDAP Injection examples.           |
| A04:2021 - Insecure Design                            | Examples demonstrating security design weaknesses.                   |
| A05:2021 - Security Misconfiguration                  | Improper server and application configuration scenarios.             |
| A06:2021 - Vulnerable and Outdated Components         | Risks associated with outdated libraries and dependencies.           |
| A07:2021 - Identification and Authentication Failures | Weak authentication and session management examples.                 |
| A08:2021 - Software and Data Integrity Failures       | Insecure deserialization and supply chain risks.                     |
| A09:2021 - Security Logging and Monitoring Failures   | Logging and monitoring weaknesses.                                   |
| A10:2021 - Server-Side Request Forgery (SSRF)         | SSRF attack scenarios and mitigation techniques.                     |

## Repository Structure

OWASP-Top10-Labs/
│
├── A01-Broken-Access-Control/
├── A02-Cryptographic-Failures/
├── A03-Injection/
├── A04-Insecure-Design/
├── A05-Security-Misconfiguration/
├── A06-Vulnerable-Components/
├── A07-Authentication-Failures/
├── A08-Software-Integrity-Failures/
├── A09-Logging-Monitoring-Failures/
├── A10-SSRF/
└── README.md
```

## Contents of Each Lab

Each lab contains:

* Vulnerability Description
* Business Impact
* Test Methodology
* Attack Scenario
* Proof of Concept (PoC)
* Sample Vulnerable Code
* Secure Code Example
* Remediation Recommendations
* References

## Tools Used

* Burp Suite
* OWASP ZAP
* Postman
* Browser Developer Tools
* SQLMap
* cURL

## Disclaimer

All examples in this repository are intended for educational and authorized security testing purposes only. Do not attempt these techniques on systems without proper authorization.

## References

* OWASP Top 10 2021
* OWASP Testing Guide
* OWASP Cheat Sheets
* CWE/SANS Top 25

