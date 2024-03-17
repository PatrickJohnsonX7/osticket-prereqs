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

Step 2-Download PHP manager for ISS, php, rewrite Module, and VC_redist.


![Github inage 21](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/68fe145b-1491-4e4e-b1be-9c878d83fcda)

Create new PHP folder on C drive.


![Github image 17](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/58a5ce6d-6369-46a8-90c1-a400422b8351)

Extrat PHP file into PHP File

![Github image 18](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/ea102242-2f0b-416b-a276-76e3869f01ab)


![Github image 20](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/60d81a97-95fe-4dda-bf6a-aec2b8a9ebc2)


Step 3-Install MySQL

![Github image 13-2](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/40cb1c0f-a454-4983-ae70-0582a30f1c05)

![Github image 13](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/76cd1308-ca7e-473c-b82e-d42477d1cace)


![Github image 24](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/0d2ae1fa-e31e-4b25-83a1-2563897394a3)


Open IIS as administrator and register PHP from within IIS

![Github image 25](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/f41e0e9d-1989-4f74-9a5d-32c53ad055a9)


![Github image 26-1](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/f85528c5-4d66-46b9-8778-58a4b0af8a37)


![Github image 27](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/e9f7b0f5-85d3-4260-892b-678f3036bce1)



![Github image 28](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/36a38db2-399c-4276-a4f9-e654fb618f33)


![Github image 29](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/e6e1ec52-e8ff-489b-bffa-930d578dcce8)

Once programs are installed write down username and password. Once credentials are committed to memory delete file of personal information. 

Step 4-Install OSTicket 

![Github image 16](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/c49f0ac3-9454-46bc-af24-05b67eab51eb)

Extract and copy "upload" folder to wwwroot 


![Github image 30](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/dee29b6b-66c4-4894-9d14-bd2e8eb5e4cb)



![Github image 31](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/bf4c010e-b23e-4ca6-bdca-f35ee1895e3a)

![Github image 32](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/d291114c-98eb-4cba-a1c5-18f4ea329b92)


![Github image 33](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/dbb50c9f-4060-4a81-a5f4-9f65d71c7330)


![Github image 34](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/45b78e1b-b605-40fb-be2a-462d0dfb64b2)

Drag "upload" folder to wwwroot

![Github image 35](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/9570d6b5-233a-4360-bab6-882dc8eaf410)

rename to osTicket


![Github image 36](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/81f48ea9-06bd-46be-853c-77c9baaba9e5)

Reload IIS-go to sites-default-OSTicket. Then "Browse *.80"


![Github image 37](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/dbcce7d9-2f0c-4d05-a115-22764b50d585)

![Github image 38](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/66c49022-9175-4be3-8728-e2d255aa2f4e)

Enable some extensions. Go back to IIS-sites-default-osTicket. Click PHP manager then click "Enable or disable an extension". Enable three options. 

![Github image 39](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/92c31760-52a9-4baf-b2e2-9ccdd3fb0861)

![Github image 40](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/003e2d8b-0dd9-46e6-9734-76bb5a990634)

![Github image 43-1](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/041f0ff9-9c09-4a3d-90c5-312a3062fd0d)

Return to osTicket 


![Github image 44](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/1649f499-fdef-4b8a-81d2-58f193e064e2)

Rename "ost-sample-config.php" to ost-config.php. Go to Windows C-inetpub-wwwroot-osTicket-include

![Github image 45](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/c99556b4-2869-4c37-867b-404d75807cf8)

Assign permissions ost-config.php. Right click ost-config.php and go to properties



![Github image 47](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/d6fa7717-178f-4f7a-801c-b471422b7b21)

Go to security and click advanced

![Github image 46](https://github.com/PatrickJohnsonX7/osticket-prereqs/assets/163357195/4bce2600-6661-4a16-a062-ae18ff4d79b2)
