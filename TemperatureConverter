import java.util.Scanner;

public class TemperatureConverter {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter the temperature value: ");
        double temperature = scanner.nextDouble();

        System.out.print("Enter the original unit (C, F, or K): ");
        char unit = scanner.next().toUpperCase().charAt(0);

        double celsius, fahrenheit, kelvin;

        switch (unit) {
            case 'C':
                celsius = temperature;
                fahrenheit = (temperature * 9.0 / 5.0) + 32.0;
                kelvin = temperature + 273.15;
                break;
            case 'F':
                fahrenheit = temperature;
                celsius = (temperature - 32.0) * 5.0 / 9.0;
                kelvin = (temperature - 32.0) * 5.0 / 9.0 + 273.15;
                break;
            case 'K':
                kelvin = temperature;
                celsius = temperature - 273.15;
                fahrenheit = (temperature - 273.15) * 9.0 / 5.0 + 32.0;
                break;
            default:
                System.out.println("Invalid unit. Please enter C, F, or K.");
                return;
        }

        System.out.println("Temperature in Celsius: " + celsius + "°C");
        System.out.println("Temperature in Fahrenheit: " + fahrenheit + "°F");
        System.out.println("Temperature in Kelvin: " + kelvin + "K");
    }
}
