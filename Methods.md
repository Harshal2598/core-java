METHODS in Java

A method in Java is a block of code that performs a specific task.

Example:
void greet() {
    System.out.println("Hello!");
}

A method usually has:

a return type

a name

parameters (optional)

a body

General syntax:
returnType methodName(parameters) {
    // code
}

✔ Types of Methods in Java
1️⃣ Instance Methods

You must create an object to use them.

class Test {
    void show() { }
}
Test obj = new Test();
obj.show();

2️⃣ Static Methods

Called without object, using class name.

class Test {
    static void display() { }
}
Test.display();

3️⃣ Parameterized Methods

Methods with input parameters.

void sum(int a, int b) {
    System.out.println(a + b);
}

4️⃣ Return Type Methods

Methods that return a value.

int add(int a, int b) {
    return a + b;
}

⭐ FUNCTION vs METHOD in Java
Feature	Function	Method
Belongs to	Independent (not tied to class)	Inside a class
Used in	C, C++, Python, etc.	Java (because everything is inside class)
Relation with object	Not related to objects	Related to classes/objects
Example	int add() {} in C	void show() inside Java class
🔥 Simple Explanation

👉 Function = general term
👉 Method = function inside a class

Because Java is 100% object-oriented, every function is inside a class, so they are called methods.

⭐ Example to Understand Clearly
C / C++ Function:
int add(int a, int b) {
    return a + b;
}

Same in Java (Now it is a method because inside a class):
class Demo {
    int add(int a, int b) {
        return a + b;
    }
}
