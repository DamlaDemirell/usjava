# usjava
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        int number, üssü,total=1;
        System.out.println("Üssü alınacak sayı : ");
        number = input.nextInt();

        System.out.println("Üs olacak sayı: ");
        üssü= input.nextInt();

        int i;
        for(i = 1; i<=üssü; i++)
        {
            total *= number;

        }
        System.out.println("Cevap" + total);
    }


}
