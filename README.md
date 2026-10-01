# FUTURE_CS_01 — Vulnerability Assessment


## Vulnerability Assessment of a Public Website

A passive, read-only security assessment was conducted against the publicly accessible website **https://www.castorama.fr/** as part of the Future Interns Cyber Security Task 1.

The assessment focused on identifying observable security weaknesses and documenting security-related configurations without performing intrusive or destructive testing.



## Website Tested

**Target:** https://www.castorama.fr/

**Assessment Type:** Passive / Read-Only Security Assessment

---

## Objective

To identify and document observable security weaknesses in the target website, review its publicly exposed security configuration, and provide practical security observations and recommendations.

---

## Scope

The assessment covered:

- Publicly accessible website pages
- HTTP/HTTPS services
- HTTP response and security headers
- Cookie security attributes
- TLS/SSL certificate configuration
- Basic network exposure
- Observable server and technology information

---

## Methodology

The assessment followed a non-intrusive approach:

1. Reviewed publicly accessible website behavior.
2. Examined HTTP and HTTPS responses.
3. Inspected response and security headers.
4. Reviewed cookie attributes and flags.
5. Checked TLS/SSL certificate details.
6. Performed basic network exposure checks.
7. Documented observations using screenshots and tool outputs.

No exploitation or destructive testing was performed.

---

## Tools Used

- **Nmap** – Basic network and service exposure checks
- **cURL** – HTTP/HTTPS response and security-header inspection
- **OpenSSL** – TLS/SSL certificate inspection
- **Browser Developer Tools** – Cookies, headers, and browser-side security observations
- **OWASP ZAP** – Security assessment tool considered within the passive/read-only methodology

---

## Evidence

The `evidence/` directory contains supporting screenshots and tool outputs collected during the assessment.

Evidence includes observations related to:

- Network/service exposure
- HTTP/HTTPS responses
- Security headers
- Cookie attributes
- TLS/SSL certificate information
- Browser Developer Tools observations

---

## Report

The complete vulnerability assessment report is available here:

**[Vulnerability Assessment Report](./Vulnerability_Assessment_Report.pdf)**

---

## Ethical Testing Disclaimer

This assessment was conducted using a passive and read-only approach. No exploitation, authentication bypass, brute-force attacks, denial-of-service testing, or destructive activities were performed.

The assessment was limited to publicly observable information and security configurations.


