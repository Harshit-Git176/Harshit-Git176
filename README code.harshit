/* Write a java program thta takes an integer input from the user and calculate the factorial
of the number . Then write the method to calculate the sum of the digit of the faactorial. For example 
if the user enter s 5,
calculate 5!(120) and then find the sum of the digit (1+2+0=3).
*/
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int fact=1;
		int r;
		int sum=0;
		System.out.println("Enter the number");
		int number=sc.nextInt();
		for(int i=1;i<=number;i++)
		{
		    fact=fact*i;
		}
		System.out.println("The facotorial of  "+number+" is " +fact);
		System.out.println("The sum of the result of the factorial");
		while(fact!=0)
		{
		     r=fact%10;
		    sum=r+sum;
		    fact=fact/10;
		}
		System.out.println(sum);
		
	}
}
