<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

<h1>Installing osTicket in Microsoft Azure</h1>

This project demonstrates deploying the open-source help desk ticketing system <b>osTicket</b> inside a Windows 10 Virtual Machine hosted in Microsoft Azure.  

The lab covers full environment setup, dependency installation, database configuration, IIS configuration, and final web-based deployment.

---

<h2>🖥️ Environment & Technologies Used</h2>

- Microsoft Azure (Virtual Machine)
- Windows 10
- Remote Desktop (RDP)
- Internet Information Services (IIS) with CGI
- PHP Manager for IIS
- PHP
- MySQL 5.5
- HeidiSQL
- Microsoft Visual C++ Redistributable
- osTicket (Open Source Ticketing System)

---

<h2>📌 Project Overview</h2>

In this lab, I:

- Created and configured a Windows 10 VM in Azure (CPU, RAM, credentials)
- Installed and configured IIS web server
- Installed PHP and required extensions
- Installed MySQL database server
- Created an osTicket database using HeidiSQL
- Configured file permissions and dependencies
- Completed the osTicket web-based installation
- Logged into both Admin and User portals

---

<h2>⚙️ Installation Walkthrough</h2>

<h3>Step 1: Create Windows 10 Virtual Machine in Azure</h3>

- Deployed a Windows 10 VM in Microsoft Azure  
- Configured CPU, RAM, networking settings  
- Set administrator username and password  
- Connected via Remote Desktop  

<p align="center">
<img src="YOUR_SCREENSHOT_LINK_HERE" width="80%" alt="Azure VM Setup Screenshot"/>
</p>

---

<h3>Step 2: Install and Configure IIS (Web Server)</h3>

- Enabled IIS through Windows Features  
- Enabled CGI under Application Development Features  
- Verified IIS default webpage loads successfully  

<p align="center">
<img src="YOUR_SCREENSHOT_LINK_HERE" width="80%" alt="IIS Installation Screenshot"/>
</p>

---

<h3>Step 3: Install PHP & Required Dependencies</h3>

- Installed PHP Manager for IIS  
- Installed PHP binaries  
- Installed Microsoft Visual C++ Redistributable  
- Enabled required PHP extensions:
  - IMAP  
  - International  
  - OPCache  

- Configured IIS to process PHP files properly  

<p align="center">
<img src="YOUR_SCREENSHOT_LINK_HERE" width="80%" alt="PHP Configuration Screenshot"/>
</p>

---

<h3>Step 4: Install and Configure MySQL Database</h3>

- Installed MySQL 5.5  
- Configured database credentials:
  - Username: root  
  - Password: root  
- Installed HeidiSQL  
- Created a new database for osTicket  

<p align="center">
<img src="YOUR_SCREENSHOT_LINK_HERE" width="80%" alt="MySQL and HeidiSQL Screenshot"/>
</p>

---

<h3>Step 5: Deploy osTicket</h3>

- Downloaded and extracted osTicket installation files  
- Copied files into IIS web root directory  
- Renamed “upload” folder to “osTicket”  
- Set proper file permissions for configuration files  
- Completed web-based installer:
  - Helpdesk name
  - Admin user details
  - Database connection details  

- Successfully logged into:
  - Admin Portal  
  - User Portal  

<p align="center">
<img src="YOUR_SCREENSHOT_LINK_HERE" width="80%" alt="osTicket Admin Portal Screenshot"/>
</p>

---

<h2>✅ Final Result</h2>

Successfully deployed a fully functional osTicket help desk system hosted on a Windows 10 Azure VM, accessible through a web browser.

This project demonstrates skills in:

- Cloud infrastructure deployment
- Web server configuration
- Database setup and management
- Dependency troubleshooting
- Application deployment
- System administration fundamentals

---

<h2>🔐 Skills Demonstrated</h2>

- Azure VM provisioning
- Windows Server configuration
- IIS management
- PHP configuration
- MySQL administration
- File permission management
- Web application deployment
- 
