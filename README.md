<!--# Manual-Automation-Testing
Streamline testing with our comprehensive repository! From manual to automated scripts, ensure flawless functionality with ease. Join us in elevating software quality standards! 🚀-->


# The syllabus for software testing:

### 1. **Introduction to Software Testing**
- Definition and Importance
- Software Development Life Cycle (SDLC)
- Software Testing Life Cycle (STLC)
- Types of Testing: Manual vs. Automated

### 2. **Fundamentals of Testing**
- Testing Principles
- Test Levels: Unit, Integration, System, Acceptance
- Test Types: Functional, Non-functional, Regression, Smoke, Sanity
- Static Testing: Reviews, Walkthroughs, Inspections

### 3. **Test Planning and Documentation**
- Test Planning: Objectives, Strategy, Scope
- Test Plan Documentation
- Test Case Design Techniques: Boundary Value Analysis, Equivalence Partitioning, Decision Table, State Transition
- Test Data Preparation

### 4. **Testing Techniques and Methods**
- Black Box Testing
- White Box Testing
- Grey Box Testing
- Exploratory Testing
- Ad Hoc Testing

### 5. **Test Management**
- Test Execution and Logging
- Defect Lifecycle and Management
- Test Metrics and Reporting
- Test Management Tools: JIRA, TestRail, Quality Center

### 6. **Automation Testing**
- Introduction to Automation Testing
- Tools and Frameworks: Selenium, QTP, UFT
- Writing and Executing Automated Test Scripts
- Continuous Integration and Continuous Testing

### 7. **Performance Testing**
- Introduction to Performance Testing
- Performance Testing Tools: JMeter, LoadRunner
- Load Testing, Stress Testing, Volume Testing
- Performance Metrics and Bottleneck Analysis

### 8. **Security Testing**
- Basics of Security Testing
- Common Security Vulnerabilities: SQL Injection, Cross-Site Scripting (XSS), CSRF
- Security Testing Tools: OWASP ZAP, Burp Suite

### 9. **Mobile Testing**
- Introduction to Mobile Testing
- Mobile Testing Tools: Appium, Espresso
- Testing on Different Mobile Platforms: iOS, Android
- Mobile App Performance Testing

### 10. **Agile and DevOps Testing**
- Introduction to Agile Methodology
- Agile Testing Practices
- Continuous Integration and Continuous Deployment (CI/CD)
- Role of QA in DevOps

### 11. **Industry Best Practices**
- Test Process Improvement
- Risk-Based Testing
- Test Automation Best Practices
- Code Quality and Code Reviews

### 12. **Real-World Projects and Case Studies**
- Working on Live Projects
- Case Studies from Different Domains: E-commerce, Banking, Healthcare
- Best Practices and Lessons Learned

### Additional Resources
- ISTQB Foundation Level Syllabus
- Online Courses and Tutorials
- Practice Tests and Interview Questions

This outline provides a broad view of the topics typically included in a software testing syllabus. Depending on your focus (manual vs. automated testing) and the certification you are pursuing (such as ISTQB), the emphasis on certain areas may vary.

# 1. Software Testing 
>Software testing is the process of evaluating and verifying that a software application or system meets specified requirements and functions correctly. It involves executing the software under controlled conditions to identify any defects, errors, or gaps in the desired functionality. 

### Importance of Software Testing:
i. Quality Assurance:
    
```   
Ensures the software meets the expected standards and performs as intended.
```
2. Identifying Defects Early:
```
      Detects bugs and issues early in the development cycle, reducing the cost and effort required to fix them later.
  ```

3. User Satisfaction:
```
Ensures the software is reliable and performs well, leading to higher user satisfaction.
```
4. Security:
```
Identifies vulnerabilities that could be exploited, ensuring the software is secure.
```
5. Compliance:
```

Ensures the software complies with relevant regulations and standards.
```
6. Performance:
```
Verifies that the software performs well under various conditions, including high load scenarios.
```
7. Compatibility:
```
Ensures the software works across different environments, devices, and platforms.
```

8. Business Continuity:
```
Prevents failures that could disrupt business operations and lead to financial loss.
```
9. Reputation:
```
A well-tested software product enhances the reputation of the company, building trust with customers and stakeholders.
```



## Type of Software Testing 
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20230808151753/Software-Testing-768.png" height="400" width="600" />


## Pyramids of testing
<img src="https://blog.getmason.io/content/images/2020/11/Testing-pyramid--6--1.jpg" height ="300" width="600" />

#### Unit Testing : 
```
* Unit testing is a software testing method where individual units or components of the software are tested in isolation from the rest of the application. 
* It is mostly done by Developers sometime QA.
```
#### Integration testing:
```
Integration testing is a type of software testing where individual units or components are combined and tested as a group. The purpose of this testing is to identify issues in the interactions between integrated units.

Type of Integratin Testing / System testing
- Big Bang Approach
- Incremental : a)Top Down approch b) Bottom Up approach


```
#### E2E Testing / UI testing:
```
End-to-End (E2E) testing is a type of software testing that validates the entire software system flow from start to finish. The purpose is to simulate real user scenarios and ensure the system works as expected across all integrated components, including databases, network infrastructure, and other external interfaces.
```

Tested end to end Demo website.[ StackDemo](https://bstackdemo.com/)

-----------------------------------------------------------------------------

## SYSTEM TESTING:
* Testing over all functionality of the application with respective client requirements.
* It is a black box testing technique.
* This testing is conducted by testing team.
* After completion of component and integration level testing's we start System testing.
* Before conducting system testing we should know the customer requirements


**System Testing focus on:**
- [ ] User Interface Testing (GUI)
- [ ] Functional Testing
- [ ] Non-Functional Testing
- [ ] Usability Testing 


**System Testing Process: System Testing is performed in the following steps:**

* Test Environment Setup: Create testing environment for the better quality testing.
* Create Test Case: Generate test case for the testing process.
* Create Test Data: Generate the data that is to be tested.
* Execute Test Case: After the generation of the test case and the test data, test cases are executed.
* Defect Reporting: Defects in the system are detected.
* Regression Testing: It is carried out to test the side effects of the testing process.
* Log Defects: Defects are fixed in this step.
* Retest: If the test is not successful then again test is performed.
---------------------------------------------------------------------------

## Functional Testing And Non Functional Testing
=> User behavior 
- Types of functional testing:
* smoke: Performed at early periods 
* sanity: Always done after making the builds stable
* integraton: collected testing of all parts in integration testing 
* regressions: Unit regression, full regration , regional regration
* localization
* unit tesing

----------------------------------------------------------------------------
# SDLC(Software Development life cycle)

<img src="https://cdn.brocoders.com/6_phases_of_software_development_life_cycle_ce25a52c62.png" hight="300" width="400"/>


Agile Methodologies
Not every organization implements Agile SDLC in the same way; there are several possible frameworks – Kanban, Scrum, Extreme Programming, Feature-Driven Development, Crystal, Lean, and Dynamic Systems Development Method. And, to make things more convoluted, there can be hybrids. For instance, Scrum + Kanban = Scrumban.

 we're just going to look at Scrum and Kanban, which are the most popular non-hybrid Agile methodologies.

<img src="https://cdn.brocoders.com/Scrum_vs_Kanban_89aa26b056.png" hight="350" width="450" />


# STLC(Software Test Life Cycle )
<img src="https://static.javatpoint.com/tutorial/software-testing/images/sdlc-vs-stlc.png" hight="300" width= "400">


