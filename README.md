<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=fvuZKaTJEEA)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments 
- Configure Teams 
- Allow anyone to create tickets 
- Configure Agents
- Configure Users
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>




<h2>Configure Roles</h2>
<p>

</p>
<p>
After you have logged into osTicket You will navigate to Admin Panel -> Agents -> Roles

![image](https://github.com/user-attachments/assets/92d91950-54b7-4fd6-9855-8d0fbe88df50)

From there you will create the role "Supreme Admin" 

to do this you will select add new role in the top right 
![image](https://github.com/user-attachments/assets/b1a171b1-c737-407e-a1e7-4cd250c86be4)



Next you will name the role "Supreme Admin" and then select permissions and check mark and assign each box and add the Role

![image](https://github.com/user-attachments/assets/52af21db-8b04-4ae6-a739-889e54b6b8e5)




</p>
<br />
<h2>Configure Departments</h2>
<p>

</p>
<p>
To configure Departments you will need to go to Admin Panel -> Agents -> Departments

![image](https://github.com/user-attachments/assets/e280e9a4-9151-4c21-a49e-4f717dbad8d9)

From here you will Add new Department ![image](https://github.com/user-attachments/assets/cb5c89b1-7231-4b8c-a58b-bbe76c5feb9a)

Next you will make the "Top Level Department" Support and then name the department "Sys Admins". Once you do this just select Add role
![image](https://github.com/user-attachments/assets/148efffd-a6e4-4bef-b453-fad561be9c1b)



</p>
<br />
<h2>Configure Teams</h2>
<p>

</p>
<p>
To configure teams you will need to go to Admin Panel -> Agents -> Teams

![image](https://github.com/user-attachments/assets/88d7f60e-55b3-40bf-9e55-39e704fdb3bb)


From here you will select add new team in the top right corner ![image](https://github.com/user-attachments/assets/c11ad757-18b1-4438-92b0-23d34d7bb477)


Now you will name the team "Online Banking" and select "Create Team"

![image](https://github.com/user-attachments/assets/e1aa6e0c-722b-45f4-ac18-4e9d969dc637)

</p>
<br />


</p>
<br />
<h2>Allow anyone to create tickets </h2>
<p>

</p>
<p>
To allow anyone to create tickets you will need to go to Admin Panel -> Settings -> User Settings

![image](https://github.com/user-attachments/assets/3e8642e7-8c75-4539-8dca-b6c90b9d6bc3)

From here you will makes sure Registration Required: Require registration and login to create tickets is unchecked 

![image](https://github.com/user-attachments/assets/5d685941-db2a-4e72-b5ec-5bff18a5cdae)



</p>
<br />


</p>
<br />
<h2>Configure Agents (Workers)</h2>
<p>

</p>
<p>
to configure Agents(workers) you will need to go to Admin Panel -> Agents -> Add New

![image](https://github.com/user-attachments/assets/bd146fa2-ed84-408f-a495-aaac10395e63)


From here you will need to create two agents and assign them to their own departments 

Jane (Dept: SysAdmins)


![image](https://github.com/user-attachments/assets/ae0a8632-010c-4378-923c-2cb962e36596)
![image](https://github.com/user-attachments/assets/70276ca8-da5c-460f-a52a-d627e9e6eb34)


John (Dept: Support)


![image](https://github.com/user-attachments/assets/dcaecf98-90fe-4286-a5cf-2e179c98c8e5)


Now you have two Agents created 

![image](https://github.com/user-attachments/assets/6ea7a629-db31-4aa8-8cbe-1c875c3358e6)

</p>
<br />




</p>
<br />
<h2>Configure Users</h2>
<p>

</p>
<p>
To configure users you will need to go to Agent Panel -> Users -> Add New


![image](https://github.com/user-attachments/assets/dea24104-e9df-4013-a934-1ae9ac074d81)
![image](https://github.com/user-attachments/assets/7eb0ae4e-d9f9-4f2d-bef7-e758462f2914)
![image](https://github.com/user-attachments/assets/71e3063b-5cda-4a25-86c1-3773055989e9)



From here you will create two users Karen & Ken

![image](https://github.com/user-attachments/assets/b2da508b-fe73-458d-a750-396cfd098367)


</p>
<br />


</p>
<br />
<h2>Configure SLA</h2>
<p>

</p>
<p>
To configure SLA you will need to go to Admin Panel -> Manage -> SLA

![image](https://github.com/user-attachments/assets/870b04cc-1342-4038-a49f-f2ba7589e233)
![image](https://github.com/user-attachments/assets/2e7a3daf-bfe5-4477-a2ab-e061913397db)
![image](https://github.com/user-attachments/assets/a21272c7-2bd2-47c7-934f-56df097a4286)


From here you will select add new SLA Plan ![image](https://github.com/user-attachments/assets/8c94b721-6f9c-48c9-a1be-de5cd3c2c63d)




Now you will create 

Sev-A (Grace Period: 1 hour, Schedule: 24/7)


![image](https://github.com/user-attachments/assets/66692371-3b77-43ed-b2e5-4428681fdc90)


Sev-B (Grace Period: 4 hours, Schedule: 24/7)


![image](https://github.com/user-attachments/assets/59c362d0-f6dc-40db-90ed-881e8d6ecf54)


Sev-C (Grace Period: 8 hours, Business Hours)


![image](https://github.com/user-attachments/assets/642d96f2-e837-4e55-942f-fb4d94b58db1)

</p>
<br />


</p>
<br />
<h2>Help Topics</h2>
<p>

</p>
<p>
To configure Helptopics s you will need to go to Admin Panel -> Manage -> Help Topics

![image](https://github.com/user-attachments/assets/870b04cc-1342-4038-a49f-f2ba7589e233)
![image](https://github.com/user-attachments/assets/2e7a3daf-bfe5-4477-a2ab-e061913397db)
![image](https://github.com/user-attachments/assets/60f8fb44-8672-4d57-b484-6dcfb2d3c5a1)
![image](https://github.com/user-attachments/assets/171aeeac-a62d-4c79-8d35-28c928a564fc)


From here you will need to add your Help topics:

Business Critical Outage


![image](https://github.com/user-attachments/assets/ddeb71c4-2b6e-4693-8a90-297b32f8083a)

Personal Computer Issues


![image](https://github.com/user-attachments/assets/e50808b3-69c4-41fa-afce-9c419280f651)

Equipment Request


![image](https://github.com/user-attachments/assets/90667219-bb83-455b-bd7b-c673e148c70a)

Password Reset


![image](https://github.com/user-attachments/assets/a0bf953b-c301-4014-bb16-4dce843c7d51)

Other


![image](https://github.com/user-attachments/assets/2a30e047-8625-4b81-bcf6-8e5ac704c6fb)


</p>
<br />


<h2>osTicket should be set up and configured!</h2>
