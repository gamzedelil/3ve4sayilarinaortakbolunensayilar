# 3ve4sayilarinaortakbolunensayilar

package forloop;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		Scanner inp = new Scanner(System.in);
		
		int k,sum = 0 ,average,common = 0;
		
		System.out.println("Enter the number:");
		k = inp.nextInt();
		
		for (int i = 0 ; i<= k ; i++) {
			if (k % 3 == 0 && k % 4 == 0) {
				common++;
				sum+=i;
				
				System.out.println(i);
			}
		
		}
		
		average = sum / common;
		System.out.println("Average: "+average);		

	}

}
