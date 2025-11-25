
# [1] Active Directory Basics
While on this room, I assumed the role of the **new IT admin at THM Inc.**  As a first task, I have been asked to review the current domain **"THM.local"** and do some additional configurations. I have been given administrative credentials over a pre-configured Domain Controller (DC) to do the tasks.

To connect to it via RDP, the following credentials are valid:

**Username: THM\Administrator** 

**Password	Password321**

**IP (RDP):	<MACHINE_IP>**


## Task 1:
A brief explanation that gave me a broad understanding of Microsoft's Active Directory is and why it is important.

It :
- is the backbone of the corporate world. 
- is a directory service used by organizations to manage users, computers, permissions, and security settings in a centralized way.
- simplifies the management of devices and users within a corporate environment.

Think of it like the "brain" of an organization's IT environment.

It is used for:
- Allowing employees to log into computersEnforcing security policies
- Managing thousands of users easily
- Giving access to apps like Outlook, Teams, SharePoint
- Protecting network resources

```plain text
No answers needed.
```

---

## Task 2:
Indeed, for a corporate with many employees with each with a work computer, it would be difficult to manage each computer as a separate entity, manually configure policies for each of the users across the network and provide on-site support for everyone.

The computers and users are organized into a group called a **Windows domain** which is a group of users and computers under the administration of a given organisation. The administration of this group is centralised in a single repository known as an **Active Directory (AD)** and controlled by a server called a **Domain Controller (DC).**

The Domain Controller, a server running the Active Directory, handles, **Login authentication, Security checks** and **Updating of the AD database.**

#### Components on a Windows Domain
At the core of a windows Domain is the AD and the DC. Within the AD are the **Objects(Users and Groups), Organizational Units (OUs)** and **Group Policies (GPOs).**

![ADcomponents](Images/ADBasics/ADcomponent.png)

The main advantages of having a configured Windows domain:
- **Centralised identity management:** All users across the network can be configured from the AD with minimum effort.
- **Managing security policies:** You can configure security policies directly from the AD and apply them to users and computers across the network as needed.

```code
In a Windows domain, credentials are stored in a centralised repository called:
***Active Directory**

The server in charge of running the Active Directory services is called:
***Domain Controller***
```

---

## Task 3:

The **Active Directory Domain Service (AD DS)** is the core of any Windows Domain. It acts as a catalogue that stores information about network **objects** such as users, groups, machines, printers, and shared resources. These objects are known as **security principals,** meaning they can authenticate and access resources.

To manage AD objects, log in to the Domain Controller and open Active Directory Users and Computers from the Start menu of a Domain Controller.

![ADstartMenu](Images/ADBasics/ADstartMenu.png)


Organizational Units (OUs) are folders in AD used to organize objects and apply policies to sets of users or computers. OUs help structure departments; for example, the AD environment in this room includes a main THM OU with child OUs for IT, Management, Marketing, R&D, and Sales. Additional OUs, such as Students, can be created as needed. 

![ADObjects](Images/ADBasics/ADObjects.png)

If any OUs is opened, we see the users they contain and you can create, delete, modify objects, or reset user passwords.

![ITOU](Images/ADBasics/ITOU.png)
users within the IT OU.

Windows also creates default containers(parent OUs) such as:
- **Builtin** - default groups for any Windows host
- **Computers** - machines joining the domain by default
- **Domain Controllers** - contains the DCs
- **Users** - default users and groups
- **Managed Service Accounts** - service-related accounts

Groups simplify permission management by grouping users or machines.
- Security groups control access to resources and can contain users, machines, or even other groups.
- OUs apply policies, while groups grant permissions.

Common default security groups include:
 **Domain Users, Domain Admins, Server Operators, Backup Operators, Domain Computers,** and **Domain Controllers.**

---

## Task 4:

---

Task 5:

---

Task 6:

---
Task 7:

---

Task 8:

----
Task 9:

---



