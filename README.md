<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>

<h2> Project Summary</h2>
 The project consists of a trusted open-source support Ticketing system designed to help manage, organize, and respond to customer service. By Using Azures VM/IP Address we created we will be able to use Remote Desktop to install the "osTicket-installation files", folder which dowloades and installs all the requirements to succesfully install osTicket.
<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1: Set up a Virtual Machine in Azure
- Item 2: Log into Remote Desktop with Azure's VM IP Address
- Item 3: Install the osTicket Requirements
- Item 4: osTicket Installation Successful

<h2>Installation Steps</h2>

<p align="center">
Create Windows 10 Virtual Machine in Azure: <br/>
<img width="450" alt="1  Azure Windows 10 Virtual Machine Created" src="https://github.com/user-attachments/assets/01609dcd-c82f-4be4-8151-99ba8a3edb89" />
<br />
<br />
Log into Remote Desktop: <br/>
<img width="450" alt="2  Logging into RD with Windows 10 VM IP Address Created" src="https://github.com/user-attachments/assets/98fb653a-240a-4674-b537-f2bda3ba4735" />
<br />
<br />
Download osTicket-Installation-File.Zip/ Unzip onto Desktop: <br/>
<img width="450" alt="3  osTicket-Installation-file unziped onto desktop" src="https://github.com/user-attachments/assets/672387d4-ea6f-41b7-94e5-1e89ed31c9d7" />
<br />
<br />
</P>
<h5> From here on out, our "osTicket-Installation-file" folder will be used to download and install the requirements for installing osTicket. </h5>
<p align="center">
Enabling ISS in Windows with CGI: <br/>
<img width="450" alt="5  End result with ISS Enabled with CGI" src="https://github.com/user-attachments/assets/dc65a03b-223a-4165-a6fc-f538a18e1995" />
<br />
<br />
From the “osTicket-Installation-Files” folder, install PHP Manager for IIS : <br/>
<img width="450" alt="6  Installing PHP Manager for ISS" src="https://github.com/user-attachments/assets/64f34bff-24da-4e2e-bd1c-368da18ee6e7" />
<br />
<br />
From the “osTicket-Installation-Files” folder, unzip PHP 7.3.8: <br/>
<img width="450" alt="7  Extracted PHP 7-3-8 into the C-PHP Folder" src="https://github.com/user-attachments/assets/3c739c7e-fcae-44da-a3e5-9cea41d40bcc" />
<br />
<br />
From the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.: <br />
<img width="450" alt="8  Visual C++ Installation" src="https://github.com/user-attachments/assets/41aa4fee-2c44-4308-8d99-20e2f6652cd4" />
<br />
<br />
From the “osTicket-Installation-Files” folder, install MySQL 5.5.62: <br /> 
<img width="450" alt="9  Installation of my- SQL" src="https://github.com/user-attachments/assets/7ea9e9b6-d24c-474d-ad38-0ff7e8fc0756" />
<br />
<br />
Register PHP from within IIS (PHP Manager -> C:\PHP\php-cgi.exe): <br /> 
<img width="450" alt="10  Register PHP from within ISS" src="https://github.com/user-attachments/assets/529ab202-3f1e-4eb7-8acc-fdad6315e787" />
<br />
<br />
Enabling PHP Extensions: <br />
<img width="450" alt="11  Enabling PHP Extension" src="https://github.com/user-attachments/assets/8e509f80-cd47-437c-841c-f65318f62f58" />
<br />
<br />
Making sure osTicket has permission to make changes: <br />
<img width="450" alt="12  Allowing osTicket to make changes" src="https://github.com/user-attachments/assets/70ca9f90-5238-4539-8a98-f142b355e656" />
<br />
<br />
From the “osTicket-Installation-Files” folder, install HeidiSQL: <br />
<img width="450" alt="13  Installation of HeidiSQL" src="https://github.com/user-attachments/assets/070e727c-0b84-4667-bc85-9273a5ebe595" />
<br />
<br />
Congratulations, hopefully it is installed with no errors! : <br />
<img width="450" alt="14  osTicket -Installation Successful" src="https://github.com/user-attachments/assets/32341290-e487-4d02-a4d3-9e1718efbce6" />
</p>
