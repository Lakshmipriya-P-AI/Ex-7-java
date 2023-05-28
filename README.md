# EXP-7 -> INSERT THE ARRAY INTO THE ELEMENT
## AIM:
To write the java program to insert an element into array

## SOFTWARE REQUIRED :
IntelliJ IDEA COMMUNITY EDITION

## ALGORITHM:
Create the class and declare the main method so that the JVM will identify the main program to run.
.Declare an array and accept the input from user.
To accept the inputs from user import Scanner and get the input and store them.
Inside for loop use SCANEER to accept the elements of array
.Print the output using for loop and SYSTEM.OUT.PRINT
The program will be executed after the compilation and results are printed.

## PROGRAM:
```
import java.util.Scanner;
public class Array {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int n= sc.nextInt();
        int[] arr =new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        System.out.print("Array elements are: ");
        for(int i=0;i<n;i++){
            System.out.print(arr[i]+" ");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/Lakshmipriya-P-AI/Ex-7-java/assets/93427923/0ff9fb6e-6d83-459d-bc77-258c39236a3a)


## RESULT:
Thus The Program is complie successfully.
