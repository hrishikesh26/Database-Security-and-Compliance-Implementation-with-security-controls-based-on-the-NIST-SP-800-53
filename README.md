# Database-Security-and-Compliance-Implementation-with-security-controls-based-on-the-NIST-SP-800-53
This project implements database security controls for an e-commerce platform using MySQL, Python, and GnuPG. It covers database creation, security controls, data encryption, and project management1. The repository contains scripts, documents, and presentations related to the project.

### This project was in contribution with [@Ishan Prabhune](https://github.com/Ishan9100) and [@Harshal Sawant](https://github.com/harshalsawant29)

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Implementation Details](#implementation-details)
5. [Access Controls Implemented](#access-controls-implemented)
6. [Data Encryption](#data-encryption)
7. [Project Management Plan (PMP)](#project-management-plan-pmp)
8. [Project Schedule](#project-schedule)
9. [References](#references)

## Overview
The **Database Security and Compliance Implementation** project aims to design and implement a database system that complies with NIST Special Publication 800-53 regulations. This project serves as a learning opportunity to deepen understanding of database security, compliance, and efficient project administration. The implementation includes a comprehensive project management plan, robust data encryption techniques, and a MySQL database with stringent security measures. By incorporating NIST SP 800-53 measures, the project underscores the commitment to industry-standard security requirements.

## Features

This project includes the following features:

- **Account Management**: This feature ensures that only authorized users have access to the database. It includes user registration, login, and password reset functionality.

- **Separation of Duties**: This feature prevents any single user from having complete control over the database. It divides the responsibilities among different users to reduce the risk of fraud and errors.

- **Unsuccessful Logon Attempts**: This feature tracks the number of unsuccessful logon attempts and locks the account after a certain number of attempts to prevent brute force attacks.

- **System Use Notification**: This feature displays a system use notification to the user upon login. The notification informs the user that they are entering a secure area and that their activities are being monitored and recorded.

- **Security Training Records**: This feature keeps track of the security training that each user has completed. It helps to ensure that all users are aware of the security policies and procedures.

- **Time Stamps**: This feature adds a time stamp to each record in the database. It allows for accurate tracking of when each record was created or modified.

- **Plan of Action and Milestones (POAM)**: This feature provides a detailed plan of action and milestones for the implementation of the security controls. It helps to ensure that the project stays on track and meets its objectives.

## Technologies Used

This project uses the following technologies:

- **Python**: Python is used for the backend development of the project. It handles the business logic and interacts with the database.

- **MySQL**: MySQL is used as the database management system. It stores and retrieves the data for the project.

- **GnuPG**: GnuPG is used for data encryption. It encrypts the data at rest and in transit to protect it from unauthorized access.

- **Linux**: Linux is used as the operating system for the project. It provides a secure and stable environment for the project.


## Implementation Details
The database is designed with interconnectivity and smart design to enhance efficiency and functionality. It consists of seven essential tables, each serving a specific function critical to the E-Learning Platform. These tables are designed for flexibility and future expansion, with over a thousand entries to accurately depict database utilization.

## Access Controls Implemented
The project implements the following NIST SP 800-53 access controls:
- AC-02 Account Management | Privileged User Accounts
- AC-05 Separation of Duties
- AC-08 System Use Notification
- AC-07 Unsuccessful Logon Attempts | Automatic Account Lock
- AT-04 Security Training Records
- AU-08 Time Stamps
- CA-05 Plan of Action and Milestones | Automation Support for Accuracy and Currency

## Data Encryption
Robust encryption mechanisms are in place for both data at rest and in transit within the database. Industry-standard encryption algorithms such as GNUPG have been implemented to fortify data protection measures. All stored data is encrypted, safeguarding it from unauthorized access, even in the event of physical storage compromise. Schema modifications, query adjustments, and configurations were made to support and optimize encryption processes.

## Project Management Plan (PMP)
This project delivers a database with the implementation of NIST Risk Management Framework controls. With over a thousand entries and more than five users, the database comprises a minimum of seven tables. MySQL and SQL Workbench were used for database creation and control scheme implementation. The Project Management Plan was developed using Project Libre/Microsoft Project.

## Project Schedule
The Project Schedule serves as a detailed roadmap for the project, enabling effective coordination and progress monitoring.

## References
- NIST SP 800-53

## Visit the repository files to view the step by step implementation.
