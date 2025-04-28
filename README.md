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
<img src="https://i.imgur.com/wBifm6s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, located inside the same unzipped folder on the desktop, install the C++ redistributable file, which is a requirement needed for the osTicket to use. Note: all of these files needed for osTicket can be found on the osTicket documentation.
</p>
<br />

<p>
<img src="https://i.imgur.com/yfWflAj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, install the MySQL file and make sure to click "Typical" at the installation setup screen and click next, then launch the MySQL program, and make sure to click "standard configuration" and follow the proceeding steps. The MySQL file is a database that osTicket will store all of the information in, such as user accounts, ticket information, etc, on the back end. 
</p>
<br />

<p>
<img src="https://i.imgur.com/6EZivmg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To configure the osTicket permissions, rename the configuration hard drive file to "osT config.php". Open up File Explorer, go to the C-drive, and locate the file named "ost sample config". After renaming the file, assign the permissions for osTicket to make changes to this file on the backend. So right click it and go to properties, then go to the security tab and click advanced. Then click "disable inheritance" to remove all permissions and assign new ones. Afterwards, click add (to add new permissions) and assign permissions to whichever user, group, or principal, then click ok, then continue to follow the prompts for the osTicket installation setup. 
</p>
<br />
