# Compromising-Active-Directory-TryHackMe-Module
While Learning how to exploit Windows Active Directory networks through core security issues stemming from misconfigurations, I have been taking the TryHackMe module: Compromising Active Directory. This Repository servers the purpose of Logging my progress in the six practice Rooms.

---

## 📂 Repository Contents:

  1. [Introduction](#introduction)
  2. [Active Directory Basics]()
  3. [Breaching Active Directory]()
  4. [Lateral Movement and Pivoting]()
  5. [Exploiting Active Directory]()
  6. [Persing Active Directory]()
  7. [Credential Harvesting]()
  8. [References](#-references)

---

## 🔥Introduction

For an enterprise with a number of users and computers in its network, it would be quite difficult to manage each computer as a separate entity, manually configure policies for each of the users across the network and provide on-site support for everyone. To overcome these limitations, enterprises use a Windows domain.

A **Windows Domain** is a group of users and computers under the administration of a given business/enterprise. It is a logical grouping of computers, users, and resources (like printers and servers) that share a common database and security policies. Its main purpose is to provide a centralized management of users and resources.

For instance, ***company.local*** could be a domain that includes all employee accounts, office PCs, and shared printers.

The core of any Windows Domain is the **Active Directory(AD) Domain Service,** or rather, we can say that the AD DS is the engine that powers Windows domains. It is a Directory Service developed by Microsoft that organises information about ‘objects’ (users, groups, computers, etc ) in a network. I.e, the AD keeps the catalogue/database of all users in ***company.local***, their passwords, group memberships and permissions.

So simply put, the **Active Directory (AD)** is a single repository that centralises the administration of common components of a Windows computer network, with the **Domain Controller (DC)** as the server that runs the Active Directory services (AD DS).

The main advantages of having a configured Windows domain in an Enterprise are:

- **Centralised identity management:** All users across the network can be configured from Active Directory with minimum effort.
- **Managing security policies:** You can configure security policies directly from Active Directory and apply them to users and computers across the network as needed.


Approximately 90% of the Global Fortune 1000 companies use Active Directory (AD).  Since AD is used for Identity and Access Management of the entire organisation, it is a critical componet in the organisations's infrastructure, making it a very likely target for attackers. This module will teach you the basics of AD and take you on the typical journey of compromising AD during a red team. You will learn to breach AD, enumerate AD, exploit AD, and finally deploy persistence through AD.

---

  ## References
