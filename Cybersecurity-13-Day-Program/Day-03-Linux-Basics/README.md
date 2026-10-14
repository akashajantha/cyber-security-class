DAY 03: LINUX BASICS

1. Linux Filesystem
/: filesystem root
/home: normal users' home directories
/root: root user's home directory
/etc: configuration files
/var/log: many system and application logs
/tmp: temporary files
/usr: programs and shared resources
/dev: device files
/proc and /sys: virtual kernel and system information

2. Navigation and Identity
pwd                  Show current directory
whoami               Show current username
id                   Show user and group IDs
ls -la               List files, including hidden files
cd /                 Move to filesystem root
cd ~                 Move to home directory
cd ..                Move to parent directory

3. File Operations
mkdir -p cyber/practice
touch notes.txt
cat notes.txt
cp notes.txt notes-backup.txt
mv notes.txt notes-renamed.txt
find . -name "*.txt"
grep -i "error" notes-renamed.txt

4. System Information
cat /etc/os-release
uname -r
hostname
df -h
free -h
uptime

5. Permissions and Processes
ls -l
chmod 600 secret.txt
ps aux
top
ss -tuln

6. Amazon Linux 2023
Amazon Linux 2023 uses dnf for package management, for example:
sudo dnf install nginx -y
Ubuntu commonly uses apt instead.

SAFETY
Practise inside your own folder. Avoid destructive commands such as rm -rf on system directories. Do not change system folder permissions while learning.

LEARNING OUTCOME
Navigate Linux, manage files, inspect system information, and understand permissions and processes.
