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

- Create Virtual Machine in Azure
- Create an Azure Virtual Machine Windows 10, 4 vCPUs
- Install / Enable IIS in Windows 
- PHP Manager for IIS

<h2>Installation Steps</h2>

<p>
<img src="https://i.gyazo.com/08f3576add2afa27c37528eff2c566ef.png"/>
</p>
<p>

</p>

Begin by using this [guide](https://github.com/jdinh2/AzureVMAD) to create a VM. (Use Windows Pro rather than the server edition.) Access the VM and go into Control Panel > Programs > Turn Windows Features on  or off 
Install / Enable IIS in Windows WITH
CGI and Common HTTP Features
World Wide Web Services -> Application Development Features ->
[X] CGI
[X] Common HTTP Features
AND IIS Management Console
Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console


<br />
