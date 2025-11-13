# Faculty's website

## 1. Introduction

This project aims at creating a website for a faculty member at a College setting. A number of tools to help with the delivery of courses will be included such as: a tool to allow students and/or groups of students to pick meeting timeslots, a tool to present informations about current courses being delivered, and a calendar of lectures.

*October 26th, 2025*

*Current Version: 3.1*

*Project Manager (and sponsor): Marcel Jar*

## 2. Overview

Marcel is planning to develop his own website to facilitate the delivery of his classes at Seneca Polytechnic.

### 2.1 Objective

A website designed for a faculty delivering courses at College setting will be up and running prior to the beginning of the Winter term with tools for allowing students and groups to pick meeting timeslots, presenting course inforamtion, and displaying a calendar of lectures.

### 2.2 Work Breakdown Structure

![Work Breakdown Structure](images/WBS.png)


### 2.3 Requirements Traceabiliy Matrix

| **Req ID** | **Requirement Description**                                           | **Deliverable ID** | **Deliverable Description**                                 | **Owner** | **Status**        | **Date of Completion** |
| ---------- | --------------------------------------------------------------------- | ------------------ | ----------------------------------------------------------- | --------- | ----------------- | ---------------------- |
| R1         | The website must provide up-to-date course information.               | D1    | Course Info pages (Design, Front-End, Back-End integration) | Marcel     | ✅ Done            | 2025-10-15             |
| R2         | Users must be able to view an academic calendar with upcoming events. | D2    | Calendar module (Design, UI, and routes)                    | Marcel       | 🔄 In Progress    | —                      |
| R3         | Faculty must be able to upload and display lecture slides securely.   | D3    | Slide presentation interface and route                      | Marcel     | 🕒 Pending Review | —                      |
| R4         | Users must be able to reserve available timeslots for meetings.       | D4    | Timeslot scheduling tool (Design + Interactive UI + Routes) | Marcel    | ⏳ Planned         | —                      |
| R5         | System must be deployed in a VM, and accessible from a functional domain. Database must be also setu up in the VM, together with the server and CI/CD pipeline            | D5                | Database interfacing and ORM setup                          | Marcel     | ✅ Done            | 2025-09-28             |
| R5         | -                     | D6                | VM setup and configuration                                  | Marcel     | ✅ Done            | 2025-09-10             |
| R5         | -                | D7                | Domain acquisition and DNS setup                            | Marcel       | 🔄 In Progress    | —                      |
| R5         | -      | D9                | Continuous integration and deployment configuration         | Marcel    | ✅ Done            | 2025-10-20             |


### 2.4 Gantt Chart

![Gantt Chart](images/GANTT_Full.png)


## 3. Milestones

1. List of technological choices for front-end, back-end, database, and hosting/domain defined
2. Website back-end up and front-end designed and some static test pages tested in development environment
3. Tool for allowing students and groups to pick timeslots designed and tested
4. Tool for presenting course information designed and tested
5. Tool for displaying course calendars designed and tested


## 4. Deliverables

1. Website up and running from the server with no interactive tools
2. Tool for students and groups to pick timeslots accessible for students
3. Course information pages accessible for students
4. Course calendars is now accessible for students
