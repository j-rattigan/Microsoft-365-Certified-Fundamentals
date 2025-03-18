
# Global Secure Access in Microsoft Entra

## ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important** 
**Microsoft Entra** provides products under **Global Secure Access**:
- **Microsoft Entra Internet Access** (Secures access to SaaS apps and the public internet)
- **Microsoft Entra Private Access** (Secures access to private corporate resources)

Both services work together under a new **Security Service Edge (SSE)** network security category.

## ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key Terms and Definitions**

### **Global Secure Access**
- **Microsoft Entra Internet Access**: Secures SaaS applications, including Microsoft services, and protects users, devices, and data from internet threats.
- **Microsoft Entra Private Access**: Provides secure access to private corporate resources, for both office and remote users.

### **Security Service Edge (SSE)**
- A new security model addressing issues like VPN vulnerabilities, internet-based asset protection, and remote office security.

### **Zero Trust**
- A network security approach where identity, device, and location are continuously verified to protect apps and data.

## ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**

### **Microsoft Entra Private Access** 
- Replaces traditional **VPNs** by blocking lateral attack movement and reducing over-permissioned access.
- **Quick Access**: Set up a new application to define and control access to private resources.
- **Global Secure Access App**: A more granular approach, allowing multiple containers (enterprise apps) for different resources and specific access policies.

**Visual**: ![Quick Access Diagram](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/quick-access-diagram.png)

## ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**

### **How Private Access Works**
- New enterprise apps serve as containers for private resources.
- For **Quick Access**, define the resources with details like FQDN, IP address, and ports, then link conditional access policies.

**Visual**: ![Per-App Access Diagram](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/per-app-access-diagram.png)

## ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
### **Microsoft Entra Internet Access**
- **Secure Web Gateway (SWG)** protects users from internet threats by filtering traffic.
- Protects **SaaS apps** and **other internet traffic**, using Conditional Access policies and **Continuous Access Evaluation (CAE)** to ensure security.

### Key Features:
- Protection against identity theft.
- Tenant restrictions prevent unauthorized data access.
- **Web Content Filtering**: Controls access to websites by category and domain.

## ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key Terms and Definitions**

- **SWG**: A cybersecurity solution to filter web traffic.
- **CAE**: Constant evaluation to ensure user access remains secure, adjusting in real-time when needed.

### **Visual**: ![Global Secure Access Dashboard](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/global-secure-access-snapshot-widget.png)

## ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
### **Global Secure Access Dashboard**
- Provides **network traffic visualizations** for both **Private Access** and **Internet Access** services.
- Widgets include:
  - **Snapshot**: Overview of user and device activity.
  - **Usage Profiling**: Shows access patterns by category.

**Visual**: ![Usage Profiling](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/dashboard-usage-profiling.png)

### **Alerts and Notifications**
- Alerts you to network irregularities, like unhealthy devices or suspicious activities.
  
**Visual**: ![Alerts and Notifications](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/dashboard-alerts-notifications.png)

## ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**

- **Cross-tenant Access**: Shows usage data for multiple tenants, sign-ins, and devices.
  
**Visual**: ![Cross-Tenant Access](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/cross-tenant-access.png)

### **Web Category Filtering**
- Displays blocked or allowed web content categories.

**Visual**: ![Device Status](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/device-status.png)

