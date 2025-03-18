
# Conditional Access in Microsoft Entra ID

### **Learning Objectives**
By the end of this module, you'll be able to:

- **Describe Conditional Access in Microsoft Entra**
- **Explain Conditional Access policy components**
  - **Assignments**
  - **Access Controls**

---

#### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
- **Conditional Access** provides an extra layer of security for authenticated users before they access data or assets.
- It uses **if-then statements** for policy enforcement.
  - Example: If a user belongs to a specific group, they must use **multi-factor authentication** (MFA) to sign in.

![Conditional Access](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/conditional-access.png)

---

#### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key terms and definitions**

- **Conditional Access**: A feature of **Microsoft Entra ID** that enforces security decisions based on factors like user, device, location, application, and risk.
- **MFA (Multi-Factor Authentication)**: A security measure requiring more than one form of verification before access is granted.

---

#### ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) **Additional but Important**
- Conditional Access policies **trigger after first-factor authentication**.
- It isn’t designed to be the first line of defense (e.g., for DoS attacks), but it can use signals from these events to adjust access.

---

#### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**

- **Example of Conditional Access policy**:
  - **If** a user belongs to a specific group, **then** MFA is required to access a certain application.

---

### **Conditional Access Policy Components**

#### **Assignments**
Assignments define **who**, **what**, **where**, and **when** a policy applies.

##### **Who**:
- Users or groups, directory roles, external guests, and workload identities.
  
##### **What**:
- **Cloud apps**: Microsoft services (e.g., Office 365), custom apps, and more.
- **User actions**: Registering security info, joining devices, etc.

##### **Where**:
- **Network location**: Trusted networks, IP ranges, or compliant devices.

##### **When**:
- **Conditions** like **sign-in risk** or **user risk** (e.g., compromised accounts).
- **Example**: If a user’s sign-in risk is high, MFA can be enforced.

![Conditional Access Policy Components](https://learn.microsoft.com/en-us/training/wwl-sci/explore-access-management-capabilities/media/conditional-access-policy-components-v3.png)

---

#### **Access Controls**
After Conditional Access policies are applied, decisions are made on how to control access to resources.

##### **Common Access Control Decisions**:

- **Block access**: Prevent the user from accessing resources.
- **Grant access**:
  - **With controls**: Requires MFA, specific authentication methods, or compliant devices.
  - **Without controls**: Straightforward access without additional checks.
- **Session controls**: Allows limited experiences within applications, like restricting the ability to download sensitive files or enforcing sign-in frequency.
  - **Example**: Restricting actions like copying or printing sensitive documents.

---

#### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important Summary**
- **Assignments** control the **who**, **what**, **where**, and **when** of Conditional Access.
- **Access controls** decide **how** a policy is enforced (block, grant, or session).

---

### **Key Takeaways**
- Conditional Access policies are **dynamic** and triggered by various signals.
- They use **assignments** and **access controls** to ensure secure and compliant access to resources.
- **MFA**, **risk-based policies**, and **device compliance** are common tools used in these policies to enforce security.

---

### **Next Steps**
- Review how Conditional Access can be applied to your environment and integrate it into your Zero Trust strategy.

