# RemainderCalculator
import java.util.Scanner;

public class RemainderCalculator {
    public static void main(String[] args) {
       
        Scanner scanner = new Scanner(System.in);

       
        System.out.print("أدخل العدد الأول: ");
        int number1 = scanner.nextInt();

       
        System.out.print("أدخل العدد الثاني: ");
        int number2 = scanner.nextInt();

       
        int remainder = number1 % number2;

    
        System.out.println("باقي القسمة هو: " + remainder);

       
        scanner.close();
    }
}
