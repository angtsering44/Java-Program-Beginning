import java.util.Scanner;

class A {
    public static void main(String args[]) {
        Scanner input = new Scanner(System.in);
        int a, b;
        System.out.println("Enter the first integer:");
        a = input.nextInt();
        System.out.println("Enter the second integer:");
        b = input.nextInt();

        if (a > b) {
            System.out.println("a is greatest: " + a);
        } else if (b > a) {
            System.out.println("b is greatest: " + b);
        } else {
            System.out.println("Both a and b are equal");
        }
        input.close(); // Close the Scanner object
    }
}
