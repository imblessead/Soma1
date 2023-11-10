# Soma1
Soma1

package exemplos;

import java.util.Scanner;

public class Soma1 {

	public static void main(String[] args) {
		
		Scanner scanner = new Scanner(System.in);
		System.out.println("Digite o primeiro valor: ");
		int valor1=scanner.nextInt();
		
		System.out.println("Digite o segundo valor: ");
		int valor2=scanner.nextInt();
		
		int soma=valor1+valor2;
		
		System.out.println("O valor da soma corresponde a: " + soma);

	}

}
