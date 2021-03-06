MyCookieBook | Software Requirements Specification
======

- [1. Introduction](#1-introduction)
  * [1.1 Purpose](#11-purpose)
  * [1.2 Scope](#12-scope)
  * [1.3 Definitions, Acronyms and Abbreviations](#13-definitions--acronyms-and-abbreviations)
  * [1.4 References](#14-references)
  * [1.5 Overview](#15-overview)
- [2. Overall Description](#2-overall-description)
  * [2.1 Vision](#21-vision)
  * [2.2 Use Case Diagram](#22-use-case-diagram)
  * [2.3 Technology Stack](#23-technology-stack)
- [3. Specific Requirements](#3-specific-requirements)
  * [3.1 Functionality](#31-functionality)
    + [3.1.1 Functional Requirement One](#311-functional-requirement-one)
- [3.2 Usability](#32-usability)
  * [3.2.1 Usability Requirement One](#321-usability-requirement-one)
- [3.3 Reliability](#33-reliability)
  * [3.3.1 Reliability Requirement One](#331-reliability-requirement-one)
- [3.4 Perfomance](#34-perfomance)
  * [3.4.1 Performance Requirement One](#341-performance-requirement-one)
  * [3.5 Supportability](#35-supportability)
    + [3.5.1 Supportability Requirement One](#351-supportability-requirement-one)
  * [3.6 Design Constraints](#36-design-constraints)
    + [3.6.1 Design Constraint One](#361--design-constraint-one-)
  * [3.7 On-line User Documentation and Help System Requirements](#37-on-line-user-documentation-and-help-system-requirements)
  * [3.8 Purchased Components](#38-purchased-components)
  * [3.9 Interfaces](#39-interfaces)
    + [3.9.1 User Interfaces](#391-user-interfaces)
    + [3.9.2 Hardware Interfaces](#392-hardware-interfaces)
    + [3.9.3 Software Interfaces](#393-software-interfaces)
    + [3.9.4 Communications Interfaces](#394-communications-interfaces)
  * [3.10 Licensing Requirements](#310-licensing-requirements)
  * [3.11 Legal, Copyright, and Other Notices](#311-legal--copyright--and-other-notices)
  * [3.12 Applicable Standards](#312-applicable-standards)
- [4. Supporting Information](#4-supporting-information)

## 1. Introduction

### 1.1 Purpose
This Software Requirements Specification (SRS) gives a general overview over the MyCookieBook project. It explains our vision and includes detailed information about the features the project will contain.

### 1.2 Scope
The project MyCookieBook is a web-application. 
The web-application consists of the following features:
* Account system where users can create accounts to save and share their recipes 
* Friends list
* Create recipe
* Share recipe
* Edit recipe
* Delete recipe
* Bookmark favourite recipe
* Leave comments and likes (optional)
* Step by step instruction (optional)
* Send request to friends' recipe (optional)
* Share the whole CookieBook (optional)

### 1.3 Definitions, Acronyms and Abbreviations
| Abbrevation | Explanation                            |
| ----------- | -------------------------------------- |
| SRS         | Software Requirements Specification    |
| UC         | Use Case                             |
| UCD      | overall Use Case Diagram   |
| n/a         | not applicable                         |
| tbd         | to be determined                       |
| FAQ       | Frequently asked questions    |

### 1.4 References
| Title                                                                           | Date       | Publishing organization   |
| --------------------------------------------------------------------------------|:----------:| ------------------------- |
| [MyCookieBook Blog](https://mycookiebook.wordpress.com)                                                                    | 17.10.2020 | MyCookieBook Team                  |
| [Github](https://github.com/zhibekbastian/CookieBook)                                                                    | 17.10.2020 | MyCookieBook Team                  |

### 1.5 Overview
The following chapters give an overview of this project with our vision and Overall Use Case Diagram. It also contains information about the software requirements specification.

## 2. Overall Description

### 2.1 Vision
Our idea is to develop a web-application that allows user to create and save recipes where they are always accessible. In addition it is possible to share your favourite recipes with your family and friends which simplifies spreading the recipes. 
Our web-application will be developed with java in the backend 

### 2.2 Use Case Diagram
The following link includes our Use Case Diagram: [OUCD](https://drive.google.com/drive/folders/1PwEWLw7x1sG2xNPuH_lOGjHWSNv4g3hT?usp=sharing)


* Yellow: Planned until the end of december
* Purple: Planned until the end of june
* Gray: Additional features

### 2.3 Technology Stack

Technologies we are going to use:

Backend: Java

Frontend: Angular, CSS, HTML, Java, SpringBoot

Database: MySQL

Testing: JUnit, Mockito

IDE: IntelliJ, Eclipse

Project Management: YouTrack, Github

## 3. Specific Requirements

### 3.1 Functionality - Web Application
### 3.1.1 User account
We need an account system to give the users access for creating, sharing and commenting recipes. 
### 3.1.2 Create a recipe
The user has the opportunity to add a recipe with step by step instruction including the ingredients and other descriptions (name of recipe, author, difficulty level and category).
### 3.1.3 Share a recipe
The user has the option to share recipes with selected friends and family members. If the user shares his recipe with someone, receiving user gets the shared recipe in his own CookieBook.
### 3.1.4 Edit recipe
It is also possible to edit an existing recipe.
### 3.1.5 Delete recipe
The user can delete an existing recipe.
### 3.1.6 Bookmark favourite recipe
The user can bookmark his favourite recipe to have faster access.
### 3.1.7 Leave comments and likes (optional)
The user is able to comment and like shared recipes.
### 3.1.9 Special view of step by step instruction (optional)
This feature makes it easier for the user to follow the recipe.
### 3.1.10 Send requests to friends' recipe (optional)
The user can send requests to friends' recipe.
### 3.1.11 Share the whole CookieBook (optional)
It could be possible to share all recipes from the CookieBook with the selected user.

## 3.2 Usability
### 3.2.1 Intuitive user guidance
We want to develop an intuitive web-application which is as easy as possible to use and gives the user the opportunity to save recipes in his own Cookiebook in order to have recipes at one place instead of having a lot of notes somewhere at home.
### 3.2.2 FAQ
We will implement a FAQ to help the user on using the web-application. 
### 3.2.3. Smartphonefriendly (optional)
The web-application should be smartphonefriendly.

## 3.3 Reliability
### 3.3.1 Server availability
The website servers will always be online so the the users have always access to their CookieBook. 
### 3.3.2 Data privacy
The data of the user is visible only for him.

## 3.4 Perfomance
### 3.4.1 Response time
The response time should be as low as possible. 
### 3.4.2 Server availability
The server should always be online to provide access to data.
### 3.4.3 Memory
(tbd)
### 3.5 Supportability
(tbd)
### 3.6 Design Constraints
(tbd)
### 3.7 On-line User Documentation and Help System Requirements
We are going to focus on building an intuitive modern-looking web-application to allow users to use our website without problems. We will also implement an "FAQ" that contains instructions on how to use the application, features and leave our contacts for possible questions. 
### 3.8 Purchased Components
(tbd)
### 3.9 Interfaces
(tbd)
#### 3.9.2 Hardware Interfaces
(tbd)
#### 3.9.3 Software Interfaces
MyCookieBook is a web-application, so it should run in any browser. We will test our web-application on Safari, Chrome, FireFox, Microsoft Edge.
#### 3.9.4 Communications Interfaces
(tbd)
### 3.10 Licensing Requirements
(tbd)
### 3.11 Legal, Copyright, and Other Notices
(tbd)
### 3.12 Applicable Standards
(tbd)
## 4. Supporting Information
(tbd)
