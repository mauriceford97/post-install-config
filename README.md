# p<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Configuration Steps</h2>

<p>
<img width="919" height="916" alt="image" src="https://github.com/user-attachments/assets/4cea794f-0c5a-4146-9df5-d4a5e724c1c1" />

</p>
<p>
configuring roles, roles determine what an agent can and cannot doin osticket. 1. make sure your logged in as an admin from there go to admin panel. 2. Navigate to agents then roles. 3. Click add new role. 4.Role name (supreme admin, IT support etc.) 5. configure permissions: such as view/update tickets, assign tickets, manage agents/teams, access reports/knowledgebase. 6. create role. this role can be assigned to agents later.
</p>
<br />

<p>
<img width="892" height="895" alt="image" src="https://github.com/user-attachments/assets/6c86e6f4-dc5e-4c56-acc6-2b969cac1be4" />

</p>
<p>
configuring departments, departments categorize tickets and route them to the right agents. 1.Go to Admin Panel then manage then departments. 2. Click add department. 3. fill in department name for example sysadmins, then click create department. tickets that are subbmitted under a department are routed correctly. 
</p>
<br />

<p>
<img width="895" height="880" alt="image" src="https://github.com/user-attachments/assets/d735b1aa-2a7f-4ae1-b352-e131c6875dc3" />

</p>
<p>
Configure teams, teams group multiple agents for easier ticket handling. 1. Go to Admin Panel then Agents then Teams. 2. Add new team. 3. team name for example online banking. 4. Add members; Assign agents to the team, Assign a team lead if needed. Then click create team. Now tickets can be assigned to a team, and agents within the team can collaborate.
</p>
<br />ost-install-config

Now we want to allow anyone to create tickets, so to do that go to the admin panel, click settings, then go to users settings and make sure registration required is unchecked.

Configure Agents, Agents are the help desk workers who log in to answer and manage tickets.
 <img width="890" height="517" alt="image" src="https://github.com/user-attachments/assets/f3f594b5-cb75-4826-b7d1-b5d43d562a20" />

 To configure Agents Go to Admin Panel the Agents then Add New.
 <img width="881" height="883" alt="image" src="https://github.com/user-attachments/assets/03c263c1-a9ea-4bc8-af91-316ed77bba84" />

 Here is where we will add the name, email and the username of the 2 agents and create a password.Then we assigned them to a department, then assigned to a role, then assigned them to a team. Then we hit create  

