# DO-LOOP-PROGRAM
package doloop;
import java.util.Scanner;
public class DoLoop {
    public static void main(String[] args) {
        // TODO code application logic here
        int i =1;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the stoping num:");
        int n = sc.nextInt();
        do{
            System.out.println(i);
            i++;        }
        while (i<=n);
    }
    
}
o/p
run:
Enter the stoping num:
5
1
2
3
4
5
BUILD SUCCESSFUL (total time: 5 seconds)

