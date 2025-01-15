<h1>Self Hosted CyberArk Lab</h1>

<h2>Description</h2>
This project involved the creation of a self-hosted CyberArk lab to simulate enterprise-level Privileged Access Management (PAM) operations. Utilizing a virtualized environment, I deployed CyberArk components, including the Digital Vault, Password Vault Web Access (PVWA), Privileged Session Manager (PSM), and Central Policy Manager (CPM). The lab was integrated with Active Directory for centralized authentication and account management, enabling secure onboarding of privileged accounts. I also configured password rotation policies, session monitoring, and audit logging to demonstrate real-world PAM workflows and security best practices. 
<br />

<h2>Languages and Environments Used (PaaS Components) </h2>

- <b>VirtualBox</b>
- <b>Windows Server 2012 ISO</b>
- <b>.NET Framework</b> 
- <b>CyberArk</b>
- <b>Vault</b>
- <b>Password Vault Web Access</b>
- <b>PrivateArk Client</b>
- <b>Privileged Session Manager</b>
- <b>Central Policy Manager</b>
- <b>PowerShell</b> 
- <b> Internet Information Services (IIS)</b>


<h2>Project walk-through:</h2>

<p align="center">
  
- <b>Deploy and Configure Virtual Machine</b> 
  
- <b>Install .NET Framework</b>

- <b>Run Digital Vault Setup<b>
<p align="center">
<img src="https://imgur.com/ufIc2e4.png" height="80%" width="80%" alt="Start Digital Vault Installation"/>
<img src="https://imgur.com/gHfY19i.png" height="80%" width="80%" alt="Choose Vault Installation Mode"/>
<img src="https://imgur.com/OfCXw4H.png" height="80%" width="80%" alt="Choose path of license file"/>
<img src="https://imgur.com/nye8DJQ.png" height="80%" width="80%" alt="Choose Operator CD Path"/>
<img src="https://imgur.com/JQbtrbu.png" height="80%" width="80%" alt="Configure remote control agent"/>
<img src="https://imgur.com/tBmmB3j.png" height="80%" width="80%" alt="Server Machine Hardening"/>
<img src="https://imgur.com/oozQ8E3.png" height="80%" width="80%" alt="Server Machine Hardening"/>
<img src="https://imgur.com/emjtdiq.png" height="80%" width="80%" alt="Setup Complete"/>

 <p align="center"> 
PrivateArk Client: <br/>
<img src="https://imgur.com/OYvrQNJ.png" height="80%" width="80%" alt="PrivateArk Client Setup"/>
<img src="https://imgur.com/Nd85hEr.png" height="80%" width="80%" alt="Configure Vault and Client Integration"/>
<img src="https://imgur.com/aAsTsob.png" height="80%" width="80%" alt="Client Setup Complete"/>
<img src="https://imgur.com/Qk3nD7I.png" height="80%" width="80%" alt="Vault Server"/>
<img src="https://imgur.com/3SSvy3s.png" height="80%" width="80%" alt="PrivateArk Client"/>
<img src="https://imgur.com/4r7Kjfk.png" height="80%" width="80%" alt="Verification of ProdVault"/>

<p align="center"> 
Configuration of Password Vault Web Access Server: <br/>
  - <b>PVWA Server IP Configuration<b>
<img src="https://imgur.com/iMjQEDR.png" height="80%" width="80%" alt="PVWA Server IP Configuration"/>
<img src="https://imgur.com/oME90Z9.png" height="80%" width="80%" alt="Configure Web Server (IIS)"/>
<img src="https://imgur.com/Fc1Yw3g.png" height="80%" width="80%" alt="Configure Web Server (IIS)"/>
<img src="https://imgur.com/qRSAcZv.png" height="80%" width="80%" alt="Begin Installation of IIS"/>
<img src="https://imgur.com/6nqcxza.png" height="80%" width="80%" alt="Begin Installation of IIS"/>
<img src="https://imgur.com/3tAKG5c.png" height="80%" width="80%" alt="Launch IIS"/>
<img src="https://imgur.com/4FfnSVp.png" height="80%" width="80%" alt="Configure Site Bindings"/>
<img src="https://imgur.com/mLN5B23.png" height="80%" width="80%" alt="Configure Site Bindings"/>
<img src="https://imgur.com/1eLefne.png" height="80%" width="80%" alt="PVWA Setup"/>
<img src="https://imgur.com/hPTV4Bo.png" height="80%" width="80%" alt="PVWA Web Application Details Setup "/>
<img src="https://imgur.com/NtPJ3E3.png" height="80%" width="80%" alt="PVWA and Vault Server Connection Setup"/>
<img src="https://imgur.com/gOP5vCS.png" height="80%" width="80%" alt="PVWA Setup Complete"/>
<img src="https://imgur.com/6JLBVq0.png" height="80%" width="80%" alt="Vwerification From Vault Server"/>

