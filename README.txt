Robot Framework
====================

`Robot Framework` is a generic open source test automation framework mainly used for acceptance testing


DOCUMENTATION FOR THE  AUTOMATED TESTS FOR CALCULATOR:

################
File Information
################
Calculator.py : The python file in which the logic for calculator tool is implemented
CalculatorLibrary.py : The python file containing test library for testing the Calculator business logic
keyword_driven.txt: This contains all the test which have workflow constructed from keywords  in CalculatorLibrary.py
output in xml format :  /Users/vijeta.b/Documents/Apigee_test/output.xml
log.html:     /Users/vijeta.b/Documents/Apigee_test/log.html
report.html:  /Users/vijeta.b/Documents/Apigee_test/report.html
README.txt: Help file. You are reading this by the way.


################
How to Execute
################
1. Make sure you have Python 2.7  and pip package manager installed on your machine. If you try to run this with any other python version, some commands might not work.
2. Run the following from command line pip install robot framework to install robot framework on your machine.
3. Open the command line prompt and go to the directory where the project lies
3. Run the following command 
   pybot keyword_driven.txt
6. To view report of the tests for  automated tests 
   /Users/vijeta.b/Documents/Apigee_test/report.html
7. For  viewing logs /Users/vijeta.b/Documents/Apigee_test/log.html

