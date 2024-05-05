public class Main {
    public static void main(String[] args) {
        // Declare variables
        int check_number = 10;
        String message;

        // Loop to check and print odd or even numbers
        for (int i = 1; i <= check_number; i++) {
            message = (i % 2 == 0) ? i + " is even number" : i + " is odd number";
            System.out.println(message);
        }
    }
}
