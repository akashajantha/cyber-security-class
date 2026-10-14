DAY 07: AUTHENTICATION AND ACCESS CONTROL

1. Authentication
Authentication answers: “Who are you?” Examples include passwords, security keys, biometrics, and multi-factor authentication (MFA).

2. Authorization
Authorization answers: “What are you allowed to do?” A logged-in user may still be denied access to a resource they cannot use.

3. Important Concepts
Least privilege: grant only the access needed.
MFA: use more than one authentication factor.
RBAC: assign permissions through roles.
Auditing: review records of access and activity.
Provisioning: grant accounts and access.
Deprovisioning: remove access when no longer needed.

4. IGA
Identity Governance and Administration manages identity lifecycles, access requests, reviews, roles, and compliance evidence.

5. Linux Examples
whoami
id
ls -l
chmod 600 secret.txt

chmod 600 makes a file readable and writable by its owner only, subject to filesystem and privilege context. Use it on your own practice file.

6. Good Practices
Use unique passwords and MFA, remove unused accounts, review permissions, avoid shared administrator accounts, and review important access events.

LEARNING OUTCOME
Understand authentication, authorization, least privilege, permissions, and identity governance.
