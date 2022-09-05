# teste
import java.util.Locale;
import java.util.Scanner;
public class Main{
    public static void main(String[] args) {
        Scanner sc = new Scanner (System.in);
        System.out.print("Coloque o primeiro número: ");
        double n1 = sc.nextDouble();
        System.out.print("Coloque o segundo número: ");
        double n2 = sc.nextDouble();
        System.out.println(" O resultado da soma é igual a:"+(n1+n2));
        sc.close();
    }
}
