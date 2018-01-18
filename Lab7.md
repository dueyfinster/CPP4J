# Introduction to C++

## Lab 7 - Inheritance

Define a class to represent a Person, the class should implement a single std::string valued property, name.
Include any appropriate constructors.

Define the necessary conversion operator function so an instance of this class can be displayed using the normal iostream mechanism, ie
```
Person p(...);
cout << p << endl;
```
Note that this will require the Person object to be converted to  
```
const char * 
```
for rendering.

Define a class to represent a course.

Define two subclasses, Student and Teacher. Override the const char *() conversion function to reflect the different "roles".

Add an abstract metbod to the Person class called "doIt()", override this in the Student class to model a student learning on a course, 
and in the Teacher to model the teacher teaching the course.

Define a class to represent a classroom. A classroom contains a variable number of people, one (or more) of whom is a teacher for a course 
and the others are students for the course. 

Add an appropriate number of Teacher(s) and Student(s) to the classroom. 

Add a method showPeople(), which processes each person in the classroom by calling the doIt() method. 
Check that the correct number of teachers and students are reported.

Does your model and implementation support the idea of a person being both a student and a teacher?

