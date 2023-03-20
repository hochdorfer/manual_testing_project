<h2>Final project for ITF Manual Testing Course</h2>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login

API Documentation: https://airportgap.dev-tester.com/docs

The final project will be split into 2 sections: Testing section and SQL section.

Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench.

<h2>Functional specifications</h2>

The below Stories were created in JIRA and describe the functional specifications of the Customer Login and Bank Manager Login module, for which the final project is performed upon.

<figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Story_XBNB%203.jpg"
         alt="Story_3">
    <figcaption>Bank Application - User Actions</figcaption>
</figure>

<h2>1 Testing section</h2>
<h4>1.1 Test Planning</h4>
The Test Plan is designed to describe all details of testing for the XYZ Bank application.
The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

<h4>1.1.1 Roles assigned to the project and persons allocated</h4>
<p>Project manager - Hochdorfer Nora<br>
Product owner - Hochdorfer Nora<br>
Software developer - Hochdorfer Nora<br>
QA Engineer - Hochdorfer Nora<br>

<h4>1.1.2 Entry criteria defined</h4>
<p>- functional specifications are defined<br>
- roles needed for the project are allocated<br>
- initial project risks were detected and mitigated<br>

<h4>1.1.3 Exit criteria defined</h4>
<p>- number of unresolved bugs is insignificant or they have low priority<br>
- all tests have been executed<br>
- all resolved bugs have been re-tested and approved by the QA team<br>
- deadline is respected<br>
- exploratory regression testing must be performed on the whole XYZ Bank Application, both Customer Login and Bank Manager Login<br>

<h4>1.1.4 Test scope</h4>
Tests in scope: All the features of Customer Login and Bank Manager Login modules which were defined in software requirement specifications need to be tested: exploratory testing, functional testing, GUI testing and API testing, as soon as documentation is available for all of them.
Tests not in scope: performance testing, compatibility testing with multiple browsers and  mobile devices.

<h4>1.1.5 Risks detected</h4>
<p>Project risks: <br>
- Lack of experience of the QA team<br>
- Short deadline of Zephyr Squad trial<br>
- Data vulnerability<br>
- Malware risks<br>
- Poor app security<br>
- Unsecured Wi-Fi and data networks<br>
  
<h4>Product risks:</h4>
Validation constraints on the fields might be too easy to the end-user<br>
Insufficient staff

<h4>1.1.6 Evaluating entry criteria</h4>
<p>The entry criterias defined in the Test Planning phase have been partially achieved and the test process can continue.</p>

<h2>1.2 Test Monitoring and Control</h2>
<p>Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 36.36% of the test cases were executed, on 12th of March 2023:<br>
  
  <figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Cycle%20Summary%207%20in%20progress.jpg"
         alt="Cycle Summary">
    <figcaption>Cycle Summary</figcaption>
</figure>
    
 <h4>1.3 Test Analysis</h4>
 <p>The testing process will be executed based on the above requirements for the Customer Login and Bank Manager Login modules. The following test conditions were found:</p>
 
● Check if users have mandatory login requirements<br>
● Check if users can use drop-down lists<br>
● Enter invalid data<br>
● Check if users can user mandatory fields<br>
● Check if list can be rearranged<br>
● View all Customers in a list<br>
● Check if essential buttons are functional<br>

<h4>1.4 Test Design</h4>
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.

<figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Tests.jpg"
         alt="Tests">
    <figcaption>Tests</figcaption>
</figure>

<h4>For the Airport Gap API, the following checklist was generated: 
csv file to be entered.</h4>

<h4>1.5 Test Implementation</h4>
<p>The following elements are needed to be ready before the test execution phase begins:

Testing environment is up and running: https://www.globalsqa.com/angularJs-protractor/BankingProject/#/login<br>

● Access to the testing environment is given:<br>  
● Username : Any from user name list | Password : none<br>
● Cycle summary was created<br>
● Test cases were added to the cycle summary<br>
● Postman collection with the dependents API methods was created<br>
● Authorization token was created for accessing the API<br>
    
<figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Cycle%20Summary%209_%20ALL%20PASS.jpg"
         alt="Cycle Summary">
    <figcaption>Cycle Summary - All Pass</figcaption>
</figure>

 Bugs have been created based on the failed tests. The complete bug reports can be found here:
    
 <figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Bug%20Report.jpg"
         alt="Bug Report">
    <figcaption>Bug report</figcaption>
</figure>
    
<h1>detail here the bugs one by one</h1>
    
Full regression testing is needed after the bugs are fixed

<h2>1.7 Test Completion</h2>

 <figure>
    <img src="https://github.com/hochdorfer/manual_testing_project/blob/main/Bug%20Report.jpg"
         alt="Test Execution Report">
    <figcaption>Test Execution Report</figcaption>
</figure>
