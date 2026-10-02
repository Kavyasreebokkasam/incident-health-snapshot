# Capture an Incident Health Snapshot

## Project Description

This project captures the health status of a Linux server during an incident and saves the collected information into a single report file.

## Tools and Commands Used

* `uptime` – checks system uptime and load average.
* `free -h` – displays memory usage.
* `ps aux` – lists running processes.
* `df -h` – displays filesystem disk usage.
* `du -sh` and `sort -hr` – identify large directories.
* `ss -tuln` – displays listening ports.
* Bash redirection (`>>`) – appends command output to a report file.

## Report Location

`/root/health-report.txt`

## Purpose

The project helps on-call engineers quickly inspect server health before troubleshooting performance issues.

## Key Learning

Linux system monitoring, disk analysis, network inspection, and Bash output redirection.