<p align="center"> 
Configuration of Central Policy Manager: <br/>
<img src="https://imgur.com/oLF6sXu.png" height="80%" width="80%" alt="Run Centraol Policy Manager Setup"/>
<img src="https://imgur.com/LvdtW70.png" height="80%" width="80%" alt="Verification of CPM"/>
<img src="https://imgur.com/Ybcjao6.png" height="80%" width="80%" alt="Verification of CPM"/>
<img src="https://imgur.com/v1unlNj.png" height="80%" width="80%" alt="Create a Safe and Assign to CPM"/>
<br />
<br />
<p align="center"> 
Deploy Windows Server and configure IP settings: <br/>
<img src="https://imgur.com/jLoz7Tz.png" height="80%" width="80%" alt="Deploy Virtual Machine and configure IP"/>

 <p align="center"> 
Install Active Directory Domain Services: <br/>
<img src="https://imgur.com/rgT3u0S.png" height="80%" width="80%" alt="Active Directory Domain Service Installation"/>
<img src="https://imgur.com/vpDjEyM.png" height="80%" width="80%" alt="Complete Installation"/>

<p align="center"> 
Configuration of Active Directory Domain Services: <br/>
<img src="https://imgur.com/Wmn26Kp.png" height="80%" width="80%" alt="Deployment Configuration"/>
<img src="https://imgur.com/4e0L2a1.png" height="80%" width="80%" alt="Domain Controller Configuration"/>
<img src="https://imgur.com/MYwgCSL.png" height="80%" width="80%" alt="Passed Validation of Configuration"/>
<img src="https://imgur.com/zutjmEt.png" height="80%" width="80%" alt="Complete"/>
  
<p align="center"> 
Deploy and Configure PSM Server and IP Settings<br/>
<img src="https://imgur.com/vOys9yN.png" height="80%" width="80%" alt="IP Configurations"/>
<img src="https://imgur.com/nuyptRD.png" height="80%" width="80%" alt="Joined PSM Server to Active Directory Domain"/>
<img src="https://imgur.com/o5wpfHi.png" height="80%" width="80%" alt="Install .NET Framework on PSM Server "/>
<img src="https://imgur.com/UHs5GCG.png" height="80%" width="80%" alt="Run PSM Installation Automation Using PowerShell"/>
<img src="https://imgur.com/edYFJri.png" height="80%" width="80%" alt="Installation Automation Complete"/>
<img src="https://imgur.com/KSFcaAO.png" height="80%" width="80%" alt="Start PSM Installation"/>
<img src="https://imgur.com/Dq0w6fk.png" height="80%" width="80%" alt="PSM Installation"/>
<img src="https://imgur.com/pL1ohWO.png" height="80%" width="80%" alt="PSM Installation"/>
<img src="https://imgur.com/jkIFhDL.png" height="80%" width="80%" alt="PSM Installation"/>
<img src="https://imgur.com/9Avgxuz.png" height="80%" width="80%" alt="Vault Server and PSM Integration "/>
<img src="https://imgur.com/GWUSmzs.png" height="80%" width="80%" alt="PSM Installation"/>

<br />
<br />
<h2>Conclusion:</h2>
This self-hosted CyberArk lab showcased my ability to deploy, configure, and manage a Privileged Access Management solution from the ground up. By simulating real-world PAM operations, I reinforced my hands-on experience in securing privileged accounts, automating credential lifecycle management, and enhancing session security through monitoring and audit capabilities. The project highlights my proficiency in CyberArk implementation and my commitment to mastering IAM technologies essential for modern enterprise security.
