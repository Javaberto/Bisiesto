# Bisiesto
/* Código que determina si un año (a partir del 0) es bisiesto. 2015 por Alberto Alsina */
 
 //CÓDIGO LIBRE
package bisiestos;

public class main {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		int año = 235445;
		
		if(año < 0){
			System.out.println("No lo sé ):");
			} else { 
				if((año%4)== 0){
					System.out.println("El año es bisiesto");
				} else {
					System.out.println("El año no es bisiesto");
				}
			}
		
	}

}
