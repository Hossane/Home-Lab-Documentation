
# Active Directory

## Overview

This project involves building and managing an Active Directory
environment using Windows Server.

The objective is to simulate an enterprise environment and
practice identity and access management, user administration,
and centralized directory management.

## Environment

| Component | Configuration |
|---|---|
| Operating System | Windows Server |
| Virtualization | Oracle VirtualBox |
| Domain Name | homelab.local |
| Server Hostname | DC01 |
| Directory Service | Active Directory Domain Services |

## Implementation

### 1. Active Directory Domain Services

- Installed Active Directory Domain Services (AD DS).
- Promoted the Windows Server machine to a Domain Controller.
- Created and configured the domain.

### 2. Organizational Units

Created Organizational Units to organize directory objects.

Document the OU hierarchy and explain the purpose of each OU.

See [Organizational Units](organizational-units.md).

### 3. Users and Groups

Created user accounts representing employees in different departments.

Configured security and distribution groups to organize users
and manage access.

See [Users and Groups](users-and-groups.md).

### 4. Group Policy

Document any Group Policy Objects (GPOs) configured to manage
user and computer settings.

## Testing and Verification

Document how the environment was tested.

- Verified domain configuration.
- Verified user account creation.
- Checked group memberships.
- Verified OU organization.
- Tested relevant permissions.

## Challenges and Troubleshooting

| Issue | Resolution |
|---|---|
| | |

## Future Improvements

- **Configure Group Policy Objects:** Implement departmental policies, password requirements, and security restrictions.
- **Join Windows Client Machines to the Domain:** Add client computers to the domain to test centralized authentication and management.
- **Implement Centralized User Management:** Explore PowerShell automation for creating, modifying, and managing user accounts.
- **Configure Additional Domain Services:** Explore DNS, DHCP, and other Windows Server services.
- **Explore Linux Integration:** Set up an Ubuntu machine and investigate integration with Active Directory.
- **Implement Role-Based Access Control:** Assign resource permissions through security groups using the AGDLP model.