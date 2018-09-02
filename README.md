# how-is-my-grade-
Find the grade based on your point from 0 to 100
package mainpackagedemo;

import java.util.Scanner;

public class SimpleIf {
	
	static Scanner reader=new Scanner(System.in);
	static Scanner reader1=new Scanner(System.in);
	public static void main(String[] args)	
	{
		System.out.print("Sa quheni ?!");
		String emri=reader.nextLine();
		
		System.out.print("Mbiemri?");
		String mbiemri=reader1.nextLine();
		
		System.out.print("Sa eshte nota juaj?");
		int nota=reader.nextInt();
		
		
		if(nota>=90)
		{
			System.out.println(emri + " " + mbiemri + " Ti ke 10!");
		}
		else if ((nota>=80) && (nota<90)) 
		{
			System.out.println(emri + " " + mbiemri + " Ti ke 9!");
		}
		else if ((nota>=70) && (nota<80))
		{
			System.out.println(emri + " " + mbiemri + " i ke 8!");
		}
		else if ((nota>=60) && (nota<70))
		{
			System.out.println(emri + " " + mbiemri + " Ti ke 7!");
		}
		else if ((nota>=50) && (nota<60))
		{
			System.out.println(emri + " " + mbiemri + " Ti ke 6!");
		}
		else {
			System.out.println(emri + " " + mbiemri + " Ti ke deshtuar!");
		}
	}
}
