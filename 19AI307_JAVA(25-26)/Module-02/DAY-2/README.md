# Ex.No:2(B) METHODS

## QUESTION:
Write a class with one static method and one non-static method. Call both from the main() method.
When staticMethod() is called, it should print  "I am static".
When nonStaticMethod() is called, it should print  "I am non-static".

Example:
```
-----------------
Result:
I am static
I am non-static
------------------
```

## AIM:
To understand how to define and use static and non-static methods in Java and call them from the main method.

## ALGORITHM :
```
1.	Start the program.
2.Create a class containing:
   -> one static method
   -> one non-static method
3.Static method prints: "I am static".
4.Non-static method prints: "I am non-static".
5.Call the static method directly from main().
6.Create an object to call the non-static method.
7.End the program.
```
## PROGRAM:
 ```

Program to implement a Methods using Java
Developed by: HARIHARAN A
RegisterNumber:  212223110013

```

## SOURCE CODE:
```java
public class Test {
    static void staticMethod() {
        System.out.println("I am static");
    }

    void nonStaticMethod() {
        System.out.println("I am non-static");
    }

    public static void main(String[] args) {
        staticMethod();
        Test obj = new Test();
        obj.nonStaticMethod();
    }
}

```

## OUTPUT:

<img width="1181" height="340" alt="image" src="https://github.com/user-attachments/assets/30046955-0a64-49ec-a597-5af528bb35ce" />

## RESULT:

Thus, the Java program demonstrating static and non-static methods was executed successfully.


