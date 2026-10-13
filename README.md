import java.util.Scanner;

public class ShoppingBillCalculator {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Item price: RM ");
        double price = sc.nextDouble();

        System.out.print("Quantity: ");
        int quantity = sc.nextInt();

        double total = price * quantity;

        System.out.println("Total bill: RM " + total);

        sc.close();
    }
}
