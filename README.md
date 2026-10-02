# FUTURE_CS_01 — Vulnerability Assessment


## Vulnerability Assessment of a Public Website

This project presents a passive, read-only security assessment of the publicly accessible **Castorama website** conducted as part of **Future Interns – Cyber Security Task 1**.

The assessment focused on observing publicly accessible security configurations and identifying potential security weaknesses without performing intrusive or destructive testing.



## Website Tested

**Target:** https://www.castorama.fr/

**Assessment Type:** Passive / Read-Only Security Assessment



## Objective

The objective of this assessment was to review the publicly observable security posture of the website, identify relevant security observations, and document them with supporting evidence and practical recommendations.



## Scope

The assessment covered publicly observable aspects of the website, including:

- Publicly accessible web pages
- HTTP/HTTPS communication
- HTTP response and security headers
- Cookie security attributes
- TLS/SSL configuration
- Basic network and service exposure
- Observable server and technology information


## Methodology

The assessment was performed using a non-intrusive, read-only approach.

The methodology included:

1. Reviewing publicly accessible pages and website behavior.
2. Inspecting HTTP/HTTPS communication and response information.
3. Examining security-related response headers.
4. Reviewing cookies and their security attributes.
5. Observing TLS/SSL certificate information.
6. Performing basic network and service exposure checks.
7. Recording relevant observations through screenshots and tool outputs.
8. Documenting security observations and recommended remediation measures.

No exploitation or destructive testing was performed.



## Tools Used

- **Nmap** – Basic network and service exposure analysis
- **cURL** – HTTP/HTTPS response and header inspection
- **OpenSSL** – TLS/SSL certificate and configuration inspection
- **Browser Developer Tools** – Headers, cookies, and browser-side security observations
- **OWASP ZAP** – Web security assessment and passive analysis



## Evidence

The `evidence/` directory contains the supporting screenshots and tool outputs collected during the assessment.

The evidence is provided to support the observations documented in the vulnerability assessment report.



## Assessment Report

The complete vulnerability assessment report is provided in:

**`Vulnerability_Assessment_Report.pdf`**

The report contains the assessment overview, scope and methodology, security observations, risk information, supporting evidence, and recommended remediation measures.



## Ethical Testing Disclaimer

This assessment was conducted as a passive and read-only security review of a publicly accessible website.

No exploitation, authentication bypass, brute-force attacks, denial-of-service testing, or destructive activities were performed.

The assessment was limited to publicly observable information and security configurations.

