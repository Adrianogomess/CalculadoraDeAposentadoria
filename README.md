# CalculadoraDeAposentadoria
Calcule se a pessoa pode ser aposentar de acordo com a idade e tempo de contribuição 




import java.util.Scanner;

public class CalculoAposentadoria {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		
		
		System.out.println("Digite a idade da Pessoa: ");
		double idade = scanner.nextDouble();
		
		System.out.println("DIgite o tempo de contribuicao ");
		double TempoDeContribuicao = scanner.nextDouble();
		
		boolean podeAposentar = idade >= 55;
		boolean tempoDeTrabalho = TempoDeContribuicao >= 25;
		
		
		if(podeAposentar) {
			System.out.println("ele pode aposentar! " );
			
		}else {
			System.out.println("ele nao pode aposentar! " );
			
			
		}
		
		scanner.close();
		

	}
	
}
