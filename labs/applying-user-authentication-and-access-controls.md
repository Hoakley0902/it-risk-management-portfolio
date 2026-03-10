# Applying User Authentication and Access Controls

## Overview
This project focused on configuring and verifying user authentication and access controls to protect system resources and shared data. The work emphasized how user accounts, security groups, permissions, and shared folder access can be managed to support least-privilege access and reduce the risk of unauthorized activity. It also reinforced the importance of validating access controls through direct user testing across multiple accounts. :contentReference[oaicite:0]{index=0}

## Skills Demonstrated
- User and group management
- Access control configuration
- Permission verification
- Shared folder security
- Role-based access control
- Active Directory administration
- ACL management
- Authentication testing

## Tools and Technologies Used
- Active Directory Users and Computers
- Windows file and folder security permissions
- TrueNAS
- SMB shared folders
- Access Control Lists (ACLs)
- Windows user accounts and group membership

## What I Worked On
In this project, I created and managed users and security groups in Active Directory, then configured file and folder permissions for different role-based access scenarios. I updated security permissions for HR, manager, and developer folders, verified which users could and could not access them, and reviewed the results by signing in with multiple accounts to confirm that restrictions were working as intended. The lab included both successful and unsuccessful access attempts, which helped validate how permissions affected different users in practice. :contentReference[oaicite:1]{index=1}

I also worked with TrueNAS to create an SMB share, configure datasets, and apply ACLs to shared folders. After setting those permissions, I verified access by signing in as different users and checking what content each person could see inside the Employees share. In the challenge portion, I reviewed additional user group memberships and expanded the shared folder configuration to support another business scenario, which reinforced how directory services and storage permissions work together in a controlled environment. :contentReference[oaicite:2]{index=2}

## Key Takeaways
This project strengthened my understanding of how authentication and access controls protect systems, files, and shared resources in business environments. It also showed the importance of testing permissions from the end-user perspective instead of only relying on configuration screens. From an IT support and security perspective, the project reinforced how user management, shared storage permissions, and least-privilege access help reduce risk while keeping systems organized and usable. :contentReference[oaicite:3]{index=3}

## Evidence of Work
- [Lab PDF Documentation](https://github.com/user-attachments/files/25857900/Applying_User_Authentication_and_Access_Controls_4e_-_Haley_Oakley.pdf)
