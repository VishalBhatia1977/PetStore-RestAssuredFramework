# PetStore-RestAssuredFramework

REST Assured - Swagger Petstore - OpenAPI 3.0
This test automation project is created for a REST API, Swagger Petstore - OpenAPI 3.0. The tests are implemented using Rest Assured & can be used for learning purpose also as ready framework to quickly get started with automation project.

Solution information
The project is supposed to automate the proposed test cases (listed in below section) using REST assured with a modular framework which allows us to scale & maintain with ease. The solution uses Maven for build compilation & dependency management. Allure reports to generate clear, user readable & presentable reports. Uses java faker library to generate random fake data wherever required.

Proposed Test cases for Automation:
Pet Endpoint

Creating a new pet
Fetch all pets by statuses
Finding pet by given id
updating pet by given id
updating pet by form data
Store Endpoint

Fetch the inventory status
Place a new order
Fetch the given order by ID
Delete an newly created order
User Endpoint

Fetch user details by username
Create a new user
Log the user into the system
Log out the current active session

Install Maven. Run following command in terminal -> brew install maven (Pre requisite: brew should be present in the system)
Install Allure. Run following command in terminal -> brew install allure

Run Automated Tests from IntelliJ / Terminal
Navigate to 'PetStore-RestAssured' folder from terminal window

Run following command -> mvn clean test
Reporting - Allure reports

From 'PetStore-RestAssured' folder, navigate to 'target' folder from terminal
Run following command -> allure serve allure-results
An Allure report will open in browser with the last run report.

Tools/Tech stack
REST-assured
Maven
Junit5
Allure Reports
Java
IntelliJ
Git
Plan for further enhancement
Adding a logger
Managing properties from outside the code
Dynamic data creation
