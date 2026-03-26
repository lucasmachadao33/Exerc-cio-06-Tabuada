import java.util.Scanner;

public class Tabuada {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Digite o número: ");
        int n = scanner.nextInt();

        int multiplicador = 1;

        while (multiplicador <= 10) {
            int resultado = n * multiplicador;
            System.out.println(n + " x " + multiplicador + " = " + resultado);
            multiplicador++;
        }

        scanner.close();
    }
}
