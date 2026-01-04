# Pytest_CI_and_CD
Automated testing with Pytest and CI/CD
Instructions:
1.Create the main file to be tested  
In my case, this is calculator.py, where all the functions are already written.
(You can open the file and check the code yourself.)

2.Create the test file  
Add a second file for tests, for example test_calculator.py, where you write Pytest tests for the calculator functions.

3.Set up CI/CD  
GitHub does not run tests automatically, so you need to create a workflow file:

Path: .github/workflows/test.yml

This file contains the configuration for running tests automatically whenever you push changes.

4.Dependencies  
There is a requirements.txt file with recommendations on what needs to be installed for everything to work correctly.
Install them with:
pip install -r requirements.txt

5.View the code  
All the source code and configuration files can be checked directly in the repository.
