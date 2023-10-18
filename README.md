# Discover-Athlete: An Athlete Management System
This is the capstone project for the course EECE 5200: Database Management Systems. Raksha Ramkumar and Akanksha Agnihotri worked on this project. The main agenda of this project is to leverage the mySQL server to create and manage a database of athletes.
This helped us to apply the various concepts of non-relational database we learnt in the course. This product also derives key insights contributing to the performance and the net worth of a particular athlete, to help the recruiters and scouts 
make well-informed decisions about each athlete, backed by data.

## Introduction
The proposed Discover-Athlete: An Athlete Management System is a database management system that stores and 
manages important details of different athletes/players across various team sports. The main aim of this database 
management project is to provide an easy platform for the recruiters and scouts to access crucial information about the 
athletes and to discover new and upcoming talent. They are also allowed to modify/delete certain aspects of the data. 

The Discover-Athlete database contains information on certain athletes across 5 Sports and 3 teams in each Sport. All 
these sports are team sports i.e., they cannot be played individually. The entire database is managed using MySQL 
workbench. MySQL is a relational database and offers the **Consistency** and **Availability** properties of the CAP theorem. 
All the tables formed here are in the third normalization form.  

## Tools 
mySQL Server, Workbench, pymysql, Python

## Conceptual Design
The Entity-Relationship Diagram (ERD) describes the conceptual design of a database. The following is the ERD for this project:
Overall, we have 7 tables/entities named as athlete, team, sports, manager, coach, diet, 
brand_end representing the information required to create this database. 

![image](https://github.com/RakshaRamkumar/Discover-Athlete/assets/63054940/1453d644-7093-42f7-8361-aad9206e22c2)

## User Flow
The flowchart below describes the user interaction with the database and what operations are supported by the 
database:

![image](https://github.com/RakshaRamkumar/Discover-Athlete/assets/63054940/8e291fd9-9abc-4b9c-9fb4-fd2eb5fe9db3)

## Application Demonstration Instructions
This section describes in detail the steps to be performed to run the application on any system. 
1. Install Required Libraries 
    - Install pymysql which is required to connect to mysql server. (pip install pymysql) (We used pip as the package 
manager for Python; Please use appropriate package managers) 
    - Install matplotlib which is required for visualization. (pip install matplotlib)

2. Run the python application 
    - Run the application by typing the command: `python project_main.py`
  Note: We ran using python3.8. Select 
options as per the menu and see the results!

## Lessons Learned
We understood the basic structure of connecting the database system with the application that is accessible to the user 
in real-time scenario. We learnt the importance of the following concepts: 

- Connection between Python and MySQL workbench using the right connection and cursor calls. 
- Creation of the entity tables as per the logical design and addition of corresponding tuples. 
- Creation of appropriate procedures and functions in SQL to handle the various operations. Usage of these 
procedures from the application.  
- Importance of Integrity constraints and how it affects the database operations 
- Error handling and input validation at every stage of CRUD operation. 
- Taking Recovery backup of the database before performing any CRUD operations.  
- Key visualizations of the data using matplotlib library to gain insight into the database.


