import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        long N = scanner.nextLong();
        boolean isNegative = (N < 0);
        if (isNegative) {
            N = -N;
        }
        long reversedNumber = 0;
        while (N > 0) {
            long lastDigit = N % 10;  
            reversedNumber = reversedNumber * 10 + lastDigit;  
            N /= 10; 
        }
        if (isNegative) {
            reversedNumber = -reversedNumber;
        }
        System.out.println(reversedNumber);
        scanner.close();
    }
}
