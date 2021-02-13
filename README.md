# homework3part2
positive and negative
import java.util.Scanner; // Import the Scanner class


public class Java1 {
	
	private static void signCheck () {
		Scanner keyboard = new Scanner (System.in);
		System.out.println("enter a number");
		int answer = keyboard.nextInt();
		if(answer>0){
				 System.out.println("positive number");
		}
		else if(answer<0) {
			System.out.println("negative number");
			

		}
		else { 
			System.out.println("0"); 
		
		}
		
		}
	
	
	
	public static void main(String[] args) { 
		
	signCheck();
		
	}
		
	}


		



