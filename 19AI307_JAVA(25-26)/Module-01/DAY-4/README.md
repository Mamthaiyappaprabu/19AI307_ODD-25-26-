# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to Find the Average of Array Elements.


## AIM:
To write a Java program to read elements of an array and compute the average of the array elements.


## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the size of the array from the user.
4.	Create an integer array of the given size.
5.	Use a loop to read each element and add it to a running sum.
6.	Calculate the average using: average = sum / size.
7.	Display the average value.
8.	Stop the program.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: MAMTHA I
RegisterNumber:  212222230076
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
        int size=in.nextInt();
        int []arr=new int[size];
        int sum=0;
        for(int i=0;i<size;i++)
        {
            arr[i]=in.nextInt();
            sum=sum+arr[i];
        }
        double avg=(double)sum/size;
        System.out.printf("The average of elements is %.2f", avg);
    
    }
}
```







## OUTPUT:

<img width="1483" height="897" alt="image" src="https://github.com/user-attachments/assets/01d19b5b-ece6-4fe5-911a-ac68beb5d9d7" />


## RESULT:
Thus, the Java program to find the average of array elements was successfully executed and the output was verified.

