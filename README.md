
# 📖 College Works

## 💻 About


Repository created with the purpose of practicing and showcasing small projects and activities from college and parallel courses. 

___

## {...} Java

Ex01 - Create a program that asks the user for a real number and displays half of the number entered on the screen. 

    import java.util.*;

    public class ex01 {

        public static void main(String[] args) {
            
            double n1, n2;
            
            Scanner input = new Scanner(System.in);
            
            System.out.print("Type a number: ");
            n1 = input.nextDouble();
            
            n2 = n1/2;

            System.out.println("\nThe half of: " + n1 + " is " + n2);
        }

    }

Ex02 - Read a number and display its successor and predecessor on the computer screen.

    import java.util.*;

    public class ex02 {

        public static void main(String[] args) {
            
            double n1, n2, n3;
            
            Scanner input = new Scanner(System.in);
            
            System.out.print("Type a number: ");
            n1 = input.nextDouble();
            
            n2 = n1+1;
            n3 = n1-1;
            
            System.out.println("\nThe predecessor is: " + n3 + " and the sucessor: " + n2);
        }

    }

Ex03 - Read two numbers and show their sum. Before the result, the message should appear: SUM:

    import java.util.*;

    public class ex03 {

        public static void main(String[] args) {
            
            double n1, n2, sum;
            
            Scanner input = new Scanner(System.in);
            
            System.out.print("Type a number: ");
            n1 = input.nextDouble();
            
            System.out.print("\nType another one: ");
            n2 = input.nextDouble();
            
            sum = n1+n2;
            
            System.out.print("\nThe sum between: " + n1 + " and " + n2 + "is: " + sum);
        }

    }

## </> Web






