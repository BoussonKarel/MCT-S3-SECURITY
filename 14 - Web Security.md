# 14 - Web Security
## Wat
- Belangrijke attack service / Point of entry
- Belangrijk naar reputatie
- CMS-Systemen
- SQL Injection
- Authenticatie / Escalation
- Cross site scripting

## Most common problems
### OWASP TOP 10
- **Injection**
- **Broken authentication**
- **Sensitive Data Exposure**
- **XML External Entities (XXE)**
- **Broken Access Control**
- **Security Misconfiguration**
- **Cross-Site Scripting (XSS)**
- **Insecure Deserialization**
- **Using Components with Known Vulnerabilities**
- **Insufficient Logging & Monitoring**

## Scanning
- Nessus, Nikto, OpenVAS...

## Testing
- OWASP, Mantra, Burp...

## Risico's
- "Defacement"
  - *Attack on a website that changes the visual appearance*
- Lek van credentials
- Reputatie
- Diefstal (shop)
- Total PWN van server & alle systemen
- ...

## Remediation
- Don't be stupid
- Use (sanitation) libraries (no DIY)
- Update site framework, plugins & libraries
- Prepared statements
- Authenticatie frameworks
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNzE2MzgzMzIsLTIxMzAyMjY0MTYsLT
E0OTU3MTQ5NjddfQ==
-->