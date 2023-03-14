# CheckingPrimeNumber
package mypackage;
import java.util.Scanner;
public class PrimeNumber {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
  System.out.println("Enter Number:");
   Scanner sc=new Scanner(System.in);
    int n=sc.nextInt();
    boolean Isprime=true;
    for(int i=2;i<=n;i++) {
    	if(n%i!=0) {
    		Isprime=false;
    		System.out.println("this is a prime number");
    		break;}
    }
    		if(n!=1) {
    			
    		if(n%n==0) {
    			System.out.println("This is a prime number:");
    			
    		}
    		else {
    			System.out.println("This is a not a prime Number:");
    		}
    			
    		}else {
    			System.out.println("Number not composition This Is a neight prime n");
    		
    
    	}
    		sc.close();
    		
    }
    
    
	}


