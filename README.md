# pattern
pattern sample
package com.java.test1;

import java.util.Scanner;

public class Pattern {

	
	public static void main(String[] args) {
	//	Pattern p=new Pattern();
		/*Scanner scan=new Scanner(System.in);
		System.out.println("enter no to print pattrn");
		int a=scan.nextInt();*/
		for(int i=4;i>0;i--){
			for(int j=0;j<i;j++){
				System.out.print("*");
			}
			System.out.println("");
		}
	}

}
