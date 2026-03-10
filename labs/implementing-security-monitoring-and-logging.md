# Implementing Security Monitoring and Logging

## Overview
This project focused on implementing security monitoring and logging mechanisms to detect unauthorized activity across systems and networks. The work emphasized how system logs, network intrusion detection systems, and file integrity monitoring tools help identify suspicious behavior and provide visibility into potential security incidents. :contentReference[oaicite:1]{index=1}

## Skills Demonstrated
- Security log analysis
- Intrusion detection system configuration
- Network traffic monitoring
- File integrity monitoring
- Authentication event tracking
- Security event investigation
- System auditing and logging
- Security alert interpretation

## Tools and Technologies Used
- Windows Event Viewer
- Snort Intrusion Detection System (IDS)
- pfSense
- rsyslog (Linux system logging)
- Tripwire
- Linux command line
- ICMP network monitoring

## What I Worked On
In this project, I investigated failed login attempts and security audit events using Windows Event Viewer to better understand how authentication activity is recorded in system logs. I reviewed event details related to unsuccessful login attempts and security auditing to identify indicators of potential unauthorized access attempts. :contentReference[oaicite:2]{index=2}

I also configured Snort on a pfSense firewall to monitor network traffic and generate alerts for suspicious ICMP activity. After enabling monitoring on the LAN interface, I generated network traffic and reviewed the Snort alert logs to observe how intrusion detection systems identify and log potential threats. :contentReference[oaicite:3]{index=3}

On the Linux system, I configured rsyslog to collect and track authentication logs, then reviewed failed login attempts and system messages to analyze potential security issues. I also used Tripwire to monitor file integrity by generating a report that compared system files against a known baseline to detect unauthorized changes. :contentReference[oaicite:4]{index=4}

## Key Takeaways
This project reinforced the importance of centralized logging and continuous monitoring for maintaining system security. It also demonstrated how combining host-level logs, network intrusion detection, and file integrity monitoring creates a layered approach to identifying threats. From an IT and security operations perspective, these monitoring systems provide critical visibility that helps administrators detect suspicious activity early and respond to incidents more effectively.

## Evidence of Work
- [Lab PDF Documentation](https://github.com/user-attachments/files/25858076/Implementing.Security.Monitoring.and.Logging.4e.-.Haley.Oakley.pdf)
