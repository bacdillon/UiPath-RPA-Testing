# UiPath-Test-Suite

Use Studio to create, design, and map test cases and execution results to requirements and defects.

# Application Testing
Through data-driven testing, run the same test using different data variations within a single test case. Here is the use-case scenario.

The following activity packages

* UiPath.System.Activities
* UiPath.UIAutomation.Activities
* UiPath.Testing.Activities

The following activities are available for testing data used by the workflows:

* Verify Control Attribute
* Verify Expression
* Verify Expression with Operator

For these types of activities, if encounter an error, the execution logs the failed activity in the Output panel as opposed to stopping the workflow from running.
![alt text]((https://github.com/bacdillon/UiPath-Test-Suite/blob/main/OutputErrorPassed.jpg))

