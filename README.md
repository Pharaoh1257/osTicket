<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system, osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Enable Internet Information Services
- Install the web platform installer
- Install C++ redistributable
- Install MySQL
- Configure permissions and install osTicket

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/zbi0PdX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To enable the IIS (Internet Information Services), you must first create a new virtual machine in Azure, and you can name the resource group osTicket. Follow the preceding steps and click Review & Confirm. Once the VM is created, open the remote desktop, copy and paste the ip address, and follow the proceeding steps within the remote desktop. From there, you can download the osTicket files and their dependencies, drag that zipped folder to the desktop, and unzip it there to begin enabling the IIS web server for osTicket. You can click start, type in control panel and open then click programs. There you will click the "Turn Windows Features On/off), then click and expand the IIS box, expand the www service box, expand application development features, and finally click the CGI box, then click ok to enable it. 
</p>
<br />

<p>
<img src="https://i.imgur.com/HMXk3ZB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, install the PHP Manager web platform installer and the supported files needed for osTicket to work properly. Go to the osTicket unzipped folder on the desktop and install the PHP Manager, following the steps. From within the same folder, install the required supported files. Next, create a directory for PHP. Simply click File Explorer and open the C-drive, and create a PHP folder. Unzip the files from the osticket folder, and extract all of the language PHP files. Review the extracted files in the C drive. 
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

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
