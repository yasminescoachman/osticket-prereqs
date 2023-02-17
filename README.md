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

- Create Resources in Azure ( Resource Group & Virtual Machine)
- Enable/Install Internet Information Services/IIS in Windows with CGI
- Install PHP Manager for IIS
- Install Rewrite Module
- Create directory labled C:\PHP
- Download PHP 7.3.8 and unzip contents into the C:\PHP
- Install VC_redist.x86.exe
- Download and install MySQL ( Set-up and standard configuration)
- Register PHP from within IIP (Note: Reload IIS by opening IIS to stop and restart the server)
- Install osTicket (Restart IIS again as noted in previous step)
- Go to sites --> Default --> osTicket then click Browse*80 
- Enable extensions that are not enabled
- Rename ost-sampleconfig.php to ost-config.php
- Assign Permissions 
- Install Heidi SQL
- Proceed with setting up osTicket in the browser


<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/1HIG877.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> Above is a picture indicating that Internet Information Services was succcessfully enabled. 

</p>
<br />

<p>
<img src="https://i.imgur.com/WiphDEA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p> The screenshot above is showing all PHP 7.3.8 contents extracted into C:\PHP.

</p>
<br />

<p>
<img src="https://i.imgur.com/v4fvOyT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Pictured above is a screen capture showing that osTicket was successfully installed.
</p>
<br />
