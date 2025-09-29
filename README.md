# LabActiveDirectory-Powershell
<p><strong>Windows Server Active Directory Lab Environment</strong></p>

<p>I designed and deployed a fully functional Windows Server domain infrastructure using VMware in a virtual lab environment.</p>

<p><strong>Setup:</strong></p>
<ul>
  <li>Windows Server 2019 configured as a Domain Controller (DC)</li>
  <li>Windows 10 virtual machine joined as a domain client</li>
</ul>

<p><strong>Key Configurations & Services:</strong></p>
<ul>
  <li>Installed and configured Active Directory Domain Services (AD DS)</li>
  <li>Set up DNS and DHCP with a defined IP scope for automated address assignment</li>
  <li>Enabled Routing and Remote Access Service (RRAS) with NAT to allow private network clients to access external resources</li>
  <li>Created administrator accounts, security groups, and Organizational Units (OUs) for structured user management</li>
</ul>

<p><strong>Automation & Scripting:</strong></p>
<ul>
  <li>Built PowerShell and Python scripts to automate the creation of 1000 Active Directory users</li>
  <li>Validated functionality by successfully joining the Windows 10 client to the domain and logging in with generated accounts</li>
</ul>
<h2>Youtube Video</h2>
<p align="center">
Topology <br/>
<img src="https://imgur.com/cyGH177.png" height="80%" width="80%" alt="Topology"/>
<br />
<p align="center">
1. Installled VMs(Windows server2019 (DC) and Windows 10(Client) <br/>
<img width="80%" height="80%" alt="WINDOWS SERVER 2019" src="https://github.com/user-attachments/assets/cfd00143-7a38-4fe1-aff8-8214d63a037b" />
<img width="80%" height="80%" alt="image" src="https://github.com/user-attachments/assets/1a5eb2f9-b5c3-4e54-8478-d6a5fea591ed" />


