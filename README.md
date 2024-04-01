<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com/watch?v=HGywPhfKt4E)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Create Role, Departments, and Teams
- Create Agents and Users
- Allow Users to create tickets
- Create System Level Agreement (SLA)
- Create Help Topics

<h2>Configuration Steps</h2>

![20240319_001920](https://github.com/tylermartin12368/post-install-config/assets/161632103/9a74309d-a6bf-4695-a114-1b66200814fc)
</p>
<p>
In OSticket we can create roles, departments, and teams. We will have Agents(workers) and Users (customers) in the system. Users will have access to Support Center where they can create tickets for any issues being experienced. Agents will be assigned to a role, department, and team and will have access to working on tickets. Roles are created to give certain permissions to an Agent. One role could have access to certain permissions that other roles may not have like assigning tickets or trasfering tickets. Departments are created to have a group of Agents in them to solve tickets on a specific issue. Lets say a ticket was placed about a networking issue, then the networking department would be responsible for solving the issue since they will have the experiece to tackle the problem. Teams are created to allow Agents to be pulled from any department and have them work on an issue. We can have Agents placed in Level 1 Support or Level 2 Support for example and Level 2 in this case are Agents who may have more experience and can handle bigger issues that may appear.   
</p>
<br />

![20240319_003907](https://github.com/tylermartin12368/post-install-config/assets/161632103/e4c9a9a7-db39-4b15-8b6f-da73d99760e0)
</p>
<p>
Service Level Agreements (SLA) in OSticket is created to provide an amount of time the Admin expects the ticket to be resolved. Let's say we have a ticket that comes in on Saturday at 11pm and its business impacting. The ticket would be placed on Sev-A and in this case and will need to resolved on Saturday at 12pm. Service Level Agreements will help us understand what tickets should be priotized first, so problems can be resolved effeciently and in the amount of time that is being provided.
</p>
<br />

![20240319_004457](https://github.com/tylermartin12368/post-install-config/assets/161632103/a3736925-5969-46f6-97ce-0f8672973acc)
</p>
<p>
In OSticket we can create Help Topics for Users. Help Topics help Users explain the issue that they are experiencing. It also helps Agents get a grasp of the problem and be able to come up with solutions quickly to resolve the matter. A User could be experiencing a problem with their password. They can select "Password Reset" and write a description saying that the password that they are trying to login with is not working. The Agent will see this and be able to quickly resolve this issue by giving the User a temporary password and allow them to create a new password when logged backed in. 
</p>
<br />
