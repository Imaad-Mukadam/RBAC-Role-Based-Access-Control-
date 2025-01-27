# RBAC-Role-Based-Access-Control

## What is RBAC?

In Azure, **RBAC (Role-Based Access Control)** is a system used to manage access to Azure resources. It allows you to assign specific roles to users, groups, or applications, granting them only the permissions they need to perform their tasks. This follows the **principle of least privilege**, reducing security risks.

### Key Points:
- **Role Assignments**: RBAC is based on assigning roles to users or groups at a specific scope (e.g., subscription, resource group, or resource).
- **Built-in Roles**: Azure provides predefined roles like:
  - **Owner**: Full access to all resources.
  - **Contributor**: Create and manage resources but cannot grant access.
  - **Reader**: View resources without making changes.
- **Custom Roles**: You can create custom roles tailored to specific requirements.
- **Scope Levels**:
  - **Management group**
  - **Subscription**
  - **Resource group**
  - **Specific resource**

### Example:
If you assign a **Reader** role to a user at the resource group level, they can only view resources in that group without modifying them.

Would you like an example of how to configure RBAC in Azure?

## Summary

### Configuring RBAC for an Azure Storage Account

In this setup, **Role-Based Access Control (RBAC)** is used to grant specific access permissions to a user for a storage account in Azure. 

#### Steps:
1. **Create a Storage Account**: Set up a new storage account in Azure.
2. **Assign Access Control**:
   - Navigate to the **Access Control (IAM)** blade of the storage account.
   - Click **Add role assignment**.
   - Choose the appropriate role (e.g., **Storage Blob Data Reader** or **Storage Blob Data Contributor**).
   - Assign the role to a user, group, or service principal.
3. **Verify Access**: Ensure the user has the intended access by testing the permissions.

## Step - 1

i. **Create a Storage Account**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/16095d9c7f1023544169213cc0a339accabf8fed/1.PNG)

ii. **Create Container to Upload Some files** 

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/2.PNG)

iii. **Upload some Random files**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/3.PNG)

## Step - 2

i. **Create a Demo User , whom we will give the access of Storage acoount**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/4.PNG)

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/5.PNG)

ii. **Creating a Demo user, Give them and click create Button**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/6.PNG)

iii. **Copy the gmail of demo user and login with the demo user**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/7.PNG)

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/8.PNG)

## Step - 3

i. **Open the storage Account to give access to demo user**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/9.PNG)

ii. **Click on Add Button then click on Add role Assignment**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/10.PNG)

iii. **In the **Role Assignment** section, select the role you want to assign to the user. In this case, I am assigning the **Owner** role, which grants full permissions to manage all actions on the resource.**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/11.PNG)

iii. **In the **Members** section, select the member to whom you want to assign the permission.**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/12.PNG)

iv. **In the **Condition** step, select the recommended permission, then click **Review + Assign** to finalize the role assignment.**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/13.PNG)

v. **You can view your storage account in the demo account.**

![image alt](https://github.com/Imaad-Mukadam/RBAC-Role-Based-Access-Control-/blob/33b33f0c8f6fdad43dc2584ab0cf87c7d1c9cec9/14.PNG)
