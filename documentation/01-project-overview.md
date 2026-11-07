# Active Directory Home Lab

## 1. Overview
This project focuses on the design and implementation of a Windows Server 2025 domain environment using Oracle VirtualBox. The virtual laboratory simulates an enterprise network infrastructure within a controlled environment, providing practical experience in server administration, centralized identity management, virtualization, and network services.

The infrastructure comprises a Windows Server 2025 virtual machine configured to provide Active Directory Domain Services (AD DS), Domain Name System (DNS), and Dynamic Host Configuration Protocol (DHCP). Windows 10 client virtual machines are deployed to join the domain and authenticate through centralized directory services. The integration of directory, naming, and addressing services reflects the core infrastructure requirements of Microsoft-based enterprise networks (Krause, 2018; Svidergol et al., 2018).

Oracle VirtualBox provides the virtualization platform for deploying and connecting the server and client operating systems. Network Address Translation (NAT) facilitates external network connectivity, while a structured IPv4 addressing scheme separates statically assigned addresses (1–100) from dynamically allocated addresses (101–200).

The project also provides practical exposure to cybersecurity principles associated with identity management, authentication, access control, and network infrastructure security. These areas are particularly relevant to enterprise environments, where weaknesses in directory configurations and excessive privileges can expose systems to unauthorized access and privilege escalation (Thomas, 2017).

The completed laboratory environment is designed to incorporate the following infrastructure components:

- Windows Server 2025 Domain Controller: Configured with Active Directory Domain Services (AD DS) to provide centralized directory management and domain authentication.
- Windows 10 Client Systems: Configured to join the Active Directory domain and authenticate using centrally managed domain accounts.
- DHCP and DNS Services: Implemented to automate IP address allocation, network configuration, hostname resolution, and domain controller discovery.
- Network Address Translation (NAT): Configured to facilitate internet connectivity for virtual machines within the laboratory environment.
- Structured Network Addressing: Implemented using a defined IPv4 allocation scheme, with addresses 1–100 reserved for static assignments and 101–200 designated for dynamic DHCP allocation.

This infrastructure provides a practical foundation for examining enterprise network administration, directory services, centralized authentication, and network security.

## 2. Aim

### 2.1 Project Aim

The aim of this project is to design, deploy, and configure a virtualized Windows Server 2025 domain environment using Oracle VirtualBox to develop practical competencies in enterprise server administration, Active Directory management, and network infrastructure configuration. The project seeks to demonstrate how centralized directory services, domain authentication, DNS, DHCP, and network connectivity operate together within a Windows-based enterprise environment.

### 2.2 Project Significance

Understanding Windows Server and Active Directory is essential for system administrators, cybersecurity professionals, IT support specialists, and students pursuing careers in information technology. Active Directory provides centralized identity and resource management, making it an important technology for administering user access and organizational network resources (Krause, 2018).

From a cybersecurity perspective, practical knowledge of Windows domain environments supports the understanding of authentication mechanisms, access control, privilege management, and enterprise security administration. These competencies are relevant to identifying and addressing security weaknesses associated with improperly configured user accounts, permissions, and directory services (Thomas, 2017).

The laboratory therefore bridges theoretical knowledge and practical application by providing a controlled environment in which enterprise Windows infrastructure can be deployed, administered, tested, and troubleshot.