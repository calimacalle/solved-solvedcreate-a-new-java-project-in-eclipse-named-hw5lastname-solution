Download Link: https://assignmentchef.com/product/solved-solvedcreate-a-new-java-project-in-eclipse-named-hw5_lastname-solution
<br>
Create a new Java Project in Eclipse named HW5_lastName and complete the following requirements. Create a package named cs520.hw5. Using this package, create the following classes.

1. Create a class named Student as follows. The class keeps track of thestudent’s homework grades. This is a modification of HW3 using arrays.

a.The instance (or member) private variables – name (String), homeworks (an integer array list).b. A single constructor with name as its argument. Also, initialize the homeworks array list.c. The public get and set methods for the name instance variable.

d.A void addHomeworkGrade method which takes one argument – the new homework grade.

e.A public computeAverage method which takes no arguments and returns a double showing the average homeworkgrade for this student.

f. Override the toString method to return the string representation of this object in the format “The ’s average grade is ”.

2. Create a Test class to test the following functionality in its main method.

a. Declare and initialize an empty Queue of Student objects named studentQueue.b. Declare and initialize an empty HashMap named studentMap. The keys will be the names of the students and the entries in the map will be the corresponding student objects.c.Use the BufferedReader class to read the data.txt file. The contents of the file are shown below. Create the data.txt file in HW5_lastName.

d. Read the contents of the text file one line at a time using a loop. The program should work for any number of input lines. In this loop,1. Invoke the processInputData method for each line read. This method returns the corresponding Student object.2. Add this Student object to the studentQueue.3. Insert this Student object into the studentMap using the student’s name as the key.e. After the loop is processed, do the following.

1. Iterate over the studentQueue and display each element to the console.2. Access the keys of the studentMap and assign them to an appropriate variable. Create an iterator over the keys. Iterate over each key in this set anddisplay the associated object in the map to the console. Write a private method processInputData with return type Student which processes its string input argument and returns the corresponding Student object as follows.

1. Tokenize the string argument usingthe StringTokenizer class using the comma as the delimiter, or using the String split method.2. Extract the name token. Create a Student object and assign to the local variable currentStudent.3. Using a while loop, read the next homework grade token. Usethe addHomeworkGrade method on the student object to add the homework grade for this homework.4. Display the string representation of the currentStudent object to the console.5. The method should return the currentStudent object.