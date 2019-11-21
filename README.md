# Robot_framework

Here, we make use of Templates, that will define the test step to be executed each time a data set is given in as arguments in test case.
Basic test set up and tear down includes opening the browser or the application under subject and closing the application browser upon completion of the test.

### Execution Steps and Calls:
1. Define a Test Template: 'Data Driven Test Cases’ is a module that is defined under
keywords for having to take in 5 arguments namely, test case ID, old password, new
password, and current password, and expected validation.
2. Method definition 'Data Driven Test Cases’: In this template we define the operations of the
method to be performed including populating the values of the data set onto the locator
text fields of Old, New and Confirm Password respectively. Then we click the “Save
Password” button
3. Store Validation: We store the validation displayed on the system, in a specific locator and
compare it with the argument given through in the test case which specifies the expected
validation to be displayed.


### Template Code



We can call this template in the test case by using the format [Template] Data Driven Test
Cases or by declaring this Test Template in settings, as used in the script, for now will directly
drive this module from its declaration, and perform function for each data set that is given as
arguments through the Test Case section.
The Data Driven Testing is now performed by asserting all string validations, and completes the
test continually for all the test cases and results are generated in the log file in the same
directory.



