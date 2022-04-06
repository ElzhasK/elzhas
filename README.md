# elzhas
just me

import java.util.*;
import java.io.*;
public class elzhas{
    public static void main(String args[]) {
     	System.out.println(max(10, 20));
     	System.out.println(max(25.0, 40.0));
     	print();
    }

    public static int sum(int a, int b){
    	int count = 0;

    	for(int i = a; i <= b; i++)
    		count += i;

    	return count;
    }

    public static int max(int x, int y){
    	System.out.println("Max called as Integer");
    	if(x > y)
    		return x;
    	else
    		return y;
    }

    public static double max(double x, double y){
    	System.out.println("Max called as Double");
    	if(x > y)
    		return x;
    	else
    		return y;
    }

    public static void print(){
    	System.out.print("Welcome to SDU");
    }
}




        
		
