# UMLGenerator

To develop this project I have used the following libraries
1)	javaparser:
I have used this library to parse the java code and to convert the code as an input to the UML Generation tool.
2)	PlantUML
I have used this library to generate the UML Class Diagram in the “.png” format.
PlantUML requires Graphviz to be installed before using it.


Instructions for executing the .jar file:
1.	Download and Install Graphviz from this URL: http://www.graphviz.org/Download..php
2.	Open the command window where the .jar file is located and execute the following command

java – jar UmlParser.jar “path_to_testcases_folder” “output_file_name”

Note: Include the path and output name in the quotes.
Ex: java – jar UmlParser.jar “C:\test_case_1” “TestCase1”
Here the output is TestCase1.png file in the same folder as the .jar file
3.	The output is a .png file in the same folder as the .jar file if no path is specified along with the name of the output file in the second argument.


Instructions for executing the Source Code in eclipse:
1.	Download and Install Graphviz from this URL: http://www.graphviz.org/Download..php
2.	Open Eclipse and import the project in the Source Code folder.
3.	To run the project, pass the arguments using run configurations in eclipse.
Select “Run” from toolbar on top and then select “Run Configurations.” A window pops up. Now, select “Arguments” tab and enter the two arguments (path to the test cases and the output file name) in double quotes separated by space, under “Program Arguments”.
4.	The output is the .png file in the same folder as the project folder if no path is specified along with the name of the output file in the second argument.
