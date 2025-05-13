# osTicket Configuration and User Management

This project involves configuring the osTicket support system on a Windows 10 VM in Azure. The setup includes defining roles, departments, SLAs, and user access to create an organized and functional help desk.

## Technology Utilized
- osTicket v1.15.8 (Support ticketing system)
- Windows 10 VM on Azure
- IIS, PHP, MySQL (Underlying stack)
-  RDP (For remote access)
  
## Accessing osTicket
Login as an adminastrator at [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php). End users access the system at [http://localhost/osTicket](http://localhost/osTicket).


## Roles
Under **Agents > Roles**, create roles such as *Supreme Admin* to define what permissions agents have in the system.


## Departments
Go to **Agents > Departments** to organize agents by departments like *SysAdmins*, which control ticket visibility and routing.


## Teams
In **Agents > Teams**, create groups like *Online Banking* that pull agents from different departments to work collaboratively.


## User Settings
In **Settings > User Settings**, uncheck the option for unregistered users to create tickets, requiring users to register and log in first.


## Agents
Add support staff under **Agents > Add New**, such as Jane (SysAdmins) and John (Support), assigning them to the appropriate departments.


## Users
Create end-user accounts under **Users > Add New** in the Agent Panel to allow people like Karen and Ken to submit tickets.


## SLAs
Define response times in **Manage > SLA**, such as *Sev-A* (1 hour, 24/7), *Sev-B* (4 hours), and *Sev-C* (8 hours, business hours).


## Help Topics
Set up categories in **Manage > Help Topics** like *Password Reset* or *Business Critical Outage* to guide users when creating tickets.

