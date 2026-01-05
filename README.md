<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Creating ticket as end user
- Assignment of ticket properties as Agent
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

<p>
Phase 1: Environment Setup
Start the Virtual Machine: Ensure your osTicket VM is running and log in via Remote Desktop using its IP address.
Access the Panels: Open two browser tabs: one for the Admin Panel (to manage configurations) and one for the Agent Panel (to manage tickets).

Admin/Analyst Login Page: http://localhost/osTicket/scp/login.php

End Users osTicket URL: http://localhost/osTicket
</p>
<br />

<p>
<img width="2259" height="302" alt="Screenshot 2026-01-04 172403" src="https://github.com/user-attachments/assets/4d0cc149-8537-4b42-b615-252572d85f56" />

</p>

<p>
<img width="455" height="274" alt="Screenshot 2026-01-04 172427" src="https://github.com/user-attachments/assets/d679c56c-0482-4b01-a386-dcab55ff536b" />

</p>

<p>
<img width="1109" height="767" alt="Screenshot 2026-01-04 170336" src="https://github.com/user-attachments/assets/3ca7f233-ff27-445a-b687-aae44a566b06" />

</p>

<p>
<img width="960" height="590" alt="Screenshot 2026-01-04 170621" src="https://github.com/user-attachments/assets/4b626a2a-8103-4628-b07a-e74ca661d695" />

</p>

<p>
Phase 2: Ticket Creation (End-User Role)
Submit Ticket as "Karen": Log in as the end-user Karen and create a new ticket.
Help Topic: Business Critical Outage / Report Problem.
Issue Summary: "Entire mobile/online banking system is down."
</p>
<br />

<p>
<img width="771" height="669" alt="Screenshot 2026-01-04 170754" src="https://github.com/user-attachments/assets/a19e57c2-1432-408f-8a0a-2dcbb0898382" />

</p>

<p>
<img width="656" height="661" alt="Screenshot 2026-01-04 170815" src="https://github.com/user-attachments/assets/5c5d1a69-f71f-47cb-9210-970edf580509" />


</p>

<p>
<img width="938" height="594" alt="Screenshot 2026-01-04 170825" src="https://github.com/user-attachments/assets/11aa0f17-fc70-424e-a4d5-9155150ca6fa" />

</p>
<p>
Phase 3: Ticket Triage (Help Desk Agent Role - "John")
Observe Properties: Log in as John to view the new ticket and inspect its default Priority, Department, and SLA.
Update & Assign: Modify the ticket properties to escalate the issue:
SLA Plan: Set to Sev-A (1 hour, 24/7).
Department: Set to Online Banking.
Assignment: Assign the ticket specifically to agent Jane.
</p>
<br />

<p>
<img width="785" height="596" alt="Screenshot 2026-01-04 170833" src="https://github.com/user-attachments/assets/9de08a86-756f-4939-9ff5-280b92c921cf" />

</p>

<p>
<img width="1017" height="444" alt="Screenshot 2026-01-04 170843" src="https://github.com/user-attachments/assets/63872616-2c10-4b73-b158-6e6852e64efb" />

</p>

<p>
<img width="731" height="661" alt="Screenshot 2026-01-04 170853" src="https://github.com/user-attachments/assets/a05cc13e-72cd-4028-a40f-ffeb082525ec" />

</p>

<p>
<img width="883" height="668" alt="Screenshot 2026-01-04 171030" src="https://github.com/user-attachments/assets/d15b78a0-9f24-4a40-9e8e-a256c95f3b2b" />

</p>

<p>
<img width="860" height="661" alt="Screenshot 2026-01-04 171041" src="https://github.com/user-attachments/assets/4dbcfb55-0668-4a99-b8fa-a4b7965f2ee1" />

</p>

<p>
<img width="906" height="659" alt="Screenshot 2026-01-04 171049" src="https://github.com/user-attachments/assets/78ef34be-bb63-4385-bd7f-fa48c118a801" />

</p>

<p>
<img width="982" height="662" alt="Screenshot 2026-01-04 171100" src="https://github.com/user-attachments/assets/38d31d33-9a55-4af5-ad67-afdfaec76bb5" />

</p>

<p>
<img width="1016" height="633" alt="Screenshot 2026-01-04 171108" src="https://github.com/user-attachments/assets/3213765a-cc6b-45b9-84af-a034a4bbb36a" />

</p>

<p>
<img width="1020" height="664" alt="Screenshot 2026-01-04 171117" src="https://github.com/user-attachments/assets/6867679b-6810-4ce2-9b4c-0b7b71531cf9" />

</p>

<p>
<img width="857" height="659" alt="Screenshot 2026-01-04 171148" src="https://github.com/user-attachments/assets/4d3f7a98-70b9-4a62-995e-bd3a30130159" />


</p>

<p>
<img width="963" height="665" alt="Screenshot 2026-01-04 171208" src="https://github.com/user-attachments/assets/1b382855-7003-42a1-805c-e0944cd71e3d" />

</p>

<p>
<img width="1031" height="648" alt="Screenshot 2026-01-04 171218" src="https://github.com/user-attachments/assets/d228eef9-e2aa-4d4c-8d59-b2b7825106d5" />

</p>

<p>
Phase 4: Ticket Resolution (Department Specialist Role - "Jane")
Work the Ticket: Log in as Jane to see the ticket now assigned to your department.
Provide Updates: Post a response or internal note to document the progress (this creates a trackable history of changes).
Resolve & Close: Change the ticket status from "Open" to "Resolved" or "Closed" to complete the workflow.

</p>
<br />

<p>
<img width="788" height="595" alt="Screenshot 2026-01-04 171229" src="https://github.com/user-attachments/assets/8e2fa7de-6d92-457f-8175-0bceb3075df7" />

</p>

<p>
<img width="1024" height="445" alt="Screenshot 2026-01-04 171238" src="https://github.com/user-attachments/assets/4bed96b7-51d8-4e60-89f4-c87f310f78a4" />

</p>

<p>
<img width="718" height="665" alt="Screenshot 2026-01-04 171247" src="https://github.com/user-attachments/assets/7a1ee020-23b3-405e-a3af-d82071c89cec" />

</p>

<p>
<img width="831" height="664" alt="Screenshot 2026-01-04 171255" src="https://github.com/user-attachments/assets/5f840470-5106-4fcf-be8e-5002ebfab748" />

</p>

<p>
<img width="789" height="665" alt="Screenshot 2026-01-04 171303" src="https://github.com/user-attachments/assets/15243361-81e8-47cb-82d1-14ef635bc136" />

</p>

<p>
<img width="1045" height="605" alt="Screenshot 2026-01-04 171313" src="https://github.com/user-attachments/assets/7bf20c0f-a992-4d51-945d-33881cb2d08f" />

</p>

<p>
When resolving incidents (tickets), effective communication is critical. This involves interfacing with internal teams and the affected end-users. Incidents with various issues are routed and assigned appropriately to designated personnel based on skill and scope.
Comprehensive documentation is essential for maintaining a stable operational environment. Proper documentation ensures that resolved incidents can be leveraged as a knowledge base or reference material for future, similar issues, facilitating efficient problem resolution and knowledge transfer.


</p>
<h3>Lessons Learned: </h3>
Ticket management processes vary by organization and are often guided by specific performance standards. These include meeting resolution targets within set timeframes and prioritizing urgent issues to minimize downtime. By installing and configuring an osTicket system from the ground up, I gained a practical understanding of how support tickets move through the IT lifecycle.

</p>
<br />









