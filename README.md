<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Operating Systems Used </h2>

- Windows 10 for Virtual Machine</b> (22H2)

<h2>Post-Install Configuration Objectives</h2>

- Set up roles and permissions for agents and users. Creating Users and Agents.
- Configure ticket visibility and help desk functionality.
- Configuring SLAs to define response times for tickets.
- Adding different types of help topics to enhance efficency and user experience.

<h2>Configuration Steps</h2>

### Step 1: Configure Roles
<p>
<img width="958" height="380" alt="image" src="https://github.com/user-attachments/assets/b6087ef8-2f10-461f-9612-4a219cab419a" />
<img width="952" height="430" alt="image" src="https://github.com/user-attachments/assets/36c19225-5c97-47b4-968a-b5c7fc7d3dfb" />
</p>
<p>
Switched to Admin Panel then navigated to Agents -> Roles. Click New Role and named it "Supreme Admin" then in the permissions tab check every box for permissions/access. Create the Role.
</p>
<br />

<p>
<img width="956" height="930" alt="image" src="https://github.com/user-attachments/assets/9c32a801-0e47-4cf9-8a01-826d21e3364f" />
</p>
<p>
In the Admin Panel navigate to Agents -> Departments -> Add New Department. Switch the Parent to "Top-Level Department" and named the department "SysAdmins". Create the Department.
</p>
<br />

<p>
<img width="953" height="679" alt="image" src="https://github.com/user-attachments/assets/f17c1fd4-02d1-4321-a07e-41ea24febf56" />
</p>
<p>
In the Admin Panel navigate to Agents -> Teams -> Add New Team. Named it "Online Banking" then create the team.
</p>
<br />

### Step 2: Agents
<p>
<img width="951" height="541" alt="image" src="https://github.com/user-attachments/assets/6e36d78d-8085-484c-a78b-97cd07e979fc" />
</p>
<p>
In the Admin Panel navigate to Settings -> Users. Verify that the "Registration Required:" setting is unchecked. This makes it so people aren't required to register and login to create a ticket.
</p>
<br />

<p>
<img width="928" height="582" alt="image" src="https://github.com/user-attachments/assets/32a41095-cdb9-4282-bb6b-1e7ab5f06c34" />
<img width="953" height="529" alt="image" src="https://github.com/user-attachments/assets/da7e9636-b4f0-4103-8dfd-a8c5f10d1c38" />
<img width="954" height="423" alt="image" src="https://github.com/user-attachments/assets/8f29952f-222f-4146-a4bd-10fdfef9525e" />
</p>
<p>
In the Admin Panel navigate to Agents -> Add New Agent. Created an agent called "Jane Doe" with the following credentials (Note: A fake email was used):
  
    - Username: jane
    - Password: Password1

Gave Jane the "SysAdmin" Department with the Role of "Supreme Admin" so that agent can have access to everything. Added Jane to the "Online Banking" Team as well. 
    
</p>
<br />

<p>
<img width="956" height="633" alt="image" src="https://github.com/user-attachments/assets/59425f0d-1bef-4084-bcc0-594f99c315d4" />
<img width="954" height="530" alt="image" src="https://github.com/user-attachments/assets/aadf69a0-e808-4cfb-a318-dafca1ee139c" />

</p>
<p>
In the Admin Panel navigate to Agents -> Add New Agent. Created an agent called "John Doe" with the following credentials (Note: A fake email was used):
  
    - Username: john
    - Password: Password1

Gave John the "Support" Department with the Role of "View Only" and created the agent.
</p>
<br />

### Step 3: Users
<p>
<img width="643" height="387" alt="image" src="https://github.com/user-attachments/assets/7c00e50f-1722-49c7-a044-8a23c486a143" />
</p>
<p>
Switched to the Agent Panel then navigate to Users -> Add New. Naming the user "karen" (Note: A fake email was used).
</p>
<br />

### Step 4: Configure SLA and Help Topics
<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />

<p>

</p>
<p>

</p>
<br />
