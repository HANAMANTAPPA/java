# Magic arena Application 
Please refer class diagram for better understanding 
I have attached word document which contains class diagram, example result and test case execution result.

## to Run the application in CMD
	there is runnable jar file with the name as "Runnable_Application.jar" in the parent zip folder 
	to run application on your machine open command prompt and execute command as
	>> java -jar Runnable_Application.jar 
	- prerequisite it needs Java installation on your machine to run the application 
## to Run the application in eclipse 
	-open the project with eclipse 
	-go to source-- > Mainclass.java and run the application 
	-provide inputs according to prompt and you will get the result
## to Run Unit test cases
	### Intro
	I have not used JUnit or other 3rd party Libraries or Frameworks So
	I have consolidated all unit test cases and inserted all test cases in the class AllUnitTestcasesWithoutJunit.java
	
	- therefore uncomment main method in class called  AllUnitTestcasesWithoutJunit.java 
	- and comment logs(printing statements) which are in the method "match" under Mainclass.java
	- run the class AllUnitTestcasesWithoutJunit.java
	- we an see EXPECTED and ACTUAL results
	- thus confirms Unit test cases are passed
	*** I could use @Test annotation and assertequals(EXPECTED,ACTUAL) method to test the test case
	*** Nut as per the requirement i have not Used any libraries.
	
## to view the local git history 
	- Open the MagicalArena folder in eclipse 
	- Open git perspective
	- Right click on folder MagicalArena 
	- click on show in -- > click on history 

