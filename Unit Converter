import java.util.Scanner;

public class UnitConverter {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        boolean keepRunning = true;

        while (keepRunning) {
            System.out.println("\n==== Unit Converter ====");
            System.out.println("1. Meters to Feet");
            System.out.println("2. Feet to Meters");
            System.out.println("3. Kilograms to Pounds");
            System.out.println("4. Pounds to Kilograms");
            System.out.println("5. Celsius to Fahrenheit");
            System.out.println("6. Fahrenheit to Celsius");
            System.out.println("7. Exit");
            System.out.print("Choose an option (1-7): ");

            int choice = scanner.nextInt();

            switch (choice) {
                case 1:
                    System.out.print("Enter meters: ");
                    double meters = scanner.nextDouble();
                    System.out.println(meters + " meters = " + (meters * 3.28084) + " feet");
                    break;
                case 2:
                    System.out.print("Enter feet: ");
                    double feet = scanner.nextDouble();
                    System.out.println(feet + " feet = " + (feet / 3.28084) + " meters");
                    break;
                case 3:
                    System.out.print("Enter kilograms: ");
                    double kg = scanner.nextDouble();
                    System.out.println(kg + " kg = " + (kg * 2.20462) + " pounds");
                    break;
                case 4:
                    System.out.print("Enter pounds: ");
                    double pounds = scanner.nextDouble();
                    System.out.println(pounds + " pounds = " + (pounds / 2.20462) + " kilograms");
                    break;
                case 5:
                    System.out.print("Enter Celsius: ");
                    double celsius = scanner.nextDouble();
                    System.out.println(celsius + " °C = " + ((celsius * 9/5) + 32) + " °F");
                    break;
                case 6:
                    System.out.print("Enter Fahrenheit: ");
                    double fahrenheit = scanner.nextDouble();
                    System.out.println(fahrenheit + " °F = " + ((fahrenheit - 32) * 5/9) + " °C");
                    break;
                case 7:
                    keepRunning = false;
                    System.out.println("Exiting the converter. Goodbye!");
                    break;
                default:
                    System.out.println("Invalid choice. Please select a valid option.");
            }
        }

        scanner.close();
    }
}
