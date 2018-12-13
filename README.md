# QA_Challenge
Automation test for search functionality

Requirements:

Open https://www.autohero.com/de/search/
● Filter for First registration ( Erstzulassung ). Filter for FROM 2015
● Apply Filter
● Sort cars by Price Descending ( Höchster Preis )
● Verify all cars are filtered by first registration ( 2015+ )
● Verify all cars are sorted by price descending


The Automation test scenario is developed using Python 2.7 with Selenium Library and the framework RobotFramework.
The IDE I chose is PyCharm.
To run the test scenario you need to install:
● Python 2.7
● Selenium Lybrary
● RobotFramework
● The Chrome Third Party Browser Driver for Selenium ---> https://www.seleniumhq.org/download/

Once the system is configured, browse to the QA_Challenge folder with a terminal and prompt the following commad: 

robot TestScenario1.robot

The test execution will take place and in the same folder will be generate a Report, an output and a log file.
 
