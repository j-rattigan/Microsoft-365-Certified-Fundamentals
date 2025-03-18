# **Identity Types in Microsoft Entra ID**

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
- Microsoft Entra ID supports different types of identities:
  - **User identities**
  - **Workload identities**
  - **Device identities**
  - **External identities**
  - **Hybrid identities**

---

### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key terms and definitions**

- **User identities**: Assigned to people (employees, customers, vendors, etc.).
- **Workload identities**: Assigned to software objects (applications, VMs, containers).
- **Device identities**: Assigned to physical devices (laptops, mobile devices, printers).

---

### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- **Categories of Identity Types**:
  1. **Human identities**: People (internal and external users).
  2. **Machine identities**: Devices and workloads (applications, virtual machines).
  
---

### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**
#### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **User Identities**
- Represents people (employees, external users).
- **Internal Authentication**: User authenticates through the organization's Microsoft Entra ID.
- **External Authentication**: User authenticates using an external identity provider.

---

### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- **User Types**:
  - **Internal Member**: Employee authenticated internally.
  - **External Guest**: External users like vendors, authenticated externally.
  - **External Member**: External users needing member-level access.
  - **Internal Guest**: Employees with limited permissions.

#### Example Matrix for User Identities:

![User Identities Matrix](https://learn.microsoft.com/en-us/training/wwl-sci/explore-basic-services-identity-types/media/entra-id-user-properties-v3-inline.png)

---

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
#### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Workload Identities**
- Identity for **software workloads** (applications, VMs, containers).
- **Important**: Securing these identities is crucial as workloads deal with multiple credentials.
  
#### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**
- **Applications & Service Principals**: Application must be registered in Microsoft Entra ID to use service principals.
- **Managed Identities**: Automatically managed identities for applications to access resources securely.

#### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- **Managed Identities Types**:
  1. **System-assigned**: Tied to the lifecycle of a resource.
  2. **User-assigned**: Can be assigned to multiple resources and managed separately.

#### Diagram for Managed Identities:

![Managed Identities Diagram](https://learn.microsoft.com/en-us/training/wwl-sci/explore-basic-services-identity-types/media/managed-identities-inline.png)

---

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
#### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Device Identities**
- Devices: Mobile devices, laptops, servers, printers.
- **Microsoft Entra Registered Devices**: Allows personal devices (BYOD) to access organization’s resources.
- **Microsoft Entra Joined Devices**: Devices joined via organizational account.
- **Hybrid Joined Devices**: Devices joined to both Active Directory and Microsoft Entra ID.

---

### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- Device identities enable **Single Sign-On (SSO)** to cloud-based and on-premises resources.
- Tools like **Microsoft Intune** can manage and secure devices.

---

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
#### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Groups**
- **Security Groups**: Manage user and device access.
- **Microsoft 365 Groups**: Used for collaboration (email, calendars, etc.).
- **Dynamic Membership**: Automatically adds/removes identities from groups based on rules.

---

### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- **Zero Trust**: Limiting access to resources based on need.
- Groups provide a streamlined way to manage access permissions.
