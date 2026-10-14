DAY 05: WEB SECURITY

1. What is Web Security?
Web security protects websites, web applications, user accounts, sessions, and data from attacks and misuse.

2. Common Risk Areas
Broken access control, injection vulnerabilities, cross-site scripting (XSS), authentication/session weaknesses, security misconfiguration, vulnerable dependencies, and sensitive data exposure.

3. Basic Assessment Checklist
- Confirm written authorization and scope.
- Identify pages, forms, APIs, and login flows in scope.
- Check HTTPS configuration.
- Review input validation and output encoding.
- Check authentication and authorization.
- Review security headers and cookie settings.
- Record findings, evidence, severity, and remediation.
- Retest fixes.

4. Defensive Practices
Validate input on the server, encode output appropriately, use parameterized database queries, enforce authorization on protected operations, update dependencies, and never expose secrets in frontend code.

PRACTICE
Assess only your own application or a lab that explicitly permits testing. Do not test public websites without authorization.

LEARNING OUTCOME
Recognize common web risks and understand a safe, authorized assessment workflow.
