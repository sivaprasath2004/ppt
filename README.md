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
  section.team h6 {
    text-align: start;
    margin-top: 1.6rem;
  }
  
  section.team li {
    font-size: .64rem;
    width: 17rem;
    letter-spacing: .05rem;
    margin-bottom: .1rem
  }
  section.team li strong {
    margin-right: .6rem;
    width: 6rem;
    display: inline-block;
  }
  section.mod li {
    font-size: .62rem
  }
  section.team h2{
    font-size:30px;
    margin-top:-30px;
  }
  section.team h3{
    text-align:start;
    font-size:1rem;
  }
  section.team,section.module{
    display:block;
  }
  section.team h4{
    text-align:start;
    font-size:30px
  }
  section.team h5{
    text-align:start;
    font-size:30px;
    margin-top:-20px;
  }
  section.lead h1 {
    text-align: start;
    font-size: 1.5rem;
  }
  section.lead p {
    text-align:start;
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
  section.spec {
   display: block;
   padding-top: 1.6rem
  }
  section.spec h6 {
    text-align: start;
    margin-top: 1rem;
  }
  section.spec li {
    font-size: .64rem;
    width: 16rem;
    letter-spacing: .05rem;
    margin-bottom: .1rem;
    margin-top:.5rem;
  }
  section.spec li strong {
    margin-right: .6rem;
    width: 5rem;
    display: inline-block;
  }
  section.module li{
    margin-top:1rem
  }
  section.moduleDec{
    display:block;
  }
  li {
    font-size: .7rem;
  }
---
<!-- _class: team -->
# ERODE ARTS AND SCIENCE COLLEGE
## AUTONOMOUS
###### Team Members

- **SIVAPRASATH R** B.Sc Computer Science
- **SURYA  S** B.Sc Computer Science

###### Guide

- **Mrs. DIVYA .M** ASSISTANT PROFESSOR <br> &nbsp;&nbsp; [ B.Sc CS ]
---
<!-- _class: lead -->
![bg brightness:1.1 left:30%](https://firebasestorage.googleapis.com/v0/b/annoncement-annocer.appspot.com/o/App_logo.png?alt=media&token=edeeeb25-d322-412b-814f-d94ec0b5c3a4)

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

<!-- _class: spec -->
# System Specifications
###### Hardware Specifications
- **Processor :** AMD A4-4350B
- **RAM :** 4GB DDR4
###### Software Specifications
- **Platform/OS :** Android 8+

- **Front-End :** React Native

- **Back-End:** Node js / Express js

- **Database:** Mongodb / Firebase


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
# THANK YOU!..
