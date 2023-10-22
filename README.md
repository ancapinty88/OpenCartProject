# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

#### The final project will be split into 2 sections: [Testing section](https://github.com/ancapinty88/OpenCartPoject/edit/main/README.md#testing-section)
# Testing section
## 1. Introduction
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage the testing process for OpenCart.

#### 1.1 Project objective
Application under test: http://docs.opencart.com/en-gb/introduction/

The focus will be on: 

- **OpenCart - Catalog/Products** (Administration)

- **Shopping Cart Functionality** (Store Front)

- **Checkout Functionality** (Store Front).

Application documentation: 

- Administration:
http://docs.opencart.com/en-gb/catalog/product/

- Store Front:
http://docs.opencart.com/en-gb/store-front/


Tools: Jira, Zephyr squad 
#### 1.2 Functionalities in scope
All the features of Catalog - Products which were defined in business requirements need to be tested:
- Functional testing
- GUI testing
 

The below user stories were created in Jira and describes functional specifications of the Admin - Products and Product Category and Front Store - Shopping Cart Functionality and Checkout Functionality.


<img width="510" alt="Screenshot 2023-10-21 at 18 47 19" src="https://github.com/ancapinty88/OpenCartPoject/assets/132688930/9db9eeec-e428-456a-bd17-f3079c0bc7c5">



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
###### *Project risks* and *Product risks* : 

<img width="871" alt="Screenshot 2023-10-20 at 20 29 06" src="https://github.com/ancapinty88/OpenCartPoject/assets/132688930/edafb81b-58f5-4490-ae61-1f225097117f">


#### 2.2 Test analysis
- Analyze the business requirements to make sure that we have all the details to create the test conditions 
- Write test conditions that will be tested in out test process 

#### 2.3 Test design

- Functional test cases will be created in Jira 
- GUI test cases will be created in Jira 

#### 2.4 Test implementation
Verify if the following elements are ready before test execution:


- Test environment is up and running:

     *Administration*:  https://demo.opencart.com/admin/ 
     
     *Store Front*: Test enviroment is up and running: https://demo.opencart.com
     
- Access to test environment is given (Administration):

  username administration: demo

  password: demo

- Cycle summary was created 
- Test cases were added to the cycle summary  

#### 2.5 Test execution
- Test cases are executed on the created cycle summary 
- Bugs have been created based on the failed test cases 


#### 2.6 Test closure
All exit criteria were met as mentioned in the Test Planning section (2.1)
The traceability matrix was generated to demonstrate the business requirements coverage
Test execution chart was generated, the final report shows a number of 3 failed test cases of a total 34
There are still 3 opened defects but they have low priority

#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.

## 3. Test Deliverables
#### 3.1 Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 
#### 3.2 Test conditions
The following test conditions were created: 
 
![testCases](https://github.com/ancapinty88/OpenCartPoject/assets/132688930/43516c73-10a5-4530-9d9c-3a0c72dbf8a1)

#### 3.3 Test cases
The following test cases were created: 
![testCases](https://github.com/ancapinty88/OpenCartPoject/assets/132688930/8232966e-a63a-4a33-afae-9db526eddd6c)

#### 3.4 Daily test summary reports
The daily report was generated: 
<img width="1120" alt="dailyTest" src="https://github.com/ancapinty88/OpenCartPoject/assets/132688930/1269582e-7807-44f4-84fc-46df98f90701">

#### 3.5 Traceability matrix
Test execution chart was generated, the final report shows that a number of 3 tests have failed of a total of 34
A number of 34 test cases were planned for execution and all of them were executed
A number of 3 total bugs were found, from which the priority is: 2 are high and 1 is medium
The traceability matrix was generated: pdf
<img width="924" alt="Screenshot 2023-10-17 at 19 28 33" src="https://github.com/ancapinty88/OpenCartPoject/assets/132688930/b0b007b3-90ae-4475-859d-238b9f8659de">


#### 3.6 Test case results
The test cases results:
[Test cases results.pdf](https://github.com/ancapinty88/OpenCartPoject/files/13062917/Test.cases.results.pdf)

#### 3.7 Bugs report
The bug reports exported from Jira:
[BugsReport.pdf](https://github.com/ancapinty88/OpenCartPoject/files/13061241/BugsReport.pdf)

#### 3.8 Test completion report
The test completion report generated from Jira:
[TestCompletitionReport.pdf](https://github.com/ancapinty88/OpenCartPoject/files/13063029/TestCompletitionReport.pdf)

#### 3.9 Schedule
A test schedule includes the testing steps or tasks, the target start and end date and responsibilities.
| Task  | Date  | Team member | 
|---|---|---|
| Run functional test cases for Product submenu of Admin module| 15.06.2023 | Anca Pintilie |
| Run functional test cases for Product Category submenu of Admin module| 15.06.2023 | Anca Pintilie |
| Run functional test cases for Shopping Cart Functionality of Front Store module| 15.06.2023 | Anca Pintilie |
| Run functional test cases for Checkout Functionality submenu of Front Store module| 15.06.2023 | Anca Pintilie |
| Run GUI test cases for Product submenu of Admin module| 20.06.2023| Anca Pintilie |
| Run GUI test cases for Product Category submenu of Admin module| 20.06.2023| Anca Pintilie |
| Run GUI test cases for Shopping Cart Functionality of Front Store module| 20.06.2023| Anca Pintilie |
| Run GUI test cases for Checkout Functionality submenu of Front Store module| 20.06.2023| Anca Pintilie |
| Summary and Report | 20.10.2023 | Anca Pintilie |

