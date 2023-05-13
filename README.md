# Active Directory
<p align="center">
<img src="https://logowik.com/content/uploads/images/microsoft-active-directory5035.jpg" alt="Active Directory logo"/>
</p>

<h1>Active Directory - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of Active Directory using Microsoft Server 2019 and Virtual Box.<br />

<h2>In-depth tutorial</h2>

https://ctrlshiftes.com/blog/ad-home-lab

<h2>Environments and Technologies Used</h2>

- Windows Server 2019 (Virtual Machine)
- Oracle Virtual Box
- Microsoft Active Directory

<h2>Operating Systems Used </h2>

- Windows 10</b> 

ACTIVE DIRECTORY

Your going to need to download ;
Oracle Virtual Box (https://www.virtualbox.org/wiki/Downloads)
Windows Server 2019 (https://www.microsoft.com/en-us/evalcenter/download-windows-server-2019)

To install VirtualBox, visit the VirtualBox website and download the version appropriate for your operating system. Once the download is complete, double-click the installer and follow the on-screen instructions to complete the installation.

After installing VirtualBox, launch the application and click the "New" button to create a new virtual machine. Give your virtual machine a name (I chose “DC” for “Domain Controller”)

select "Microsoft Windows" as the operating system, and select the “Other Windows (64-bit)” as the version to install.
The next step is to allocate memory to the virtual machine. 

Microsoft Server requires at least 2GB of RAM, so make sure you allocate at least this amount of memory to your virtual machine.  Then chose how many processor to give to the machine (I chose 2)  

Next, create a virtual hard disk for your virtual machine. Select "Create a virtual hard disk now" and click "Create". Choose the "VDI" format for the virtual hard disk and click "Next". Select "Dynamically allocated" as the storage type and click "Next". Allocate a suitable amount of storage space for the virtual hard disk and click "Create".

With the virtual machine created, it is time to install Microsoft Server. Click on the virtual machine in the VirtualBox Manager window and click "Start". Select the installation media, such as an ISO image of the Microsoft Server installation disc, and click "Start".

Follow the on-screen instructions to complete the installation of Microsoft Server. Make sure you select the appropriate options for your purpose.  I used “Windows Server 2019 Standard Evaluation (Desktop Experience).”  If you select one of the options that does not include “Desktop Experience” in the title, there will be no GUI and you will have to work from the command line.

Once Microsoft Server is installed, it is time to install Active Directory. Open the Server Manager application and select "Add roles and features". Follow the on-screen instructions to install Active Directory.

During the installation process, you will be prompted to create a domain.

With Active Directory installed, it is time to configure it. Open the Active Directory Users and Computers application and create user accounts and groups as needed. You can also assign permissions to users and groups using the Active Directory administrative tools.

If you followed the steps correctly, congratulations! You have successfully installed Active Directory and can begin tinkering with the software.
