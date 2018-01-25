# How to run the tests
## Prerequisites
Following need to be installed prior running the tests:
- robotframework
- python

## Before running the tests
- By defaults tests are set to be run no localhost. In order to change the environment please edit robot-selenium-demo.txt file and change
${WEBAPP}	http://localhost:3000/
into
${WEBAPP}	<your_environment>

## Running the tests
Instructions are provided for Windows OS. In order to run the tests please follow below steps (once the code is checked out locally):
- access the rbc-interview within the command line
- run pybot robot-selenium-demo

## Troubleshooting
In most cases when errors are encountered while running the tests a clear message is displayed on what should be done to remove an error