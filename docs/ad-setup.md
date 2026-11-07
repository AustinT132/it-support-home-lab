# Active Directory Setup - Windows Server 2022

## 1) Domain Controller Setup

![Server Adapter DHCP Setup](../images/Server-Adapter-Setup.png)

- Install Windows Server 2022 in VMWare
- Congifure Networks
    - **Nat-Lab-Adapter**: Bridged Network
    - **AD-Lab-Adapter**: Internal Network
- Assign Static IP for Internal Network: 172.16.0.1
- Install **Active Directory Domain Services** and promote the server to a Domain Controller for the root domain

## 2) Admin Setup

![Created Admin Account](../images/user-admin.png)

![Update User Privileges](../images/domain-admin.png)

- Created an **_ADMIN_** organizational unit (OU)
- Added a new admin user account
