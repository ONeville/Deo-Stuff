// Excercise C

import java.util.Scanner;

public class Main
{
	public static void main(String[] args) {
	    // For 8 Students score in 3 tests
		int scores[][] = new int[8][3];
		
		for(int i = 0; i < 8; i++){
    		    System.out.println("Enter score for Student: " + (i + 1));
		    for(int j =0; j < 3; j++){
		        // CAPTURE
    		    System.out.println("Enter score for Test: " + (j + 1));
    		    Scanner scan = new Scanner(System.in);
    		    
    		    // STORE
    		    scores[i][j] = scan.nextInt();
		    }
		}
		
		// DISPLAY
		for (int i = 0; i < 8; i++) {
            System.out.println("The score for student :" + (i + 1));
		    for(int j=0; j < 3; j++){
                System.out.println(" on Test: " + j + " = " + scores[i][j]);
                System.out.println("");
		    }
        }
	}
}
