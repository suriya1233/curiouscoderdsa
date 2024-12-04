import java.util.Scanner;

public class InputAndPrint {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user for an integer
        System.out.print("Enter an integer: ");
        int number = scanner.nextInt();
        scanner.nextLine(); // Consume the leftover newline character

        // Prompt the user for a string
        System.out.print("Enter a string: ");
        String text = scanner.nextLine();

        // Prompt the user for a character
        System.out.print("Enter a character: ");
        char character = scanner.next().charAt(0);

        // Print the inputs
        System.out.println("\nExpected Output:");
        System.out.println(number);
        System.out.println(text);
        System.out.println(character);

        scanner.close();
    }
}
