# TP1_2_spring
##Description
Ce projet présente l'implémentation de deux travaux pratiques :

TP1 : Utilisation de la Programmation Dynamique en Java
TP2 : Implémentation de l'Inversion de Contrôle et Injection des Dépendances avec Spring
Le TP1 se concentre sur l'utilisation de la programmation dynamique pour instancier des classes et gérer les dépendances, tandis que le TP2 explore l'utilisation de Spring pour l'inversion de contrôle et l'injection de dépendances via des annotations.

##TP1 - Programmation Dynamique en Java
Fonctionnalités :
Création d'une interface IDao pour obtenir une valeur.
Implémentation de l'interface avec la classe DaoImpl.
Création d'une interface IMetier et de sa classe d'implémentation MetierImpl.
Utilisation de la réflexion pour charger les classes dynamiquement et injecter les dépendances.
##Exécution :
Pour exécuter ce TP:
-compiler et exécuter la classe Presentation2. 
-Si correctement configuré, le résultat dans la console sera Résultats = 200.0.

##TP2 - Inversion de Contrôle avec Spring
Fonctionnalités :
Utilisation de Spring pour gérer les beans avec des annotations.
Création d'une interface IDao et de deux implémentations : DaoImpl et DaoImpl2.
Implémentation de l'interface IMetier avec la classe MetierImpl, incluant l'injection de dépendances via l'annotation @Autowired.
Configuration du contexte Spring avec AnnotationConfigApplicationContext pour récupérer les beans.
##Exécution :
Pour exécuter ce TP:
-compiler et exécuter la classe Presentation2.
-Le résultat attendu dans la console sera Résultat = 200.0.

##Installation :
Cloner le dépôt ou télécharger les fichiers sources des projets.
Configurer les fichiers de projet en fonction de l'environnement (JDK, IDE utilisé).
Compiler et exécuter chaque projet depuis votre IDE (NetBeans, Eclipse).
##Vidéo :

##Crédits :
Développé par Zaggar.
