import java.util.Scanner;

public class math {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.println("Please input integer 1.");
		int num1 = sc.nextInt();
		System.out.println("Please input integer 2.");
		int num2 = sc.nextInt();
		System.out.println("What math would you like to do?");
		String s = sc.next();
		
		if(s.toLowerCase().contains("add")) {
		System.out.println("The result is " + Addition(num1,num2));
		}
		else if(s.toLowerCase().contains("sub")) {
			System.out.println("The result is " + Subtraction(num1,num2));
			}
		else if(s.toLowerCase().contains("mult")) {
			System.out.println("The result is " + Multiplication(num1,num2));
			}
		else if(s.toLowerCase().contains("div")) {
			System.out.println("The result is " + Division(num1,num2));
		}
		else {
			System.out.println("Sorry! We do not understand your command.");
		}
		sc.close();
	}
	
	public static double Addition(int num1, int num2) {
		return 1;
	}
	public static double Subtraction(int num1, int num2) {
		return 2;
	}
	public static double Multiplication(int num1, int num2) {
		return 3;
	}
	public static double Division(int num1, int num2) {
		return 4;
	}
	
	}
