# Manual-Testing-Project-IT-Factory
-------------
The objective of the final project for the ITF Manual Testing Course is to put into practice all the knowledge acquired throughout the course by utilizing a live application.

Application under test: https://demo.guru99.com/V4/index.php

Documentation : https://docs.google.com/document/d/1rPW5DV82VJT6vtA1VDSrfxaCBuAduxW0zb1yfTh_VMk/edit 

Tools used: JIRA, Zephyr Squad 

# Functional specifications

The following stories were generated in JIRA and outline the functional specifications of the Dependants modules, which serve as the focus for the final project.

[Create New Customer Story](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/blob/d1b1d2cf8b99ad63046770005718e7dd7d160781/Guru99%20Banking%20Project/Create%20New%20Customer%20Story.pdf)

[Edit Customer Story](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/blob/91eac541caeaa5499f4ed18cb7fc5da56185e403/Guru99%20Banking%20Project/Edit%20Customer%20Story.pdf)

[Delete Customer Story](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/blob/e1eaf9f386152d41d916fc62277f463b2c90b4ca/Guru99%20Banking%20Project/Delete%20Customer%20Story.pdf)

[New Account Story](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/blob/e1eaf9f386152d41d916fc62277f463b2c90b4ca/Guru99%20Banking%20Project/New%20Account%20Story.pdf)

[Edit Account Story](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/blob/e1eaf9f386152d41d916fc62277f463b2c90b4ca/Guru99%20Banking%20Project/Edit%20Account%20Story.pdf)

# 1 Testing section

## 1.1 Test Planning

The Test Plan has been formulated to provide a comprehensive description of all testing aspects related to the Dependants module within the Guru99 Bank application.

The plan encompasses the identification of test items, the features targeted for testing, the various types of testing to be executed, the designated person responsible for conducting the tests, the required resources and schedule for completing the testing process, and the potential risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

* Project manager - Gabriela Radu
* Product owner - Andrei Popescu
* Software developer - Mirela Toma
* QA Engineer - Adrian Birtas

#### 1.1.2 Entry criteria defined

 *  Functional specifications have been established, outlining the specific requirements and functionalities of the project.
 *  Roles necessary for the project have been assigned to respective team members, ensuring clear responsibilities and accountability.
 *  Initial project risks have been identified and appropriate measures have been taken to mitigate them, minimizing potential negative impacts on the project.

#### 1.1.3 Exit criteria defined

*   The number of unresolved bugs is minimal, and any remaining issues have either low priority or are insignificant in nature.
*   All planned tests have been successfully conducted, covering the necessary test scenarios.
*   All bugs that have been resolved have undergone re-testing and have been approved by the QA team, ensuring their proper resolution.
*   The project has met its established deadline, ensuring timely completion.
*   No significant risks remain unaddressed or unmitigated, reducing potential impacts on the project.
*   As part of the testing process, exploratory regression testing needs to be carried out specifically on the Manager section, including all modules.

#### 1.1.4 Test scope

* __Tests in scope:__ functional testing will be conducted to ensure that all the features defined in the software requirement specifications for the Dependents module are thoroughly tested. This includes validating the functionality of each feature to ensure they meet the specified requirements.
* __Tests not in scope:__ performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

#### 1.1.5 Risks detected

* Project risks: lack of experience of the QA and development team in the banking industry, short deadline of Zephyr Squad trial, unavailability of test environment
* Product risks: the need for increased security, bad marketing, to have better competitors, to delay the project.

#### 1.1.6 Evaluating entry criteria

The entry criteria established during the Test Planning phase have been successfully met, indicating that the necessary conditions and prerequisites for the test process to proceed have been fulfilled. As a result, the test process can continue as planned.

## 1.2 Test Monitoring and Control

In order to monitor and track the progress of the testing process, periodic reports have been generated. These reports provide an up-to-date overview of the current status of testing activities. In the event of major problems or issues arising during testing, these reports serve as valuable tools for assessing the situation and implementing appropriate control measures to address and resolve the issues promptly.

The following status report was generated

![Daily Test Execution Progress](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/assets/90641668/48b558c1-afb7-40ba-9704-d8c108d0ed50)

## 1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:
 * Enter data for all available fields and check that the dependant is created/updated/deleted
 * View dependant details and check they are correct
 * View all dependants in a list
 * Check all validation constraints for the fields

## 1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating some of the test cases 
was boundary value analysis, equivalence partitioning and use case testing.

**Test cases:**

![image](https://github.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/assets/90641668/b7ae200a-f576-41a9-ba26-f41e97738c2d)

The test cases with steps can be viewed here: [Test Cases](https://rawcdn.githack.com/BirtasAdrian/Manual-Testing-Project-IT-Factory/b4242b46ab1c784ce5af5294fbfaa29eef183fff/Guru99%20Banking%20Project/Test%20Cycle%20Summary/ZFJ-Cycles-07-04-2023.html)


## 1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: https://demo.guru99.com/V4/index.php
* Access to the testing environment is given: Username : mngr511485 | Password : AnerEvE
* Cycle summary was created 
* Test cases were added to the cycle summary

## 1.6 Test Execution

* Test cases are executed on the created test Cycle summary
*  Bugs have been created based on the failed tests
  
 
* Full regression testing is needed after the bugs are fixed

## 1.7 Test Completion

* As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
* The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/julai215/itf_final_project_example_and_portofolio/blob/main/Final%20Project/Traceability_matrix.xlsx)
* Test execution chart was generated, the final report shows that a number 5 tests have failed of a total of 23 
* A number of 23 test cases were planned for execution and all of them were executed
* A number of 5 total bugs were found, from which the priority is: 1 is high, 4 are medium and 1 is low


