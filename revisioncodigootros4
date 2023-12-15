public class Codigo4 {

	public static void main(String[] args) {

		
/*  
 * LAs variables las cambie por nombres adecuados , en  varios if al ser String es necesario usar el metodo 
 * equals en vez del operador ==
 * Agregue un ciclo para que se puede jugar varias veces seguidas y si alguien escribe exit sale del ciclo
 * 
 * Agregue algunos break por que no tenian 
 * y por ultimo al scanner le meti como parametro System.in 
 * 
 * */
		
		
		
		Scanner scanner = new Scanner(System.in);
		
		ciclo:
		do {
			
			System.out.print("Turno del jugador 1 (introduzca piedra, papel o tijeras): ");
			String jugador1 = scanner.nextLine();
			jugador1 = jugador1.toLowerCase();

			System.out.print("Turno del jugador 2 (introduzca piedra, papel o tijeras): ");
			String jugador2 = scanner.nextLine();
			jugador2  = jugador2 .toLowerCase();

			
			if(jugador1.equals("exit") || jugador2 .equals("exit")) {
				System.out.println("Hasta pronto");
				break ciclo;
			}
			
			if (jugador1.equals(jugador2 )) {
				System.out.println("Empate");
			} else {
				int jugador = 2;
				switch (jugador1) {
				case "piedra":
					if (jugador2 .equals("tijeras")) {
						jugador = 1;
					} 
				case "papel":
					if (jugador2 .equals("piedra")) {
						jugador = 1;
					} 
					break;
				case "tijeras":
					if (jugador2 .equals("papel")) {
						jugador = 1;
					} 
					break;
				default:
					System.out.println("Se escribio algo invalido (Piedra , Papel o Tijeras)");
					
				}
				System.out.println("Gana el jugador " + jugador);
			}
		} while (true);
		
		
	

	}

}
