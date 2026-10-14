DAY 10: DIGITAL FORENSICS

1. What is Digital Forensics?
Digital forensics identifies, preserves, examines, and reports digital evidence using methods that maintain its integrity.

2. Key Principles
Preserve original evidence, document actions and timestamps, limit access, maintain chain-of-custody records where required, use repeatable methods, and report findings objectively.

3. Logs
Linux systems may record authentication, service, and system events in different locations depending on distribution and configuration. Common locations include /var/log and the system journal.

Useful read-only commands:
journalctl --since "1 hour ago"
journalctl -p warning
last

Some commands or logs may not be installed or enabled on every system. Some logs require elevated permissions.

4. File Integrity
sha256sum filename
This calculates a SHA-256 digest that can be recorded when documenting a file.

5. Basic Investigation Workflow
Confirm authorization and scope; record date, time, system, and investigator; preserve evidence; calculate hashes when appropriate; examine relevant logs; document commands and observations; protect reports and evidence.

SAFETY
Do not investigate devices or accounts without authorization. Avoid modifying original evidence unnecessarily.

LEARNING OUTCOME
Understand evidence preservation, logs, hashes, and documented investigation.
