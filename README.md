# Studentcalculator
package com.springcore.Dsa;
import java.util.Scanner;

public class Studentgradesystem {
	public static void main(String[] args) {
		 
		 
		 Scanner s1=new Scanner(System.in);
   														 System.out.println("Marks obtained out of 100");
		 System.out.println("Enter the marks obtained in chemistry ");
		 int chem=s1.nextInt();
		 
		 System.out.println("Enter marks obtained in physics ");
		 int phy=s1.nextInt();
		 
		 System.out.println("Enter  marks obtained in mathematics ");
		 int maths=s1.nextInt();
		 
		 System.out.println("Enter marks obtained in computer science ");
		 int comsci=s1.nextInt();
		 
		 int totalmarks=phy+chem+maths+comsci;
		 float percentage=totalmarks/4;
		 
		 System.out.println(" total marks obtained are "   + totalmarks);
		 System.out.println("percentage obtained is "      +percentage);
		 
		 
		 if(percentage>=91&& percentage<=100) {
			 System.out.println("grade=A");
			 
		 }
		 if(percentage>=81&&percentage<=90) {
			 System.out.println("grade=B");
			 		
		 }
		 if(percentage>=71&&percentage<=80) {
			 System.out.println("grade=C");
			 
		 }
		 if(percentage>=61&&percentage<=70) {
			 System.out.println("grade=D");
		 }
		 else if(percentage<=60){
			 System.out.println("fail");
		 }
		 
		}
}
