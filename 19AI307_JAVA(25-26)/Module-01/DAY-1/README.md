Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS
QUESTION:
Lovely is training to become a logic wizard. She enters a gate that tests her understanding of logical conditions.

She is given two magical conditions:

hasKey – whether she has the golden key (boolean)

knowsPassword – whether she knows the secret password (boolean)

The gate then evaluates her truthfulness using logical operators:

image
Write a program that:

Accepts two boolean inputs: hasKey and knowsPassword

Displays the results of:

hasKey && knowsPassword hasKey || knowsPassword !hasKey !knowsPassword Input Format:

First line: true or false (hasKey)

Second line: true or false (knowsPassword)

Output Format:

Access with AND: <true/false>

Access with OR: <true/false>

Does NOT have key: <true/false>

Does NOT know password: <true/false>

AIM:
Aim: To write a Java program that reads two integer numbers from the user and performs basic arithmetic operations such as addition, subtraction, multiplication, division, and modulus, and displays the results.

ALGORITHM :
Start

Create a Scanner object to read input from the user.

Read two boolean values i and j from the user.

Compute the following: l1 = i && j → Logical AND of i and j

l2 = i || j → Logical OR of i and j

l3 = !i → Logical NOT of i

l4 = !j → Logical NOT of j
5.Display the results:

  "Access with AND: " + l1

  "Access with OR: " + l2

   "Does NOT have key: " + l3

  "Does NOT know password: " + l4
Stop
PROGRAM:
/*
Program to implement variables and Operators using Java
Developed by: HARIHARAN A
RegisterNumber:  212223110013
*/
Sourcecode.java:
import java.util.*;
public class Main{
    public static void main(String[]args)
    {
        Scanner sc=new Scanner(System.in);
        boolean i=sc.nextBoolean();
        boolean j = sc.nextBoolean();
        boolean l1=(i&&j);
        boolean l2=(i||j);
        boolean l3=(!i);
        boolean l4=(!j);
        System.out.println("Access with AND: "+l1);
        System.out.println("Access with OR: "+l2);
        System.out.println("Does NOT have key: "+l3);
        System.out.println("Does NOT know password: "+l4);
    }
}
OUTPUT:
image
RESULT:
The program has been executed successfully and the desired output has been obtained.
