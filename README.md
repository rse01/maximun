# maximun
package eje;

import java.util.Scanner;

public class maximun {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
int premiere, deuxieme, laPlusGrande;
Scanner lectureClavier = new Scanner(System.in);
System.out.print("entrer une valeur :");
premiere = lectureClavier.nextInt();
System.out.print("entrer une deuxieme valeur :");
deuxieme = lectureClavier.nextInt();
if(premiere > deuxieme)
{
	//afficher  les valeurs dans l'ordre croisont
	System.out.println(deuxieme + "   "   + premiere );
	// stocker la plus grande  dans une variable specifique
	laPlusGrande = premiere;
}
else
{
	//afficher les valeurs dans l'ordre croissant
	System.out.println(premiere + "  " + deuxieme);
	// stocker la plus grande dans une variable specifique
}
	}
