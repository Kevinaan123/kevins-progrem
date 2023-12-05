import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        System.out.println("Enter Numbers, and press 0 after translation:");
        Scanner Number = new Scanner(System.in);
        Boolean a = true;
        while(a) {
            int number = Number.nextInt();
            System.out.print((char) number);
            if (number == 0) {
                a = false;
            }
        }
    }

}
