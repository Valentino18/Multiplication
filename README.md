Introduction 

Objectif
On souhaite concevoir une application web qui affiche une table de multiplication (1 à 10), selon une valeur soumise par l’utilisateur

Pour la partie 1,

On devra faire une application sur une page qui consistera à afficher les tables de multiplications.

On crée alors un projet "ng new multiplication --style=css --routing=false" puis on mettra le formulaire dans app component.html

![](img/img1.PNG)

Puis on créera un nouveau composannt que je vais appeler table-multiplications la commande est  "ng generate component components/table-multiplications".

C'est dans ce composant qu'on tapera le code qui affichera la table de multiplication faites par le formulaire.

![](img/img2.PNG)

Dans le table-multiplication.component.ts on fait la réception de données du composant parent à l’enfant, le rôle du decorateur. le @input qui nous permettra de faire rentrée des données dans le système informatique. Il faudra rajouter le "input" pour qu'il soit active.
![](img/img3.PNG)  

Pour faire afficher ce résultat dans le app.component.html la page principal on a mis dans le formulaire ce code ce qui va nous permettre de recuperer le resultat du code de la multiplication au moment ou on va envoyer la valeur choisi.

![](img/img4.PNG)  

Dans app.component.ts nous allons la valeur par le parent.Il faudra rajouter output et EvenEmitter import { Component, "Output, EventEmitter", OnInit } from '@angular/core';

![](img/img5.PNG)  


