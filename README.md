<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

## Operating Systems Used

- macOS
- Windows 10 (21H2)

## Post-Install Configuration Objectives

- Microsoft Azure
- Virtual Machine
- osTicket

## Resources 

- <ins>For better understanding of each go to</ins>:

  - [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
  - [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
  - [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
  - [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
  - [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
  - [Service Level Agreement (SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)

***

## Part 1 - <ins>Admin Portal</ins> Configuration Steps

### 1. ) Login

- Username: `*Use the credentials you made during the installation tutorial*`

- Password: `*Use the credentials you made during the installation tutorial*`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/bf01b1e9-4eae-4941-95c7-cfe2f338b89f"><br>

***

### 2.A ) Configure Roles

  - Go To: `Admin Panel` > `Agents` > `Roles`

  - Click: `Add New Roles`

*(There are 2 pictures in this step 2.A)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/4e413d8b-26f2-48a4-b2b8-156c52c19c6e"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/3d0f4f65-9735-4d68-b54c-6e7594257049"><br>

***

### 2.B ) Configure Roles

- Name: `Supreme Admin`

- Click: `Permissions`

  - Tickets: `Check all boxes`

  - Tasks: `Check all boxes`

  - Knowledages: `Check all boxes`

  - Click: `Add Role`

*(There are 4 pictures in this step 2.B)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/0cae777b-33d2-4766-af3f-6391f201694f"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/911a723e-13e6-48f1-86ad-922bcf5d1e9c"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/95cfc187-153c-4c8a-a957-45da2a2b4bee"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/f99c7051-776f-431d-bb26-5a883ffaed9d"><br>

***

### 2.C ) Configure Roles

- <ins>Congrats!</ins>

  - *Go to the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/f6554fa5-46d1-4fcf-baee-8d5ef37e313b"><br>

***

### 3.A ) Configure Departments

- Go To: `Admin Panel` > `Departments` > `Add New Departments`
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/598b4c02-6d6c-40d1-930f-337cfd853d1e"><br>

***

### 3.B ) Configure Departments

- Name: `Systems Administrators`

- Click: `Create Dept`

*(There are 2 pictures in this step 3.B)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/ef8f1c53-e9e5-4c6c-9182-ba7c3c16a64b"><br>
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/4a28b876-6fe8-4e3c-92cf-d913e283663e"><br>

***

### 3.C ) Configure Departments

- <ins>Congrats!</ins>

  - *Go to the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/6af57166-6847-41d6-b5c0-2c3b3b72e5e8"><br>

***

### 4.A ) Configure Teams

 - Go To: `Admin Panel` > `Agents` > `Teams`

  - Click: `Add New Team`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/fa7b31d4-38da-4538-bc0f-0c1c3af42afa"><br>

***

### 4.B ) Configure Teams

- Name: `Level II Support`

- Member: *`The username you used to login into osTicket`*

- Click: `Create Team`

*(There are 2 pictures in this step 4.B)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/85050192-d8da-40ec-bc59-43a465f188af"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/32f63549-9fda-41cb-ad1c-7f7a12d849ba"><br>

***

### 4.C ) Configure Teams

- <ins>Congrats!</ins>

  - *Go to the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5f550163-de75-47c3-9252-4d19c943e6f9"><br>

***

### 5. ) Allow Anyone To Create Tickets

- Go To: `Admin Panel` > `Settings` > `Users`

- Require registration and login to create tickets: <ins>`Uncheck`<ins>

- Click: `Save Changes`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/cee292b5-f098-43e7-ac89-648911edcacb"><br>

***

### 6.A ) Configure Agents (workers)

- Go To: `Admin Portal` > `Agents` > `Agents`

- Click: `Add New Agent`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/ccd4d824-d33f-46b2-99ea-8db0ad475776"><br>

***

### 6.B ) Configure Agents (workers)

- Name: `Jane Doe`

- Email Address: `jane.doe@gmail.com`

- Username: `jane.doe`

- Click: `Set Password`

  - Uncheck: `Send the agent a password reset email`

  - Password: *`Your osTicket Login Password`*
 
  - Uncheck: `Require password change at next login`
 
  - Click: `Set`
 
- Go To: The `Access` Tab

*(There are 3 pictures in this step 6.B)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/28bf2f82-c529-4d14-90d1-890559bcc68e"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/c6044063-1b89-4c88-bbe6-d5223a7adf43"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/26c9cca7-d870-4cb1-8c2f-0313d56534db"><br>
***

### 6.C ) Configure Agents (workers)

- <ins>Primary Department Access</ins>:

  - System Administrators
 
  - Supreme Admin
 
- Go To: The `Permissions` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/e2707efd-9230-42fd-b6c2-de616cd58088"><br>

***

### 6.D ) Configure Agents (workers)

- Check: `All Boxes`

- Go To: The `Teams` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/100144d4-92e7-4fa5-b389-de0bc6a8361b"><br>

***

### 6.E ) Configure Agents (workers)

- Assigned Teams: `Level II Support`

- Click: `Create`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/b5dfcc2b-ab55-4d4f-aecd-999584e2f5c9"><br>

***

### 6.F ) Configure Agents (workers)

<ins>Congrats!</ins>

- *Go To The Next Step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/07a6fca4-1fb0-4008-9b57-ab4c22f239d1"><br>

***

### 7.A ) Configure Agents (workers)

*(Go To: `Admin Portal` > `Agents` > `Agents` > `Add New Agent`)*

- Name: `John Doe`

- Email Address: `john.doe@gmail.com`

- Username: `john.doe`

- Click: `Set Password`

  - Uncheck: `Send the agent a password reset email`

  - Password: *`Your osTicket Login Password`*
 
  - Uncheck: `Require password change at next login`
 
  - Click: `Set`
 
- Go To: The `Access` Tab

*(There are 3 pictures in this step 7.A)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/62d5d16e-f81b-42ff-bf3b-0baa27428cba"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/1311b464-9600-4446-9d6d-5867358d64f0"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/e505151c-2fa9-4613-a872-b7dc902d88e1"><br>

***

### 7.B ) Configure Agents (workers)

- <ins>Primary Department Access</ins>:

  - Select: `System Administrators`
 
  - Select: `Supreme Admin`
 
- Go To: The `Permissions` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/201f7a16-c66a-40ae-90b3-cb5e245208f8"><br>

***

### 7.C ) Configure Agents (workers)

<ins>Congrats!</ins>

- *Go To: Part 2 - <ins>Agent Portal</ins> Configuration Steps*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/aa8cd245-2fd1-40f2-bfcf-421e8fba5f50"><br>

***

## Part 2 - <ins>Agent Portal</ins> Configuration Steps

### 8.A ) Configure Users (Customers)

- Go To: `Agents` > `Users` > `User Directory` > `Add User `

  - Email Address: `Karen@osticket.com`
 
  - Full Name: `Karen Karen`
 
  - Click: `Add User`
 
*(There are 3 pictures in this step 8.A)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/9cb4bebd-b0b8-4412-ba0b-a93722453ee2"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/3c2693bc-cf7a-42e3-a362-421bab2c6015"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5df98d4f-9c94-4710-9e08-c2898a0c91ed"><br>

***

### 8.B ) Configure Users (Customers)

- Go To: `Agents` > `Users` > `User Directory` > `Add User `

  - Email Address: `Ken@osticket.com`
 
  - Full Name: `Ken Ken`
 
  - Click: `Add User`
 
*(There are 3 pictures in this step 8.B)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/d28ceaca-ad99-479d-aa21-cbc8d0b196c0"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/50b407b0-8928-4992-b5ab-8e43d207aa14"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/959587b2-3d6e-4ca0-b493-b31ae82d48c5"><br>

***

### 8.C ) Configure Users (Customers)

<ins>Congrats!</ins>

- *Continue To The Next Step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/088d9037-d06e-4091-8326-53a1cebc676b"><br>

***

### 9.A ) Configure SLA

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Create: `SEV-A (1 Hour: 24/7 )`

  - Create: `SEV-B (4 Hours: 24/7 )`

  - Create: `SEV-C (8 Hours: Business Hours = Monday - Friday 8am to 5pm )`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5196eb74-6b90-47c2-bfad-7ab07aed1741"><br>

***

### 9.B ) Configure SLA

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-A`

  - Grace Period: `1 Hour`

  - Schedule: `24/7`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/e850f855-a6f5-41d8-8be5-99c1cf1d23ed"><br>

***

### 9.C ) Configure SLA

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-B`

  - Grace Period: `4 Hours`

  - Schedule: `24/7`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/1c7ab212-2c15-4e2f-9a7d-4e58114b5678"><br>

***

### 9.D ) Configure SLA

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-C`

  - Grace Period: `8 Hours`

  - Schedule: `Business Hours: Monday - Friday 8am to 5pm`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/fa2d4d6b-d495-48d2-ab2b-d97ebb672861"><br>

***

### 9.E ) Configure SLA

<ins>Congrats!</ins>

- *Proceed To The Next Step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/cdbca621-8b4b-4105-ac2b-e10f85be37a3"><br>

***

### 10.A ) Configure Help Topics

- Go To: `Admin Panel` > `Manage` > `Add New Help Topics`

- <ins>Make the following Help Topics</ins>:

  - `Business Critical Outage`
 
  - `Equipment Request`
 
  - `Personal Computer Issues`
 
  - `Password Reset`

*(There are 5 pictures in this step 10.A)*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7a4ee028-d064-44b1-bf3b-85f1df87c4e7"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7c99fdf8-1359-4944-b584-251220693901"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/9cebecd8-b418-4a2d-a788-2d0dbef58b90"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/d7c0e6f1-c66e-40bd-aa18-dd27708b40ab"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/45483a06-5149-4918-bd4e-1719593dbac3"><br>
***

### 10.B ) Configure Help Topics

- Congratulations! You configured osTicket!

- Click here to move on to the final part of this tutorial!

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7f1f496f-6f42-49c5-a32d-5ae1a013664e"><br>

***
