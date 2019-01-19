# How to Java

# Table des matières

- [Les bases d'une classe](#les-bases)
	- [Naming et structure de fichier](#Naming-et-structure)
	- [Méthodes](#méthodes)


## Les bases :

### Naming et structure :
```java

package <Nom_du_package>.<sous-dossier>.<etc>; // Convention de naming : comme pour les variables.

import <Chemin_vers_class_dans_un_sous_dossier>.<Nom_de_la_classe> // Pour importer une classe ou une de ses méthodes, ne pas mettre l'extension à la fin.

// ou 

import <librairie_de_java(class)>. /* * pour toutes les méthodes de la class, ou .<nom_de_la_méthode> si vous la connaissez. */

public class NomDeLaClasse {
	
	// L'espace défini pour les variables relatives a l'objet.
	
	/*
	* Définition du constructeur, qui initialisera les données de la classe comme les variables et autres instructions.
	* @param unParametre La convention veux que l'on nomme une variable en commencant par une minuscule, puis séparé les "mots" par des majuscules, ou des '_' suivi du mots dont l'initial est en majuscule, exemple : "un_Nom_De_Variable_Correct"
	*/
	public NomDeLaClasse() {
		// instructions.
		// variables spécifiques à la méthode si non précédé de this
	}
}
```
### Méthodes

Il existe deux sortes de méthodes, celles attendant un type spécifiques de return, et celles exécutant simplement une suite d'instructions.





