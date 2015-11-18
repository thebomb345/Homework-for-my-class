
import java.util.Scanner;



public class Text_based_game {



	public static void main(String[] args){

		System.out.print("Welcome to D & D ");
		Scanner input = new Scanner(System.in);
		String color  
		;

		main();
		subclass();
		Worldgen();
		Worldgen2();
		World();



	}

	private static void main() {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);
		String color;


		System.out.print("What class are you? Magic-User, Fighter, Thief: ");
		color = input.next();


		if ( color.equals("Thief") ) {

			System.out.println("You are a Thief.");
		}
		else if ( color.equalsIgnoreCase("Fighter") ){

			System.out.println("You are a strong Fighter.");
		}

		else if ( color.equalsIgnoreCase("Magic-User") ) {

			System.out.println("You are a strong Mage.");
		}
	}

	private static void subclass() {
		// TODO Auto-generated method stub
		Scanner input = new Scanner(System.in);

		String color;


		System.out.print("What class is player 2? Magic-User, Fighter, Thief:");
		color = input.next();


		if ( color.equals("Thief") ) {

			System.out.println("You are a Thief.");
		}
		else if ( color.equalsIgnoreCase("Fighter") ){

			System.out.println("You are a strong Fighter.");
		}

		else if ( color.equalsIgnoreCase("Magic-User") ) {

			System.out.println("You are a strong Mage.");
		}
	}

	private static void Worldgen() {

		Scanner input = new Scanner(System.in);

		String color;


		System.out.print("What race are you player 1? Human, Elf, Dwarf, Halfling, Gnome, Half-Orc");
		color = input.next();


		if ( color.equals("Human") ) {

			System.out.println("You are a Human.");
		}
		else if ( color.equalsIgnoreCase("Elf") ){

			System.out.println("You are a strong Elf.");
		}

		else if ( color.equalsIgnoreCase("Dwarf") ) {

			System.out.println("You are a Dwarf.");
		}

		else if ( color.equalsIgnoreCase("Halfling") ) {

			System.out.println("You are a Halfling.");
		}

		else if ( color.equalsIgnoreCase("Gnome") ) {

			System.out.println("You are a Gnome.");
		}
		else if ( color.equalsIgnoreCase("Half-Orc") ) {

			System.out.println("You are a Half-Orc.");
		}

	}


	public static void Worldgen2(){


		Scanner input = new Scanner(System.in);

		String color;


		System.out.print("What race are you player 2? Human, Elf, Dwarf, Halfling, Gnome, Half-Orc");
		color = input.next();


		if ( color.equals("Human") ) {

			System.out.println("You are a Human.");
		}
		else if ( color.equalsIgnoreCase("Elf") ){

			System.out.println("You are a strong Elf.");
		}

		else if ( color.equalsIgnoreCase("Dwarf") ) {

			System.out.println("You are a Dwarf.");
		}

		else if ( color.equalsIgnoreCase("Halfling") ) {

			System.out.println("You are a Halfling.");
		}

		else if ( color.equalsIgnoreCase("Gnome") ) {

			System.out.println("You are a Gnome.");
		}
		else if ( color.equalsIgnoreCase("Half-Orc") ) {

			System.out.println("You are a Half-Orc.");

		}


	}


	public static void World(){
		Scanner input = new Scanner(System.in);

		String color;		

		System.out.println("You enter a room.");
		System.out.println("A goblin is there");
		System.out.println("What do you do?");
		System.out.print("Slay it, Bribe it, or run from it");
		color = input.next();


		if ( color.equalsIgnoreCase("Slay it"));{

			System.out.println("You slayed the goblin");
		}


		else if( color.equalsIgnoreCase("Bribe it") ) {

			System.out.println("The bribe succeded.");

		}
		
		 
		 else if ( color.equalsIgnoreCase("Run from it") ) {

				System.out.println("You ran away you p*ssy!");

		
			}
			
		}





	}


































