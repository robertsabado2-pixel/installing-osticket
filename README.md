<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

<h1>Installing osTicket</h1>

This project demonstrates the installation and configuration of <b>osTicket</b>, an open-source help desk ticketing system.  
The lab was performed in a virtualized environment using Microsoft Azure and Windows 10.

---

<h2>🎥 Video Demonstration</h2>

- [YouTube: Installing osTicket in Azure](https://www.youtube.com)

---

<h2>🖥️ Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Windows 10 (21H2)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS)
- PHP Manager for IIS
- MySQL
- osTicket v1.15.8

---

<h2>💻 Operating System</h2>

- Windows 10 Pro (21H2)

---

<h2>📋 Prerequisites</h2>

Before installing osTicket, the following components were installed:

- IIS (Web Server)
- CGI Module
- PHP Manager for IIS
- MySQL Database Server
- Microsoft Visual C++ Redistributable
- URL Rewrite Module

---

<h2>⚙️ Installation Steps</h2>

<h3>Step 1: Create Azure Virtual Machine</h3>

<p align="center">
<img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="Azure VM Creation"/>
</p>

- Deployed a Windows 10 VM in Microsoft Azure  
- Configured networking and security settings  
- Connected via Remote Desktop  

---

<h3>Step 2: Install IIS and Required Features</h3>

<p align="center">
<img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="IIS Installation"/>
</p>

- Enabled IIS through Windows Features  
- Enabled CGI under Application Development  
- Verified web server functionality in browser  

---

<h3>Step 3: Install PHP and MySQL</h3>

<p align="center">
<img src="https://i.imgur.com/DJmEXEB.png" width="80%" alt="PHP and MySQL Installation"/>
</p>

- Installed PHP Manager for IIS  
- Configured PHP environment variables  
- Installed MySQL and created osTicket database  

---

<h3>Step 4: Install osTicket</h3>

- Downloaded osTicket installation files  
- Moved files to IIS root directory  
- Configured permissions on upload/include folder  
- Completed web-based setup wizard  
- Connected osTicket to MySQL database  

---

<h2>✅ Result</h2>

Successfully deployed a fully functional osTicket help desk system accessible through a web browser.

# installing-osticket
