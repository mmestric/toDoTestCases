# toDoTestCases
General test cases for the first task


The first task just included manual testing cases. The test cases in question contain positive scenarios, negative scenarios and edge cases. 

1st test case is a simple postive test scenario.
  Tests basic functionality and creates a new task (as defined in the expected result)

2nd test case is a negative test scenario
  Currently there is an issue with the application and it will throw a 500 server error on attempted save of a title that is too large (1500+ characters). This scenario tests that functionality. The expected result is not met and there is an actual result that differs.

3rd, 4th and 5th test cases cover edge cases in the application and they include the following: 
  - trimming the task content after 150 characters
  - expired cookie
  - max number of tasks (with a bug on 40+ tasks)
  
  
  At the end of the document there is additional inforamtion about testable elements on the webapp
  
  
 Additional documents are the:
  - test data (used for manual testing to trigger specific states, can be switched to a standard CSV, per testing scenario with the standard input information, expected result format)
  - testFlow.pdf that has the basic flow through the application defined, highlighted some of the potentially problematic areas and flows of the application
