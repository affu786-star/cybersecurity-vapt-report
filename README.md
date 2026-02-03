# Vulnerability Assessment and Penetration Testing (VAPT)

## Project Overview
This repository contains the Vulnerability Assessment Report and evidences
for the web application **http://demo.testfire.net**.

The assessment was conducted as part of a cybersecurity internship task
using **OWASP ZAP**.

## Scope of Testing
- Target Application: http://demo.testfire.net
- Testing Type: Passive Security Assessment
- Tool Used: OWASP ZAP
- Environment: Test/Demo Application

## Key Findings
- Missing X-Content-Type-Options Header
- Server Version Information Disclosure
- Missing Anti-Clickjacking Header
- Content Security Policy (CSP) Not Set
- Cookie without SameSite Attribute

## Repository Structure
- `/Report` → Final Vulnerability Assessment Report
- `/Evidences` → Screenshots and tool outputs
- `/Tools_Used.md` → Tools and versions used

## Disclaimer
This assessment was performed on a deliberately vulnerable demo application
for educational purposes only.
