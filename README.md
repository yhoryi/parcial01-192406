# parcial01-192406
// punto 1:
import java.util.Scanner;
public class palindromo {
    public static void main(String[] args) {
        boolean palindromo = true;
        Scanner scanner = new Scanner (System.in);
        System.out.println ("ingrese la palabra para ver si es palindromo");
        String palindromo = scanner.nextLine();
        palindromo = palindromo.toLowerCase().replaceAll("\\s+", "");
        String reverso = new StringBuilder(palindromo).reverse().toString();
      if (frase.equals(reverso)){

        System.out.println (" es una palindromo")
      } else {System.out.println (" es una palindromo")

      }


    }
}

punto 2:
