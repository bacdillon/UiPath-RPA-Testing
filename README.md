# UiPath-Test-Suite

Use Studio to create, design, and map test cases and execution results to requirements and defects. RPA testing, can define the inputs, expected results and outputs to check whether automation projects are working properly.

# Application Testing
The following activity packages was installed.

* UiPath.System.Activities
* UiPath.UIAutomation.Activities
* UiPath.Testing.Activities

The following activities are available for testing data used by the workflows:

* Verify Control Attribute
* Verify Expression
* Verify Expression with Operator

For these types of activities, if encounter an error, the execution logs the failed activity in the Output panel as opposed to stopping the workflow from running.

![alt text](https://github.com/bacdillon/UiPath-Test-Suite/blob/main/OutputErrorPassed.JPG)

# Data-Driven Testing
Data-driven testing allows to test RPA workflows and applications to make sure that the automations can handle multiple scenarios.
In this scenario, configure data sources with Excel file for data variation.

Through data-driven testing, run the same test using different data variations within a single test case. Here is the use-case scenario.

 Data driven test case to verify the hash code for the keyword `Brave` by using different hash methods like gost, md5, crc32, etc
 
# Test Manager
Test Manager is the component used for managing the test process, automated test case creation in Studio or automated test execution by test robots.

![alt text](https://github.com/bacdillon/UiPath-Test-Suite/blob/main/Test Manager validate HASH.JPG)
