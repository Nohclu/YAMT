# Yet Another Management Tool

## Index
- Overview
- Requirements

## Overview
YAMT (Yet Another Management Tool) is a task delegation tool for all types of projects with the key aim of automating task delegation based on the current members skill sets and availability. 
The overall goal of YAMT is to remove the tedious nature of micro-management and increase productivity through streamlining task assignment accordingly.

## Requirements
Users of YAMT should be able to do the following:
- A **User** can create an Account
- A **User** can create a **Project**
    - A **User** can set:
        - Project _duration_ (in days)
        - Base _skills_ required for **Project**
- A **User** can invite other users to a project
    - Email
    - TTL link
- When a **User** joins a **Project** they can:
    - Set _workdays_ per month
    - Select their _skills_ from Projects base skills
- Users can create one or many **Tasks** within a Project
    - Assign these tasks:
        -  _estimated duration_
        -  _estimated number users_
        - Required _skills_ to complete 
- Once a task is created it will find the "best suited" user and automatically assign them based on:
    - Tasks estimated duration vs Users time left
    - Tasks required skills vs Users skills
