<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket Logo"/>
</p>

# Installing osTicket in Microsoft Azure

This project demonstrates deploying the open-source help desk ticketing system **osTicket** inside a Windows 10 Virtual Machine hosted in Microsoft Azure.  
Follow the steps below to see exactly how this environment was built and configured.

---

## 🖥️ Environment & Technologies Used

- Microsoft Azure (Virtual Machine)
- Windows 10 (21H2)
- Remote Desktop Protocol (RDP)
- Internet Information Services (IIS) with CGI
- PHP Manager for IIS
- PHP
- MySQL 5.5
- HeidiSQL
- Microsoft Visual C++ Redistributable
- osTicket (Open Source Ticketing System)

---

## ⚙️ Installation Walkthrough

### Step 1: Create Windows 10 Virtual Machine in Azure

- Deployed a Windows 10 VM in Microsoft Azure  
- Configured CPU, RAM, networking settings  
- Set administrator username and password  
- Connected via Remote Desktop  

<p align="center">
<img width="2215" height="1142" alt="Screenshot 2026-03-03 141733" src="https://github.com/user-attachments/assets/1e0b9e5f-4f4b-42f1-b22c-016ee969140c" />
  
`screenshots/vm-setup.png`  
</p>

---

### Step 2: Install and Configure IIS (Web Server)

- Enabled IIS through Windows Features  
- Enabled CGI under Application Development Features  
- Verified IIS default webpage loads successfully  

<p align="center">
<img width="908" height="1027" alt="Screenshot 2026-03-03 142544" src="https://github.com/user-attachments/assets/66563f65-0885-4b7f-ac57-db65e3d296b5" />
  
`screenshots/iis-install.png`  
</p>

---

### Step 3: Install PHP & Required Dependencies

- Installed PHP Manager for IIS  
- Installed PHP binaries  
- Installed Microsoft Visual C++ Redistributable  
- Enabled required PHP extensions:  
  - IMAP  
  - International  
  - OPCache  
- Configured IIS to process PHP files properly  

<p align="center">
<img width="1119" height="816" alt="Screenshot 2026-03-03 143043" src="https://github.com/user-attachments/assets/fe964981-3822-469a-8cd3-70b522e0c1ed" />
  
`screenshots/php-config.png`  
</p>

---

### Step 4: Install and Configure MySQL Database

- Installed MySQL 5.5  
- Configured database credentials:
  - Username: root  
  - Password: root  
- Installed HeidiSQL  
- Created a new database for osTicket  

<p align="center">
<img width="1065" height="731" alt="Screenshot 2026-03-03 143440" src="https://github.com/user-attachments/assets/e470de99-612a-48e5-a35b-8023e6cc135a" />

`screenshots/mysql-setup.png`  
</p>

---

### Step 5: Deploy osTicket

- Downloaded and extracted osTicket installation files  
- Copied files into IIS web root directory  
- Renamed `upload` folder to `osTicket`  
- Set proper file permissions for configuration files  
- Completed web-based installer:
  - Helpdesk name
  - Admin user details
  - Database connection details  
- Successfully logged into Admin & User portals  

<p align="center">
<img width="892" height="700" alt="Screenshot 2026-03-03 143819" src="https://github.com/user-attachments/assets/344da3a8-9e6f-4871-a720-cec21cf75cb5" />
  
`screenshots/osticket-admin.png`  
</p>

---

## ✅ Final Result

Successfully deployed a fully functional osTicket help desk system accessible through a web browser.

This project demonstrates skills in:

- Cloud infrastructure deployment
- Web server configuration
- Database setup and management
- Dependency troubleshooting
- Application deployment
- System administration fundamentals

---

## 🔐 Skills Demonstrated

- Azure VM provisioning  
- Windows Server configuration  
- IIS management  
- PHP configuration  
- MySQL administration  
- File permission management  
- Web application deployment
