# Active Directory Home Lab  
Based on YouTube Guide: *How to Create Active Directory Domain Controller on Windows Server*  
Link: https://www.youtube.com/watch?v=mWqYyl89QaY  

## Objective
This project follows a structured walkthrough to build a fully functional Active Directory environment from scratch using Windows Server and Windows 10. The goal was to learn how identity, authentication, and domain services work in an enterprise network while practicing system administration tasks hands-on.

---

## Skills Learned
- Installing and configuring Windows Server  
- Deploying Active Directory Domain Services (AD DS)  
- Promoting a server to a Domain Controller  
- Creating a domain and setting up DNS  
- Adding organizational units (OUs)  
- Creating and managing domain users  
- Domain joining Windows client machines  
- Understanding authentication, permissions, and directory structure  
- Applying Group Policy Objects (GPOs)  

---

## Tools Used
- Windows Server 2019 / 2022  
- Windows 10 Client VM  
- Oracle VirtualBox or VMware Workstation  
- Active Directory Users and Computers (ADUC)  
- Group Policy Management Console (GPMC)  
- PowerShell  
- Event Viewer  

---

## Steps & Screenshots  
*(Add screenshots as you complete each step — replacing IMAGE_URL_HERE with your images.)*

---

### **Ref 1: Windows Server Installation**
<img src="IMAGE_URL_HERE" width="800">

*Installed Windows Server and configured the initial server settings (hostname, network, updates).*

---

### **Ref 2: Installing Active Directory Domain Services**
<img src="IMAGE_URL_HERE" width="800">

*Added the AD DS role through Server Manager to prepare the server for promotion.*

---

### **Ref 3: Promoting Server to Domain Controller**
<img src="IMAGE_URL_HERE" width="800">

*Promoted the server by creating a new forest and domain as shown in the tutorial.*

---

### **Ref 4: Domain Setup Complete**
<img src="IMAGE_URL_HERE" width="800">

*Domain Controller successfully configured with DNS and default AD structure.*

---

### **Ref 5: Creating Organizational Units**
<img src="IMAGE_URL_HERE" width="800">

*Created OUs to organize users, computers, and administrative accounts.*

---

### **Ref 6: Creating User Accounts**
<img src="IMAGE_URL_HERE" width="800">

*Added domain users following naming conventions and group assignments.*

---

### **Ref 7: Joining Windows 10 Client to Domain**
<img src="IMAGE_URL_HERE" width="800">

*Connected the Windows 10 VM to the domain and validated login.*

---

### **Ref 8: Group Policy Configuration**
<img src="IMAGE_URL_HERE" width="800">

*Created and linked GPOs to control user environments and enforce security settings.*

---

## Summary
Following this video-based lab provided hands-on experience in building and managing a full Active Directory environment. This strengthened knowledge in system administration, identity management, and enterprise networking — all core skills for System Administrator and IT roles.

