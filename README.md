# Exercises-Java

Ðåñóðñ w3resource (Java Basic Part I)

1. Write a Java program to print 'Hello' on screen and then print your name on a separate line. 
Expected Output :
Hello
Alexandra Abramov
Solution:
public class Main {
  public static void main(String[] args) {
  System.out.println("Hello!");
  System.out.println("Yuriy Savchuk");
 }
}

2. Write a Java program to print the sum of two numbers.
Test Data:
74 + 36
Expected Output :
110
Solution:
public class Main {
  public static void main(String[] args) {
  int a = 74, b = 36;
  System.out.println(a + b);
 }
}

3. Write a Java program to divide two numbers and print on the screen.
Test Data :
50/3
Expected Output :
16
Solution:
public class Main {
  public static void main(String[] args) {
  int a = 50, b = 3;
  System.out.print(a / b);
 }
}

4.  Write a Java program to print the result of the following operations
Test Data:
a. -5 + 8 * 6
b. (55+9) % 9
c. 20 + -3*5 / 8
d. 5 + 15 / 3 * 2 - 8 % 3
Expected Output :
43
1
19
13
Solution:
public class Main {
  public static void main(String[] args) {
  System.out.println(-5 + (8 * 6));
  System.out.println((55+9) % 9);
  System.out.println(20 + ((-3*5) / 8));
  System.out.println(5 + (15 / 3 * 2) - 8 % 3);
 }
}

5. Write a Java program that takes two numbers as input and display the product of two numbers. 
Test Data:
Input first number: 25
Input second number: 5
Expected Output :
25 x 5 = 125
Solution:
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
  Scanner scan = new Scanner(System.in);
  System.out.println("Input first number: ");
  int a = scan.nextInt();
  System.out.println("Input second number: ");
        int b = scan.nextInt();
        int pr = a * b;
System.out.println(a  + " * " + b + " = " +  pr);
 }
}

6. Write a Java program to print the sum (addition), multiply, subtract, divide and remainder of two numbers. 
Test Data:
Input first number: 125
Input second number: 24
Expected Output :
125 + 24 = 149
125 - 24 = 101
125 x 24 = 3000
125 / 24 = 5
125 mod 24 = 5
Solution:
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
  Scanner scan = new Scanner(System.in);
  System.out.println("Input first number: ");
  int a = scan.nextInt();
  System.out.println("Input second number: ");
        int b = scan.nextInt();
        int sum = a + b;
        int sub = a - b;
        int pr = a * b;
        int div = a / b;
        int mod = a % b;
        System.out.println(a  + " + " + b + " = " +  sum);
        System.out.println(a  + " - " + b + " = " +  sub);
        System.out.println(a  + " * " + b + " = " +  pr);
        System.out.println(a  + " / " + b + " = " +  div);
        System.out.println(a  + " mod " + b + " = " +  mod);
 }
}

7. Write a Java program that takes a number as input and prints its multiplication table upto 10. 
Test Data:
Input a number: 8
Expected Output :
8 x 1 = 8
8 x 2 = 16
8 x 3 = 24
...
8 x 10 = 80
Solution:
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    Scanner scan = new Scanner(System.in);
    System.out.print("Input a number: ");
    int n = scan.nextInt();
    int i, result;
    for(i = 1; i<=10; i++) {
      result = n * i;
     System.out.println(n + " * " + i + " = " + result);
    }
 }
}

8. Write a Java program to display the following pattern. 
Sample Pattern :
   J    a   v     v  a                                                  
   J   a a   v   v  a a                                                 
J  J  aaaaa   V V  aaaaa                                                
 JJ  a     a   V  a     a
Solution:
public class Main {
  public static void main(String[] args) {
    System.out.println("   J    a   v     v  a");
    System.out.println("   J   a a   v   v  a a ");
    System.out.println("J  J  aaaaa   V V  aaaaa ");
    System.out.println(" JJ  a     a   V  a     a");
    }
 }

9. Write a Java program to compute the specified expressions and print the output.
Test Data:
((25.5 * 3.5 - 3.5 * 3.5) / (40.5 - 4.5))
Expected Output
2.138888888888889
Solution:
public class Main {
  public static void main(String[] args) {
  double result = ((25.5 * 3.5 - 3.5 * 3.5) / (40.5 - 4.5));
  System.out.println(result);
    }
 }

10. Write a Java program to compute a specified formula. 
Specified Formula :
4.0 * (1 - (1.0/3) + (1.0/5) - (1.0/7) + (1.0/9) - (1.0/11))
Expected Output
2.9760461760461765
Solution:
public class Main {
  public static void main(String[] args) {
  double result = 4.0 * (1 - (1.0/3) + (1.0/5) - (1.0/7) + (1.0/9) - (1.0/11));
  System.out.println(result);
    }
 }
