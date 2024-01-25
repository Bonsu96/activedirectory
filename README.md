# On-premises Active Directory Deployed in the Cloud (Azure)
This tutorial illustrates the implementations of Microsoft Azure Active Directory
<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1: Access Azure Portal
- Step 2: Navigate to Active Directory
- Step 3: Create New Active Directory
- Step 4: Review and Create
- Step 5: Create a Deployment
- Step 6: Access Directory

<h2>Deployment and Configuration Steps</h2>

Creating an Active Directory in Azure involves using Azure Active Directory (Azure AD), which is Microsoft's cloud-based identity and access management service. Azure AD is not the same as the traditional on-premises Active Directory, but it serves as an identity provider for cloud-based and on-premises applications. Here are the steps to create an Active Directory in Azure:

### 1. **Sign in to the Azure Portal:**
   - Go to the [Azure Portal](https://portal.azure.com/) and sign in with your Azure account.

### 2. **Navigate to Azure Active Directory:**
   - In the Azure Portal, click on "Azure Active Directory" in the left-hand navigation menu.

### 3. **Create a New Azure Active Directory:**
   - In the Azure Active Directory pane, click on "Create a directory."
   - Choose "Create a new directory."
   - Fill in the required information, such as the organization name and initial domain, and select your country or region.
   - Click on the "Review + create" button.

### 4. **Review and Create:**
   - Review your configuration settings.
   - If everything looks correct, click on the "Create" button.

### 5. **Wait for Deployment:**
   - Azure will deploy your new Azure AD directory. This process may take a few minutes.

### 6. **Access the New Azure AD Directory:**
   - Once the deployment is complete, go to the Azure Active Directory pane in the Azure Portal.
   - You'll see your newly created directory listed.

### Additional Configurations:

- **Configure Users and Groups:**
  - You can add users and groups to your Azure AD directory to manage access to resources.

- **Configure Applications:**
  - Azure AD can be used to manage access to various applications. You can configure applications to integrate with Azure AD for authentication and authorization.

- **Configure Domain Names:**
  - If you want to use a custom domain, you can configure domain names in the Azure AD settings.

- **Configure Security Settings:**
  - Implement security policies and configurations to enhance the security of your Azure AD directory.

### Note:
Azure AD is a cloud-based service, and it is distinct from the traditional on-premises Active Directory. If you need to set up a traditional Active Directory on virtual machines in Azure, you would typically do that by creating a Windows Server virtual machine and configuring it as a domain controller. However, for cloud-based identity and access management, Azure AD is the recommended solution.

Ensure that you understand the differences between Azure AD and on-premises Active Directory based on your specific requirements.
