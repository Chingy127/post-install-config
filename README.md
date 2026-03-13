<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial continues from the previous lab where **osTicket was successfully installed and accessed through the browser**.

In this section, the help desk system will be configured so it can properly organize **tickets, users, agents, departments, and service level agreements (SLAs)**.  

These configurations allow the system to function like a **real IT help desk environment**, where support tickets are categorized, prioritized, and assigned to the correct teams.

---

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines / Compute)
- Remote Desktop
- Internet Information Services (IIS)
- osTicket Help Desk System

---

<h2>Operating Systems Used</h2>

- Windows 11 (Azure Virtual Machine)

---

<h2>Post-Install Configuration Objectives</h2>

During this section we will configure the following components of the help desk system:

- Help Topics (ticket categories)
- Service Level Agreements (SLA plans)
- Users (people submitting support requests)
- Agents (support staff handling tickets)
- Teams (groups of agents working together)
- Departments (organizational support groups)
- Roles (permissions for agents)

---

<h2>Configuration Steps</h2>

---

<h3>Step 1 – Configure Help Topics</h3>

<p>
<img width="1440" height="823" alt="Screenshot 2026-03-07 at 3 21 15 PM" src="https://github.com/user-attachments/assets/eccb57a9-2244-4172-a4ce-92b4c1dbae22" />
</p>

Help Topics are used to categorize incoming support tickets.

To configure help topics:

1. Log in to the **osTicket Admin Panel**
2. Navigate to **Admin Panel → Manage → Help Topics**
3. Click **Add New Help Topic**
4. Create topics such as:
   - Password Reset
   - Software Installation
   - Network Issues
   - Equipment Request

Help topics allow the help desk to **organize tickets based on the type of issue being reported**.

---

<h3>Step 2 – Configure Service Level Agreements (SLAs)</h3>

<p>
<img width="1440" height="819" alt="Screenshot 2026-03-07 at 3 21 51 PM" src="https://github.com/user-attachments/assets/f7799c78-45be-4438-b3f5-f4f4fd32c409" />
</p>

Service Level Agreements define **how quickly tickets must be resolved**.

To configure SLAs:

1. Navigate to **Admin Panel → Manage → SLA**
2. Click **Add New SLA Plan**
3. Create the following severity levels:

Sev-A  
Highest priority issues such as **system outages or security incidents**

Sev-B  
Moderate priority issues such as **software problems or user account issues**

Sev-C  
Low priority issues such as **general questions or minor requests**

SLAs ensure that **critical issues receive faster response times**.

---

<h3>Step 3 – Add Users to the Help Desk</h3>

<p>
<img width="1438" height="824" alt="Screenshot 2026-03-07 at 3 22 53 PM" src="https://github.com/user-attachments/assets/f2a8aa34-9a78-4c43-a12e-bef39616ec9c" />
</p>

Users are the people who submit support tickets to the help desk.

To add a user:

1. Navigate to **Agent Panel → Users → Add User**
2. Enter the user's information such as:
   - Name
   - Email address
3. Save the new user account.

These users represent **employees or customers requesting technical support**.

---

<h3>Step 4 – Create Support Agents</h3>

<p>
<img width="1440" height="818" alt="Screenshot 2026-03-07 at 3 23 57 PM" src="https://github.com/user-attachments/assets/2bf10f4a-b0e9-4fd5-8e41-536097e6b8dc" />
</p>

Agents are the **IT support staff responsible for resolving tickets**.

To create a new agent:

1. Navigate to **Admin Panel → Agents → Add New Agent**
2. Enter the agent's:
   - Name
   - Email
   - Username
3. Assign the agent to a department.

Agents will be able to **view, respond to, and resolve support tickets**.

---

<h3>Step 5 – Create Teams</h3>

<p>
<img width="1429" height="817" alt="Screenshot 2026-03-07 at 3 24 26 PM" src="https://github.com/user-attachments/assets/be4f87fd-2e0f-48e8-a1cf-0dc9028c0aae" />
</p>

Teams allow agents from **different departments to collaborate on tickets**.

To create a team:

1. Navigate to **Admin Panel → Agents → Teams**
2. Click **Add New Team**
3. Add agents who should collaborate together.

Teams are useful when **multiple specialists must work together to solve a problem**.

---

<h3>Step 6 – Configure Departments</h3>

<p>
<img width="1440" height="822" alt="Screenshot 2026-03-07 at 3 24 52 PM" src="https://github.com/user-attachments/assets/0d60241d-0b4a-4039-8197-052ccb157200" />
</p>

Departments organize the help desk into **separate support groups**.

To configure departments:

1. Navigate to **Admin Panel → Agents → Departments**
2. Click **Add New Department**
3. Create departments such as:
   - System Administration
   - Network Support
   - Help Desk

Tickets can then be **routed to the correct department automatically**.

---

<h3>Step 7 – Configure Agent Roles</h3>

<p>
<img width="1440" height="823" alt="Screenshot 2026-03-07 at 3 25 56 PM" src="https://github.com/user-attachments/assets/776dae89-2b27-47d7-8016-427d84726241" />
</p>

Roles define the **permissions each agent has inside the system**.

To configure roles:

1. Navigate to **Admin Panel → Agents → Roles**
2. Click **Add New Role**
3. Assign permissions based on responsibilities.

Examples:

Administrator  
Full system access including configuration settings.

Support Agent  
Can view, respond to, and resolve support tickets.

Roles ensure the help desk system maintains **proper access control and security**.

---

<h2>Lab Outcome</h2>

After completing these configuration steps, the osTicket help desk environment is now fully operational.

The system can now:

- Accept support tickets from users
- Assign tickets to agents and departments
- Prioritize tickets using SLA policies
- Organize issues using help topics
- Allow multiple teams to collaborate on support requests

This configuration simulates a **real-world IT support help desk environment** used in many organizations.
