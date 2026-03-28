IAM JML Lab Project

Overview

This project demonstrates Identity and Access Management (IAM) concepts using Active Directory and Microsoft Entra ID. It simulates real-world enterprise scenarios including user lifecycle management and access control.

Key Concepts Implemented

- Identity and Access Management (IAM)
- Role-Based Access Control (RBAC)
- Joiner-Mover-Leaver (JML) lifecycle
- Multi-Factor Authentication (MFA)
- Single Sign-On (SSO)

Tools Used

- Active Directory (Windows Server in Virtual Machine)
- Microsoft Entra ID

Project Implementation

1. User Creation

Created a user (Suzy) in Active Directory and assigned login credentials.

2. RBAC (Group-Based Access)

Created a Finance group and added the user to the group instead of assigning permissions individually.

3. JML Lifecycle

- Joiner: Created user and assigned to Finance group
- Mover: Changed user role by updating group membership
- Leaver: Disabled user account to revoke access

4. Folder Access Control

Configured folder-level permissions using security groups to control access.

## Screenshots

### User Creation
![User Creation](SC1_UserCreated.png)

### Group Membership
![Group Membership](SC2_GroupMembership.png)

### Folder Permissions
![Folder Permissions](SC3_FinancePermission.png)

Outcome

This project demonstrates practical IAM implementation and simulates real-world access management processes in an enterprise environment.
