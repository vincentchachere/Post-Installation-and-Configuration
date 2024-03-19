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

## Part 1: <ins>Admin Portal</ins> Configuration Steps

### 1. ) Login

- Username: `*Use the credentials you made during the installation tutorial*`

- Password: `*Use the credentials you made during the installation tutorial*`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/bf01b1e9-4eae-4941-95c7-cfe2f338b89f"><br>

***

### 2.A ) Configure Roles

  - Go To: `Admin Panel` > `Agents` > `Roles`

  - Click: `Add New Roles`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/4e413d8b-26f2-48a4-b2b8-156c52c19c6e"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/3d0f4f65-9735-4d68-b54c-6e7594257049"><br>

***

### 2.B ) Configure Roles

- Name: `Supreme Admin`

- Click: `Permissions`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/3405ce7e-f3e2-4b36-b79d-2e802c3b13d8"><br>

***

### 2.C ) Configure Roles

- Tickets: `Check all boxes`

- Tasks: `Check all boxes`

- Knowledages: `Check all boxes`

- Click: `Add Role`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/145a3c05-eaab-4ce1-969e-c9713b9f469a"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/8bc678ef-039b-4e36-b094-027b1ee6c9fd"><br>
***
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/640c35bd-3149-41f0-9e15-47ab789131af"><br>

***

### 2.D ) Configure Roles

- <ins>Congrats!</ins>

  - *Go to the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/f6554fa5-46d1-4fcf-baee-8d5ef37e313b"><br>

***

### 3.A ) Configure Departments

- <ins>Within Admin Panel Go To</ins>:

  - Click: `Departments`

  - Click: `Add New Departments`
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/598b4c02-6d6c-40d1-930f-337cfd853d1e"><br>

***

### 3.B ) Configure Departments

- Name: `Systems Administrators`

- Click: `Create Dept`

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

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/563d4c83-149a-451a-84e6-c785d7631a61"><br>
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/047fb3f8-24db-4e93-b3fd-13131c4ece1d"><br>

***

### 4.C ) Configure Teams

- <ins>Congrats!</ins>

  - *Go to the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5f550163-de75-47c3-9252-4d19c943e6f9"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/cee292b5-f098-43e7-ac89-648911edcacb"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/ccd4d824-d33f-46b2-99ea-8db0ad475776"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/2c411f6e-eefc-4440-9c73-36e0b61136ec"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/c6044063-1b89-4c88-bbe6-d5223a7adf43"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/e2707efd-9230-42fd-b6c2-de616cd58088"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/100144d4-92e7-4fa5-b389-de0bc6a8361b"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/b5dfcc2b-ab55-4d4f-aecd-999584e2f5c9"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/07a6fca4-1fb0-4008-9b57-ab4c22f239d1"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/cec9e992-59b5-4bab-be67-733c67a73573"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/1311b464-9600-4446-9d6d-5867358d64f0"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/201f7a16-c66a-40ae-90b3-cb5e245208f8"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/aa8cd245-2fd1-40f2-bfcf-421e8fba5f50"><br>

***

## Part 2: <ins>Agent Portal</ins> Configuration Steps

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5ae41544-5193-4c73-8b02-50c8854496bf"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/60e07c43-bbbc-448c-81a0-086174608c43"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/92329b05-10fe-4427-a9d0-45e83d3a2bcc"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/886a966b-b422-49e8-b40e-c22176d012d4"><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src=""><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src=""><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src=""><br>

***

### 

<ins></ins>

- 

<img width="1511" alt="isolated" src=""><br>

***

