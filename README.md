# Cyber-Security-Task3

API Security Risk Analysis of JSONPlaceholder Public API using Postman, including risk assessment, findings, and remediation recommendations.

## Overview

This project presents an API Security Risk Analysis conducted on the JSONPlaceholder Public API as part of the Cyber Security Internship Program at Future Interns.

The objective was to evaluate common API security risks, review endpoint accessibility, inspect response data, analyze response headers, and identify potential security concerns in a safe and ethical manner.

---

## Tools Used

- Postman
- JSONPlaceholder Public API
- Browser Developer Tools
- Microsoft Word
- GitHub

---

## Methodology

The assessment followed a structured approach:

1. Review API documentation
2. Test publicly accessible endpoints
3. Inspect API responses
4. Analyze response headers
5. Identify security risks
6. Classify findings based on severity
7. Provide remediation recommendations

---

## Endpoints Analyzed

- GET /users
- GET /users/1
- GET /posts
- GET /posts/1
- GET /comments

---

## Key Findings

### Medium Risk Findings

- Missing Authentication Controls
- Excessive Data Exposure
- Potential Enumeration Risk

### Low Risk Findings

- Technology Disclosure Through Headers

### Positive Security Controls

- Rate Limiting Enabled
- Security Headers Present
- Cloudflare Protection

---

## Scope

This assessment was limited to read-only testing of publicly available API endpoints.

No exploitation attempts, denial-of-service testing, authentication bypasses, or unauthorized activities were performed.

---

## Report

The complete assessment report is available in:

`API_Security_Risk_Analysis_Report.pdf`

---

## Author

**Divya Sri K**  
Cyber Security Intern  
Future Interns
