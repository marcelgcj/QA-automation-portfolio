# QA-automation-portfolio
Automation practice projects, Robot Framework, public demo sites

QA Automation Portfolio. About this project: 
learning and building automation skills. Technologies and tools: Robot Framework, Python, Git, and GitHub. 
Project goals: build simple automated tests on demo websites and practice end-to-end scenarios. 
Test environment: uses public demo sites for learning. 
About the author: QA professional with experience in manual testing, test management, performance testing, and exploring automation.

*Test Scenarios* 
Feature: Login, description, verify that users can log in to SauceDemo using valid credentials.

Scenario 1: login successfully with valid credentials. Given the user is on the SauceDemo login page, when the user enters valid credentials, and clicks the login button, then the user should be redirected to the products page, and the products list should be displayed. 

Scenario 2: login fails with invalid credentials. Given the user is on the SauceDemo login page, when the user enters invalid credentials, and clicks the login button, then an error message should be displayed, and the user should remain on the login page
