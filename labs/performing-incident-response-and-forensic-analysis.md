# Performing Incident Response and Forensic Analysis

## Overview
This project focused on investigating a simulated cybersecurity incident using forensic analysis techniques. The work involved examining network traffic captures, analyzing disk images for malware artifacts, identifying compromised user activity, and building a timeline of the attack. The goal was to determine how the incident occurred, what systems were affected, and what indicators of compromise were present. :contentReference[oaicite:1]{index=1}

## Skills Demonstrated
- Digital forensic investigation
- Network traffic analysis
- Malware artifact identification
- Incident timeline reconstruction
- Evidence documentation
- Email and phishing analysis
- Compromised credential investigation
- Incident response reporting

## Tools and Technologies Used
- NetWitness Investigator
- Autopsy Digital Forensics Platform
- PCAP network capture analysis
- Disk image forensic analysis
- Windows system artifact analysis
- Email forensic investigation

## What I Worked On
In this project, I analyzed a packet capture (PCAP) file using NetWitness Investigator to identify suspicious network activity and potential data exfiltration. By examining network sessions and timestamps, I was able to identify suspicious connections and reconstruct portions of the attack timeline. :contentReference[oaicite:2]{index=2}

I then performed disk image analysis using the Autopsy digital forensics platform. During this investigation, I identified artifacts related to a malicious keylogger file and reviewed system timestamps showing when the file was created and executed. Evidence indicated the keylogger executable was created on **June 30, 2021 at 15:00:13** and later executed on **July 1, 2021 at 15:54:39**, suggesting compromised user activity associated with the affected account. :contentReference[oaicite:3]{index=3}

Additional evidence was discovered in email records indicating social engineering activity involving malicious instructions to install spyware and provide FTP credentials. The investigation showed that the compromised account was used to transmit sensitive information through the organization's FTP system, which helped confirm the scope of the incident and the attacker’s likely method of entry. :contentReference[oaicite:4]{index=4}

## Key Takeaways
This project demonstrated how digital forensics and incident response procedures help organizations investigate security breaches and determine the root cause of an attack. By analyzing network traffic, system artifacts, and user communications, it is possible to reconstruct attack timelines and identify compromised systems. The experience highlighted the importance of structured incident response processes, forensic evidence preservation, and rapid containment strategies to minimize organizational risk.

## Evidence of Work
- [Lab PDF Documentation](https://github.com/user-attachments/files/25858197/Performing.Incident.Response.and.Forensic.Analysis.4e.-.Haley.Oakley.pdf)
