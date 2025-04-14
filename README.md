## Creating a Virtual Machine in Azure

## Project Summary

This project demonstrates how to create and configure a virtual machine (VM) using Microsoft Azure. The goal is to deploy a Windows 10 virtual machine within a newly created resource group and connect to it using Remote Desktop Protocol (RDP).

This project simulates a basic but realistic IT task often handled by support teams or system administrators — provisioning virtual infrastructure in the cloud.

---

### Languages & Tools Used:
- Microsoft Azure (via web portal)
- Remote Desktop Protocol (RDP)
- Windows 10 VM

---

### Environments Used:
- Azure Cloud Platform
- Windows 10 (host machine for RDP connection)

---

### Technologies and Services Used:
- Azure Resource Groups
- Azure Virtual Machines
- Azure Networking (Virtual Network, Public IP Address, Network Security Group)
- Windows 10 OS image

---

## Demonstration

### Step 1: Log in to Azure and Create a Resource Group
- Opened the [Azure Portal](https://portal.azure.com)
- Navigated to **Resource Groups**
- Clicked **Create**
- Entered the name: `MyVMGroup`
- Selected region: East US
- Clicked **Review + Create**

### Step 2: Deploy a Virtual Machine
- Navigated to **Virtual Machines**
- Clicked **Create**
- Chose the following settings:
  - **Subscription**: Free Trial or Pay-As-You-Go
  - **Resource Group**: `MyVMGroup`
  - **VM Name**: `MyWindowsVM`
  - **Region**: East US
  - **Image**: Windows 10 Pro
  - **Size**: Standard_B1s
  - **Authentication**: Username & password
  - **Public inbound ports**: Allow selected ports (RDP - port 3389)

### Step 3: Configure Networking
- Created new virtual network and subnet
- Enabled public IP
- Created a Network Security Group (NSG) with RDP (TCP 3389) inbound rule

### Step 4: Review and Create
- Clicked **Review + Create**
- Validated settings and clicked **Create**
- Azure began provisioning the virtual machine

### Step 5: Connect to the VM
- After deployment, clicked **Connect > RDP**
- Downloaded the `.rdp` file and opened it
- Entered login credentials set earlier
- Successfully connected to the Windows 10 VM

---

## Outcome

By following this process, I successfully created and connected to a fully functional Windows 10 virtual machine hosted on Microsoft Azure. This setup simulates what many IT professionals do in real-world environments — provisioning virtual resources, managing security, and configuring networking.

This project showcases basic cloud computing, virtualization, and remote access skills — all important in modern IT help desk and system admin roles.

---

## Author

**[Your Name]**  
IT Student — Course Careers Program  
GitHub: [yourusername]

 osticket-prereqs
