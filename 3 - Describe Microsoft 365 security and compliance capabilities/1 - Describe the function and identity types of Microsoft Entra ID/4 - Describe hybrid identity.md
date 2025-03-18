# Hybrid Identity Overview

#### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important** 
Hybrid identity allows for a common identity across on-premises and cloud-based applications, making it easier for users to access resources from various locations.

#### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key terms and definitions**

- **Hybrid Identity**: A combination of on-premises and cloud-based identity solutions to provide a unified identity across different applications.
- **Inter-Directory Provisioning**: The process of creating an identity in one directory system (e.g., Active Directory) and syncing it with another (e.g., Microsoft Entra ID).
- **Synchronization**: Ensures that identity information for on-premises users and groups matches with their cloud-based counterparts.

#### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important** 
Microsoft’s hybrid identity solutions span on-premises and cloud capabilities, enabling a seamless authentication and authorization experience for users regardless of the resource location.

#### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**

- **Microsoft Entra Cloud Sync**: A tool that helps organizations accomplish hybrid identity goals by syncing and provisioning users, groups, and contacts to Microsoft Entra ID.
  - Uses the **Microsoft Entra Cloud Sync Agent** to act as a bridge between Active Directory and Microsoft Entra ID.
  - The agent provides a lightweight provisioning experience that requires minimal configuration.
  - **SCIM (System for Cross-domain Identity Management)** is used to automate the exchanging of identity information between domains.

![Hybrid Identity Diagram](https://learn.microsoft.com/en-us/training/wwl-sci/explore-basic-services-identity-types/media/entra-cloud-sync-inline.png)

The image above illustrates the hybrid identity process, showing the connection between on-premises Active Directory and cloud-based Microsoft Entra ID via Microsoft Entra Cloud Sync.
