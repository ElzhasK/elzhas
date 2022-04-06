# elzhas
just me

import java.util.*;
import java.io.*;
public class elzhas{
    public static void main(String args[]) {
    	//System.out.println(sum(1, 10));
     	System.out.println(max(10, 20));
     	System.out.println(max(25.0, 40.0));
     	print();
    }

    public static int sum(int a, int b){
    	int axx = 0;

    	for(int i = a; i <= b; i++)
    		axx += i;

    	return axx;
    }

    public static int max(int a, int b){
    	System.out.println("Max called as Integer");
    	if(a > b)
    		return a;
    	else
    		return b;
    }

    public static double max(double a, double b){
    	System.out.println("Max called as Double");
    	if(a > b)
    		return a;
    	else
    		return b;
    }

    public static void print(){
    	System.out.println("Welcome to SDU");
    }
}
