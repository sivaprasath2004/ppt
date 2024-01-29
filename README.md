---
marp: true
title: Announcement Annoncer
theme: uncover
style: |
  h1 {
    text-align: center;
    text-transform: uppercase;
    font-size: 1.25rem;
    margin-bottom: 1rem
  }
  p {
    font-size: .68rem;
    letter-spacing: 0;
    text-align: start;
    margin-bottom: .7rem;
  }
  section.lead h1 {
    text-align: center;
    font-size: 1.5rem;
  }
  section.lead p {
    text-align:center;
    font-size: .9rem;
  }
  section.ref p {
    font-size: .63rem;
    margin-bottom: .4rem;
  }
  section.ref a,section.moduleDec a {
    position: relative;
    font-weight: 500;
    color: black;
  }
  section.ref a:after , section.moduleDec a:after{
    content: '';
    text-decoration: underline;
    position: absolute;
    height: .7px;
    width: 100%;
    background: black;
    bottom: -6%;
    left: 0;
  }
  section.sys h2{
    font-size:.9rem;
    text-align:start;
  }
  section.module,section.sys{
    display:block;
  }
  section.moduleDec{
    display:block;
  }
  li {
    font-size: .7rem;
  }
---

<!-- _class: lead -->


<!-- https://) -->

# Announcement Annoncer

A specialized information sharing app crafted for EASC students!.

---

# Abstract
 - This application simplifies communication processes within educational institutions by facilitating the creation and distribution of messages to students.

 - It provides a user-friendly interface for crafting messages, selecting target email addresses, and seamlessly recording communications.

 -  The focus on efficiency and time management enhances the overall experience, ensuring a straightforward and easy process for both administrators and users.

 - By offering a centralized solution, the application optimizes communication workflows, contributing to a more effective and organized educational environment.
 
 - In essence, it transforms the complex task of managing school and college communications into a simplified and user-centric process.

---

# Introduction

- Welcome to our Announcement Announcer application, a dynamic platform designed to revolutionize the dissemination of information through seamless email communication.

- Tailored for efficiency and simplicity, our application serves as a specialized tool for sending announcements, ensuring that important messages reach their intended recipients with ease.

- With a user-friendly interface, users can effortlessly compose and send messages, delivering timely and relevant information to their audience.

- Our application prioritizes accessibility, allowing users to manage and send announcements conveniently from any device. 

- Experience the power of efficient message delivery, real-time updates, and a comprehensive toolset for effective announcement management.

---

# Existing System

- The current announcement system encounters delays in real-time communication and hinders attachment visibility.

-  Messages are not promptly sent, leading to communication lags, and attachments may not display properly.

-  In response, our application revolutionizes this process, ensuring instant announcement delivery and optimizing attachment visibility.

- Users benefit from enhanced efficiency and streamlined communication, mitigating the challenges of the current system. 

- Our platform represents a significant upgrade, providing a more effective and immediate approach to information sharing.
---

# Proposed System

- The Announcement Annoncer Android application with a Node.js server backend for efficient message delivery. 

- The React Native framework supports admin and super user modules, offering a versatile and user-friendly interface.

- Data storage is seamlessly handled by MongoDB and Firebase databases, ensuring robust file and information storage.

-  The Admin module guarantees security measures and specific information handling, enhancing overall data protection. 

-  This comprehensive system architecture promises a seamless and secure communication platform, blending advanced technologies to optimize information management and enhance user experience.

---

<!-- _class: sys -->
# SYSTEM REQUIREMENTS

## HARDWARE CONFIGURATION
- Processor  :AMD A4-4350B

- RAM : 4GB DDR4
## SOFTWARE SPECIFICATION

- **Operating system:** Android

- **Front-End:** React Native

- **Back-End:** Node js / Express js

- **Database:** Mongodb / Firebase

---

<!-- _class: ref -->

# References

- The primary resource for Announcement Annoncer user interface development is the official documentation for [React Native](https://), offering comprehensive guides and tutorials for building cross-platform mobile applications.

- For the logical foundation of Announcement Annoncer, the project relies on [React](https://) documentation, which provides in-depth insights into React's declarative and efficient JavaScript library for building user interfaces.

- Explore [Mongodb](https://) and [firebase](http://) an open-source and freemium backend service chosen for Announcement Annoncer, providing  database management and scalability.

- Announcement Annoncer streamlines development using [Expo](https://), which offers powerful tools and libraries for React Native app deployment, enhancing the overall development experience.

- [NPM](https://) serves as the package manager for Announcement Annoncer dependencies, facilitating the efficient installation and management of JavaScript packages.

---
<!-- _class: module -->
# MODULES
- **Admin**

- **Super User**
---
<!-- _class: moduleDec -->
# MODULES
- **Admin Module**
1. The Admin module in this application empowers administrators with the authority to control user actions, including sending, recording, and deleting messages.

2. The Admin's pivotal role extends to user management, encompassing the ability to remove users from the system for enhanced security measures

3. In addition to user control, the Admin module facilitates seamless management of receiver addresses, both in adding and controlling access to them

4. Robust security mechanisms are maintained as the Admin exercises authority over the removal of users, safeguarding the integrity of the application

5. The Admin module grants the administrator the pivotal capability to modify the database, ensuring adaptability and responsiveness to evolving requirements.
---
<!-- _class: moduleDec -->
- **Super User**
1. The Super User module plays a pivotal role in supporting message control within the application, offering advanced capabilities for seamless administration

2. With enhanced privileges, the Super User can not only control messages but also view the message content, ensuring comprehensive oversight of communication activities.

3. The Super User's authority extends to monitoring and managing the recipients, providing a detailed view of who can receive specific messages within the system.

4. Detailed visibility into the recipients allows the Super User to make informed decisions, contributing to a more targeted and streamlined communication strategy.
---
<!-- _class: moduleDec -->
# REFERENCES
- **Java Script** class , API , function , objects , JSON and Packages concept in [MDN Web Docs](https://developer.mozilla.org) Last published: Sep 2023.

- **React Native** Android and ios setup Tags, Native Component  concept in  [React Native Docs](https://reactnative.dev/docs/getting-started) Last published: Dec 2023.

- **Expo** Installation,TypeScript,SDK and Expo packages guide in [Expo Docs](https://docs.expo.dev/).

- **MongoDB** Database connection,Collection,Atlas and Cluster concept in [MongoDB Docs](https://www.mongodb.com/docs/) Last Published: Sep 2023.

- **Firebase** Storage , Key connection , Rules and file management  concept in [Firebase Docs](https://firebase.google.com/docs)  Last Published: Nov 2023.

- **Node js** Get and Post method,Request and Response handling,Handlebars,V8 JavaScript engine,ENV and Advance concept in [Nodejs Docs](https://nodejs.org/docs/latest/api/) Last Published: Jan 2024.
---
# THANK YOU..
