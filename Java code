package Game;  //Project
import java.util.Random;
import java.util.Scanner;

public class guess {

	    public static void main(String[] args) {

	        Random rand = new Random();
	        Scanner sc = new Scanner(System.in);

	        // Random number between 1 to 100
	        int randomNumber = rand.nextInt(100) + 1;

	        int guess;
	        int attempts = 5;

	        System.out.println("=== Number Guessing Game ===");
	        System.out.println("Guess a number between 1 to 100");
	        System.out.println("You have 5 attempts");

	        // Loop for attempts
	        for (int i = 1; i <= attempts; i++) {

	            System.out.print("Enter your guess: ");
	            guess = sc.nextInt();

	            // Check guess
	            if (guess == randomNumber) {
	                System.out.println("Correct! You guessed the number.");
	                break;
	            } 
	            else if (guess > randomNumber) {
	                System.out.println("Lower");
	            } 
	            else {
	                System.out.println("Higher!");
	            }

	            // Last attempt message
	            if (i == attempts) {
	                System.out.println("Game Over!");
	                System.out.println("The correct number was: " + randomNumber);
	            }
	        }

	        sc.close();
	    }
	
	
}
