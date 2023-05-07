Download Link: https://assignmentchef.com/product/solved-intermediate-programming-using-c
<br>
1. What must be true for a class to be considered an abstract class?

2. Consider a class declaration that begins

class Derived : public Base

{. . .

Determine whether each of the following statements is true or false.

a. The public members of Base become public members of Derived.

b. The public members of Derived become public members of Base.

c. The protected members of Base become protected members of Derived.

d. The private members of Derived become public members of Base.

e. The private members of Base remain private to Base, and are inaccessible to Derived.

3. Given the following class definition:

class B

{

public:

int e();

void f();

private:

int x;

};

class D : public B

{

public:

void h();

void g();

private:

float y;

}

How many public methods does class D have? List them.

4. For each of the following, state whether the terms have an “is-a” or “has-a” relationship, and explain your answer.

a. State University and the School Of Dentistry

b. Superhero and Batman

c. Student and Student Number

d. Student and Undergraduate

5. Modify your previous StudentGrade class so that all methods are marked const that can be. Make sure you have a constructor that accepts all data values. Create a simple main function that declares a const StudentGrade object and demonstrates that the values have been successfully stored inside.

6. Working from the last problem, create a StudentMajor class with “get” and “set” methods (the major itself is a string). Add a StudentMajor data member to your StudentGrade class, and add methods to StudentGrade to get and set this member.

7. Your coworker Fred has written a class for a Customer record. You plan to inherit from his class to make a specialized version called LocalCustomer.

a. What would be the potential reasons and benefits for using public inheritance?

b. Suppose Fred is known to frequently change the underlying data structures of his classes. Why would private inheritance then be a better choice?

8. a. Using your previous BaseballBatter class, create a subclass called BaseballPlayer that adds methods to store and retrieve the number of fielding errors.

b. Does your subclass have a new data member? Why or why not?

c. Did you use public or private inheritance? Why?

9. a. Using your previous StudentGrade class, create a subclass called StudentLetterGrade with an additional method, getLetterGrade, that returns the grade as a char (simple “A”, “B”, etc., no plus or minus).

b. Does your subclass have a new data member? Why or why not?

10. Describe the object-oriented technique called polymorphism, including the pre-conditions for its use in C++. Offer a scenario where polymorphism might be useful that does not appear in your text.