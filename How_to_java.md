# How to Java
# Table des matières
- [Les bases d'une classe](#les-bases)
	- [Naming et structure de fichier](#Naming-et-structure)
	- [Méthodes](#méthodes)
## Les bases
### Naming et structure
```java
package <Nom_du_package>.<sous-dossier>.<etc>; // Convention de naming : comme pour les variables.

import <Chemin_vers_class_dans_un_sous_dossier>.;<Nom_de_la_classe> // Pour importer une classe ou une de ses méthodes, ne pas mettre l'extension à la fin.

// ou 

import <librairie_de_java(class)>.; // .* pour toutes les méthodes de la class, ou .<nom_de_la_méthode> si vous la connaissez.

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
### Les références 
Une référence est se qui définit la portée par laquelle la variable ou fonction peut être utilisé.
Dans le code, ce sont les mots clefs tels que : `public` `protected` & `private`.

`public` : Grossièrement la portée est générale, on peut accéder a ce qui est référé ensuite de n'importe où.

`protected` : La portée est limitée a toutes les classes étant dans le même package que la références précédé de 'protected'.

`private` : La portée est ici limitée uniquement à la classe elle-même, il faudra définir des accesseurs et des  


### Méthodes
Il existe deux sortes de méthodes, celles attendant un type spécifiques de return, et celles exécutant simplement une suite d'instructions.
```java
public void functionSansReturn {
	// instructions..
}

public int functionAvecReturn {
	// instructions..
	return; // int attendu ici, on change le type attendu lors de la déclaration de la fonction en fonction du besoin.
}
```
### Variables
Une variable se définit d'abord par sa références 
