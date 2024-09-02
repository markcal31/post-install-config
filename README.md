<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this lab i outline the post-install configuration of the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Open azure virtual machine
- open osTicket Dashboard


<h2>Configuration Steps</h2>
<p>
Open osTicket
</p>

![image](https://github.com/user-attachments/assets/87f3faaa-3329-462b-8bf9-f4625900dc9a)

<p>
Configure Roles
<br>- Admin Panel -> Agents -> Roles </b>
<br>- Add new role: Supreme Admin </b>
<br>- give the role all permissions </b>
</p>

![image](https://github.com/user-attachments/assets/6d2f852d-d7dc-49d8-a6d6-32cb96608fde)

![image](https://github.com/user-attachments/assets/48e54084-5bce-4046-819b-544aa412268a)

![image](https://github.com/user-attachments/assets/18467dde-6b03-4195-b47a-bcc98b240d88)

![image](https://github.com/user-attachments/assets/9a23e20f-7b3c-48a3-ac94-fce0707191c8)

![image](https://github.com/user-attachments/assets/3c2f94c8-9d26-41c7-856e-1317f15040b4)

<p>
Configure Departments 
<br>- Admin Panel -> Agents -> Departments </b>
<br>- Add new Department: System Administrators </b>
</p>

![image](https://github.com/user-attachments/assets/6bd7fbde-3b14-4ba7-a029-af3fe3721935)

![image](https://github.com/user-attachments/assets/3521726d-2ac8-40db-b733-cecb0ebec354)

![image](https://github.com/user-attachments/assets/c3ce1e11-6eb5-4e4a-9414-6a91cb5b7ed6)

<p>
Configure Teams
<br>- Admin Panel -> Agents -> Teams </b>
<br>- Add Level 1 Support </b>
<br>- Add Level 2 Support </b>
</p>

![image](https://github.com/user-attachments/assets/ecffb65b-cb2a-4626-9e13-70c5c1c979ae)

![image](https://github.com/user-attachments/assets/0129092b-841f-4a38-b29e-7766d16771ee)

<p>
Allow anyone to create tickets
<br>- Admin Panel -> Settings -> User Settings </b>
<br>- Registration Required: Require registration and login to create tickets </b>
</p>

![image](https://github.com/user-attachments/assets/3c35444b-6392-462f-90d4-16461e430d77)

![image](https://github.com/user-attachments/assets/11cf86dd-aae0-46e3-a1e4-6677acc9465e)

![image](https://github.com/user-attachments/assets/c6c1c72a-9514-483f-b6fd-fdcc943ca269)

<p>
Configure Agents (workers)
<br>- Admin Panel -> Agents -> Add New </b>
<br>- Jane </b>
<br>- John </b>
</p>

![image](https://github.com/user-attachments/assets/a432b386-1d31-4305-85cc-8cdb76d84e94)

![image](https://github.com/user-attachments/assets/8d7e4f3b-e959-4e3f-b09f-ef4ccc9ad0fd)

![image](https://github.com/user-attachments/assets/aad41e59-870d-473c-b2e8-2ed070e20427)

<p>
Configure Users (Customers)
<br>- Agent Panel -> Users -> Add New </b>
<br>- Karen </b>
<br>- Ken </b>
</p>

![image](https://github.com/user-attachments/assets/662dc971-d629-40fb-bf1f-275260d8572a)

![image](https://github.com/user-attachments/assets/aed56de8-e5e3-4f6d-af28-f1d9117f4331)

![image](https://github.com/user-attachments/assets/18460f14-3cc0-4f5c-bab6-e741f3439ff6)

![image](https://github.com/user-attachments/assets/5faea1ef-e769-4308-9fc8-234d4cbed2d4)

<p>
Configure SLA
<br>- Admin Panel -> Manage -> SLA </b>
<br>- Sev-A (1 hour, 24/7) </b>
<br>- Sev-B (4 hours, 24/7) </b>
<br>- Sev-C (8 hours, business hours) </b>
</p>

![image](https://github.com/user-attachments/assets/e3f1b8be-7397-4331-abe0-991f67f9c024)

![image](https://github.com/user-attachments/assets/e953a881-d757-42b5-adb2-2121576c5473)

![image](https://github.com/user-attachments/assets/37ad93f0-be64-4b39-bbf0-d9a4b923b60a)

![image](https://github.com/user-attachments/assets/4b267271-0224-452a-9ab9-9c375ebb2443)

![image](https://github.com/user-attachments/assets/3b0322fd-658f-4516-a537-80fc47a4e3d6)

![image](https://github.com/user-attachments/assets/0fe0b6e2-e40e-46d2-ad3f-d4158e34debf)

<p>
Configure Help Topics
<br>- Admin Panel -> Manage -> Help Topics </b>
<br>- Personal Computer Issues </b>
<br>- Equipment Request </b>
<br>- Password Reset </b>
</p>

![image](https://github.com/user-attachments/assets/9a5f49a1-7b95-408d-b9c4-ef4ca9a0142e)

![image](https://github.com/user-attachments/assets/eeb796bd-5e98-4d99-bd34-8a1cb7ad6a5d)

![image](https://github.com/user-attachments/assets/b34707a0-7ed4-4a33-97cd-4b95d8e68d7b)

![image](https://github.com/user-attachments/assets/d6b59a46-5cbc-4f4a-9008-95e020191289)

Post installation setup is now complete!
