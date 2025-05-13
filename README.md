# osTicket Configuration and User Management

This project involves configuring the osTicket support system on a Windows 10 VM in Azure. The setup includes defining roles, departments, SLAs, and user access to create an organized and functional help desk.

## Technologies Utilized
- osTicket v1.15.8 (Support ticketing system)
- Windows 10 VM on Azure
- IIS, PHP, MySQL (Underlying stack)
-  RDP (For remote access)
  
## Accessing osTicket
Login as an adminastrator at [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php). End users access the system at [http://localhost/osTicket](http://localhost/osTicket).

![mstsc_gt6kH987fC](https://github.com/user-attachments/assets/3a1f1c1b-5f02-462a-8543-e97b1b626ae0)


## Roles
Under **Agents > Roles**, create roles such as *Supreme Admin* to define what permissions agents have in the system.

![mstsc_oFxe6pziQb](https://github.com/user-attachments/assets/0b4b7ca6-9e52-4250-92ee-ac1740b18c77)


## Departments
Go to **Agents > Departments** to organize agents by departments like *SysAdmins*, which control ticket visibility and routing.

![mstsc_aiKOTzG2Y7](https://github.com/user-attachments/assets/3973a431-5e29-4b21-98d4-17e90b48d73b)


## Teams
In **Agents > Teams**, create groups like *Online Banking* that pull agents from different departments to work collaboratively.


## User Settings
In **Settings > User Settings**, uncheck the option for unregistered users to create tickets, requiring users to register and log in first.

![mstsc_Te9vEY8rSp](https://github.com/user-attachments/assets/8ae924c0-25d2-4fe7-ae8a-fa3397cbc850)


## Agents
Add support staff under **Agents > Add New**, such as Jane (SysAdmins) and John (Support), assigning them to the appropriate departments.

![mstsc_kmxXWfEBmB](https://github.com/user-attachments/assets/64f6125e-4a26-4530-b914-e54f51c5f73c)


## Users
Create end-user accounts under **Users > Add New** in the Agent Panel to allow people like Karen and Ken to submit tickets.

![mstsc_VX6jPtUYHJ](https://github.com/user-attachments/assets/5651b278-6a47-4555-ad92-8fbd9a9e4d43)

## SLAs
Define response times in **Manage > SLA**, such as *Sev-A* (1 hour, 24/7), *Sev-B* (4 hours), and *Sev-C* (8 hours, business hours).

![mstsc_yiBzQchGDV](https://github.com/user-attachments/assets/3004cb14-85bf-4306-b1d7-71934501b516)

## Help Topics
Set up categories in **Manage > Help Topics** like *Password Reset* or *Business Critical Outage* to guide users when creating tickets.

![mstsc_Gdv0Dd1S6o](https://github.com/user-attachments/assets/eba404e3-0a0f-4e2d-879e-de5b41bba095)

![mstsc_0BfZ8H7wTp](https://github.com/user-attachments/assets/eb3d8b3b-282b-4aef-8ed0-aab62d819496)


