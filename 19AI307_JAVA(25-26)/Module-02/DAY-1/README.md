# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:

Create a class Vehicle with attributes as number, type and owner.

## AIM:

To write a Java program that creates objects for a user-defined class and accesses their data members to display the stored information.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class Vehicle with data members: number, type, and owner.
4. In main(), create two objects of the Vehicle class.
5. Read values for each object from the user and store them in the respective attributes.
6. Display the details of both vehicle objects and end the program.
7. 
## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: PRIYADHARSHINI S
RegisterNumber: 212223240129
*/
```

## SOURCE CODE:
```
import java.util.Scanner;
class Vehicle {
    String number;
    String type;
    String owner;
}

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Vehicle v1 = new Vehicle();
        v1.number = sc.next();
        v1.type = sc.next();
        v1.owner = sc.next();

        Vehicle v2 = new Vehicle();
        v2.number = sc.next();
        v2.type = sc.next();
        v2.owner = sc.next();

        System.out.println(v1.number + " | " + v1.type + " | " + v1.owner);
        System.out.println(v2.number + " | " + v2.type + " | " + v2.owner);

        sc.close();
    }
}
```

## OUTPUT:

<img width="829" height="339" alt="image" src="https://github.com/user-attachments/assets/161fb2d3-edae-46eb-8650-f2c0895eceae" />


## RESULT:
Thus, the Java program to create objects for a class and display their details was executed successfully.

