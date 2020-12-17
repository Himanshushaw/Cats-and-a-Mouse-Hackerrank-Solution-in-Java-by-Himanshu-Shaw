# Cats-and-a-Mouse-Hackerrank-Solution-in-Java-by-Himanshu-Shaw
Cats and a Mouse Hackerrank Solution in Java By Himanshu Shaw. 

import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
       // System.out.println("Enter queries");
        int x,y,z;

        int q=sc.nextInt();
       // System.out.println("enter x, y,z");
        for (int i=0;i<q;i++){
            x=sc.nextInt();
            y=sc.nextInt();
            z=sc.nextInt();
            int c1=Math.abs(z-x);
            int c2=Math.abs(z-y);

            if (c1<c2){

                System.out.println("Cat A");
            }else
                if (c2<c1){
                    System.out.println("Cat B");

                }else
                    if (c1==c2){

                        System.out.println("Mouse C");
                    }
            //System.out.println(r);
        }

    }
}
