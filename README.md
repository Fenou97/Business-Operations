# Data Warehouse System

## Table of contents

- [Project Overview](#project-overview)
- [Tools](#tools)
- [Audiences](#audiences)
- [Business Process Modeling Notation ](#business-process-modeling-notation)
- [Data Flow Diagram ](#data-flow-diagram)
- [Use cases Diagram](#use-cases-diagram)
-  [Data Design](#data-design)
  

## Project Overview

Revival Financial Services, an alternative banking organization (Microfinance Institution), was developed from providing small loans, savings accounts, and other financial services (Money transfer operations) to low-income individuals or those without access to traditional banking. Customers can transact business by depositing and withdrawing cash through an agent who is the bridge between the customer and the company with a role of collecting customer data and responsible for addressing customer issues. During field visits, agents can also collect data, observe business operations and gather additional information about the borrower’s financial situation. The Overall existing information technology systems is outdated.  Customer data (names, money transfer operations, loan amount, interest rate, loan duration, grace period, etc.…) collected by agents from regions were poor, duplicate, inconsistent, causing misunderstanding and affecting customer trust. Most decision making is performed with instinct and not through data analysis since there is no reliable source of analytical data available. The company is attempting to build several data warehouses, by line of business to integrate and manage customer data.

## Tools
- Micorosoft Project
- Microsoft Visio

## Audiences
Two diverse audiences will be targeted for this system’s proposal. The stakeholder audience is composed of anyone affected by the company’s performance, such as customers and stockholders. The second audience will be the Users audience (Experts subject matters) composed of stakeholder inside or outside the company who will interact with the system.  

## Business Process Modeling Notation 
 Through this model, Revival Financial Services can capture, analyze, understand, automate, and even optimize their data warehouse processes. This starts by collecting data from various sources, structure it, combine it and store it in the data store. Once data is stored, users can retrieve it and perform data preparation tasks, helping them to make data ready for analysis, modeling, and report. The Figure below shows the logical model representing these processes.
 
![BPM](https://github.com/user-attachments/assets/ea8770ec-5135-46b6-9c7d-9bd28d92e45b)

                                   Figure 1: Business Process Model for Data Warehouse System

 ## Data Flow Diagram 

 This will map out the flow of information for any process or system. It will be used to show how the system stores, processes, and transforms data. In order to visually say things that would be hard to explain in words, Data Flow Diagram designed for Revival Financial Services data warehouse system will illustrate how data moves through the system, from initial input through processing to final storage and output.  In the Data Warehouse System, "Store Data", "Integrate Data and Load Data", "ETL", "Generate Reports" and "Analytics" processes are at the center and are surrounded by six entities: Core Banking system, Credit Bureau, Users, Customer Relationship, Accounting System and Data Warehouse System. Core Banking system, Credit Bureau, Users, Customer Relationship, Accounting System are the data sources and have only one outgoing data flow, while Users and Data Warehouse have one incoming and one outgoing data flow.
 
![Data Flow Diagram](https://github.com/user-attachments/assets/7f434f24-ff07-4c80-ae23-0cbb5de344a3)

                               Figure 2: Context Diagram DFD for Data Warehouse System

## Use cases Diagram
When designing the information system of the institution, it is prominent to make sure that the system deliverables are clear and easy to understand. This involves designing a Use Case Diagram. For the data warehouse system, there are several use cases: collect data, store data, integrate data, transform data, report, and analyze data. These use cases will be performed by different actors like loan officer, data analyst, system administrator. 

![Use case Diagram](https://github.com/user-attachments/assets/15cd416a-a97f-407f-96d0-149109886ee7)

                           Figure 3:Use Case Diagram for Data Warehouse System

## Data Design

During the fact-finding process, users have defined the different data that the Data Warehouse System of Revival Financial Services must store as inputs. Transactional Data, Operational Data, External Data are the core inputs that will support the functionality of the business information system. In alignment with these requirements (inputs), we have been able to design a physical model for Data Warehouse System that will provide a detailed schema that includes tables, attributes, data types, primary keys, foreign keys in order to ensure that everyone has a clear understanding of the database structure and its capabilities for data integrity and data quality. 
    
![Data Design](https://github.com/user-attachments/assets/dd927da2-3e5a-42c5-9444-7d9b903cc88d)

                         Figure 4:Data Design for Data Warehouse System

          

## Feasibility 

Once the Data Warehouse System is designed, Revival International Financial Services will have a centralized repository for data from various sources which will ensure consistent and accurate data management. It will also improve data quality by data cleansing and validation and support real-time data analytics, enabling timely insights into business operations, loan performance, customer behavior, and market trends. This will invlove using cloud-based infrastructure to ensure that the system can scale elastically with growing data volumes and user demands when business expands, implementing encryption, access controls, and compliance with data protection regulations to guarantee a secure environment for sensitive financial and customer data.

