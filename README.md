<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

This lab guides users through the post-installation configuration of the osTicket help desk system within a Microsoft Azure virtualized environment. Participants will configure roles, departments, teams, agents, users, and Service Level Agreements (SLAs) to tailor the system for efficient help desk management.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop (macOS)
- Internet Information Services (IIS)

## Operating Systems Used

- Windows 10 (21H2)

## Post-Install Configuration Objectives

- Microsoft Azure
- Virtual Machine
- osTicket

## Resources 

<ins>For better understanding of each go to</ins>:

- [Roles](https://docs.osticket.com/en/latest/Admin/Agents/Roles.html)
- [Departments](https://docs.osticket.com/en/latest/Admin/Agents/Departments.html)
- [Teams](https://docs.osticket.com/en/latest/Admin/Agents/Teams.html) 
- [Agents](https://docs.osticket.com/en/latest/Admin/Agents/Agents.html)
- [Users](https://docs.osticket.com/en/latest/Agent/Users/User%20Directory.html)
- [Service Level Agreement (SLA)](https://docs.osticket.com/en/latest/Admin/Manage/SLA%20Plans.html)

<ins>For the prerequisite setup and initial configuration required for this lab, refer to my previous lab</ins>:

  - [osTicket - Prerequisites](https://github.com/vincentchachere/osTicket-Prerequisites)

<details>

<summary>

## 🎟️ Part 1: Configure Roles

</summary>

### 1. ) Login to osTicket

- Username: *Use the credentials you made in Part E: Step 21 of the* [Installation Tutorial](https://github.com/vincentchachere/osTicket-Prerequisites)

- Password: *Use the credentials you made in Part E: Step 21 of the* [Installation Tutorial](https://github.com/vincentchachere/osTicket-Prerequisites)

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/bf01b1e9-4eae-4941-95c7-cfe2f338b89f">

<br>
<br>
<br>

### 2. ) Configure Roles inside osTicket

  - Go To: `Admin Panel` > `Agents` > `Roles`

  - Click: `Add New Roles`

<img width="1511" alt="isolated" src="https://github.com/user-attachments/assets/8b04144f-9447-488f-987f-3ba0962436f8">

<br>
<br>
<br>

<ins>Configuring Roles inside osTicket</ins>:

- Name: `Supreme Admin` then..

- Go to: `Permissions` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/0cae777b-33d2-4766-af3f-6391f201694f">

<br>
<br>
<br>

<ins>Configuring Roles inside osTicket</ins>:

*Within the Permissions Tab:*

- Tickets Tab: `Check all boxes`

- Tasks Tab: `Check all boxes`

- Knowledages Tab: `Check all boxes`

- Select: `Add Role`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/911a723e-13e6-48f1-86ad-922bcf5d1e9c">
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/95cfc187-153c-4c8a-a957-45da2a2b4bee">
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/f99c7051-776f-431d-bb26-5a883ffaed9d">

<br>
<br>
<br>

### You've Successfully configured your first role within osTicket!

*Proceed to the Part 2: Configuring Departments inside osTicket*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/f6554fa5-46d1-4fcf-baee-8d5ef37e313b">

</details>

<details>

<summary>

## 🎟️ Part 2: Configure Departments

</summary>

### 3. ) Configuring Departments inside osTicket

- Go To: `Admin Panel` > `Departments` > `Add New Departments`
 
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/598b4c02-6d6c-40d1-930f-337cfd853d1e">

<br>
<br>
<br>

<ins>Configuring Departments inside osTicket</ins>:

- Name: `Systems Administrators`

- Click: `Create Dept`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/ef8f1c53-e9e5-4c6c-9182-ba7c3c16a64b">
<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/4a28b876-6fe8-4e3c-92cf-d913e283663e">

<br>
<br>
<br>

### You've Successfully configured Departments inside osTicekt!

*Proceed to the Part 3: Configuring Teams inside osTicket*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/6af57166-6847-41d6-b5c0-2c3b3b72e5e8">

</details>

<details>

<summary>

## 🎟️ Part 3: Configure Teams

</summary>

### 4. ) Configuring Teams inside osTicket

 - Go To: `Admin Panel` > `Agents` > `Teams`

- Click: `Add New Team`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/fa7b31d4-38da-4538-bc0f-0c1c3af42afa">

<br>
<br>
<br>

<ins>Configuring Teams inside osTicket</ins>:

- Name: `Level II Support`

- Select: `Members` Tab

- Member: *The First and Last name you used in the [Prerequisites and Installtion](https://github.com/vincentchachere/osTicket-Prerequisites) osTicket Lab*

- Click: `Create Team`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/85050192-d8da-40ec-bc59-43a465f188af">

<br>
<br>
<br>

<ins>Configuring Teams inside osTicket</ins>:

- Member: *`The username you used to login into osTicket`*

- Click: `Create Team`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/32f63549-9fda-41cb-ad1c-7f7a12d849ba">

<br>
<br>
<br>

### You've Successfully configured Teams inside osTicket!

*Proceed to the final step within this part of the lab.*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5f550163-de75-47c3-9252-4d19c943e6f9">

<br>
<br>
<br>

### 5. ) Allow Anyone To Create Tickets

- Go To: `Admin Panel` > `Settings` > `Users`

- Uncheck: the `Require registration and login to create tickets` box

- Click: `Save Changes`

<img width="1511" alt="isolated" src="https://github.com/user-attachments/assets/acf7871a-020a-44bd-a00e-6d4e0a61bd73">

</details>

<details>

<summary>

## 🎟️ Part 4: Configure Agents

</summary>

### 6. ) Configuring Agents (workers) inside osTicket

- Go To: `Admin Portal` > `Agents` > `Agents`

- Click: `Add New Agent`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/ccd4d824-d33f-46b2-99ea-8db0ad475776">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Name: `Jane Doe`

- Email Address: `jane.doe@gmail.com`

- Username: `jane.doe`

- Click: `Set Password`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/c3b28c22-2ee1-440a-bd86-34b803006700">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Uncheck: `Send the agent a password reset email`

- Password: `Your osTicket Login Password`
 
- Uncheck: `Require password change at next login`
 
- Click: `Set`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/c6044063-1b89-4c88-bbe6-d5223a7adf43">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Go To: The `Access` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/127f7308-70e0-40bb-8c46-3966f12af183">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- <ins>Primary Department</ins>:

  - Department: `System Administrators`

  - Role: `Supreme Admin`

- <ins>Extended access</ins>:

  - Department: `Support`
 
  - Role: `Supreme Admin`

- Go To: The `Permissions` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/36899b8c-a312-4ef5-8c86-8c1efd1afb67">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

*Within the Permissions Tab*

- Check: `All Boxes`

- Go To: The `Teams` Tab

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/100144d4-92e7-4fa5-b389-de0bc6a8361b">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

*Within the Teams Tab*

- Assigned Teams: `Level II Support`

- Click: `Create`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/b5dfcc2b-ab55-4d4f-aecd-999584e2f5c9">

<br>
<br>
<br>

### You've configured your first Agents (workers) inside osTicekt!

*Continue creating your second Agent in the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/07a6fca4-1fb0-4008-9b57-ab4c22f239d1">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Go To: `Admin Portal` > `Agents` > `Agents` > `Add New Agent`

- Name: `John Doe`

- Email Address: `john.doe@gmail.com`

- Username: `john.doe`

- Click: `Set Password`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/37900d59-37d0-47ea-a249-9ff56c9733f6">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Uncheck: `Send the agent a password reset email`

- Password: `Your osTicket Login Password`
 
- Uncheck: `Require password change at next login`
 
- Click: `Set`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/1311b464-9600-4446-9d6d-5867358d64f0">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- Go To: The `Access` Tab

<img width="1511" alt="isolated" src="https://github.com/user-attachments/assets/67d28066-455e-45a1-8525-c474fcb2dd18">

<br>
<br>
<br>

<ins>Configuring Agents (workers) inside osTicket</ins>:

- <ins>Primary Department Access</ins>:

  - Select: `Support`
 
  - Select: `View Only`
 
- Go To: The `Permissions` Tab

  - Check: `All Boxes`
 
- Select: `Create`
 
*Leave the Teams part blank*

<img width="1511" alt="isolated" src="https://github.com/user-attachments/assets/6a7ca361-2e5b-482f-b2e6-d5570cb82cc7">

<br>
<br>
<br>

### You've Successfully configured your Agents (workers) inside osTicket!

*Proceed to the Part 5: Configuring Users (Customers) inside osTicket*

<img width="1511" alt="isolated" src="https://github.com/user-attachments/assets/53b687c8-f33b-4176-9c08-7c4329024dac">

</details>

<details>

<summary>

## 🎟️ Part 5: Configure Users

</summary>

### 8. ) Configuring Users (Customers) inside osTicket

- Go To: `Agents` > `Users` > `User Directory` > `Add User `

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/9cb4bebd-b0b8-4412-ba0b-a93722453ee2">

<br>
<br>
<br>

<ins>Configuring Users (Customers) inside osTicket</ins>:

- Email Address: `Karen@osticket.com`
 
- Full Name: `Karen Karen`
 
- Click: `Add User`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/3c2693bc-cf7a-42e3-a362-421bab2c6015">

<br>
<br>
<br> 

<ins>Configuring Users (Customers) inside osTicket</ins>:

You've configured your first User inside osTicket!

*Continue creating your second User in the next step*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5df98d4f-9c94-4710-9e08-c2898a0c91ed">

<br>
<br>
<br>  

<ins>Configuring Users (Customers) inside osTicket</ins>:

- Go To: `Agents` > `Users` > `User Directory` > `Add User `

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/d28ceaca-ad99-479d-aa21-cbc8d0b196c0">

<br>
<br>
<br>

<ins>Configuring Users (Customers) inside osTicket</ins>:

- Email Address: `Ken@osticket.com`
 
- Full Name: `Ken Ken`
 
- Click: `Add User`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/50b407b0-8928-4992-b5ab-8e43d207aa14">

<br>
<br>
<br>

<ins>Configuring Users (Customers) inside osTicket</ins>:

You've officially configured your second Users!

*Go back into the User Directory to oberserve the Users you've created.*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/959587b2-3d6e-4ca0-b493-b31ae82d48c5">

<br>
<br>
<br>

### You've Successfully configured your Users (customers) inside osTicekt!

*Proceed to the Part 6: Configuring SLAs inside osTicket*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/088d9037-d06e-4091-8326-53a1cebc676b">

</details>

<details>

<summary>

## 🎟️ Part 6: Configure SLAs

</summary>

### 9. ) Configuring SLAs inside osTicket

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

*We will be creating the following Service Level Agreements:*

  - Create: `SEV-A (1 Hour: 24/7 )`

  - Create: `SEV-B (4 Hours: 24/7 )`

  - Create: `SEV-C (8 Hours: Business Hours = Monday - Friday 8am to 5pm )`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/5196eb74-6b90-47c2-bfad-7ab07aed1741">

<br>
<br>
<br>

<ins>Configuring SLAs inside osTicket</ins>:

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-A`

  - Grace Period: `1 Hour`

  - Schedule: `24/7`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/e850f855-a6f5-41d8-8be5-99c1cf1d23ed">

<br>
<br>
<br>

<ins>Configuring SLAs inside osTicket</ins>:

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-B`

  - Grace Period: `4 Hours`

  - Schedule: `24/7`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/1c7ab212-2c15-4e2f-9a7d-4e58114b5678">

<br>
<br>
<br>

<ins>Configuring SLAs inside osTicket</ins>:

- Go To: `Admin Panel` > `Manage` > `SLA` > `Add New SLA Plan `

  - Name: `SEV-C`

  - Grace Period: `8 Hours`

  - Schedule: `Business Hours: Monday - Friday 8am to 5pm`

- Click: `Add Plan`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/fa2d4d6b-d495-48d2-ab2b-d97ebb672861">

<br>
<br>
<br>

### You've Successfully configured SLAs inside osTicekt!

*Proceed to the Part 7: Configuring Help Topics inside osTicket*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/cdbca621-8b4b-4105-ac2b-e10f85be37a3">

<br>
<br>
<br>

</details>

<details>

<summary>

## 🎟️ Part 7: Configure Help Topics

</summary>

### 10. ) Configuring Help Topics inside osTicket

- Go To: `Admin Panel` > `Manage` > `Add New Help Topics`

*We will be creating the following Help Topics:*

  - `Business Critical Outage`
 
  - `Equipment Request`
 
  - `Personal Computer Issues`
 
  - `Password Reset`

*Notice the current Help Topics that are created.*

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7a4ee028-d064-44b1-bf3b-85f1df87c4e7">

<br>
<br>
<br>

<ins>Configuring Help Topics inside osTicket<ins>:

- Topic: `Business Critical Outage`

- Click: `Add Topic`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7c99fdf8-1359-4944-b584-251220693901">

<br>
<br>
<br>

<ins>Configuring Help Topics inside osTicket<ins>:

- Topic: `Equipment Request`

- Click: `Add Topic`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/9cebecd8-b418-4a2d-a788-2d0dbef58b90">

<br>
<br>
<br>

<ins>Configuring Help Topics inside osTicket<ins>:

- Topic: `Personal Computer Issues`

- Click: `Add Topic`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/d7c0e6f1-c66e-40bd-aa18-dd27708b40ab">

<br>
<br>
<br>

<ins>Configuring Help Topics inside osTicket<ins>:

- Topic: `Password Reset`

- Click: `Add Topic`

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/45483a06-5149-4918-bd4e-1719593dbac3">

<br>
<br>
<br>

<h2 align="center">Congratulations! You finished setting up osTicket!</h2>

Now, it's time to build on this foundation by [practicing the lifecycle of tickets](https://github.com/vincentchachere/Ticket-Lifecycle) from intake to resolution.

<img width="1511" alt="isolated" src="https://github.com/vincentchachere/post-install-config/assets/161680745/7f1f496f-6f42-49c5-a32d-5ae1a013664e">

</details>

<h2 align="center">Final Thoughts</h2>

This lab provided hands-on experience in configuring the osTicket help desk ticketing system after installation, covering essential tasks such as setting up roles, departments, teams, agents, users, and Service Level Agreements (SLAs). The lab was conducted in a Microsoft Azure virtualized environment, offering practical skills for managing and optimizing help desk operations in a cloud-based infrastructure.

To continue building on this lab, check out the [next tutorial](https://github.com/vincentchachere/Ticket-Lifecycle) within this series, where we’ll practice working tickets from intake to relsoution.

Thank you for following along with this project. Your time and effort in learning and implementing these concepts are greatly appreciated.

☎️ For questions or to connect you can reach me at: www.linkedin.com/in/vincentchachere
