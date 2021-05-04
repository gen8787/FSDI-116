# Final Scrum for FSDI Project - MapApp

#### Polish and add to your previous Scrum structure of your project all the tests necessary for each one of your sprints.

## Contents
1. [Project Definition](#project-definition)
2. [Software Requirements](#software-requirements)
3. [Scrum Structure](#scrum-structure)
    1. [Product Backlog](#product-backlog)
    2. [Sprint Backlog](#sprint-backlog)

## Project Definition

### *MapApp is an app that lets a registered user plan how long an outing will take depending on what type of terrain they are in and what travel method they are using (e.g., uphill, downhill, walking, skiing).*

#### User Persona
Outdoorsy person of any age that wants to know how long a tour will take.

## Software Requirements

### User Stories

**As a user, I want to:**
- [ ] Create a user account
- [ ] View user accoount
- [ ] Update user account
- [ ] Delete user account  
  &nbsp;
- [ ] Login to the website
- [ ] Logout of the website
- [ ] Change my password
- [ ] Reset a password
- [ ] Reset username  
  &nbsp;
- [ ] Use the munter calculator to determine tour times
- [ ] Create a new tour
- [ ] Read all my tours
- [ ] Update tours
- [ ] Delete tours

## Scrum Structure

### Product Backlog

**As a user, I want to:**
- [ ] Create a user account
- [ ] View user accoount
- [ ] Update user account
- [ ] Delete user account  
&nbsp;
- [ ] Login to the website
- [ ] Logout of the website
- [ ] Change my password
- [ ] Reset a password
- [ ] Reset username  
&nbsp;
- [ ] Use the munter calculator to determine tour times
- [ ] Create a new tour
- [ ] Read all my tours
- [ ] Update tours
- [ ] Delete tours

### Duration of Sprints
As the project is fairly simple, there is a limited amount of time, and only one person working on the project, sprints will be kept short. I believe this will help by setting small and attainable goals, and also to get the feel for multiple sprints. I was thinking 2-4 day working sprints.

### Sprint Backlog

#### Sprint 1
- [ ] Initial Project Setup

#### Sprint 2
- [ ] Basic webpages setup

#### Sprint 3
- [ ] Databse and Models

#### Sprint 4
- [ ] Munter Calculation

#### Sprint 4
- [ ] CRUD Operations

## Test Cases

**As a user, I want to:**
- [ ] Create a user account
    - Must be able to create user in db
- [ ] View user accoount
    - Must be able to read newly created user from db
- [ ] Update user account
    - Must be able to update newly created user in db
- [ ] Delete user account
    - Must be able to delete newly created user from db  
&nbsp;
- [ ] Login to the website
    - Username & password correct = user login
    - Username and/or password incorrect = user can't login
- [ ] Logout of the website
    - User can't access any pages except the landing page
- [ ] Change my password
    - User able to change password in db
- [ ] Reset a password
    - User able to request a password reset
- [ ] Reset username
    - User able to request a forgotten username  
&nbsp;
- [ ] Use the munter calculator to determine tour times
    - The calculation must be accurate
- [ ] Create a new tour
    - Must be able to create a tour in the db with all information
- [ ] Read all my tours
    - Must be able to read newly created tour from db
- [ ] Update tours
    - Must be able to update newly created tour in db
- [ ] Delete tours
    - Must be able to delete newly created tour from db