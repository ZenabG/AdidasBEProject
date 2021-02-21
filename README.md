# Adidas BE Project

The test framework used is **Soap UI** (open source version).

The project consists of 4 api request-response steps added for API automated checks required in the exercise.
* Get All available pets
* Add a new pet
* Update the pet status to 'sold'
* Delete the new pet added

The project has 1 test suite - **PetManagementFunctionalTests** which consists of 1 test case - **TestCase** which has 5 test steps (one for each request-response mentioned above and 5th one for *Validating that the pet was deleted successfully*).

Each test step has *assertions* added to it. 

There is **groovy script** added for running all the test steps through groovy script. It is at path /PetManagementFunctionalTests/RunTheTestCaseThroughGroovy/Groovy Script.

There is also a csv report mechanism added for getting the test result for all the test steps created in the form of a csv file. This report is added in terms of a groovy script at path /Library/Reporting_Utility/GenerateCSVreport. The report is already added in the *Tear Down Script* of the test case. The report is generated at the project path in the folder **Soap UI Results**.
