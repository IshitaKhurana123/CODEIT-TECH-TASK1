# CODEIT-TECH-TASK1
import java.util.Scanner;
public class Calculator
{
  public static void main(String[] args) 
  {
      double num1;
      double num2;
      double sol;
      char operator;
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter two numbers: ");
      num1 = sc.nextDouble();
      num2 = sc.nextDouble();
      System.out.println("Enter an operator (+, -, *, /): ");
      operator = sc.next().charAt(0);
      switch(operator) 
      {
         case '+': sol = num1 + num2;
            break;
         case '-': sol = num1 - num2;
            break;
         case '*': sol = num1 * num2;
            break;
         case '/': sol = num1 / num2;
            break;
      default: System.out.println(" Enter operator from above mentioned");
         return;
      }
      System.out.println("The sol is:");
      System.out.println(num1 + " " + operator + " " + num2 + " = " + sol);
   }
}
