# hexadecimal-input
Write a java program to take input as hexadecimal number and print output in decimal.

import java.util.*;

public class UseRadix {

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        
        sc.useRadix(16);
        
        int a;
        a = sc.nextInt();
        System.out.println(a);
    }
    
}
