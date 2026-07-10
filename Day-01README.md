# Day 01

## Problem Name
##Java Stdin and Stdout I
import java.util.Scanner;

public class Solution {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int a = sc.nextInt();
        int b = sc.nextInt();
        int c = sc.nextInt();

        System.out.println(a);
        System.out.println(b);
        System.out.println(c);

        sc.close();
    }
}
## Problem Name
##Print Squares
public class Main {
    public static void main(String[] args) {
        for(int i = 1; i <= 5; i++) {
            System.out.println(i + " - " + (i * i));
        }
    }
}
