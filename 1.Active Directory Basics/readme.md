
# [1] Active Directory Basics
While on this room, I assumed the role of the **new IT admin at THM Inc.**  As a first task, I have been asked to review the current domain **"THM.local"** and do some additional configurations. I have been given administrative credentials over a pre-configured Domain Controller (DC) to do the tasks.

To connect to it via RDP, the following credentials are valid:

**Username	Administrator** >> use **THM\Administrator** as the username to specify you want to log in using the user Administrator on the THM domain.

**Password	Password321**

**IP (RDP)	MACHINE_IP**


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

#### Components on an Active Directory

![ADcomponents](Images/ADBasics/ADcomponent.png)

- **Users and Groups:** Where Users are individual accounts and Groups are a collection of users that helps in simplifying permissions.
- **Organizational Units (OUs):** These are Folders in AD used to organize users, computers, and policies.
- **Group Policy (GPO):** Rules that control what users and computers can do, such as: **Password requirements, Blocking USB devices, Installing software automatically** , etc.

```code
In a Windows domain, credentials are stored in a centralised repository called:
***Active Directory**

The server in charge of running the Active Directory services is called:
***Domain Controller***
```

---

## Task 3:

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


