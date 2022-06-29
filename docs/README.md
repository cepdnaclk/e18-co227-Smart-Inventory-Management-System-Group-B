---
layout: home
permalink: index.html

# Please update this with your repository name and title
repository-name: e18-co227-Smart-Inventory-Management-System-Group-B
title:
---

[comment]: # "This is the standard layout for the project, but you can clean this and use your own template"

# Smart Inventory Management System

---

![Sample Image](./images/cover_page.jpg)


## Team
-  E/18/147, JAMEEL S.  [e18147@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/242, NIMNADI J.A.S.  [e18242@eng.pdn.ac.lk](mailto:name@email.com)
-  E/18/379, WANDURAGALA T.D.B.  [e18379@eng.pdn.ac.lk](mailto:name@email.com)

## Table of Contents
1. [Introduction](#introduction)
2. [Other Sub Topics](#other-sub-topics)
3. [Solution Architecture](#solution-architecture)
4. [Links](#links)


## Introduction
---

#### About

Scheduling and maintaining assets are important in an engineering laboratory, of for that matter any laboratory. Keeping track of the usage of all the tools manually is not easy, nor efficient. Hence, we now see that there are many automated systems used in labs to assist activties. 

#### Problem

The most commonly used methods such as file systems, etc are hard to maintain and are often not continued. Therefore, in a lab, you loose track of the items available, and as a result they will not be maintained properly. 
Traditional laboratories also do not allow for resource scheduling. There are times when students come to the lab with the hope of using a particular machine or tool and find that it is being used by another person. This could happen to you everytime you go to the lab intending to use that instrument. It is never vacant.
Thus, we see that traditional laborities have no proper scheduling methods, that lead to the waste of time and resources.

##### Solution

In response to the problems identified, we introduce a smart inventory management system with resource scheduling and maintenance scheduling. This system maintains an inventory of all tools in the lab and allows students/ lecturers to view and make reservations online for a particular item.
Additionally, the system is designed to sen scheduled reminders to the technical officers in charge of the lab about maintanance tasks to be carried out. 


## Solution Architecture
---

The Web Applciation is hosted using a remote server. The web system can be accessed by all user groups. Upon login, the users can access relevant pages according to the defined control flow. Accordingly, Guests, regular users(students), admins/ maintainers will be directed to their relevant pages of the site.
Thereafter, the users will be able to use the system as per their requirements to make/ view reservations for a particular station in the laboratory. 

![Sample Image](./images/SolArchScheduling.png)

To assist technical officers, the system allows a maintainer/ admin of the web system to add relevant maintenance tasks for all the tools in the lab. These tasks will also be scheduled to be done on specific dates. As such, an automated reminder will be sent to the relevant technical officer about his/ her work that needs to be done on a given day.

![Sample Image](./images/SolArchMaintenance.png)

## Data Flow
---

![Sample Image](./images/dataflow.png)


## Other Sub Topics
---

#### The layout of the MakerSpace lab

![Sample Image](./images/lab_view.jpg)


#### A station in the lab

![Sample Image](./images/station.jpg)
 

## Links

- [Project Repository](https://github.com/cepdnaclk/{{ page.repository-name }}){:target="_blank"}
- [Project Page](https://cepdnaclk.github.io/{{ page.repository-name}}){:target="_blank"}
- [Department of Computer Engineering](http://www.ce.pdn.ac.lk/)
- [University of Peradeniya](https://eng.pdn.ac.lk/)


[//]: # (Please refer this to learn more about Markdown syntax)
[//]: # (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
