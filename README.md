package estudando;

import java.util.Scanner;

public class quadra {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Digite a temperatura em °C: ");
        double temp = sc.nextDouble();
        double fah = (temp*9/5)+32;
        double kel = (temp+273.15);
        System.out.println("Temperatura em celsius é: "+ temp+"°C");
        System.out.println("Temperatura em fahrenheit é: "+ fah+"°F");
        System.out.println("Temperatura em Kelvin é: "+ kel+"°K");

    }
}
