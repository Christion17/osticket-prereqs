<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Install / Enable IIS in Windows WITH CGI and Common HTTP Features:
    World Wide Web Services -> Application Development Features ->
    [X] CGI,
    [X] Common HTTP Features
- Install/Enable IIS Management Console:
    Internet Information Services -> Web Management Tools -> IIS Management Console
	  [X] IIS Management Console
- Download and install PHP Manager for IIS
- Downlaod and isntall the Rewrite Module
- Create the directory C:\PHP
- Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip) and unzip the contents into C:\PHP
- Download and install VC_redist.x86.exe.
- Download and install MySQL 5.5.62 (mysql-5.5.62-win32.msi)
- Open IIS as an Admin
- Register PHP from within IIS
- Reload IIS (Open IIS, Stop and Start the server)
- Install osTicket v1.15.8
- Reload IIS (Open IIS, Stop and Start the server)
- Go to sites -> Default -> osTicket
- Rename: ost-config.php:
    From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php,
    To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
- Assign Permissions: ost-config.php:
    Disable inheritance -> Remove All,
    New Permissions -> Everyone -> All
- Continue Setting up osTicket in the browser:
    Named Helpdesk,
    Default email (receives email from customers)
- Download and install HeidiSQL:
    Open Heidi SQL,
    Create a new session, root/Password1,
    Connected to the session,
    Created a database called “osTicket”
- Finish creating the osTicket in browser:
    MySQL Database: osTicket,
    MySQL Username: root,
    MySQL Password: Password1,
    Clicked “Install Now!”
- Clean up:
    Delete: C:\inetpub\wwwroot\osTicket\setup,
    Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php

<h2>Installation Steps</h2><p>
  
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
