<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used</h2>

- Windows 10 (21H2)

<h2>List of Prerequisites</h2>

- IIS
- PHP Manager for IIS
- Rewrite Module
- PHP
- VC Redistributable
- MySQL
- HeidiSQL
- osTicket



<h2>Installation Steps</h2>

<p>
I begin by making a Windows virtual machine in Azure to use to host osTicket and its prerequisites. I then logged into the virtual machine and began installing the prerequisites for osTicket.
</p>
<br />
<p>
  
![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/2bc3fda4-b9c8-466e-bb8b-5064e49adbe9)

</p>


<p>

Next, I Installed IIS- Internet information services as osTicket will need to use it on the browser.I then Confirmed IIS was installed by browsing to 127.0.0.1 to get the below confirmation webpage.

</p>
<br />

<p>

  ![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/9bc3b242-91df-4eb7-b832-52a47635a979)

</p>

<p>

Next I installed PHP Manager for IIS for a convenient and centralized way to configure and manage PHP settings for web applications hosted on IIS.

</p>
<br />

<p>

![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/5b0885ea-6ae2-4d1a-8e6e-9b074b5b586e)

</p>


<p>

Next I Installed the IIS rewrite module to enable URL rewriting and redirection within IIS.

</p>
<br />

<p>

![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/013a77ac-ca32-487e-bd5f-bf8875a5e689)

</p>
<p>

Next i installed MySQL server to store and manage data for the osTicket helpdesk and ticketing system including ticket information, user details, settings, and more. 

</p>
<br />

<p>

![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/89e42209-7c65-4e1d-ad4f-708aec90f7a9)

</p>
<p>

 Next, I Registered PHP from within IIS to configure the web server to properly handle PHP scripts and enable execution of the osTicket application; essentially configuring IIS to understand and process PHP files.  

</p>
<br />

<p>

![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/d2c4afd6-62f7-4269-a7c6-f5e99fecb2ac)

</p>
<p>

Next, I installed osTicket and enabled extensions I saw fit to have for my ticketing system like the php_imap.dll extension to aid in email integration, ticket creation and email parsing.

I had a Successful osTicket installation and just had to remove write-access to the ost-config.php file as a security measure. Avoiding modifications or tampering with configuration settings.

</p>
<br />

<p>

![image](https://github.com/teeckay/osticket-prereqs/assets/64244011/5508982b-12c6-4b9b-8a93-920099a962c8)

</p>

<p>

Next I was able to Successfully  login to the osTicket ticketing system and began working on the post-installation setup.

</p>
<br />








