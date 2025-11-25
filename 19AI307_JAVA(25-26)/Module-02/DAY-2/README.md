# Ex.No:2(B) METHODS

## QUESTION:
Write a method int cube(int x) that calls a method int square(int x) internally to calculate the cube as x * square(x).

## AIM:
To write a Java program that uses methods inside a class to compute the square and cube of a number, and to demonstrate method calling within another method.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Create a class MathUtil with methods square(int) and cube(int).
4. The cube() method should internally call the square() method.
5. In the main() method, read an integer from the user and create an object of MathUtil.
6. Call the cube() method with the input value and display the result.

## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: PRIYADHARSHINI S
RegisterNumber: 212223240129
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class MathUtil {
    int square(int x) {
        return x * x;
    }

    int cube(int x) {
        return x * square(x);
    }
}

class prog {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        MathUtil m = new MathUtil();
        System.out.println(m.cube(n));
        sc.close();
    }
}
```

## OUTPUT:

<img width="439" height="254" alt="image" src="https://github.com/user-attachments/assets/0e89c18d-7bef-45b0-b465-90b294f1cefd" />


## RESULT:
Thus, the Java program using methods to compute the square and cube of a number was executed successfully.

