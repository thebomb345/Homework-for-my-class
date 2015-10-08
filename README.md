# Homework-for-my-class

import java.util.Scanner;


public class C4 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub



		// Variables
		Scanner input = new Scanner(System.in);
		Scanner input2 = new Scanner(System.in);
		System.out.print("what color is your hair:");
		String name 
		;
		name = input.next();





		System.out.print("if you hair is long type 1 if it is short type 2:");
		String FAIL 
		;
		FAIL = input.next();
		
	



		if (name.equalsIgnoreCase("red") ) {

			System.out.println("You have red hair.");
		}
		if (name.equalsIgnoreCase("black") ) {

			System.out.println("You have dark hair");
		}

		else if (name.equalsIgnoreCase("blonde") ) {

			System.out.println("You have light hair");
			if (FAIL.equalsIgnoreCase("2")) {
				System.out.println("you have short hair");
			}
			


		else if (name.equalsIgnoreCase("blonde") ) {

			System.out.println("You have dark hair");
		
		if (FAIL.equalsIgnoreCase("2")) {
			System.out.println("you have short hair");
		}


		else if (name.equalsIgnoreCase("blonde") ) {

			System.out.println("You have dark hair");
		}
		}




	}

}
