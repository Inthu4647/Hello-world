# Hello-world
The first respiratory
#for python
#Begginers...
print("Hello My name is Inthu")
print("Welcome to python programming language")
//For java beginners
System.out.print("Hello world this is Inthu");

/*Program to check whether the given string is palindrome or not*/
import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
		String a;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter a string:");
		a=sc.nextLine();
		StringBuffer sb=new StringBuffer(a);
		sb.reverse();
		String b=sb.toString();
		if(a.equalsIgnoreCase(b))
		System.out.println("Given string is Palindrome");
		else
		System.out.println("Given string is not a Palindrome");	
	}
}
