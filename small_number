import java.util.Scanner;

public class SmallArray {
	public static void main(String[] args) {
	
		Scanner ask = new Scanner(System.in);
		int[] numbers = new int[5];
		
		for(int number: numbers) {
			System.out.print("Type a number: ");
			number = ask.nextInt();
		}
		
		int smallest = numbers[0];
		
		for(int i = 0; i < numbers.length; i++) {
			if(numbers[i] < smallest) {
				smallest = numbers[i];
			}
		}
		
		System.out.println("The samallest number is: " + smallest);
		
	}
}
