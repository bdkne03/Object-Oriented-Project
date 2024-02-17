# Object-Oriented-Project
Overview: Small java programming project that deals with inheritance, abstract classes, abstract methods, and method overriding. 

The project includes implementing a simple personnel program. The program contains three kinds of objects: Staff, Student, and Faculty. For each object, the program stores relevant information such as university ID, name, etc. Different information is stored depending on the type of object. For example, a student has a gpa, a faculty has a title and department (professor, mathematics).

The Student class has the private attributes:
-	full name : String
-	id: String
-	gpa: double
-	Number of credit hours currently taken: int

For a faculty, we need a:
-	full name: String
-	id: String
-	department (mathematics, engineering or english): String
-	Rank (professor or adjunct): String

For a staff, we need a:
-	full name: String
-	id: String
-	department (mathematics, engineering or english): String
-	status (part time or full time): String

Tthe following inheritance hierarchy:

Person -> (Student      Employee)
                           |
                           v
                  (Faculty    Staff)

Both classes Student and Employee inherit from the abstract class Person. The abstract class Person has what is common to a Student and an Employee (Faculty or Staff). The class Person must include the signature: public abstract void print(); The abstract method print is overridden to print the fee invoice for a student and to print the information for a faculty or a staff member.

The class Employee is abstract, and it is supposed to include what is common to a staff and a faculty.
