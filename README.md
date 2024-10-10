<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure roles 
- Configure departments
- Configure teams
- Configure agents(employees)
- Configure users (customers)
- Configure SLA (Service Level Agreement)
- Configure Help Topics

<h2>Configuration Steps</h2>


![image](https://github.com/user-attachments/assets/c0b6581f-dc2e-4f6f-a7ef-0d6e497bf35e)





</p>
<p>
1.)Upon logging into the helpdesk via the admin/ analyst link (http://localhost/osTicket/scp/login.php) I found myseelf in the tickets tab.
<br />

<p>

  
  ![image](https://github.com/user-attachments/assets/84810f42-329f-416f-bc2d-aa016d4e687d)  ![Image 10-7-24 at 5 02 AM](https://github.com/user-attachments/assets/91ce5fd4-fa52-4db5-bf59-10f820b37209)  ![Image 10-7-24 at 5 03 AM](https://github.com/user-attachments/assets/4a6a9319-8e24-4b87-afb3-30e8966aaae3)



</p>
<p>
2.) Configuring roles:
  
  Agents -> Roles -> Add New Role. From there you can name the role you want to create as well as choose/ group permissions it will be granted. In this case, the name given was "Supreme admin" and it was given "full access" hence the name.
</p>
<br />

<p>

  ![image](https://github.com/user-attachments/assets/ccc7b380-b142-43a4-9692-30b88a39eb80)  ![image](https://github.com/user-attachments/assets/dd1b2984-a43b-40ee-b67d-9f063ed33c6b)


</p>
<p>
3.) Configuring departments:

Agents -> Departments. Just like I did when I created a new role, I am naming the department and choosing what access will be granted to members of said apartment.
<p>

![Image 10-7-24 at 6 51 AM](https://github.com/user-attachments/assets/a70c411e-371a-4f72-9d8c-881baead1970)  ![image](https://github.com/user-attachments/assets/7d1bc5bf-dde8-4221-bc32-5842875c308f)
  ![image](https://github.com/user-attachments/assets/5995fb85-8adc-47aa-9bcf-851902408d04)





</p>
<p>
4.) Configuring teams:
  
  Navigate to the admin panel if you are't there already in the top right corner -> Agents -> Teams -> Add New Team

From there you can give the new team name, assign a team lead, and select which of your agents will be apart of the new team.
<p>

![image](https://github.com/user-attachments/assets/89371671-ea9e-4700-bf61-d418d05efe8d)  ![image](https://github.com/user-attachments/assets/145995eb-2c78-427c-b475-5a95a3ab1887)  ![image](https://github.com/user-attachments/assets/0173e83b-e647-4b33-a0ae-10f6e8bb8ebb) ![image](https://github.com/user-attachments/assets/6e860291-a31a-4a7f-b335-a9fe1f68c8f9)  ![image](https://github.com/user-attachments/assets/cb274bf5-2579-498b-921b-8cfd05318697)

</p>
<p>
5.) Configuring agents:

Admin panel -> agents -> Add New Agent

Here you can add all of the credentials needed for an agent account such as usernames, emails, phone numbers, and passwords. You can also assign them to a certain department, role, or team as well as grant certain permissions.
<p>


![image](https://github.com/user-attachments/assets/9c7a6836-a045-4cff-8f6d-c22eb449c567)  ![image](https://github.com/user-attachments/assets/4bf60463-2122-4ce9-8df9-1aea90f97845)

</p>
<p>
6.) Configuring users (customers):

(In the top right corner) Agent panel -> Users -> Add New User

This obviously does not require as much information as creating an agent profile would. All that is needed is a name, email address and phone number(optional)
<p>

![image](https://github.com/user-attachments/assets/73464616-3975-4245-a001-35b5f9948fe3)  ![image](https://github.com/user-attachments/assets/42b9d935-666b-4ef1-838b-04101d5abc1c)

</p>
<p>
7.) Configuring SLA (Service Level Agreement):
Admin panel (top right corner) -> Manage -> SLA -> Add New SLA Plan

I already added 3 new SLA plans from Sev-A to Sev-C (Sev-A being the highest priority and Sev-C being the lowest). You can name the SLA plans whatever you want as well as assign a grace period(in hours) and a schedule for it (24/7, 24/5, or a generic 5 business days schedule)
<p>


![image](https://github.com/user-attachments/assets/33557038-6f1c-42c3-9f51-dcfd5211ab49)  ![image](https://github.com/user-attachments/assets/472b9408-bf6e-42b1-a03a-113f60f32db7) 

</p>
<p>
8.) Configuring Help Topics:

Admin panel (top right corner) -> Manage -> Help Topics -> Add New Help Topic
Help Topics will determine what Department the ticket is routed to which will determine which Agents have access to the ticket. You can create a name for the new topic,make it public or private/ internal, and also assign a "Parent Topic"










