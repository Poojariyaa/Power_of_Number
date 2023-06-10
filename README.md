# Power_of_Number
# Java-Experiment-6

# Method Creation

# Aim:

        To write a Java program to create a method to calculate power of a number raised to other.

# Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class called "Power" and create a method.

Step 3 : Create a main class,called the "Solution".

Step 4 : Calll the method from the Power class in Solution.

Step 5 : Display the result using Solution Class in the terminal.

# Program
~~~
import java.util.Scanner;
class Power {
public static void main(String[] args) {
int base , powerRaised;
Scanner s =new Scanner(System.in);
System.out.println("Enter the Base value:");
base=s.nextInt();
System.out.println("Enter the value of power:");
powerRaised=s.nextInt();
int result = power(base, powerRaised);
System.out.println(base + "^" + powerRaised + "=" + result);
}
public static int power(int base, int powerRaised) {
if (powerRaised != 0) {
// recursive call to power()
return (base * power(base, powerRaised - 1));
}
else {
return 1;
}
}
}
~~~
# Output

![image](https://github.com/Poojariyaa/Power_of_Number/assets/127511817/b21fdacb-acb9-403b-bc23-2bd0ae4c1701)

# Result

     We have successfully created a Java program to calculate power of a number raised to other using method
