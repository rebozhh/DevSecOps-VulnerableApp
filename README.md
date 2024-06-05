# DevSecOps Vulnerability

This repository has a simple website made in html that was originally vulnerable.


Injection: Users credentials were stored in localStorage, which could led to injection attacks. localStorage was removed and the usage was to perform server side validation

Broken Authentication: Admin login was insecure. The remediation was to use proper authentication mechanism and server-side validation

Sensitive Data Exposure: Storing password in localStorage could led to potential damage this due the exposition of data. We avoid localStorage for credentials.

XSS: User input login was injected directly to html without sanitization. Remediation is to sanitize user input before displaying it.

"Main" branch contains: Final secured version of the original HTML

