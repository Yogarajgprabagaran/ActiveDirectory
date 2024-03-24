# Active Directory Domain Administration

<h2>Active Directory Initial Configuration</h2>

<h2>Description</h2>
This project involves configuring and managing an Active Directory domain on Windows Server 2019 using Server Manager and administrative tools. The project walks through various tasks such as setting up domain controllers, creating organizational units (OUs), managing user accounts and security groups, and integrating member servers into the domain.
<h2>Utilities Used</h2>
<b>Vsphere</b> <br/>
<b>Windows Server 2019 templates</b> 
<h2>Environments Used </h2>
<b>Windows Server 2019 VM for Domain Controller</b> <br/>
<b>Two Windows Server 2019 VM's for Domain Computers</b>
<h2>Project Walk-through:</h2>
<p align="center">
Adding Active Directory Domain Services (ADDS)<br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/5cda7ff5-e7b4-478e-8f9a-b3c8e3a327b6" height="80%" width="80%"/>
<br />
<br/>
Promoting Server to Domain Controller<br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/f9328054-bd40-471c-a5aa-1a250379669b" height="80%" width="80%" alt="Active Directory Configuration Steps"/>
<br/>
<br/>
Creation of Organizational Units (OUs):  <br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/0513f103-7c79-440c-aa63-92c0ad2ea415" height="80%" width="80%"/>
<br />
<br />
Creation of a Security Group and its User in Service Accounts OU: <br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/4e8880fb-e7b9-4275-ad9c-d1d399fd72ccs" height="80%" width="80%"/>
<br />
<br />
Creation of Standard user accounts in Employees OU:  <br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/86515fb5-416c-457e-9c12-edb208163b30" height="80%" width="80%"/>
<br />
<br />
Creation of Administrative user account and the adding it to the "Domain Admins" Group in Administrators OU:  <br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/2281306e-e4fd-407d-ae64-abd61e2e9e0c" height="80%" width="80%"/>
<br />
<br />
Configure DNS server address to point to the domain controller in VM02 and VM03:  <br/>
VM02 Sample Screenshot below but the same was done for VM03: <br />
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/5479b9d4-4dc6-4819-84d3-a4e2fc2222ad" height="80%" width="80%"/>
<br />
<br />
Successful addition of VM02 and VM03 to the domain: <br />
VM02 Sample Screenshot below but the same was done for VM03: <br />
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/e8293da5-915d-4533-abe8-700a7267943c" height="80%" width="80%"/>
<br />
<br />
Successful login with the administrative account in VM03:  <br/>
VM03 Sample Screenshot below but the same was verfified in VM02: <br />
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/c532c649-7e3d-4c9e-8b36-92f433bc4765" height="80%" width="80%"/>
<br />
<br />
Verifying the above steps in Active Directory Users and Computers <br/>
<img src="https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/d202db2b-9120-4d00-aaa3-326e5a954f3f" height="80%" width="80%"/>
<img src=https://github.com/Yogarajgprabagaran/ActiveDirectory-Projects/assets/162944315/3770dfc1-eeff-44c6-a639-6f753faf5e47" height="80%" width="80%"/>
<br />
<br />
<h2>Other Active Directory Projects and Labs:</h2>
  Active Directory Initial Configuration <br />
  Group Policy and File System Permissions <br />
  WSUS Config and Active Directory Backup and Authoritative Restore <br />
</p>
