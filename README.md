# basic-operation
assign
/*
 * A simple calculator to help user perform the basic operations (+ - * /
 */

import java.util.Scanner;

public class calculator {
    public static void main(String [] arguments) {
    	int operator , n1, n2;
    	System.out.print("1-add \n 2-subtract \n 3-multiply \n 4-divide");
    	System.out.print("Choose operator:");
    	Scanner Sc=new Scanner(System.in);
    	operator = Sc. nextInt();
    	System.out.print("Enter first number:");
    	n1= Sc.nextInt();
    	System.out.print("Enter second number:");
    	n2= Sc.nextInt();
    	
    	int results=0;
    	switch(operator) {
    	case 1:
    		results=n1+n2;
    		break;
    		
    	case 2:
    		results=n1-n2;
    		break;
    		
    	case 3:
    		results=n1*n2;
    		break;
    		
    	case 4:
    		results=n1/n2;
    		break;
    		
    		default:
    			System.out.print("Entered operator is not valid");
    	}
    	     System.out.print("Results is:" + results );
    }
}
