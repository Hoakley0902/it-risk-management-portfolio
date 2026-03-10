# Configuring Backup and Recovery Functions

## Overview
This project focused on implementing backup and recovery strategies to maintain system availability and protect critical data. The work emphasized how scheduled backups, shared storage, and load balancing help ensure business continuity during system failures or service interruptions. It also demonstrated how high-availability configurations reduce downtime by distributing workloads across multiple servers. :contentReference[oaicite:1]{index=1}

## Skills Demonstrated
- Backup and recovery configuration
- Disaster recovery planning
- System state backup management
- Shared storage configuration
- Load balancing implementation
- Failover testing
- DNS and network troubleshooting
- High-availability infrastructure design

## Tools and Technologies Used
- Windows Server Backup
- Windows Server Manager
- Linux NFS server
- pfSense firewall
- HAProxy load balancer
- DNS tools (nslookup / reverse DNS)
- Linux command line
- Web server infrastructure

## What I Worked On
In this project, I installed the Windows Server Backup feature and configured scheduled System State backups on a domain controller to protect essential configuration data. I verified the backup schedule and tested the recovery process through the Windows Server Recovery Wizard to confirm that the system could be restored if necessary. :contentReference[oaicite:2]{index=2}

I also configured a Linux-based NFS share to provide centralized storage that could be accessed by multiple web servers. After mounting the shared storage, I verified connectivity and confirmed that the web servers could successfully access the hosted content. 

To improve service availability, I implemented load balancing using HAProxy on a pfSense firewall. I configured backend server pools, frontend access rules, and DNS host overrides, then verified that traffic was distributed across both web servers. Finally, I simulated server failure scenarios and reviewed HAProxy statistics to confirm that traffic was redirected to the remaining active server. :contentReference[oaicite:3]{index=3}

## Key Takeaways
This project reinforced the importance of combining backup strategies with high-availability infrastructure to protect organizational systems. Regular backups help preserve critical system data, while load balancing and failover mechanisms help maintain service availability even when individual servers experience failures. From an IT operations perspective, these techniques are essential for maintaining uptime and supporting reliable system recovery.

## Evidence of Work
- [Lab PDF Documentation](https://github.com/user-attachments/files/25858114/Configuring.Backup.and.Recovery.Functions.4e.-.Haley.Oakley.pdf)
