# Hackerrank-Java4-Java-Stdin-and-Stdout-II
Problem 4 of HackerRank - Java Stdin and Stdout II

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
    
        int i = scan.nextInt();
        double d = scan.nextDouble();
        scan.nextLine();//To clear buffer
        String s= scan.nextLine();
           
        System.out.println("String: " + s);
        System.out.println("Double: " + d);
        System.out.println("Int: " + i);
    }
}
