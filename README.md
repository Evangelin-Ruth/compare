# EXP-2 Java program to compare two numbers
# AIM:
To compare two numbers in java
# PROCEDURE:
## Step 1:
## Step2:
## Step 3:
## Step 4:
## Step 5:

# PROGRAM:
```
import java.util.Scanner;
public class compare {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        if(a==b)
        {
            System.out.println(a+"=="+b);
        }
        else if(a>b)
        {
            System.out.println(a+">"+b);
        }
        else if(a<b)
        {
            System.out.println(a+"<"+b);
        }
        else {
            System.out.println(a+"!="+b);
        }
    }
}
```
# OUTPUT:
![image](https://github.com/Evangelin-Ruth/compare/assets/94219798/0f5d587c-95b2-46e7-93b1-11c2affdabd1)
