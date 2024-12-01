
<p align="center">
  <img src="hstu_logo_ .jpg" alt="hstu" width="250" height="300">
</p>

<h3 align="center">
  Hajee Mohammad Danesh Science and Technology University,Dinajpur-5200.
</h3>
<h3 align="center">
Project Name: HSTU Library and TSC Seat Vacancy Tracking and Requisition System 
</h3>

<h3 align="center">
  Course Title: Software Engineering
</h3>

<h3 align="center">
  Course Code: CSE 305
</h3>
<br>
<h1 align="center">Submitted By</h1>

 <p align="center">Raisa Islam Fariha<br>Student ID: 2102018<br>Level: 3 Semester: I<br>Department of Computer Science and Engineering</p> 
 <br>

<h1 align="center">Submitted To</h1>

 <p align="center">Pankaj Bhowmik<br>Lecturer<br>Department of Computer Science and Engineering</p>


<br><br><br>
## Table of Contents
1. [Introduction](#introduction)
2. [Project Scope](#project-scope)
3. [Objectives](#objectives)
4. [Agile SDLC Approach](#agile-sdlc-approach)
5. [Design](#design)
6. [System Features and Functionalities](#system-features-and-functionalities)
7. [Technology Stack](#technology-stack)
8. [Development Process](#development-process)
9. [Testing](#testing)
10. [Challenges and Solutions](#challenges-and-solutions)
11. [Future Enhancements](#future-enhancements)
12. [Conclusion](#conclusion)

---

## 1. Introduction

The *HSTU Library and TSC Seat Vacancy Tracking and Requisition System* is an innovative solution developed to streamline the process of tracking seat availability and requisition in Hajee Mohammad Danesh Science and Technology University (HSTU). The system also integrates the management of library resources, allowing users to request seats and manage library book issuance effectively. The system aims to enhance user convenience and optimize seat allocation in the TSC (Teacher-Student Center) and the library.

This project was developed using the *Agile Software Development Life Cycle (SDLC)* methodology to ensure flexibility, continuous feedback, and iterative development. This report outlines the scope, objectives, features, and technical implementation of the system.

---

## 2. Project Scope

The system focuses on two main areas:
- *TSC Seat Vacancy Tracking:* The system will allow students and faculty to view available seats in the TSC and request a seat online.
- *Library Resource Management:* Users can check the availability of books, request them, and manage the return process.

The system will be used by students, faculty, and library administrators. The goal is to simplify seat allocation and improve the user experience at both the library and TSC.

---

## 3. Objectives

The main objectives of the system are:
- To enable real-time tracking of seat vacancies at the TSC.
- To allow students and faculty to book and manage seat reservations online.
- To enable library users to search, request, and manage library resources.
- To automate the seat requisition process and ensure smooth operation.

---

## 4. Agile SDLC Approach

The project was developed using *Agile SDLC*, which follows an iterative and incremental approach. The following Agile principles were adopted:
- *Iterative Development:* The system was built in multiple iterations (sprints), each focusing on delivering specific features or improvements.
- *Collaboration with Stakeholders:* Continuous feedback from stakeholders (students, faculty, and library staff) was incorporated during the development cycle.
- *Adaptability:* The system design was flexible enough to accommodate changes in requirements based on stakeholder feedback after each iteration.
- *Continuous Testing:* Testing was integrated into each sprint to ensure the functionality and quality of the system were up to standard.
  
![WhatsApp Image 2024-12-01 at 10 40 11_e3166c54](https://github.com/user-attachments/assets/b0ab6b61-4605-45e7-8713-df7a6b65016c)
*Agile Phases:*
1. *Sprint Planning:* Defining the sprint goals and backlog based on user stories.
2. *Design & Development:* The development team created the system incrementally.
3. *Review & Testing:* At the end of each sprint, the system was reviewed and tested for feedback and validation.
4. *Deployment:* After finalizing the system, the software was deployed for use by students and faculty.
5. *Sprint Retrospective:* After each sprint, the team discussed improvements and lessons learned to make the next sprint more efficient.

---
## 5. Design

![Raisa](https://github.com/user-attachments/assets/8a0926f8-086b-4056-939c-b44156f79dec)

## 6. System Features and Functionalities

The HSTU Library and TSC Seat Vacancy Tracking and Requisition System includes the following features:

### TSC Seat Vacancy Tracking:
- Real-time tracking of available seats in the TSC.
- Ability for students and faculty to reserve seats for specific time slots.
- Notifications for users when a reserved seat is available.

### Library Resource Management:
- Search functionality for books by title, author, or genre.
- Book issuance and return functionality.
- Management of overdue books and fines.
- Notifications for users when books are due for return or available for request.

### Admin Panel:
- Management of seat availability and requisition in the TSC.
- Monitoring of library resources (books, availability, reservations).
- Admin can manually override seat requisitions or book requests in case of emergencies or system issues.

---

## 7. Technology Stack

The following technologies were used in the development of the system:
- *Frontend:* 
  - HTML, CSS, Bootstrap for UI design
  - JavaScript (React.js) for dynamic content and interactivity
- *Backend:* 
  - Node.js for server-side development
  - Express.js for API management
- *Database:*
  - MySQL for managing library and seat data
- *Tools & Technologies:*
  - Git for version control
  - Visual Studio Code for development
  - Postman for API testing

---

## 8. Development Process

The development process followed the Agile methodology, with work divided into 3-week sprints. The major milestones of the project included:
- *Sprint 1:* Requirements gathering and system design.
- *Sprint 2:* Implementation of the TSC seat tracking and reservation system.
- *Sprint 3:* Development of the library management features.
- *Sprint 4:* Integration of both modules and testing.
- *Sprint 5:* Deployment and feedback collection.

Each sprint involved daily stand-up meetings, sprint reviews, and retrospectives to discuss progress, challenges, and improvements for the next sprint.

---

## 9. Testing

Testing was an integral part of the Agile approach, performed iteratively in each sprint. The testing process included:
- *Unit Testing:* Each feature was tested independently for correctness.
- *Integration Testing:* Ensuring that different parts of the system work together seamlessly.
- *User Acceptance Testing (UAT):* End-users (students, faculty, and library staff) tested the system to ensure it met their needs and expectations.
- *Load Testing:* Simulating high traffic to ensure the system could handle peak usage.

---
![Screenshot (14)](https://github.com/user-attachments/assets/17708d34-3ad1-4991-843f-7d842e9035ae)

## 10. Challenges and Solutions

### Challenges:
- *Real-time Seat Availability:* Synchronizing seat availability data across multiple users in real-time posed a challenge. The system had to ensure data consistency.
- *User Experience:* Creating an intuitive interface for users who may not be tech-savvy was another challenge.

### Solutions:
- *Real-time Updates:* Used WebSockets to provide real-time updates for seat availability.
- *User-Centric Design:* Conducted regular user feedback sessions to enhance the usability and design of the system.

---

## 11. Future Enhancements

- *Mobile App Development:* To enhance accessibility, a mobile app version of the system could be developed for easier access by students and faculty.
- *AI Integration:* Using AI algorithms to suggest optimal seat reservations based on user patterns or busy times.
- *Extended Reporting:* Adding more detailed reports for administrators, such as seat usage statistics and user behavior analysis.

---

## 12. Conclusion

The *HSTU Library and TSC Seat Vacancy Tracking and Requisition System* was successfully developed using the Agile SDLC methodology. The system allows students and faculty to track seat availability and manage library resources efficiently, enhancing the user experience and optimizing space utilization. The project demonstrates the power of Agile development to create flexible and adaptable software solutions.

By continuously collaborating with stakeholders, incorporating feedback, and testing throughout the development process, the team delivered a robust and user-friendly system that meets the needs of its users.
