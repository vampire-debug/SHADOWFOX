import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        while (true) {
            System.out.println("Select operation:");
            System.out.println("1. Addition");
            System.out.println("2. Subtraction");
            System.out.println("3. Multiplication");
            System.out.println("4. Division");
            System.out.println("5. Square Root");
            System.out.println("6. Exponentiation");
            System.out.println("7. Temperature Conversion");
            System.out.println("8. Currency Conversion");
            System.out.println("9. Exit");
            int choice = scanner.nextInt();
            if (choice == 9) break;
            performOperation(choice, scanner);
        }
        scanner.close();
    }

    private static void performOperation(int choice, Scanner scanner) {
        switch (choice) {
            case 1:
                System.out.println("Enter two numbers:");
                double a1 = scanner.nextDouble();
                double b1 = scanner.nextDouble();
                System.out.println("Result: " + (a1 + b1));
                break;
            case 2:
                System.out.println("Enter two numbers:");
                double a2 = scanner.nextDouble();
                double b2 = scanner.nextDouble();
                System.out.println("Result: " + (a2 - b2));
                break;
            case 3:
                System.out.println("Enter two numbers:");
                double a3 = scanner.nextDouble();
                double b3 = scanner.nextDouble();
                System.out.println("Result: " + (a3 * b3));
                break;
            case 4:
                System.out.println("Enter two numbers:");
                double a4 = scanner.nextDouble();
                double b4 = scanner.nextDouble();
                if (b4 != 0) {
                    System.out.println("Result: " + (a4 / b4));
                } else {
                    System.out.println("Error: Division by zero");
                }
                break;
            case 5:
                System.out.println("Enter a number:");
                double a5 = scanner.nextDouble();
                System.out.println("Result: " + Math.sqrt(a5));
                break;
            case 6:
                System.out.println("Enter base and exponent:");
                double base = scanner.nextDouble();
                double exponent = scanner.nextDouble();
                System.out.println("Result: " + Math.pow(base, exponent));
                break;
            case 7:
                System.out.println("Select conversion:");
                System.out.println("1. Celsius to Fahrenheit");
                System.out.println("2. Fahrenheit to Celsius");
                int tempChoice = scanner.nextInt();
                System.out.println("Enter temperature:");
                double temp = scanner.nextDouble();
                if (tempChoice == 1) {
                    System.out.println("Result: " + (temp * 9/5 + 32) + " °F");
                } else {
                    System.out.println("Result: " + ((temp - 32) * 5/9) + " °C");
                }
                break;
            case 8:
                System.out.println("Enter amount in USD:");
                double usd = scanner.nextDouble();
                double inr = usd * 74.85; // Example conversion rate
                System.out.println("Result: " + inr + " INR");
                break;
            default:
                System.out.println("Invalid choice");
        }
    }
}
