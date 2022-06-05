# QAN26-Solution
This is QA N26 Solution repository

Task 01 Solution:
-------------------
Task 01 Solution folder contains Test plan with all the possible test cases and test scenarios in Microsoft Excel Format. Also mention the detail about automation test cases and status (Pass / Failure)

I have created test plan with Test Suite ID,Name,Description,Test Case ID,Test Case,Expected Results,Automation Required & Status(Pass/Run) sections. Test cases are divided into different pages of Application and prioratized as per User Interface & Functional levels.

User Interface : It covers all test cases for navigation & valid/invalid value scenarios.
Functional : It covers all the test cases for the functionality of app like if all the details are correctly updated as per user input.

Secondly, I have created N26 Solution Document in Detail that will indicate and setp what bug I have found. I have illustrated in detail.

Task 02 Solution:
-------------------
**Appium is used to automate the mobile application.**
First of all check the dethe dependencies needed to install Appium

1. Node.js
2. Java
3. Appium Server
4. Appium Client Libraries
5. Selenium Libraries
6. Android Studio with SDK (For Adb Device Integrations)
7- Maven 
8- TestNG
**Then clone the my repo (Task Solution 02)
Dependencies will install (Because its POM)
Now we can run the test suite from a command line : mvn test or Execute with TestNG
**
**Scenarios**
The automated scenarios here are the most used scenarios which have a business impact in case of failure with priority serious and high:

Test cases:
  1. A user can CRUD income (Priority: serious).
  2. A user can CRUD expense (Priority: serious).
  3. A user can CRUD account (Priority: high).
  4. Settings (like changing language, changing categories' name, changing currency)(Priority: medium).
  5. Search (search field, search by date) (Priority: medium).
  6. Filter balance by day, by month or by year (Priority: medium).

Also check N26 Solution Document that will indicate the approach and framework for this task.

Task 03 Solution:
----------------
For this task I have used Rest-Assured library to automated Rest API end points. Major test cases are focused on correct functionality of endpoints.

Steps to Execute
----------------

Download and install Eclipse IDE or IntelliJ for Java
Make sure the Bestbuy API playground server is running (For me its running on 8080 Port)
Clone this repo : Task Solution 03
Import Rest-assured libraries in External Jars if needed (I have already added in my project)

--> Right click on the project folder -> Run As -> JUnit Test
---> Execute the testng File.

If you need any information please let me know.
Thanks & Regards
Raza
