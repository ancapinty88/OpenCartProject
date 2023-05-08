# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

#### The final project will be split into 2 sections: Testing section (Jira, Postman) and SQL Section (MySQL)

## 1. Introduction
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage the testing process for OpenCart.

#### 1.1 Project objective
Application under test: http://docs.opencart.com/en-gb/introduction/. The focus will be only on **OpenCart - Catalog/Products** 

Application documentation: 
http://docs.opencart.com/en-gb/catalog/product/

Tools: Jira, Postman, MySQL 
* If needed: The final project will be split into 2 sections: Testing section (Jira, Postman) and SQL Section (MySQL)

#### 1.2 Functionalities in scope
All the features of Catalog - Products which were defined in business requirements need to be tested:
- Functional testing
- GUI testing
- API testing 

The below user story was created in Jira and describes functional specifications of the Catalog - Products
*Screenshots din Jira cu user story-ul

#### 1.3 Functionalities and tests out of scope
- Non-functional testing like stress, performance, integrations of the dependents module with other modules, compatibility testing with multiple browsers is beyond scope of this project. 
- No QA support for mobile application developed. Only web application will be tested. 
- Automation testing is beyond scope.

## 2. Test Process
#### 2.1 Test planning
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.
##### Roles and responsibilities

| Rol  | Name  |
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
#### 2.5 Test execution
#### 2.6 Test closure
#### 2.7 Test monitoring and control


