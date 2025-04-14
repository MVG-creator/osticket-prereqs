# Creating a Virtual Machine in Azure

## Project Title  
Creating a Virtual Machine in Azure

---

## Project Summary

This project demonstrates how to create and configure a Windows 10 virtual machine using Microsoft Azure.

### Languages Used  
No coding language was used. Configuration was completed through the Azure Portal interface.

### Environments Used  
- Microsoft Azure Portal  
- Windows 10 Virtual Machine  

### Technologies / Applications / Services Used  
- Azure Resource Group  
- Azure Virtual Machine (Standard_D2s_v3)  
- Virtual Network (VNet)  
- Network Interface  
- Network Security Group (NSG)  
- Public IP Address  
- Remote Desktop Protocol (RDP)  

---

## Demonstration

1. Created a resource group named `MyVMGroup` in the East US region.  
2. Created a Windows 10 virtual machine using the Azure Portal.  
   - Selected size: Standard_D2s_v3  
   - Allowed RDP (port 3389) for remote access  
3. Configured networking with default virtual network and a new NSG.  
4. Deployed the VM successfully.  
5. Copied the public IP address from the VM overview page.  
6. Opened Remote Desktop on my local machine and connected using the IP.  
7. Logged in with the admin username and password I set.  
8. Successfully accessed the Windows 10 virtual machine via RDP.


