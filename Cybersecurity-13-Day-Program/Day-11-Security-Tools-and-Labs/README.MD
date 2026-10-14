DAY 11: SECURITY TOOLS AND LABS

PURPOSE
Record the tools actually demonstrated or used during training. Update this file to match your sessions.

1. Linux Utilities
pwd, ls, cd: navigate the filesystem.
grep and find: search text and files.
chmod and chown: manage permissions and ownership.
ps and top: inspect processes.
df and free: inspect disk and memory usage.
ip and ss: inspect network configuration and listening sockets.
sha256sum: calculate file hashes.

2. Cryptography Utilities
openssl: cryptographic and certificate utility.
gpg: encryption and digital-signature tool.
Use approved exercises and protect private keys.

3. Example Local Integrity Lab
mkdir -p ~/cyber/labs/integrity
cd ~/cyber/labs/integrity
echo "Practice file" > sample.txt
sha256sum sample.txt
echo "Updated content" >> sample.txt
sha256sum sample.txt

Compare the hashes and record your observation.

4. Lab Report Template
Lab title:
Date:
Objective:
Authorized environment:
Tools used:
Steps performed:
Observations:
Result:
Lessons learned:
Screenshot filename:

IMPORTANT
Only list tools and exercises you actually used. Perform scans or security tests only in an authorized lab or on systems for which you have permission.

LEARNING OUTCOME
Document security utilities and create clear, reproducible lab reports.
