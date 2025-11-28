# METHODS in Java

A **method** in Java is a block of code that performs a specific task.

### Example
```java
void greet() {
    System.out.println("Hello!");
}
```

A method usually has:
- a return type  
- a name  
- parameters (optional)  
- a body  

### General Syntax
```java
returnType methodName(parameters) {
    // code
}
```

---

# ✔ Types of Methods in Java

## 1️⃣ Instance Methods  
You must create an object to call them.

```java
class Test {
    void show() {
        System.out.println("Instance Method");
    }
}

Test obj = new Test();
obj.show();
```

---

## 2️⃣ Static Methods  
Can be called without creating an object — using class name.

```java
class Test {
    static void display() {
        System.out.println("Static Method");
    }
}

Test.display();
```

---

## 3️⃣ Parameterized Methods  
Methods with input parameters.

```java
void sum(int a, int b) {
    System.out.println(a + b);
}
```

---

## 4️⃣ Return Type Methods  
Methods that return a value.

```java
int add(int a, int b) {
    return a + b;
}
```

---

# ⭐ FUNCTION vs METHOD in Java

| Feature | Function | Method |
|--------|----------|---------|
| Belongs to | Independent (not inside a class) | Always inside a class |
| Used in | C, C++, Python | Java |
| Relation with object | Not related to objects | Related to classes/objects |
| Example | `int add() {}` in C | `void show()` in Java class |

---

# 🔥 Simple Explanation

👉 **Function = general term**  
👉 **Method = function inside a class**

Because Java is 100% object-oriented, every function exists **inside a class**, so they are called **methods**.

---

# ⭐ Example to Understand Clearly

### C / C++ Function
```cpp
int add(int a, int b) {
    return a + b;
}
```

### Same in Java (Now it is a method)
```java
class Demo {
    int add(int a, int b) {
        return a + b;
    }
}
```
