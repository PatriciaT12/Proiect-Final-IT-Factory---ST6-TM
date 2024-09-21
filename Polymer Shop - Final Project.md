<h1>Testing Project for Polymer Shop</h1>

The primary objective of this testing plan project is to outline the strategies, scope, schedule, and approach for testing the Polymer Shop application. The goal is to ensure that all functionalities are working as expected and to identify potential bugs or performance issues.

Application under test: [Polymer Shop](https://shop.polymer-project.org/)

Tools used: Jira, Zephyr Squad.

<h1> Table of Content:</h1>

1. Introduction
* Project Objective
* Functionalities in Scope
2. Test Process
* Test Planning
* Roles and Responsibilities
* Entry Criteria
* Exit Criteria
* Risks
* Test Analysis
* Test Design
* Test Implementation
* Test Execution
* Test Closure
* Test Monitoring and Control
3. Test Deliverables
* Test Conditions
* Test Cases
* Daily Test Summary Reports
* Traceability Matrix
* Test Case Results
* Bugs Report
* Test Completion Report
* Schedule
4. Conclusion
   
<h2>Functional specifications:</h2>

The stories below were created in Jira and describe the functional specifications of the "SHOP" module, for which the final project is performed.

![Story 1](https://github.com/user-attachments/assets/ae0c31b8-36c9-47e9-b4c2-aacb42aa3da6)

![Story 2](https://github.com/user-attachments/assets/8d46b744-885f-4004-bccd-b36daa73f049)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here:

[Polymer Shop Testing Plan.pdf](https://github.com/user-attachments/files/17084490/Polymer.Shop.Testing.Plan.pdf)

<h4>1.1.1. Roles assigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: Abigail Sing</li> 
  <li>Product owner: IBM</li>
  <li>Software developer: Daniel Pearson</li>
  <li>QA Engineer: Patricia Tulai</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

* The development team has completed coding and unit testing.
* All test data is prepared and available.
* All necessary test environments are set up.

<h4> 1.1.3 Exit criteria defined </h4>

* All critical and major bugs are resolved.
* 98% of test cases are passed.
* No high-severity defects remain unresolved.

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

**1. Product Catalog**

* Viewing products in various categories (e.g., Men’s Outwear, Ladies Outwear).
* Filtering and sorting products by price, name, or popularity.

**2. Product Details Page**

* Viewing product descriptions, prices, and available sizes/colours.
* Selecting product quantity.

**3. Cart Management**
* Adding a product to the cart.
* Modifying product quantity in the cart.
* Removing products from the cart.
* Viewing cart summary (total price, product details).

**4. Checkout**

* Entering shipping and billing information
* Payment gateway integration (if applicable).
* Confirming orders.

**5. Navigation**

* Navigating between different pages (e.g., home, product pages, cart).
* Testing for broken links or buttons that don’t function correctly.

<h5>Tests not in scope: </h5>

* Backend database optimizations and server-side performance tuning.
* Third-party API performance (if any).
* Security Testing
* Performance Testing

<h4>1.1.5 Risks detected</h4>

**<h5>Project risks:</h5>**

**Risk 1: Incomplete execution of planned tests**

* Description: Of the 10 tests written, only 3 have been run to date, indicating a potential delay in testing completion.

* Impact: High - If tests remain unrun, there is a risk that other critical bugs will not be identified before release.

* Probability: Medium

* Priority: High

* Mitigation: Allocating additional testing resources and setting clear deadlines for the execution of the remaining tests.

**Risk 2: Insufficient resources for testing**

* Description: The low number of tests run suggests that the test team may be undersized or that there are issues with time and resource management.

* Impact: High - Insufficient resources can lead to inadequate testing coverage, which increases the likelihood of releasing a defective product.

* Probability: Medium

* Priority: High

* Mitigation: Reviewing resource planning, ensuring that the test team has sufficient staff and time allocated to complete all required tests.

**<h5> Product risks: </h5>**

**Risk 1: Severity A bugs**

* Description: The two bugs identified with severity A may affect the critical functionality of the application, having a major impact on end users.

* Impact: Very High - Severity A bugs can result in data loss, and users' inability to perform transactions or access critical functionality.

* Likelihood: Medium - Given that bugs have already been identified, there is a chance that other critical issues are still present.

* Priority: Very High

* Mitigation: Immediate remediation of A-severity bugs and re-executing tests to verify application stability after remediation.

**Risk 2: Negative impact on user experience**

* Description: Critical bugs directly affect the user experience, which can lead to dissatisfaction, loss of customers and damage to the app's reputation.

* Impact: Very High - A broken or unstable product can negatively affect user loyalty and the commercial success of the application.

* Probability: Medium

* Priority: Very High

* Mitigation: Focusing on quickly identifying all major functionality issues and correcting them prior to official release.

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control for Polymer Shop Project</h3>
  
The testing process for the Polymer Shop Project will be closely monitored through periodic reports that provide an overview of the current status and progress of testing activities. Key aspects of test monitoring and control will include:

•	**Progress Updates**: Regular reports will be shared with the QA team, developers, and other stakeholders, highlighting the overall progress of the testing phase. This will ensure that everyone is aware of the current state of testing.

•	**Test Results Communication**: Achieved test results, including test case execution status and defect reports, will be communicated to all relevant parties. This will help stakeholders understand the performance and quality of the system.

•	**Tracking Key Metrics**: Relevant testing metrics such as pass/fail rates, defect density, test coverage, and execution timelines will be continuously monitored. These metrics will guide decision-making and future planning.

•	**Test Case Development and Review**: All test cases will be documented, reviewed, and approved by the QA team. This ensures alignment with project requirements and that critical scenarios are thoroughly tested.

•	**Planning and Adjustments**: Based on the metrics and progress being tracked, adjustments to the testing strategy will be made. This may involve reallocating resources, adjusting timelines, or reordering priorities.

•	**Prioritization of Testing Efforts**: Testing priorities may be reevaluated to focus on high-risk areas, based on insights from test results and issues identified so far.

•	**Test Schedule and Deadlines**: If necessary, test schedules and deadlines will be reorganized to accommodate changes in project requirements or testing priorities, ensuring critical features are tested within the available time.

•	**Environment Restructuring**: The test environment may be modified to address any issues or bottlenecks encountered, ensuring that it reflects the real-world conditions where the application will be deployed.

•	**Reprioritization of Test Cases and Conditions**: Based on ongoing assessments, test cases and conditions will be reprioritized to ensure that the most critical functionalities are tested first, with less critical tests scheduled as resources allow.

Through this process of monitoring and control, the Polymer Shop Project will remain agile and responsive, ensuring that testing efforts are directed where they are most needed and that the overall quality of the application is maintained.

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>

The following test conditions were found: <br>

![Test Conditions](https://github.com/user-attachments/assets/994db4eb-a5f4-4ae9-853b-2dcf72c3ba4e)

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here 

![Test Case 1](https://github.com/user-attachments/assets/e9ad3b37-506d-40c6-951d-44b6df24de35)

![Test Case 2](https://github.com/user-attachments/assets/70f42e48-8bfe-48eb-a67c-157e15937726)

![Test Case 3](https://github.com/user-attachments/assets/1264056f-4988-4fcf-9590-a5ec9f37e3cc)


<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**•	Test Cases:**
o	All test cases must be fully documented, reviewed, and approved.

o	Both manual and automated test cases should be clearly outlined to cover all functionalities such as user authentication, cart management, and checkout process.

**•	Test Data:**
o	Accurate and comprehensive test data needs to be created to simulate real-world scenarios.

o	This includes multiple user profiles, different product types (e.g., Men's and Women's Outwear), and various payment methods.

**•	Test Environment:**
o	The test environment should be set up to mirror the production environment as closely as possible.

o	All necessary components such as servers, databases, and third-party integrations must be configured correctly.

**•	Test Tools:**
o	All testing tools (e.g., JIRA with Zephyr Squad for test case management) should be installed, integrated, and verified.

**•	Test Resources:**

o	The testing team must be briefed on their roles and responsibilities.

o	Adequate resources and personnel should be allocated for test execution, defect reporting, and re-testing.

**•	Test Environment Accessibility:**

o	Ensure the environment is accessible to all testers and stakeholders, with proper permissions and access to tools and infrastructure.

**•	Test Schedule:**

o	A finalized test schedule should be in place, outlining the timeline for test execution, regression testing, and final reviews.

Once these elements are in place, the Test Execution phase can proceed, ensuring comprehensive coverage of the Polymer Shop functionalities and a robust validation process.

<h3> 1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: 

![Bug Report 1](https://github.com/user-attachments/assets/38cb55b4-a9e9-482b-803b-696ebbddf93e)

![Bug Report 2](https://github.com/user-attachments/assets/d7f3db85-4828-47e3-948d-2acb190df9c6)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![Traceability Matrix](https://github.com/user-attachments/assets/d7c0e3e9-d610-4fec-b00d-d2730e739c8f)

Test execution chart was generated and can be found below. 

![Raport de executie](https://github.com/user-attachments/assets/114137c8-4476-4d37-9d18-712f516bc46e)

The final report shows that a number of 2 tests failed, of which there were a total of 3.

A number of 2 total bugs were found, from which the priority is high.

**<h2> Conclusion </h2>**

The "Polymer Shop" application testing project was successfully carried out, using JIRA and the Zephyr plugin to organize and track testing activities.

Within this project, 3 stories were created and planned, all covered by tests, which shows a good alignment between development requirements and testing activities.
10 tests were written to cover these stories, but only 3 of them have been executed so far.

Following the execution of the tests, 2 major bugs were identified, classified with severity A, which indicate critical issues that can significantly affect end users. Severity A suggests that these bugs affect the core functionality of the application, which can lead to a severely compromised user experience.

These issues should be addressed with the highest priority, because if left unresolved, they can lead to the inability to access certain critical features of the application.

In conclusion, although the test coverage is promising and all stories are covered, the limited test execution and critical bugs identified show that the project needs further attention to ensure the delivery of a stable and reliable application. It is essential that the development team prioritizes the resolution of identified bugs to minimize the impact on end users and improve the overall quality of the application before release.
