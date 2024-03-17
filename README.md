<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This is a tutorial for the prerequisites and installation of osTicket. An open-source help desk ticketing system.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Step 1-Create Resource group in Azure 
![Github image 1](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/8d0ad429-ae97-4adc-9917-35e0a600a16f)


![githum image 2](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/2e6f4775-516c-4971-8bb8-cc8ddbd37a9f)


-Step 2-Create a Windows 10 VM(Virtual Machine) with 2-4 virtual CPUs
  A) When creating the VM, also create a new virtual network(Vnet)
![Github image 3](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/ad299366-1359-40ea-8161-36ffa5e079e7)
![Github image 4](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/13b78ba1-78b2-4523-a003-8a63f16aa4cc)
 ![Gethub image 5](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/b4a986f5-a6a2-4e6c-830d-b05effa532d5)
 ![Github image 6](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/675edc78-bed2-4296-8310-7b316b98f709)
![Github image 7](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/9548f7cf-de20-439a-ad48-d00d48f33071)



<h2>Installation Steps</h2>
Step 1-Install/Enable IIS in Windows with CGI and Common HTTP Features. Go to the control panel and select programs. Once in programs pick "Turn Windows features on or off". Computer will restart(do not be alarmed). Lastly, verify by going to web-browser typing 127.0.0.1

![Github image 8](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/1ebd018d-0cf4-4304-8159-7ea01f931dbf)

![Github image 9-3](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/eadf0f8c-73a4-4663-ba13-e45dc4cc9e75)

![Github image 10](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/983eb698-a7eb-4564-88ea-8944937c1090)


![Github image 11](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/111fb1ce-22a4-475c-b0be-80f5b625ac57)

Step 2-Download PHP manager for ISS, rewrite Module, and VC_redist.

![Github image 12](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/6a71df0b-0cb9-4ba7-a566-026f6d98479b)

Step 3-Install MySQL. A)Username and Password and HeidiSQL


![Github image 13-2](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/40cb1c0f-a454-4983-ae70-0582a30f1c05)

![Github image 13](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/76cd1308-ca7e-473c-b82e-d42477d1cace)

Once programs are installed write down username and password. Once credentials are committed to memory delete file of personal information. 

![Github image 14](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/4a3d45d4-f6f5-4e9f-8709-89f9bdcae074)
![Github image 15](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/3ee92d75-78e8-4c52-beb9-3cffbaa89e05)



