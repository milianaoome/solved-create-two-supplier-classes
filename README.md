Download Link: https://assignmentchef.com/product/solved-create-two-supplier-classes
<br>
5/5 - (2 votes)

You’ll create two supplier classes that interact with each other (through a “has a” relationship). Here are UML Class Diagrams for the objects you are to create. Pay attention to the diagram notation indicating whether methods are public (+) or private (-); ask questions if you need clarification. Understanding the model is of critical importance here.



Class StudentClassDepartment(you figure out the private data needed)

(you figure out the private data needed)Constructors

+Student(firstName : String, lastName : String, id : String)

+Student(firstName : String, lastName : String, id : String, csc110 : Boolean, csc142 : Boolean, csc143 : Boolean)

Accessors

+getFirstName() : String

+getLastName() : String

+getID() : String

+getCSC110() : Boolean

+getCSC142() : Boolean

+getCSC143() : Boolean

+getBalance() : Double

+toString() : String

Mutators

+setCSC110(csc110 : Boolean)

+setCSC142(csc142 : Boolean)

+setCSC143(csc143 : Boolean)

Constructors

+Department()

+Department(totalStud110 : Integer, totalStud142 : Integer, totalStud143 : Integer, totalBalance : Double)

Accessors

+getTotalCSC110 () : Integer

+getTotalCSC142 () : Integer

+getTotalCSC143 () : Integer

+getTotalStudents() : Integer

+getTotalBalance() : Double

+getTotalGr110() : Integer

+getTotalGr142() : Integer

+getTotalGr143() : Integer

+toString() : String

Other Methods

+addStudent(newStudent : Student) : void3   Constraints and Assumptions

•       Create no static methods except for the test methods.

•       Mark each instance variable and each method as either public or private; follow the UML where it gives guidance and make smart decisions where it doesn’t.

•       Use exactly the method names shown. Look carefully at the parameter data types and the return data types; they give you clues.

•       Department’s addStudent method maintains the appropriate total students of each group and the total balance.

•       Department’s getTotalGr… methods calculate how many groups need for each class (28 students in the class).

•       The toString method should do their best to summarize the state of the object instance in questions; include newlines in the strings to make the result displayable and attractive.

•       Create a test method for each class that checks every constructor and every method except toString.

•       One credit equals 5, and one credit costs $110.

•       Throw an IllegalArgumentException if any of these preconditions are violated:

o A first name, last name, and ID can’t be empty.

o Total students of each group can’t be negative.