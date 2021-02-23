Bienvenue!!! CSI2532_playground 

 : )

student name:  Yvan Pongang
student number:300113568

#LAB03
![1](https://github.com/yvan04/csi2532_playground/tree/lab03/IMG-1016.jpg)
![2](https://github.com/yvan04/csi2532_playground/tree/lab03/IMG-1017.jpg)

Une base de données universitaire
Une base de données universitaire contient des informations sur les professeurs (identifié par le numéro de sécurité sociale ou SSN) et les cours (identifié par courseid). Les professeurs donnent des cours; chacun de les situations suivantes concernent l'ensemble de relation teaches.

Diagramme ER
Pour chaque situation voici un diagramme ER qui le décrit (en supposant qu'aucune autre contrainte).

Les professeurs peuvent enseigner le même cours sur plusieurs semestres et seule la plus récente doit être enregistrée.
![ER #1](https://github.com/yvan04/csi2532_playground/tree/lab03/er_01.png)

Chaque professeur doit enseigner un cours.
![ER #2](https://github.com/yvan04/csi2532_playground/tree/lab03/er_02.png)

Chaque professeur enseigne exactement un cours (ni plus, ni moins).
![ER #3](https://github.com/yvan04/csi2532_playground/tree/lab03/er_03.png)

Chaque professeur enseigne exactement un cours (ni plus, ni moins), et chaque cours doit être enseigné par un professeur.
![ER #4](https://github.com/yvan04/csi2532_playground/tree/lab03/er_04.png)

Les professeurs peuvent enseigner le même cours sur plusieurs semestres et chaque doit être enregistrée.
![ER #5](https://github.com/yvan04/csi2532_playground/tree/lab03/er_05.png)

Supposons maintenant que certains cours puissent être enseignés conjointement par une équipe de professeurs, mais il est possible qu'aucun professeur dans une équipe ne puisse enseigner le cours. Modélisez cette situation en introduisant des ensembles d'entités et des ensembles de relations supplémentaires si nécessaire.
![ER #6](https://github.com/yvan04/csi2532_playground/tree/lab03/er_06.png)

Diagramme de relation
Avec les diagrammes ER ci-dessus, modèlez un diagramme relationnel pour les systèmes.

Schèma de relation
Avec les diagrammes relationnel ci-dessus, écrivez un schéma SQL relationnel pour les systèmes.
