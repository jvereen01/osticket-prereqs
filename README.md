# osticket-prereqs
<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services(IIS)
- Install Web Platform installer
- Install MySQL(set up username and password)
- Install C++ Redistributable 
- Configure permissions and Intall osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/EsfxF8C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install and enable Internet Information Services (IIS) on Windows with CGI and Common HTTP Features, follow these steps. Open the "Server Manager" on your Windows machine, navigate to "Manage" and select "Add Roles and Features." In the "Add Roles and Features Wizard," proceed to the "Server Roles" section, and check "Web Server (IIS)." Within the "Web Server (IIS)" role, under "Application Development," select both "CGI" and "Common HTTP Features." Then, proceed to the "Web Server" section, and ensure that "IIS Management Console" is selected under "Web Management Tools." Complete the installation process, and IIS will be installed with CGI, Common HTTP Features, and the IIS Management Console.
</p>
<br />

<p>
<img src="https://i.imgur.com/D2LZQuC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/VNNZfq8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install MySQL and C++ Redistributable to start the next process. Then, open Internet Information Services (IIS) as an administrator on your Windows server. Once in IIS, register PHP to ensure compatibility. Following this, reload IIS by stopping and starting the server. Proceed to install osTicket version 1.15.8 by first downloading it from the Installation Files Folder. After downloading, extract the contents and copy the "upload" folder to the directory c:\inetpub\wwwroot. Within this directory, rename the "upload" folder to "osTicket." This sequence of steps ensures the proper configuration of IIS with PHP support and sets up the necessary environment for hosting osTicket version 1.15.8 on your Windows server.
</p>
<br />

<p>
<img src="https://i.imgur.com/sJXrztg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/VDmgE2P.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
<img src="https://i.imgur.com/stQ0Pky.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <img src="https://i.imgur.com/Q0PKFiZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
There is some extentions that are not enabled so we need to enable those.  Next we need to assign the permisssions and finish setting up osTicket through the browser.
</p>
<br />
