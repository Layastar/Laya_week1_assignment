Laya Gollamandala

1.Write a program to perform basic arithmetic
   operations (addition, subtraction, multiplication,
   division).


Program:


class arithmaticOperations 
{
	public static void main(String[] args) 
	{
		int a=3;
		int b=7;
		System.out.println("Addition = "+ (a+b));
		System.out.println("Subtraction = "+(a-b));
		System.out.println("Multiplication "+(a*b));
		System.out.println("Division = "+(a/b));
	}
}
Output:
Addition = 10
Subtraction = -4
Multiplication 21
Division = 0

2.Create a program that takes user input and
   checks if the number is even or odd.

Program:

import java.util.Scanner;
class evenOdd
{
	public static void main(String[] args) 
	{
		Scanner b=new Scanner(System.in);
		System.out.println("Number : ");
    int a=b.nextInt();
		if(a%2 == 0)
		{
			System.out.println("The given number is Even");
		}
		else
		{
			System.out.println("The number is odd");
		}
	}
}
Output:
Number :
17
17 is Odd Number

3.Implement a simple calculator using switch-
   case statements.

Program:

import java.util.Scanner;
class calculator 
{
	public static void main(String[] args) 
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter first number :");
		int a= sc.nextInt();
		System.out.println("Enter second number :");
		int b= sc.nextInt();
		System.out.println("Enter an operator + , - , * , / : ");
		char c= sc.next().charAt(0);
		sc.close();
		double output;
		switch(c)
		{
			case'+': 
				output =  a + b;
				break;
			case'-':
				output = a - b;
				break;
			case'*':
				output = a * b;
				break;
			case'/':
				output = a / b;
				break;
			default:
				System.out.println("Invalid "); 
				return;
		}
		System.out.println(a+" "+c+" "+b+" = "+output);
	}
}

Output:
Enter first number :
14
Enter second number :
12
Enter an operator + , - , * , / :
*
14 * 12 = 168.0

