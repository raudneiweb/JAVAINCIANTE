# mundojava
import java.util.Scanner;

public class questao11 {
	
	static Scanner sc = new Scanner(System.in);
public static void main(String[] args) {

	double pi=3.14159;
	double raio;
	double altura;
	double volume;
	
	
	System.out.println("Calcule o valor do volume de uma lata de oleio");
	
	System.out.print ("Digite o Raio da Lata:");
	raio = sc.nextDouble();
	
	System.out.print ("Digite a altura da Lata:");
	altura = sc.nextDouble();
	
	volume= (pi*raio*raio)*altura;
    System.out.println("Volume da lata é:" +volume);
}
}
