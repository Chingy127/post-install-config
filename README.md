<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial continues from the previous lab where osTicket was successfully installed.  
In this section, the help desk system is configured so it can properly organize users, agents, departments, and support tickets.

These settings allow the help desk to function like a real IT support environment.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11 (25H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure help topics for ticket organization
- Configure Service Level Agreements (SLAs)
- Create user accounts
- Create and manage support agents
- Configure teams, departments, and roles

<h2>Configuration Steps</h2>

<p>
<img width="1440" height="823" alt="Screenshot 2026-03-07 at 3 21 15 PM" src="https://github.com/user-attachments/assets/eccb57a9-2244-4172-a4ce-92b4c1dbae22" />
</p>
<p>
Help Topics are configured to categorize incoming support requests.  
These topics help organize tickets based on the type of issue, such as password resets, system outages, or equipment requests.
</p>
<br />

<p>
<img width="1440" height="819" alt="Screenshot 2026-03-07 at 3 21 51 PM" src="https://github.com/user-attachments/assets/f7799c78-45be-4438-b3f5-f4f4fd32c409" />
</p>
<p>
Service Level Agreements (SLAs) define how quickly support tickets should be handled.  
Different SLA levels can be assigned depending on how urgent the issue is.
Sev-A being the highest severity, Sev-B average severity, and Sev-C minimal severity 
</p>
<br />

<p>
<img width="1438" height="824" alt="Screenshot 2026-03-07 at 3 22 53 PM" src="https://github.com/user-attachments/assets/f2a8aa34-9a78-4c43-a12e-bef39616ec9c" />
</p>
<p>
Users are added to the system so they can submit support tickets.  
These users represent employees or customers who need assistance from the help desk.
</p>
<br />

<p>
<img width="1440" height="818" alt="Screenshot 2026-03-07 at 3 23 57 PM" src="https://github.com/user-attachments/assets/2bf10f4a-b0e9-4fd5-8e41-536097e6b8dc" />
</p>
<p>
Agents are the support staff who manage and resolve tickets.  
Each agent can be assigned to specific departments or teams depending on their responsibilities.
</p>
<br />

<p>
<img width="1429" height="817" alt="Screenshot 2026-03-07 at 3 24 26 PM" src="https://github.com/user-attachments/assets/be4f87fd-2e0f-48e8-a1cf-0dc9028c0aae" />
</p>
<p>
Teams allow agents from different departments to collaborate when resolving support tickets.  
This is useful when multiple specialists need to work together on an issue.
</p>
<br />

<p>
<img width="1440" height="822" alt="Screenshot 2026-03-07 at 3 24 52 PM" src="https://github.com/user-attachments/assets/0d60241d-0b4a-4039-8197-052ccb157200" />
</p>
<p>
Departments organize the help desk into different support areas such as system administrators or general support.  
Tickets can be routed to the correct department for faster resolution.
</p>
<br />

<p>
<img width="1440" height="823" alt="Screenshot 2026-03-07 at 3 25 56 PM" src="https://github.com/user-attachments/assets/776dae89-2b27-47d7-8016-427d84726241" />
</p>
<p>
Roles define what permissions each agent has inside the system.  
For example, administrators can manage system settings while other agents may only view and respond to tickets.
</p>
<br />
