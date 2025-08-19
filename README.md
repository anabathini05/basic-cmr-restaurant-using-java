# basic-cmr-restaurant-using-java
this is my first repository
//program to build a restaurant
import java.util.*;
public class Main
{
	public static void main(String[] args) {
		System.out.println("Welcome to cmr restaurant");
			System.out.println("hi, please enter your name:");
			Scanner sc = new Scanner(System.in);
			String str = sc.nextLine();
			System.out.println("hey "+str+ " what do u like to have?");
			System.out.println("1.dal fry-40");
			System.out.println("2.panner butter masala-100");
			System.out.println("3.chicken curry-120");
			System.out.println("4.fish fry-100");
			System.out.println("5.tomato curry-30");
			System.out.println("select from the menu!");
			int n = sc.nextInt();
			switch(n)
			{
			    case 1:
			        System.out.println("please enter the quantity");
			    int q=sc.nextInt();
			    System.out.println("you have selected dal fry please pay " +(q*40));
			    int p=sc.nextInt();
			    if(p==(q*40))
			    {
			        System.out.println("order placed please wait");
			    }
			    else
			    {
			        System.out.println("invalid");
			    }
			    break;
			    case 2: System.out.println("please enter the quantity");
			    int a=sc.nextInt();
			    System.out.println("you have selected panner butter masala please pay " +(a*100));
			    int b=sc.nextInt();
			    if(b==(a*100))
			    {
			        System.out.println("order placed please wait");
			    }
			    else{
			        System.out.println("invalid");
			    }
			    break;
			    case 3: System.out.println("please enter the quantity");
			    int c=sc.nextInt();
			    System.out.println("you have selected chicken curry please pay " +(c*120));
			    int d=sc.nextInt();
			    if(d==(c*120))
			    {
			        System.out.println("order placed please wait");
			    }
			    else{
			        System.out.println("invalid");
			    }
			    break;
			    case 4: System.out.println("please enter the quantity");
			    int e=sc.nextInt();
			    System.out.println("you have selected fish fry please pay " +(e*100));
			    int f=sc.nextInt();
			    if(f==(e*100))
			    {
			        System.out.println("order placed please wait");
			    }
			    else{
			        System.out.println("invalid");
			    }
			    break;
			    case 5: System.out.println("please enter the quantity");
			    int g=sc.nextInt();
			    System.out.println("you have selected tomato curry please pay " +(g*100));
			    int h=sc.nextInt();
			    if(h==(g*100))
			    {
			        System.out.println("order placed please wait");
			    }
			    else{
			        System.out.println("invalid");
			    }
			    break;
			    default:
			    System.out.println("invalid");
			}
	}
}
