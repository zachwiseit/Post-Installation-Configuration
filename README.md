<p align="center">
<img width="1000" height="750" alt="image" src="https://github.com/user-attachments/assets/4698e6ac-8f43-48aa-8dc6-102d5665a896" />
</p>

<h1>osTicket – System Configuration Post-Install</h1>
This is the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Windows App (MacOS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- macOS Sonama 14.6.1

<h2>Configuration Aims Post-Installation</h2>

- Roles 
- Departments 
- Teams 
- Agents 
- Users
- SLA
- Help Topics 

<h2>Configuration Steps</h2>
1 Continuing on, if you're coming back, log into the Admin Analyst page. http://localhost/osTicket/scp/login.php
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 12 54 PM" src="https://github.com/user-attachments/assets/9ded31bb-1398-45c3-98f6-fb1e99349334" />
</p>
<p>
2 Then open up the end user support page to submit tickets. http://localhost/osTicket
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 12 57 PM" src="https://github.com/user-attachments/assets/c11bacd4-1115-4a52-9283-bdbfea5d45f1" />
</p>
<p>
3 Go back to the Analyst page to configure roles.
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 15 08 PM" src="https://github.com/user-attachments/assets/ec81a68e-063a-4294-b167-7422fe20d281" />
</p>
<p>
5 Click on the "Agents" tab. 
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 18 09 PM" src="https://github.com/user-attachments/assets/dcb49ef7-3e2f-4025-9841-f2ebb0c0d7c2" />
</p>
<p>
6 Then click on "Roles".
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 18 25 PM" src="https://github.com/user-attachments/assets/635042bd-b8bc-49ae-9ead-7b20515a18c5" />
</p>
<p>
7 On this page you can see the different levels of access and change who has access to what.
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 18 50 PM" src="https://github.com/user-attachments/assets/4e02e526-f092-41ea-9ea1-51abc765e3fa" />
</p>
<p>
8 From here click on "Permissions".
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 18 59 PM" src="https://github.com/user-attachments/assets/5d75a3ce-1950-4c6a-9ac5-785a0f26251b" />
</p>
<p>
9 As you can see, because it is view only, none of the permissions are checked. 
<p>
<img <img width="1440" alt="Screenshot 2025-05-27 at 3 19 22 PM" src="https://github.com/user-attachments/assets/9b80e966-0a3a-4455-ad16-d33018314547" />
</p>
<p>
10 Now go back to Roles and click "Expanded Access".
<p>
<img <img width="1440" alt="PIC_10" src="https://github.com/user-attachments/assets/6085410e-211e-440e-9e70-e04b4bef1615" />
</p>
<p>
11 Also in the permissions tab you can see more access is granted but not completely. 
<p>
<img <img width="1440" alt="PIC_11" src="https://github.com/user-attachments/assets/42428647-ba2f-4b66-a990-eb28d7d412c0" />
</p>
<p>
12 Next go back to "Roles", click "All Access", and "Permissions" again. Naturally everything is checked. 
<p>
<img <img width="1440" alt="PIC_12" src="https://github.com/user-attachments/assets/af1c48f9-ee5a-45d7-9b00-bae583f16a21" />
</p>
<p>
13 You can also create and define your own role like this. In Roles click "Add New Role" 
<p>
<img <img width="1440" alt="PIC_13" src="https://github.com/user-attachments/assets/0dcd49d0-ea0d-4b1e-bc8d-e74639ea46c4" />
</p>
<p>
14 Add the name of your choice to the role. I used Supreme Admin.
<p>
<img <img width="1440" alt="PIC_14" src="https://github.com/user-attachments/assets/58c83731-c6b3-4859-a9c6-740c79216418" />
</p>
<p>
15 For permissions because I named the role Supreme Admin I gave them full access. 
<p>
<img <img width="1440" alt="PIC_15" src="https://github.com/user-attachments/assets/827c3060-c252-4a03-bf3d-f20e8b2e3677" />
</p>
<p>
16 Full access to "Tasks"
<p>
<img <img width="1440" alt="PIC_16" src="https://github.com/user-attachments/assets/939d1d7e-613d-42ca-86bc-a69ec2bb4138" />
</p>
<p>
17 With access to "Knowledgebase as well. Once you have done that click "Add Role".
<p>
<img <img width="1440" alt="PIC_17" src="https://github.com/user-attachments/assets/9145605a-6590-4ad3-9352-0ffb35e39265" />
</p>
<p>
18 Now you will see your new role added to the list.
<p>
<img <img width="1440" alt="PIC_18" src="https://github.com/user-attachments/assets/b6c627ab-3bd2-40ad-9f17-e15b8772d555" />
</p>
<p>
19 Next is Department configuration. Next to Roles, click "Departments". 
   This is useful to make a ticket visable to the correct departments. 
<p>
<img <img width="1440" alt="PIC_19" src="https://github.com/user-attachments/assets/66430b9e-59ab-4406-a338-56692f2cb016" />
</p>
<p>
20 Click "Add New Department" 
<p>
<img <img width="1440" alt="PIC_20" src="https://github.com/user-attachments/assets/efa30687-7464-4763-82f2-064d5163810a" />
</p>
<p>
21 Here you can add new departments with specific information. For now, just change the "Parent" and "Name" to what I have below. 
   Parent: "Top Level Department"
   Name: "SysAdmins"
   Now click "Access"
<p>
<img <img width="1440" alt="PIC_21" src="https://github.com/user-attachments/assets/b675d5e5-0591-4dc0-8422-990ff7e9ea6c" />
</p>
<p>
22 This is where you will add agents to the departments (After they are created shortly).
<p>
<img <img width="1440" alt="PIC_22" src="https://github.com/user-attachments/assets/e84340a8-ad1d-452e-906b-7db76d9e7ecc" />
</p>
<p>
23 Back at the settings tab, scroll down and click "Create Dept" at the bottom. 
<p>
<img <img width="1440" alt="PIC_23" src="https://github.com/user-attachments/assets/4abf1340-2565-4d74-85c1-e4dd8becf97d" />
</p>
<p>
24 Now you will see your Support SysAdmins that was just created. Next step is to create a Team. 
<p>
<img <img width="1440" alt="PIC_24" src="https://github.com/user-attachments/assets/35210fad-06bd-4ff0-8a2d-dafea0816a4c" />
</p>
<p>
25 The purpose of this is to group people with similar roles or responsibilities to optimize ticket assignments, collaboration, and overall workload. 
  First from the admin panel click "Agents" and then "Teams" between Agents and Roles. Then "Add New Team".
<p>
<img <img width="1440" alt="PIC_25" src="https://github.com/user-attachments/assets/cb6f994e-5787-4fd8-9815-eca0509ea573" />
</p>
<p>
26 From here change the name to "Online Banking" and click "Create Team". 
<p>
<img <img width="1440" alt="PIC_26" src="https://github.com/user-attachments/assets/6f3f3c26-d518-42f5-9efd-c365986dfd2d" />
</p>
<p>
27 Now we need to change the settings so Anyone can create a ticket. 
   Go to "Settings" and then "Users". 
<p>
<img <img width="1440" alt="PIC_27" src="https://github.com/user-attachments/assets/e67509e0-f47d-4e02-8e6c-bff908e39d09" />
</p>
<p>
28 If it is checked, make sure the box for "Registration Required" is unchecked for the purpose of this exercise. 
<p>
<img <img width="1440" alt="PIC_28" src="https://github.com/user-attachments/assets/f44614f9-1fdc-46c3-99ea-7dbddaad1086" />
</p>
<p>
29 Next we need to configure the agents to act as our admins and supports. 
   In the top right click "Agents".
<p>
<img <img width="1440" alt="PIC_29" src="https://github.com/user-attachments/assets/e0f760c1-414c-4537-adf9-cea8ffb1a093" />
</p>
<p>
30 Now click "Add New Agent". 
<p>
<img <img width="1440" alt="PIC_30" src="https://github.com/user-attachments/assets/bbaed4b0-1524-427e-9b44-2eed87edd7a5" />
</p>
<p>
31 First we will create our SysAdmin. Choose a Name, Email Address, and Username (save this information for Agents, also the email can be fake).
<p>
<img <img width="1440" alt="PIC_31" src="https://github.com/user-attachments/assets/f7eec134-5db4-4b5c-b676-f7a59fd03248" />
</p>
<p>
32 Now under Access for Department select Support/SysAdmins and Role choose Supreme Admin. 
<p>
<img <img width="1440" alt="PIC_32" src="https://github.com/user-attachments/assets/ee475bd6-3d33-4b0b-88c8-df96dd594e11" />
</p>
<p>
33 In the permissions tab make sure all boxes are checked. 
<p>
<img <img width="1440" alt="PIC_33" src="https://github.com/user-attachments/assets/bb3238b4-a54a-4a68-ba3b-42654a7298d9" />
</p>
<p>
34 For Teams, make them a part of the Online Banking team that was created earlier. 
<p>
<img <img width="1440" alt="PIC_34" src="https://github.com/user-attachments/assets/035ae7aa-7a48-430a-86a2-ad617c7f30e7" />
</p>
<p>
35 Now that the first agent account is created we will make one more. 
<p>
<img <img width="1440" alt="PIC_35" src="https://github.com/user-attachments/assets/32579cb0-f47e-40e8-bff0-e0668cbe354d" />
</p>
<p>
39 Now go through the same steps again to create the support agent. 
<p>
<img <img width="1440" alt="PIC_39" src="https://github.com/user-attachments/assets/b51ee3e4-96da-465a-b5be-484fcafab53c" />
</p>
<p>
40 Fill out the account information same as before but with different information. 
<p>
<img <img width="1440" alt="PIC_40" src="https://github.com/user-attachments/assets/4263c7e2-bc14-4f62-8e34-2f548bbffa28" />
</p>
<p>
41 For Access it will be a little different. For Departments it will be "Support" and "View only". 
<p>
<img <img width="1440" alt="PIC_41" src="https://github.com/user-attachments/assets/24c7835e-16a9-4309-91a9-ba3a0a4f20ee" />
</p>
<p>
42 In Permissions leave everything checked. 
<p>
<img <img width="1440" alt="PIC_42" src="https://github.com/user-attachments/assets/46e40673-fb3c-4177-9d7a-dc95344b00f5" />
</p>
<p>
43 For Teams leave as is and click "Create".
<p>
<img <img width="1440" alt="PIC_43" src="https://github.com/user-attachments/assets/ec1836da-8876-4ed0-b6c8-8e04d408fa0f" />
</p>
<p>
44 Now in Agents you will see the two that you just created. Next set the Agents password by clicking on their name. 
<p>
<img <img width="1440" alt="PIC_44" src="https://github.com/user-attachments/assets/86194c32-6808-405e-ba55-208dd07d4193" />
</p>
<p>
45 Click "Set Password".
<p>
<img <img width="1440" alt="PIC_45" src="https://github.com/user-attachments/assets/484e97b4-7e7b-452b-b556-cb5d68503b8c" />
</p>
<p>
46 Uncheck the box next to "Send the agent a password reset email" and choose a password and write it down. 
   Uncheck the box Next to "Request password change at next login" and click update. 
<p>
<img <img width="1440" alt="PIC_46" src="https://github.com/user-attachments/assets/06c1dd85-ec79-4f46-82e1-cb44a4b6edbd" />
</p>
<p>
47 With the first agents password set go back to "Agents" 
<p>
<img <img width="1440" alt="PIC_47" src="https://github.com/user-attachments/assets/981d937b-81e3-4e84-8bdf-24e273412898" />
</p>
<p>
48 Click on the next agent that was created and do the same process. 
<p>
<img <img width="1440" alt="PIC_48" src="https://github.com/user-attachments/assets/338d5c84-10c5-44d3-9a80-16cd9214d80f" />
</p>
<p>
49 Uncheck the boxes, choose a password, and click update. 
<p>
<img <img width="1440" alt="PIC_49" src="https://github.com/user-attachments/assets/26700704-4d1f-4017-a4bc-032390209cc5" />
</p>
<p>
50 With both Admin Agents fully created next we will create a user from the "Agent Panel". 
<p>
<img <img width="1440" alt="PIC_50" src="https://github.com/user-attachments/assets/504d154c-d2df-47d0-b329-e80857f47970" />
</p>
<p>
51 In the top right of the page click "Agent Panel".
<p>
<img <img width="1440" alt="PIC_51" src="https://github.com/user-attachments/assets/3fe9904b-21e7-4a71-9a85-03f3b3894578" />
</p>
<p>
52 In the Agents Panel click "Users".
<p>
<img <img width="1440" alt="PIC_52" src="https://github.com/user-attachments/assets/b3fe7b3d-c407-436e-bba6-d282075a24e6" />
</p>
<p>
53 Now click "Add User". 
<p>
<img <img width="1440" alt="PIC_53" src="https://github.com/user-attachments/assets/2f5c73b6-ba5e-4f98-8b4d-4b890030686f" />
</p>
<p>
55 Give them a fake email, enter their name and click "Add User". 
<p>
<img <img width="1440" alt="PIC_55" src="https://github.com/user-attachments/assets/ba4ff052-b438-4b26-86ed-adf7cf739e23" />
</p>
<p>
56 Now that you have your user make sure to right down their information for later (Name and email).
<p>
<img <img width="1440" alt="PIC_56" src="https://github.com/user-attachments/assets/50696cab-e86b-4ded-a90d-6033e94cc72f" />
</p>
<p>
57 Next we will configure the SLA(Service Level Agreement). 
   Click the "Admin Panel".
   Click the "Manage tab" and click "SLA".
<p>
<img <img width="1440" alt="PIC_57" src="https://github.com/user-attachments/assets/99f5a788-ba80-4151-a596-70104c85357b" />
</p>
<p>
58 Click "SLA" at the top.
<p>
<img <img width="1440" alt="PIC_58" src="https://github.com/user-attachments/assets/169d39e4-102f-445b-9468-ed298b8fd503" />
</p>
<p>
59 Click "Add New SLA Plan".
<p>
<img <img width="1440" alt="PIC_59" src="https://github.com/user-attachments/assets/aa3224eb-6b1a-4c08-93bc-6b1b6c145dab" />
</p>
<p>
60 We are going to create three different SLA's. Fill out the Name, Grace Period, and schedule like so. 
   Name: Sev-A
   Grace Period: 1 (The amount of time in hours to complete a ticket till considered overdue.) 
   Schedule: 24/7
   Click "Add Plan"
<p>
<img <img width="1440" alt="PIC_60" src="https://github.com/user-attachments/assets/9593c811-ba8f-4a9a-a727-56e5886da29a" />
</p>
<p>
61 Now SLA two, this one being considered more severe. 
    Name: Sev-B
   Grace Period: 4 
   Schedule: 24/7
   Click "Add Plan"
<p>
<img <img width="1440" alt="PIC_61" src="https://github.com/user-attachments/assets/eb710f55-b5f4-46f9-81d9-1bb85b6da5ec" />
</p>
<p>
62 SLA 3 for tickets that could cause a very serious impact and require a lot more time. 
   Name: Sev-C
   Grace Period: 
   Schedule: Monday - Friday 8am - 5pm with U.S. Holidays
   Click "Add Plan"
<p>
<img <img width="1440" alt="PIC_62" src="https://github.com/user-attachments/assets/0b340dfa-4c14-43a8-a195-d64b9221b785" />
</p>
<p>
63 With all the SLA's created next we will configure "Help Topics" when a user creates a ticket.
<p>
<img <img width="1440" alt="PIC_63" src="https://github.com/user-attachments/assets/c764d981-de19-4328-806d-18a0e6d3505b" />
</p>
<p>
64 From the Manage tab click "Help Topics" and click "Add New Help Topic" 
<p>
<img <img width="1440" alt="PIC_64" src="https://github.com/user-attachments/assets/2099be39-0583-4d04-98c8-f3e7a22a0c4f" />
</p>
<p>
66 First one 
   Topic: Business Critical Outage.
   Parent Topic: Report a Problem
   Click "Add topic". 
<p>
<img <img width="1440" alt="PIC_66" src="https://github.com/user-attachments/assets/72f61caa-94b2-4a25-b4ba-d0bbc9ea806c" />
</p>
<p>
67 Go back to "Help Topics" and click "Add New Help Topic" again.
<p>
<img <img width="1440" alt="PIC_67" src="https://github.com/user-attachments/assets/e6be8add-a223-4f1d-9408-5a0525759d3c" />
</p>
<p>
68  Second 
   Topic: Personal Computer Issues 
   Parent Topic: Report a Problem
   Click "Add topic". 
<p>
<img <img width="1440" alt="PIC_68" src="https://github.com/user-attachments/assets/e14d7d71-de6b-45b3-8095-a64743f6ccbb" />
</p>
<p>
69 Third
   Topic: Equipment Request
   Parent Topic: General Inquiry
   Click "Add topic". 
<p>
<img <img width="1440" alt="PIC_69" src="https://github.com/user-attachments/assets/2c0bfd86-9463-42dc-919b-6ee7ee47e863" />
</p>
<p>
71 Fourth
   Topic: Password Reset
   Parent Topic: Report a Problem
   Click "Add topic". 
<p>
<img <img width="1440" alt="PIC_71" src="https://github.com/user-attachments/assets/50e301c5-9e3e-4ad7-8838-d6928a115462" />
</p>
<p>
72 Fifth
   Topic: Other
   Parent Topic: General Inquiry
   Click "Add topic". 
<p>
<img <img width="1440" alt="PIC_72" src="https://github.com/user-attachments/assets/70cd4935-0b79-47e4-b079-7034f93e8256" />
</p>
<p>
73 Now you can see the five Help Topics you just created. 
<p>
<img <img width="1440" alt="PIC_73" src="https://github.com/user-attachments/assets/62e4133d-928f-47ee-a6c7-5b63fe1178c6" />
</p>
<p>
In the next portion we will go through all Ticket life cycle. 
