<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Installation</h1>
This tutorial goes over the prerequisites and steps to install the ticketing software OsTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>
- Create a Windows Virtual Machine</br>
- Remote Desktop connect to the VM</br>
- Install the prereqs for OsTicket</br>
- Install OsTicket</br>
- Clean up files and OsTicket</br>
</br>
</br>
</br>
</br>
</br>
<p>
<img width="1088" height="1159" alt="image" src="https://github.com/user-attachments/assets/276bbc66-768e-4de1-8248-508946046492" />
</p>
<p>
Create a azure virtual machine that is using a windows image = Windows 10 pro
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1110" height="587" alt="image" src="https://github.com/user-attachments/assets/11411a27-4918-4dea-922f-803396f6665d" />
</p>
<p>
Connect to the virtual machine and download the following folder on the virtual machine: https://drive.usercontent.google.com/download?id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD&export=download&authuser=0
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1407" height="795" alt="image" src="https://github.com/user-attachments/assets/7ec61373-10c4-418b-8ca3-3fd2a42b3670" />
</p>
<p>
Unzip the file to the desktop for easy access.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="987" height="861" alt="image" src="https://github.com/user-attachments/assets/3b0585e7-9235-432d-8c11-0bca0c2c6f9d" />
</p>
<p>
Open Control Panel
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1438" height="832" alt="image" src="https://github.com/user-attachments/assets/eed6e60b-ea5c-48b1-837d-d788bed7b370" />
</p>
<p>
Navigate to programs, then check the box for Web Management Tools, World Wide Web Services, and CGI then click ok.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1411" height="794" alt="image" src="https://github.com/user-attachments/assets/33745b41-d3b9-45ea-b4c4-603fbc80dccf" />
</p>
<p>
Double click the PHP manager for IIS to install it
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1410" height="791" alt="image" src="https://github.com/user-attachments/assets/1eca0e01-289b-4b6b-bca5-c3092c92ea1c" />
</p>
<p>
Double click the Rewrite AMD to install it
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1413" height="796" alt="image" src="https://github.com/user-attachments/assets/d856f778-cc9a-4d28-9220-70b61772b046" />
</p>
<p>
Create a new folder on the C drive called PHP
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1404" height="790" alt="image" src="https://github.com/user-attachments/assets/5c6c9644-7599-426f-971a-6a07e627c8a5" />
</p>
<p>
Unzip the PHP zip file onto the folder that was just created.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1407" height="792" alt="image" src="https://github.com/user-attachments/assets/d17d33fc-5ad7-4cca-9fce-b2b74ef85433" />
</p>
<p>
Double click the VC redist file to install it. 
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1409" height="789" alt="image" src="https://github.com/user-attachments/assets/f916dfee-1505-4606-85b9-09131736658c" />
</p>
<p>
Double click the mySQL file to install it and create a username and password.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="978" height="848" alt="image" src="https://github.com/user-attachments/assets/c561bd12-5022-4c77-9bc1-6f263f012d8c" />
</p>
<p>
Open Internet Information Services Manager as administrator 
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1902" height="986" alt="image" src="https://github.com/user-attachments/assets/82c6b084-d1ec-4b8c-9b6f-288161d9fe77" />
</p>
<p>
Navigate to PHP manager and click on register new PHP version
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1265" height="751" alt="image" src="https://github.com/user-attachments/assets/46c14626-1cf0-4fd5-b606-9b769fc4b8a8" />
</p>
<p>
Give the path to the PHP folder we created and click on PHP-CGI and click open. 
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1898" height="992" alt="image" src="https://github.com/user-attachments/assets/3d285718-eaba-468b-861e-10e108585be9" />
</p>
<p>
Restart the IIS manager by clicking restart on the right side. 
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1415" height="804" alt="image" src="https://github.com/user-attachments/assets/bf1878a4-e793-4ae9-9d14-36722d695f74" />
</p>
<p>
Unzip the osTicket zip file
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1405" height="803" alt="image" src="https://github.com/user-attachments/assets/7c5c4444-32b1-417c-9a6d-b66c7bf0dd93" />
</p>
<p>
Click into the unzipped file and copy the upload folder.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1406" height="849" alt="image" src="https://github.com/user-attachments/assets/9dc0227c-97b4-4c15-8657-88fd785cfaf9" />
</p>
<p>
Paste the folder into the file path above and renamed it to osTicket exactly
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1900" height="1003" alt="image" src="https://github.com/user-attachments/assets/c1e06dca-28f4-4982-9f99-da38edb6ad95" />
</p>
<p>
Restart IIS again.
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1895" height="1000" alt="image" src="https://github.com/user-attachments/assets/d7ff11dd-a3b5-4c38-835d-8e56b4b056cb" />
</p>
<p>
Click on sites, default website, and then osTicket afterwards on the right click Browse *:80
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1898" height="1002" alt="image" src="https://github.com/user-attachments/assets/b4ff9e2a-2339-49f6-a2c4-3b6212be95d6" />
</p>
<p>
Click on PHP manager and click on add extensions
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1891" height="1011" alt="image" src="https://github.com/user-attachments/assets/21327a53-b1fc-489c-adf7-dbd9c327e4c7" />
</p>
<p>
Enable the extensions php_imap.dll, php_intl.dll, and php_opcache.dll
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1416" height="781" alt="image" src="https://github.com/user-attachments/assets/74083861-7f08-49f4-990f-9cab66071701" />
</p>
<p>
Navigate to the C drive>inetpub>wwwroot>osTicket>include and change the name of the file ost-sampleconfig.php to ost-config.php
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1423" height="1017" alt="image" src="https://github.com/user-attachments/assets/d8445183-3d02-49ab-901f-8a5057e243bb" />
</p>
<p>
Right click on the file we just renamed and click properties
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1017" height="638" alt="image" src="https://github.com/user-attachments/assets/8c2a37df-9b02-4a14-ac17-e7aa1001f9ed" />
</p>
<p>
Navigate to security and advance and click disable inheritance
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="1448" height="718" alt="image" src="https://github.com/user-attachments/assets/7fc5b1ab-4bcb-4688-85c1-27664f5aad9e" />
</p>
<p>
Click on add, then principal, and type in everyone then hit check names then ok. After hit apply and then close.
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1017" height="638" alt="image" src="https://github.com/user-attachments/assets/8c2a37df-9b02-4a14-ac17-e7aa1001f9ed" />
</p>
<p>
Navigate to security and advance and click disable inheritance
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="874" height="779" alt="image" src="https://github.com/user-attachments/assets/3b7594cd-70e9-41dc-81d6-45c2bc4a30d0" />
</p>
<p>
Fill in admin and helpdesk info.
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1429" height="810" alt="image" src="https://github.com/user-attachments/assets/5cb71f6e-1543-4ad3-b400-3fc7962b5056" />
</p>
<p>
Go back to osTicket zip file and double heidi to install
</p>
<br />
<br />
<br />
<br />
<br />
<p>
<img width="862" height="601" alt="image" src="https://github.com/user-attachments/assets/152995cd-ffda-4aea-87a0-e763b68ac5e3" />
</p>
<p>
From Heidi click new and type in password for root created earlier and click open.
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1170" height="642" alt="image" src="https://github.com/user-attachments/assets/204dfcdc-e4cf-4917-9722-38264b6d7f80" />
</p>
<p>
Right click unnamed and click new and create a new database and name it osTicket.
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1017" height="638" alt="image" src="https://github.com/user-attachments/assets/8c2a37df-9b02-4a14-ac17-e7aa1001f9ed" />
</p>
<p>
Go back to osTicket browser and fill info and filled in the name of SQL database = osTicket and username = root and password = root password from earlier
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1030" height="806" alt="image" src="https://github.com/user-attachments/assets/1dd8e515-aeee-4bc3-9739-ab755b9b1262" />
</p>
<p>
Then we finished setting up osTicket where we can see our login with the following link: http://localhost/osTicket/scp/login.php
</p>
<br />
<br />
<br />
<br />
<br />

<p>
<img width="1403" height="940" alt="image" src="https://github.com/user-attachments/assets/4c2d0980-ba98-4215-89bc-9f304dd455c4" />
<img width="1726" height="913" alt="image" src="https://github.com/user-attachments/assets/6856856a-ae48-4dfd-ac1f-fcdf474222ff" />
</p>
<p>
For final cleanup we can delete the setup folder in the osTicket folder and change ost-config permissions to read-only
</p>
<br />
<br />
<br />
<br />
<br />
