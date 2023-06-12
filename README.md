# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

#### The final project will be split into 2 sections: [Testing section](https://github.com/ancapinty88/OpenCartPoject/edit/main/README.md#testing-section) and [SQL section](https://github.com/ancapinty88/OpenCartPoject/edit/main/README.md#sql-section-mysql)
# Testing section
## 1. Introduction
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage the testing process for OpenCart.

#### 1.1 Project objective
Application under test: http://docs.opencart.com/en-gb/introduction/

The focus will be on: 
**OpenCart - Catalog/Products** (Administration)
**Shopping Cart Functionality** (Store Front)
**Checkout Functionality** (Store Front).

Application documentation: 
Administration:
http://docs.opencart.com/en-gb/catalog/product/

Store front:
http://docs.opencart.com/en-gb/store-front/


Tools: Jira, Postman, MySQL 
#### 1.2 Functionalities in scope
All the features of Catalog - Products which were defined in business requirements need to be tested:
- Functional testing
- GUI testing
- API testing 

The below user story was created in Jira and describes functional specifications of the Catalog - Products. Screenshots din Jira cu user story-ul

#### 1.3 Functionalities and tests out of scope
- Non-functional testing like stress, performance, integrations of the dependents module with other modules, compatibility testing with multiple browsers is beyond scope of this project. 
- No QA support for mobile application developed. Only web application will be tested. 
- Automation testing is beyond scope.

## 2. Test Process
#### 2.1 Test planning
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
##### Roles and responsibilities

| Role  | Name  |
|---|---|
| Product Owner | Nicoleta Dumitrache |
| Software Developer | Gabriel Soare |
| Tester | Anca Pintilie |

##### Entry criteria:
- Business specifications are defined 
- Roles needed for the project are allocated 
- Initial project risks were detected and mitigated 
##### Exit criteria:
- All test cases have been executed 
- The unresolved bugs/defects have low priority 
- No detected major risks remained un-mitigated 
- All resolved bugs have been retested and approved by the testers
- Regression testing have been ran and no major bugs detected  
- All business requirements have been covered by test cases 
- All business requirements have been met 
##### Risks:
###### *Project risks* :
- Lack of experience of QA team
- Lack of tools, short deadline for Jira and Zephyr Squad
- Unavailability of OrangeHRM demo environment
###### *Product risks* : 
- Validation constraints on the fields might be too restrictive to the end user

#### 2.2 Test analysis
- Analyze the business requirements to make sure that we have all the details to create the test conditions 
- Write test conditions that will be tested in out test process 

#### 2.3 Test design
- Functional test cases will be created in Jira 
- GUI test cases will be created in Jira 
- API test case will be created in Postman 
- Queries in DB will be done in MySQL

#### 2.4 Test implementation
Verify if the following elements are ready before test execution:
- Test environment is up and running: https://demo.opencart.com/admin/ 
- Access to test environment is given:

  username administration: demo

  password: demo
- Cycle summary was created 
- Test cases were added to the cycle summary 
- Postman collection with the API methods was created 
- Authorization token was created accessing the API and it is valid 

#### 2.5 Test execution
- Test cases are executed on the created cycle summary 
- Bugs have been created based on the failed test cases. The complete bug reports can be found here: 
*se poate pune link catre un fisier cu bug reports in Github 
- API tests are executed based on the checklist (requirements)
- Full regression pack is executed after changes made to the application 

#### 2.6 Test closure
All exit criteria were met as mentioned in the Test Planning section (2.1)
The traceability matrix was generated to demonstrate the business requirements coverage
Test execution chart was generated, the final report shows a number of 3 failed test cases of a total 30
There are still 3 opened defects but they have low priority

#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

## 3. Test Deliverables
#### 3.1 Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 
#### 3.2 Test conditions
The following test conditions were created: 
-screenshot Jira 
#### 3.3 Test cases
The following test cases were created: 
-screenshot Jira 
#### 3.4 Daily test summary reports
The daily report was generated: 
-screenshot Jira
#### 3.5 Traceability matrix
The traceability matrix was generated: 
-screenshot Jira 
#### 3.6 Test case results
The test cases results:
-pdf exported from Jira with all test cases and results
#### 3.7 Bugs report
The bug reports exported from Jira:
-pdf exported from Jira with all bug reports
#### 3.8 Test completion report
The test completion report generated from Jira:
-screenshot with test completion report 
#### 3.9 Schedule
A test schedule includes the testing steps or tasks, the target start and end date and responsibilities.
| Task  | Date  | Team member | 
|---|---|---|
| Run functional test cases for Product submenu of Admin module| 10.05.2023 | Anca Pintilie |
| Run GUI test cases for Product submenu of Admin module| 20.06.2023| Anca Pintilie |
| Summary and Report | 08.05.2023 | Anca Pintilie |
# SQL section (MySQL)
