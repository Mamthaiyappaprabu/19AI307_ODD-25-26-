# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
In a haunted house, lights turn on or off based on the hour of entry:

If the hour is even and between 2 and 6 (inclusive), lights flicker.

If the hour is odd and between 7 and 11, lights stay off.

If the hour is 12, lights turn red.

Otherwise, the house is dark.


## AIM:
To write a Java program that implements conditional statements to determine light behavior in a haunted house based on the hour of entry.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the hour as input from the user.
4.	Check if the hour is even and between 2 and 6 → print "Lights flicker".
5.	Else if the hour is odd and between 7 and 11 → print "Lights stay off".
6.	Else if the hour is 12 → print "Lights turn red".
7.	Otherwise → print "House is dark".
8.	End the program.




## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
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
        int num=in.nextInt();
        if(num%2==0 && (num >=2 && num<=6))
        {
           System.out.println("Lights flicker");
        }
        else if(num%2!=0 && num >= 7 && num<=11)
        {
            System.out.println("Lights off");
        }
        else if(num==12)
        {
           System.out.println("Lights red"); 
        }
        else
        {
            System.out.println("Dark house");
        }
    }
}
```







## OUTPUT:
<img width="1034" height="663" alt="image" src="https://github.com/user-attachments/assets/70ccd82b-7cba-4fe9-9a89-ed92168de18d" />




## RESULT:
Thus, the Java program using conditional statements for the haunted house lighting scenario was successfully executed.

