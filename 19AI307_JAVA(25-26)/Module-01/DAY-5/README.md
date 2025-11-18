# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to reverse a given string.

## AIM:
To write a Java program that reads a string from the user and prints its reverse using string functions.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read a string input from the user.
4.	Use StringBuilder to reverse the given string.
5.	Store the reversed string in a variable.
6.	Display the reversed string.
7.	End the program.





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: MAMTHA I
RegisterNumber: 212222230076
*/
```

## SOURCE CODE:
```Python
import java.util.*;
public class Main
{
    public static void main(String[]args)
    {
        Scanner in=new Scanner(System.in);
        String str=in.nextLine();
        String rev_str = new StringBuilder(str).reverse().toString();
        System.out.println("Reversed string: "+rev_str);
        
    }
}
```







## OUTPUT:
<img width="1674" height="643" alt="image" src="https://github.com/user-attachments/assets/619b3e80-31c1-42ba-b988-a2571e5cea5a" />





## RESULT:
Thus, the Java program to reverse a given string was successfully written, executed and verified.

