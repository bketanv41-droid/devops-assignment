# devops-assignment
This assignment focuses on implementing system monitoring, user management, and automated backup solutions in a Linux environment.


# Task 1: System Monitoring

# Implementation:
Installed htop and nmon
Monitored CPU, memory, and processes
Used df and du for disk tracking
Created monitoring script (monitoring.sh)
Stored logs in /logs/system.log

# Output:
Real-time system monitoring
Log file with system metrics

# Task 2: User Management

# Implementation:
Created users: Sarah and Mike
Created secure directories:
/home/Sarah/workspace
/home/mike/workspace
Applied permissions (chmod 700)
Set password expiry to 30 days

# Output:
Secure and isolated user environments

# Task 3: Backup Configuration

# Implementation:
Created backup scripts:
Apache (/etc/httpd, /var/www/html)
Nginx (/etc/nginx, /usr/share/nginx/html)
Stored backups in /backups/
Configured cron job:
Every Tuesday at 12:00 AM
Verified backups using tar -tzf

# Output:
Automated backup files
Verification logs generated

# Challenges Faced
Permission denied errors while accessing directories
Cron job path issues
Missing directories during backup